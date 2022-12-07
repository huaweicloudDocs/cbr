# 安装eBackup<a name="cbr_03_0060"></a>

介绍通过VMware vSphere Client ，使用eBackup镜像模板创建虚拟机，并为虚拟机配置网络。

## 背景信息<a name="zh-cn_topic_0000001258243879_section141721547194214"></a>

-   支持的VMware版本包括VMware vSphere 5.1、VMware vSphere 5.5、VMware vSphere 6.0、VMware vSphere 6.5。
-   一个eBackup备份管理系统中有且只有一个备份服务器，可以部署多个备份代理。请根据需要保护的虚拟机数量规划备份代理的数量。
-   本节以VMware vSphere Client 6.0为例进行介绍。当使用其他版本的VMware vSphere Client时，请参见VMware相关文档。
-   由于镜像模板中不包含VMware的VDDK（Virtaual Disk Development Kit）需要用户访问VMware官方网站[https://code.vmware.com/web/sdk/6.0/vddk](https://code.vmware.com/web/sdk/6.0/vddk)下载VDDK。
-   安装eBackup的服务器规格要求CPU不低于4vCPU内存不低于8GiB，数据盘和系统盘容量不小于200GB。

## 前提条件<a name="zh-cn_topic_0000001258243879_section973862813353"></a>

-   已安装VMware vSphere Client。
-   已下载eBackup镜像模板。
-   已获取VDDK包：VMware-vix-disklib-6.0.3-4888596.x86\_64.tar.gz。
-   已准备跨平台文件传输工具，如“WinSCP”。

## 操作步骤<a name="zh-cn_topic_0000001258243879_section11590154583611"></a>

1.  解压已下载的eBackup镜像模板包，获得“OceanStor BCManager 8.0.0-LHC01\_eBackup\_VMware\_template.ovf”文件。
2.  打开VMware vSphere Client，选择“文件 \> 部署OVF模板”。
3.  选择“OceanStor BCManager 8.0.0-LHC01\_eBackup\_VMware\_template.ovf“，单击“下一步”。
4.  查看OVF模板详细信息，单击“下一步”。
5.  为已部署模板指定名称并选择位置，单击“下一步”。
6.  选择要运行部署模板的主机或群集，单击“下一步“。
7.  选择虚拟机文件的目标存储，单击“下一步”。
8.  选择虚拟机磁盘格式为“厚置备延迟置零”，单击“下一步”。
9.  选择虚拟机的网络映射，单击“下一步”。
10. 查看虚拟机的部署设置，单击“完成”。
11. 等待虚拟机部署完成。
12. 修改虚拟机的网络标签。
    1.  在页面左侧虚拟机列表中，单击选中创建好的虚拟机。
    2.  选择“入门”页签。
    3.  单击“编辑虚拟机设置”。
    4.  在弹出的页面中，单击选择网络适配器，并在“网络标签”中根据实际环境选择网络标签。

        >![](public_sys-resources/icon-note.gif) **说明：** 
        >使用模板创建的虚拟机默认有三张网卡，请根据[规划网络](规划网络.md#cbr_03_0105)选择网络标签。

    5.  修改好全部网络适配器的网络标签后，单击“确定”。

13. 在页面左侧虚拟机列表中，单击选中创建好的虚拟机。
14. 单击上方![](figures/icon-start.png)按钮，等待虚拟机启动。
15. 虚拟机启动成功后，选择“控制台”页签。
16. 输入“root“帐户和密码登录虚拟机。

    “root“帐号初始密码为“Cloud12\#$“。

17. 为虚拟机的各网卡配置静态IP地址。

    IP地址的规划请参考[规划网络](规划网络.md#cbr_03_0105)。

    1.  执行**cd /etc/sysconfig/network-scripts/**命令进入“network-scripts”目录。
    2.  执行**ip a**命令查看虚拟机当前网卡名称。eth0为例进行说明，实际操作中请替换为实际名称。
    3.  <a name="zh-cn_topic_0000001258243879_li68117292492"></a>执行**vi ifcfg-eth0**命令，打开“ifcfg-eth0”配置文件。
    4.  按“i”进入编辑模式，修改配置文件。

        需要配置的参数如下，如果配置文件中不存在以下配置参数，请手动输入。

        -   BOOTPROTO="static"，表示使用静态IP地址。
        -   IPADDR，NETMASK和GATEWAY分别配置为已规划好的虚拟机IP地址，子网掩码以及网关。
        -   ONBOOT=yes，表示系统启动时，启动该网卡。

    5.  <a name="zh-cn_topic_0000001258243879_li13683113875018"></a>按“Esc”，输入**:wq**保存并退出。
    6.  重复[17.c](#zh-cn_topic_0000001258243879_li68117292492)\~[17.e](#zh-cn_topic_0000001258243879_li13683113875018)为其他网卡配置静态IP地址。

18. 执行**service network restart**命令，重启网络。
19. 在维护终端上，使用“WinSCP”工具，将“VMware-vix-disklib-6.0.3-4888596.x86\_64.tar.gz”上传到任意目录下，如/opt目录。
20. 执行**cd /opt**命令进入“/opt”目录。
21. 执行**tar -xvf VMware-vix-disklib-6.0.3-4888596.x86\_64.tar.gz**命令，解压VDDK包。
22. <a name="zh-cn_topic_0000001258243879_li19212134210118"></a>执行**mkdir -p /opt/huawei-data-protection/ebackup/microservice/ebk\_vmware/lib/3rd/vddk/lib64**命令创建“/opt/huawei-data-protection/ebackup/microservice/ebk\_vmware/lib/3rd/vddk/lib64”目录。
23. 执行**cp -d /opt/vmware-vix-disklib-distrib/lib64/lib\* /opt/huawei-data-protection/ebackup/microservice/ebk\_vmware/lib/3rd/vddk/lib64/**命令，将VDDK的文件拷贝到[22](#zh-cn_topic_0000001258243879_li19212134210118)创建的目录下。
24. 执行**chmod 550 -R /opt/huawei-data-protection/ebackup/microservice/ebk\_vmware/lib/3rd/vddk/**修改目录权限。
25. 执行**chown hcpprocess:hcpmgr -R /opt/huawei-data-protection/ebackup/microservice/ebk\_vmware/lib/3rd/vddk/**命令修改目录属组为“hcpprocess”。

## 后续操作<a name="zh-cn_topic_0000001258243879_section7331935171715"></a>

-   当用户使用专线或者VPN接入华为云时，请在备份服务器和备份代理服务器上配置华为云的DNS。
-   当eBackup服务器需要接入管理平面或存储平面（包括生产存储平面和备份存储平面）的其他网段或者IP地址时，需要进行路由配置。
    1.  执行**ifconfig**命令，查看与需要接入管理平面或存储平面通信的网卡信息。

        ```
        eth2   Link encap:Ethernet  HWaddr 2A:BE:D4:88:99:01   
               inet addr:192.168.31.190  Bcast:192.168.31.255  Mask:255.255.255.0 
        …
        ```

    2.  执行**vi /etc/sysconfig/static-routes**命令，打开配置文件。
    3.  在文件中添加路由信息，输入**:wq**保存并退出文件。

        ```
        any net 192.168.1.0 netmask 255.255.255.0 gw 192.168.31.1 dev eth2
        ```

        >![](public_sys-resources/icon-note.gif) **说明：** 
        >上述回显信息四列分别表示目标网络，目标网络子网掩码，本端的网关和网卡名称。

    4.  执行**service network restart**命令，重启网络使路由生效。
    5.  执行**route**命令，查看路由信息。

        ```
        Kernel IP routing table 
        Destination     Gateway         Genmask         Flags Metric Ref    Use Iface 
        192.168.1.0     192.168.31.1    255.255.255.0   UG    0      0        0 eth2
        ```



