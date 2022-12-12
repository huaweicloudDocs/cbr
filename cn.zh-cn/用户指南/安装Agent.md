# 安装Agent<a name="cbr_03_0021"></a>

启用数据库服务器备份前，需先在弹性云服务器上更改安全组和成功安装Agent。

如果服务器未安装Agent而执行了数据库服务器备份，则会出现数据库服务器备份失败，只能进行普通云服务器备份的情况。为了确保数据库服务器备份正常进行，请先按照本章节下载并安装Agent。

## 操作说明<a name="section84209306505"></a>

-   当前仅支持x86计算类型的服务器，暂不支持鲲鹏计算类型的服务器。
-   安装客户端时，系统会以“rdadmin”用户运行安装程序。请定期修改Agent的操作系统“rdadmin”用户的登录密码，并禁止“rdadmin”用户远程登录，以提升系统运维安全性。详情请参见[修改rdadmin帐号密码](修改rdadmin帐号密码.md)。
-   支持安装客户端的操作系统如[表1](#table1997917214406)所示。

    **表 1**  支持安装客户端的操作系统列表

    <a name="table1997917214406"></a>
    <table><thead align="left"><tr id="row17963824406"><th class="cellrowborder" valign="top" width="19%" id="mcps1.2.4.1.1"><p id="p69631254015"><a name="p69631254015"></a><a name="p69631254015"></a>数据库名称</p>
    </th>
    <th class="cellrowborder" valign="top" width="16%" id="mcps1.2.4.1.2"><p id="p16963229402"><a name="p16963229402"></a><a name="p16963229402"></a>操作系统类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="65%" id="mcps1.2.4.1.3"><p id="p1596372134014"><a name="p1596372134014"></a><a name="p1596372134014"></a>版本范围</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row89794274012"><td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.4.1.1 "><p id="p59631620403"><a name="p59631620403"></a><a name="p59631620403"></a>SQLServer 2008/2012</p>
    </td>
    <td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.4.1.2 "><p id="p20963420405"><a name="p20963420405"></a><a name="p20963420405"></a>Windows</p>
    </td>
    <td class="cellrowborder" valign="top" width="65%" headers="mcps1.2.4.1.3 "><p id="p39633217408"><a name="p39633217408"></a><a name="p39633217408"></a>Windows Server 2008, 2008 R2, 2012, 2012 R2 for x86_64</p>
    </td>
    </tr>
    <tr id="row129799211400"><td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.4.1.1 "><p id="p109791629407"><a name="p109791629407"></a><a name="p109791629407"></a>SQLServer 2014/2016/EE</p>
    </td>
    <td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.4.1.2 "><p id="p139794217407"><a name="p139794217407"></a><a name="p139794217407"></a>Windows</p>
    </td>
    <td class="cellrowborder" valign="top" width="65%" headers="mcps1.2.4.1.3 "><p id="p102273139182"><a name="p102273139182"></a><a name="p102273139182"></a>Windows Server 2014, 2014 R2, 2016 Datacenter for x86_64</p>
    </td>
    </tr>
    <tr id="row397920294015"><td class="cellrowborder" rowspan="4" valign="top" width="19%" headers="mcps1.2.4.1.1 "><p id="p49796244012"><a name="p49796244012"></a><a name="p49796244012"></a>MySQL 5.5/5.6/5.7</p>
    </td>
    <td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.4.1.2 "><p id="p79791323404"><a name="p79791323404"></a><a name="p79791323404"></a>Red Hat</p>
    </td>
    <td class="cellrowborder" valign="top" width="65%" headers="mcps1.2.4.1.3 "><p id="p19791827406"><a name="p19791827406"></a><a name="p19791827406"></a>Red Hat Enterprise Linux 6, 7 for x86_64</p>
    </td>
    </tr>
    <tr id="row189792264012"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p20979152134011"><a name="p20979152134011"></a><a name="p20979152134011"></a>SUSE</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p1375648143615"><a name="p1375648143615"></a><a name="p1375648143615"></a>SUSE Linux Enterprise Server 11, 12, 15 SP1, 15 SP2 for x86_64</p>
    </td>
    </tr>
    <tr id="row097919254017"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p3979172144013"><a name="p3979172144013"></a><a name="p3979172144013"></a>CentOS</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p3979722409"><a name="p3979722409"></a><a name="p3979722409"></a>CentOS 6, 7 for x86_64</p>
    </td>
    </tr>
    <tr id="row197918220402"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p209790216406"><a name="p209790216406"></a><a name="p209790216406"></a>Euler</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p139791820408"><a name="p139791820408"></a><a name="p139791820408"></a>Euler OS 2.2, 2.3 for x86_64</p>
    </td>
    </tr>
    <tr id="row18979422401"><td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.4.1.1 "><p id="p997910234020"><a name="p997910234020"></a><a name="p997910234020"></a>HANA 1.0/2.0</p>
    </td>
    <td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.4.1.2 "><p id="p1797910214408"><a name="p1797910214408"></a><a name="p1797910214408"></a>SUSE</p>
    </td>
    <td class="cellrowborder" valign="top" width="65%" headers="mcps1.2.4.1.3 "><p id="p297916274013"><a name="p297916274013"></a><a name="p297916274013"></a>SUSE Linux Enterprise Server 12 for x86_64</p>
    </td>
    </tr>
    </tbody>
    </table>


>![](public_sys-resources/icon-notice.gif) **须知：** 
>客户端安装时，系统会打开弹性云服务器的59526-59528端口的防火墙其中之一。当59526端口被占用时，则会打开59527端口的防火墙，以此类推。

## 前提条件<a name="section161871429165316"></a>

-   已获取管理控制台的登录帐号与密码。
-   已经配置好安全组。
-   弹性云服务器的“Agent状态”为“未安装”。
-   通过IE浏览器访问时需要将用到的网站加入受信任的站点。

## 安装Linux版本客户端（方式一）<a name="section104061326161019"></a>

1.  登录云备份管理控制台。
    1.  [登录管理控制台](https://console.huaweicloud.com/console/?locale=zh-cn#/cbr/manager/csbs/vaultList)。
    2.  单击管理控制台左上角的![](figures/icon-region.png)，选择区域和项目。
    3.  选择“存储 \> 云备份”。选择对应备份的页签。

2.  选择“安装Agent“页签，进入“安装Agent”页面。

    **图 1**  进入Linux安装界面<a name="fig2096411149591"></a>  
    

    ![](figures/Snipaste_2021-08-03_16-46-25.png)

3.  在方式一中，根据需要选择相应的Agent版本，并将步骤二的安装命令复制下来。
4.  前往“弹性云服务器”界面，选择目标服务器，单击“操作”列下的“远程登录”，登录该弹性云服务器。
5.  将步骤二的安装命令粘贴至该服务器，以root权限执行。若执行失败，请先使用命令yum install -y bind-utils进行dig模块安装；若使用该命令安装仍旧失败，再使用安装Linux版本客户端（方式二）进行安装。
6.  Linux系统客户端安装完成后，即表示Agent已在正常工作。后续请参考《云备份最佳实践》修改或编写自定义脚本，来实现MySQL或SAP HANA等数据库的一致性备份。

## 安装Linux版本客户端（方式二）<a name="section16845112510521"></a>

1.  登录云备份管理控制台。
    1.  [登录管理控制台](https://console.huaweicloud.com/console/?locale=zh-cn#/cbr/manager/csbs/vaultList)。
    2.  单击管理控制台左上角的![](figures/icon-region.png)，选择区域和项目。
    3.  选择“存储 \> 云备份”。选择对应备份的页签。

2.  选择“安装Agent“页签，进入“安装Agent”页面。

    **图 2**  Linux安装界面<a name="fig1111011107016"></a>  
    

    ![](figures/Snipaste_2021-08-03_16-46-25-2.png)

3.  在方式二中，单击“点击下载“。在弹出的“下载客户端“，根据目标弹性云服务器的操作系统类型，选择需要下载的版本，单击“确定“。如[图3](#fig1827319471211)所示。

    **图 3**  下载客户端<a name="fig1827319471211"></a>  
    

    ![](figures/Snipaste_2021-08-03_16-48-37.png)

4.  将客户端下载至本地任意目录后，使用文件传输工具（例如：“Xftp”、“SecureFX”、“WinSCP”），将下载的客户端安装包上传到待安装客户端的弹性云服务器。
5.  上传完毕后，前往“弹性云服务器”界面，选择目标服务器，单击“操作”列下的“远程登录”，登录该弹性云服务器。
6.  执行**tar -zxvf**命令，将客户端安装包解压至任意目录，执行以下命令，进入解压后目录中的bin目录。

    **cd** **bin**

7.  执行以下命令，运行安装脚本。

    **sh agent\_install\_ebk.sh**

8.  系统提示客户端安装成功，如[图4](#fig98742261182)所示。

    **图 4**  安装Linux客户端成功<a name="fig98742261182"></a>  
    ![](figures/安装Linux客户端成功.png "安装Linux客户端成功")

9.  <a name="li1857075115439"></a>若弹性云服务器中已经安装了MySQL或SAP HANA数据库，需要执行以下命令加密MySQL或HANA数据库登录密码。

    **/home/rdadmin/Agent/bin/agentcli encpwd**

10. 使用[上一个步骤](#li1857075115439)中的加密密码替换/home/rdadmin/Agent/bin/thirdparty/ebk\_user/目录下脚本里的数据库登录密码。
11. Linux系统客户端安装完成后，即表示Agent已在正常工作。后续请参考《云备份最佳实践》修改或编写自定义脚本，来实现MySQL或SAP HANA等数据库的一致性备份。

## 安装Windows版本客户端（方式一）<a name="section06291649175414"></a>

1.  登录云备份管理控制台。
    1.  [登录管理控制台](https://console.huaweicloud.com/console/?locale=zh-cn#/cbr/manager/csbs/vaultList)。
    2.  单击管理控制台左上角的![](figures/icon-region.png)，选择区域和项目。
    3.  选择“存储 \> 云备份”。选择对应备份的页签。

2.  选择“安装Agent“页签，进入“安装Agent”页面。

    **图 5**  进入Windows安装界面<a name="fig56681027201010"></a>  
    

    ![](figures/Snipaste_2022-01-06_16-52-13.png)

3.  在方式一中，单击“点击下载“。将下载的安装包保存至本地任意目录。
4.  将客户端下载至本地任意目录后，使用文件传输工具（例如：“Xftp”、“SecureFX”、“WinSCP”），将下载的客户端安装包上传到待安装客户端的弹性云服务器。
5.  登录控制台，以Administrator的权限进入弹性云服务器。
6.  将安装包解压至任意目录，进入“_安装路径_**\\bin**”目录中。
7.  双击**agent\_install\_ebk.bat**脚本开始安装。
8.  系统提示客户端安装成功，如[图6](#fig15516539536)所示。

    **图 6**  Windows客户端安装成功<a name="fig15516539536"></a>  
    ![](figures/Windows客户端安装成功.png "Windows客户端安装成功")


## 安装Windows版本客户端（方式二）<a name="section1092910942916"></a>

1.  登录云备份管理控制台。
    1.  [登录管理控制台](https://console.huaweicloud.com/console/?locale=zh-cn#/cbr/manager/csbs/vaultList)。
    2.  单击管理控制台左上角的![](figures/icon-region.png)，选择区域和项目。
    3.  选择“存储 \> 云备份”。选择对应备份的页签。

2.  选择“安装Agent“页签，进入“安装Agent”页面。

    **图 7**  Windows安装界面<a name="fig555144111116"></a>  
    

    ![](figures/Snipaste_2022-01-06_16-52-13-3.png)

3.  前往“弹性云服务器”界面，选择目标服务器，单击“操作”列下的“远程登录”，以Administrator的权限登录该弹性云服务器。
4.  将方式二步骤二框中的安装命令复制到该服务器，在CMD中执行。
5.  将应答名称中的任一IP地址复制下来，在浏览器地址中粘贴，并替换下面的0.0.0.0，**_cn-north-1_**需要根据实际区域进行替换，此处以华北区为例。然后在浏览器中按“Enter”下载安装包。

    **http://_0.0.0.0_/csbs-agent-**_cn-north-1_**/Cloud Server Backup Agent-WIN64.zip**

6.  解压后得到安装文件。将安装包解压至任意目录，进入“_安装路径_**\\bin**”目录中。
7.  双击**agent\_install\_ebk.bat**脚本开始安装。
8.  系统提示客户端安装成功，如[图8](#fig7765912171519)所示。

    **图 8**  安装Windows客户端成功<a name="fig7765912171519"></a>  
    ![](figures/安装Windows客户端成功.png "安装Windows客户端成功")


