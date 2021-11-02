# 管理VMware受保护环境<a name="cbr_03_0081"></a>

受保护环境是备份数据的来源，通常被称作生产端。当受保护环境增加至eBackup备份管理系统后，您可以对已增加的受保护环境执行查看、修改、删除等操作。

## 图标说明<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_section48515817"></a>

VMware受保护环境添加至eBackup备份管理系统后，系统会自动获取虚拟机的信息，相关图标说明如[表1](#zh-cn_topic_0175068521_zh-cn_topic_0170955547_view_vmware_tab01)所示。关于VMware受保护环境的中的对象定义以及之间的关联关系详细说明，请参见VMware配套文档。

**表 1**  VMware受保护环境中图标说明

<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_view_vmware_tab01"></a>
<table><thead align="left"><tr id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_row23021753"><th class="cellrowborder" valign="top" width="11.221122112211221%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p52822718"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p52822718"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p52822718"></a>对象名称</p>
</th>
<th class="cellrowborder" valign="top" width="8.160816081608163%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p50781751"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p50781751"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p50781751"></a>图标</p>
</th>
<th class="cellrowborder" valign="top" width="80.61806180618062%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p19681165"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p19681165"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p19681165"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_row50670503"><td class="cellrowborder" valign="top" width="11.221122112211221%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p10670061"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p10670061"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p10670061"></a>vCenter Server</p>
</td>
<td class="cellrowborder" valign="top" width="8.160816081608163%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p58968649"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p58968649"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p58968649"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image60955793"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image60955793"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image60955793" src="figures/icon-twosquare.png"></span>/<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image11731232"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image11731232"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image11731232" src="figures/icon-lockProtect.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="80.61806180618062%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p10705756"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p10705756"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p10705756"></a>vCenter Server可提供对数据中心便捷的单点控制，运行于Windows服务器之上，可集中管理VMware ESXi主机，并提供基本的数据中心服务。</p>
<p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p29242948"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p29242948"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p29242948"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image61859941"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image61859941"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image61859941" src="figures/icon-twosquare.png"></span>表示未添加证书，<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image19868562"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image19868562"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image19868562" src="figures/icon-lockProtect.png"></span>表示已添加证书。</p>
</td>
</tr>
<tr id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_row44599330"><td class="cellrowborder" valign="top" width="11.221122112211221%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p55775996"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p55775996"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p55775996"></a>数据中心</p>
</td>
<td class="cellrowborder" valign="top" width="8.160816081608163%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p21561818"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p21561818"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p21561818"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image59838638"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image59838638"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image59838638" src="figures/icon-grid.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="80.61806180618062%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p15091534"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p15091534"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p15091534"></a>数据中心是主机和虚拟机等对象的主要容器，您可以将主机、文件夹、集群添加到数据中心。</p>
</td>
</tr>
<tr id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_row1606084"><td class="cellrowborder" valign="top" width="11.221122112211221%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p62983968"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p62983968"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p62983968"></a>文件夹</p>
</td>
<td class="cellrowborder" valign="top" width="8.160816081608163%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p1427744"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p1427744"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p1427744"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image12849697"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image12849697"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image12849697" src="figures/icon-file.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="80.61806180618062%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p34192531"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p34192531"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p34192531"></a>文件夹允许您对相同类型的对象进行分组，从而轻松地对这些对象进行管理。文件夹可以包含其他文件夹或一组相同类型的对象：数据中心、集群、数据存储、网络、虚拟机、模板或主机。例如，文件夹可以包含主机和含有主机的文件夹，但它不能包含主机和含有虚拟机的文件夹。</p>
</td>
</tr>
<tr id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_row39297325"><td class="cellrowborder" valign="top" width="11.221122112211221%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p28966795"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p28966795"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p28966795"></a>集群</p>
</td>
<td class="cellrowborder" valign="top" width="8.160816081608163%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p64609069"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p64609069"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p64609069"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image44610716"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image44610716"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image44610716" src="figures/icon-cluster.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="80.61806180618062%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p56698207"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p56698207"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p56698207"></a>集群是ESXi主机及关联虚拟机的集合。为集群添加主机时，主机的资源将成为集群资源的一部分。集群管理所有主机的资源。</p>
</td>
</tr>
<tr id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_row40521823"><td class="cellrowborder" valign="top" width="11.221122112211221%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p61042239"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p61042239"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p61042239"></a>主机</p>
</td>
<td class="cellrowborder" valign="top" width="8.160816081608163%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p45474307"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p45474307"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p45474307"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image6615582"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image6615582"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image6615582" src="figures/icon-cabinet.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="80.61806180618062%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p66100148"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p66100148"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p66100148"></a>主机是运行了虚拟化软件（ESXi）的物理服务器，其上可运行虚拟机。主机为虚拟机提供CPU和内存资源，以及图形处理器、USB设备、网络连接和存储访问等能力。同一台主机可以同时运行多台虚拟机。</p>
</td>
</tr>
<tr id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_row58030425"><td class="cellrowborder" valign="top" width="11.221122112211221%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p2843962"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p2843962"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p2843962"></a>vApp</p>
</td>
<td class="cellrowborder" valign="top" width="8.160816081608163%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p29034401"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p29034401"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p29034401"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image59983017"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image59983017"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image59983017" src="figures/icon-threesquare.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="80.61806180618062%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p26786193"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p26786193"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p26786193"></a>vApp是可作为单个对象来进行管理的一组虚拟机。对于在相互依赖的多台虚拟机上运行的复杂多层应用程序，vApp可简化其管理。vApp的基本操作与虚拟机和资源池的基本操作相同。</p>
</td>
</tr>
<tr id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_row39749146"><td class="cellrowborder" valign="top" width="11.221122112211221%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p65564286"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p65564286"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p65564286"></a>资源池</p>
</td>
<td class="cellrowborder" valign="top" width="8.160816081608163%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p9106950"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p9106950"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p9106950"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image14853691"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image14853691"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image14853691" src="figures/icon-percent.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="80.61806180618062%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p62298357"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p62298357"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p62298357"></a>资源池用于划分主机或集群内的CPU和内存资源。虚拟机在资源池中执行并利用其中的资源。可以创建多个资源池，作为独立主机或集群的直接子级。</p>
</td>
</tr>
<tr id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_row23814308"><td class="cellrowborder" valign="top" width="11.221122112211221%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p49910794"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p49910794"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p49910794"></a>虚拟机</p>
</td>
<td class="cellrowborder" valign="top" width="8.160816081608163%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p16242484"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p16242484"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p16242484"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image11964630"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image11964630"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image11964630" src="figures/icon-manage.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="80.61806180618062%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p29610978"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p29610978"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p29610978"></a>虚拟机与物理计算机一样，是运行操作系统和应用软件的虚拟计算机。虚拟机运行在主机上，并从主机上获取所需的CPU、内存等计算资源，显卡、USB设备、网络连接和存储访问等能力。多台虚拟机可以同时运行在一台主机中。</p>
</td>
</tr>
<tr id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_row65172214"><td class="cellrowborder" valign="top" width="11.221122112211221%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p44457949"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p44457949"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p44457949"></a>磁盘</p>
</td>
<td class="cellrowborder" valign="top" width="8.160816081608163%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p44324137"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p44324137"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p44324137"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image63372921"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image63372921"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image63372921" src="figures/icon-disk.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="80.61806180618062%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p32932951"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p32932951"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p32932951"></a>磁盘是从与主机关联的数据存储中划分出来的存储单元，为该主机上的虚拟机提供存储空间，与物理磁盘一样，用于存储操作系统、应用程序以及其他数据。多个磁盘可以绑定给一个虚拟机，磁盘主要用于存放虚拟机配置文件和其他磁盘文件。</p>
</td>
</tr>
</tbody>
</table>

## 相关操作<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_section33989175"></a>

<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_table50323341"></a>
<table><thead align="left"><tr id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_row48981745"><th class="cellrowborder" valign="top" width="13.398660133986603%" id="mcps1.1.5.1.1"><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p8098397"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p8098397"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p8098397"></a>任务</p>
</th>
<th class="cellrowborder" valign="top" width="28.86711328867114%" id="mcps1.1.5.1.2"><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p51990381"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p51990381"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p51990381"></a>界面入口</p>
</th>
<th class="cellrowborder" valign="top" width="28.86711328867114%" id="mcps1.1.5.1.3"><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p50471305"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p50471305"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p50471305"></a>任务描述</p>
</th>
<th class="cellrowborder" valign="top" width="28.86711328867114%" id="mcps1.1.5.1.4"><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p61643930"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p61643930"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p61643930"></a>关键参数</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_row27102472"><td class="cellrowborder" valign="top" width="13.398660133986603%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p47816634"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p47816634"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p47816634"></a>查看VMware受保护环境信息</p>
</td>
<td class="cellrowborder" valign="top" width="28.86711328867114%" headers="mcps1.1.5.1.2 "><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul47942169"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul47942169"></a><ul id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul47942169"><li>查看基本信息入口：在导航栏上选择“<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image58110476"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image58110476"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image58110476" src="figures/icon-protect1.png"></span> &gt; VMware”，单击导航树中的一级、二级、三级节点。</li><li>查看详细信息入口：在导航栏上选择“<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image9328124"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image9328124"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image9328124" src="figures/icon-protect1.png"></span> &gt; VMware”，单击导航树中的一级、二级、三级节点后，单击待查看的虚拟机。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="28.86711328867114%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p17380560"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p17380560"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p17380560"></a><strong id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b22207315"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b22207315"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b22207315"></a>操作背景</strong></p>
<p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p65648113"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p65648113"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p65648113"></a>当您想要查看VMware受保护环境的详细信息时，请执行该操作。VMware受保护环境添加至eBackup备份管理系统后，系统会自动获取虚拟机的信息。</p>
<p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p53962105"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p53962105"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p53962105"></a><strong id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b15896902"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b15896902"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b15896902"></a>注意事项</strong></p>
<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul8854391"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul8854391"></a><ul id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul8854391"><li>执行该操作前，请确保已经成功创建增加VMware受保护环境。</li><li>当受保护环境信息有更新时，您需要手动触发更新，同步变更信息至eBackup备份管理系统。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="28.86711328867114%" headers="mcps1.1.5.1.4 "><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul44498462"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul44498462"></a><ul id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul44498462"><li>保护状态<p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p47605654"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p47605654"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p47605654"></a>虚拟机最近一周的保护状态。</p>
</li><li>UUID<p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p30852742"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p30852742"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p30852742"></a>UUID（Universally Unique Identifier ）是指受保护环境中虚拟机的唯一标识。</p>
</li><li>最近备份时间<p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p16044183"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p16044183"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p16044183"></a>虚拟机最近一次备份开始的时间。如果虚拟机未执行过备份任务，此处显示为“--”。</p>
</li><li>所在主机<p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p24510448"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p24510448"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p24510448"></a>虚拟机所在主机的名称。如果虚拟机未绑定主机，则此处显示为“--”。</p>
</li></ul>
</td>
</tr>
<tr id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_row19267448"><td class="cellrowborder" valign="top" width="13.398660133986603%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p17159441"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p17159441"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p17159441"></a>修改VMware受保护环境信息</p>
</td>
<td class="cellrowborder" valign="top" width="28.86711328867114%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p47737479"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p47737479"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p47737479"></a>在导航栏上选择“<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image26984128"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image26984128"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image26984128" src="figures/icon-protect1.png"></span> &gt; VMware”，在“受保护环境”区域，选中左侧导航树一级节点，并单击<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image41530561"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image41530561"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image41530561" src="figures/icon-edit1.png"></span>。</p>
</td>
<td class="cellrowborder" valign="top" width="28.86711328867114%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p8532263"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p8532263"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p8532263"></a><strong id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b9681511"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b9681511"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b9681511"></a>操作背景</strong></p>
<p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p20024739"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p20024739"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p20024739"></a>当VMware受保护环境的vCenter Server/ESXi主机地址、鉴权信息等发生变更时，您需要在eBackup备份管理系统同步更新对应信息，以便系统能够及时获取虚拟机信息并正常备份该vCenter Server/ESXi下的虚拟机。</p>
<p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p46004923"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p46004923"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p46004923"></a><strong id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b11391130"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b11391130"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b11391130"></a>注意事项</strong></p>
<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul35411312"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul35411312"></a><ul id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul35411312"><li>执行该操作前，请确保存在已成功增加的受保护环境。</li><li>修改受保护环境vCenter Server地址时，请确保修改后的IP地址与生产端IP地址一致。如果系统检测到修改后的受保护环境与原受保护环境不一致，则提示修改失败。</li><li>ESXi主机不支持修改IP地址。如果需要修改，则需要删除已有的受保护环境，重新增加配置新IP地址的受保护环境。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="28.86711328867114%" headers="mcps1.1.5.1.4 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p24623100"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p24623100"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p24623100"></a>无。</p>
</td>
</tr>
<tr id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_row20281314"><td class="cellrowborder" valign="top" width="13.398660133986603%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p32173737"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p32173737"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p32173737"></a>删除VMware受保护环境信息</p>
</td>
<td class="cellrowborder" valign="top" width="28.86711328867114%" headers="mcps1.1.5.1.2 "><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ol55935896"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ol55935896"></a><ol id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ol55935896"><li>在导航栏上选择“<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image34513752"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image34513752"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image34513752" src="figures/icon-protect1.png"></span> &gt; VMware”。</li><li>在“受保护环境”区域，选中左侧导航树一级节点（即待删除的受保护环境），并在右侧单击每一个虚拟机，在信息预览区查看该受保护环境下的虚拟机是否存在关联的保护集。<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul44150545"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul44150545"></a><ul class="subitemlist" id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_ul44150545"><li>如果“保护集”区域存在关联的保护集，请进入保护集界面找到关联的保护集。确认该保护集不需要后，删除关联保护集，然后再执行删除受保护环境的操作。</li><li>如果所有虚拟机“保护集”区域均不存在关联的保护集，请直接执行删除受保护环境的操作。</li></ul>
</li><li>在“受保护环境”区域，再次选中左侧导航树一级节点（即待删除的受保护环境），并单击<a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image29869451"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image29869451"></a><span><img id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_image29869451" src="figures/icon-delete1.png"></span>。</li></ol>
</td>
<td class="cellrowborder" valign="top" width="28.86711328867114%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p3506461"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p3506461"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p3506461"></a><strong id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b31558151"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b31558151"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b31558151"></a>操作背景</strong></p>
<p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p15587911"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p15587911"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p15587911"></a>当不再需要备份vCenter Server/ESXi管理下的虚拟机时，可以删除该受保护环境。</p>
<p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p6073477"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p6073477"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p6073477"></a><strong id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b54661298"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b54661298"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_b54661298"></a>注意事项</strong></p>
<p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p22189639"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p22189639"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p22189639"></a>执行该操作前，请确保待删除的vCenter Server/ESXi下管理的虚拟机不在任何一个保护集中。</p>
</td>
<td class="cellrowborder" valign="top" width="28.86711328867114%" headers="mcps1.1.5.1.4 "><p id="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p52530358"><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p52530358"></a><a name="zh-cn_topic_0175068521_zh-cn_topic_0170955547_p52530358"></a>无。</p>
</td>
</tr>
</tbody>
</table>

