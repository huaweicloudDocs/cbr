# 管理eBackup服务器<a name="cbr_03_0093"></a>

查看eBackup备份管理系统内备份服务器和备份代理的状态，以便及时发现异常并进行处理。此外，您还可以通过设置HA参数，将eBackup配置为高可用系统。

## 背景信息<a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_section17081350"></a>

HA（High Availability），即高可用性，通常指采用主、备两个相同的模块以热备份或者冷备份的方式完成指定功能，在主用模块故障时，备用模块会自动接替主用模块执行系统功能，以提高系统可靠性。

eBackup备份管理系统支持HA功能，需要规划至少两个eBackup服务器（将其中一台服务器初始化为备份服务器，其余服务器初始化为备份代理）。默认情况下，完成安装配置后系统不具备HA功能，需要用户设置HA参数，将eBackup配置为高可用系统。设置完成后，备份服务器和一个备份代理互为主备节点。当备份服务器故障时，备份代理接替其维持系统正常运行。

## 操作步骤<a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_section19514424"></a>

1.  在导航栏上选择“![](figures/icon-task.png)  \> 服务器”。
2.  **可选：**在右上角搜索栏设置搜索条件，单击![](figures/icon-search.png)，快速查找相应的服务器。
3.  查看服务器信息，相关参数说明如[表1](#zh-cn_topic_0174994048_zh-cn_topic_0170955449_manage_node_tab01)所示。

    **表 1**  服务器信息参数说明

    <a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_manage_node_tab01"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_row9553870"><th class="cellrowborder" valign="top" width="19%" id="mcps1.2.3.1.1"><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p35666021"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p35666021"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p35666021"></a>参数名称</p>
    </th>
    <th class="cellrowborder" valign="top" width="81%" id="mcps1.2.3.1.2"><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p3266617"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p3266617"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p3266617"></a>参数说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_row63269425"><td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p24549814"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p24549814"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p24549814"></a>ID</p>
    </td>
    <td class="cellrowborder" valign="top" width="81%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p42377903"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p42377903"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p42377903"></a>服务器在eBackup备份管理系统中的唯一标识。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_row45856811"><td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p23414190"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p23414190"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p23414190"></a>可访问状态</p>
    </td>
    <td class="cellrowborder" valign="top" width="81%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p17501209"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p17501209"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p17501209"></a>服务器的在线状态，包括：</p>
    <a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_ul23293157"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_ul23293157"></a><ul id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_ul23293157"><li>可访问<p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p7697601"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p7697601"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p7697601"></a>备份服务器和备份代理之间通信正常，且能够正常运行备份恢复业务。</p>
    </li><li>不可访问<p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p19525912"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p19525912"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p19525912"></a>由于备份服务器需要通过心跳来与备份代理保持互通，检测备份代理可访问状态。当超过设定的时间后检测不到备份代理在线时，系统会将该备份代理置为不可访问状态。</p>
    </li></ul>
    </td>
    </tr>
    <tr id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_row41515486"><td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p7311228"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p7311228"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p7311228"></a>注册状态</p>
    </td>
    <td class="cellrowborder" valign="top" width="81%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p55338570"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p55338570"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p55338570"></a>服务器的注册状态，包括：</p>
    <a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_ul28285082"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_ul28285082"></a><ul id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_ul28285082"><li>已注册<p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p9390324"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p9390324"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p9390324"></a>备份服务器和备份代理在eBackup备份管理系统首次部署完成后，会自动注册到eBackup备份管理系统中。</p>
    </li><li>未注册<p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p22418770"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p22418770"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p22418770"></a>系统运行过程中，如果用户手动将备份代理注销后，该服务器“注册状态”将显示为“未注册”。如果需要继续使用该备份代理执行备份恢复任务，请先将其注册到eBackup备份管理系统中。</p>
    </li></ul>
    </td>
    </tr>
    <tr id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_row442342"><td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p35829766"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p35829766"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p35829766"></a>备份管理平面IP地址</p>
    </td>
    <td class="cellrowborder" valign="top" width="81%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p16529951"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p16529951"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p16529951"></a>服务器的备份管理平面IP地址。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_row14551832"><td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p37847704"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p37847704"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p37847704"></a>内部通信平面IP地址</p>
    </td>
    <td class="cellrowborder" valign="top" width="81%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p45765156"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p45765156"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p45765156"></a>服务器的内部通信平面IP地址。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_row9233227"><td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p9693909"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p9693909"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p9693909"></a>角色</p>
    </td>
    <td class="cellrowborder" valign="top" width="81%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p47009184"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p47009184"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p47009184"></a>eBackup备份管理系统的服务器包含以下两种角色：</p>
    <a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_ul20429477"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_ul20429477"></a><ul id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_ul20429477"><li>备份服务器<p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p44174964"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p44174964"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p44174964"></a>eBackup备份管理系统的控制中心，负责备份和恢复任务的调度和监控、备份存储和备份代理的管理、生产系统的管理，并直接接受和响应用户的操作。备份服务器同时兼备备份代理的功能。</p>
    </li><li>备份代理<p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p21402327"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p21402327"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p21402327"></a>负责接收备份服务器下发的备份和恢复任务，与生产系统和备份存储直接交互，以执行备份和恢复任务。</p>
    </li></ul>
    </td>
    </tr>
    <tr id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_row58403220"><td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p33040369"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p33040369"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p33040369"></a>NTP时间同步状态</p>
    </td>
    <td class="cellrowborder" valign="top" width="81%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p59024214"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p59024214"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p59024214"></a>显示备份代理与备份服务器的时间是否同步。包含“已同步”、“未同步”和“未知”三种状态。</p>
    <p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p61455884"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p61455884"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p61455884"></a>当某个备份代理的该状态为“未同步”时，用户可以单击该备份代理后，在其右侧信息预览区中单击“同步时间”，使其与备份服务器进行时间同步。</p>
    <p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p16232044"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p16232044"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p16232044"></a>由于备份代理重启或者刚注册等原因，可能会出现“未知”状态，此时用户只需等待系统自动同步该备份代理时间。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_row1531133305819"><td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p7532113375812"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p7532113375812"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p7532113375812"></a>iSCSI启动器名称</p>
    </td>
    <td class="cellrowborder" valign="top" width="81%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p16532143325815"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p16532143325815"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p16532143325815"></a>服务器的iSCSI启动器名称。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_row1746063665818"><td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p14460936155817"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p14460936155817"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p14460936155817"></a>是否安装多路径</p>
    </td>
    <td class="cellrowborder" valign="top" width="81%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p194606367586"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p194606367586"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p194606367586"></a>服务器是否安装多路径软件。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_row3937144011587"><td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p19937164013587"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p19937164013587"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p19937164013587"></a>FusionStorage Manager管理平面浮动IP地址</p>
    </td>
    <td class="cellrowborder" valign="top" width="81%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p19371140115819"><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p19371140115819"></a><a name="zh-cn_topic_0174994048_zh-cn_topic_0170955449_p19371140115819"></a>服务器加入的FusionStorage集群的FusionStorage Manager管理平面浮动IP地址。</p>
    </td>
    </tr>
    </tbody>
    </table>

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >由于备份服务器同时兼备备份代理的功能，为方便用户查看和管理备份服务器的该项功能，在界面上将该项功能独立成一条信息进行展示。  

4.  根据服务器的注册状态，可以对备份代理执行注册或注销操作。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >不能对配置了HA或与备份服务器关联的备份代理执行注册和注销操作。  

    -   注册所选备份代理

        选择“可访问状态”为“可访问”、“注册状态”为“未注册”的备份代理，通过以下方式中的任意一种，执行注册操作。

        -   在服务器列表左上角操作按钮区单击“注册”，并在弹出的“确认”对话框中单击“确定”。
        -   在右侧信息预览区单击![](figures/icon-right.png)，并在弹出的“确认”对话框中单击“确定”。

    -   注册所有备份代理

        eBackup备份管理系统提供批量注册所有备份代理的功能，提升用户配置效率。单击“注册所有”，并在弹出的“确认”对话框中单击“确定”。系统将批量执行注册“可访问状态”为“可访问”、“注册状态”为“未注册”的备份代理命令。

    -   注销所选备份代理

        选择“注册状态”为“已注册”的备份代理，通过以下方式，执行注销操作。在右侧信息预览区单击![](figures/icon-wrong.png)，并在弹出的“确认”对话框中单击“确定”。

    >![](public_sys-resources/icon-notice.gif) **须知：**   
    >对“可访问状态”为“不可访问”，“注册状态”为“已注册”的备份代理进行注销前，还需要确保服务器满足以下条件之一：  
    >-   关闭状态。  
    >-   开机状态且服务器上的所有存储单元已经被解挂载。可以通过执行**mount |grep /opt/huawei-data-protection/ebackup/bricks**命令查看，如果存在挂载的存储单元，请执行**umount /opt/huawei-data-protection/ebackup/bricks**命令解挂载存储单元。  
    >对“可访问状态”为“可访问”，“注册状态”为“已注册”的备份代理进行注销后，检查是否服务器上的所有存储单元已经被解挂载。可以通过执行**mount |grep /opt/huawei-data-protection/ebackup/bricks**命令查看，如果存在挂载的存储单元，请执行**umount /opt/huawei-data-protection/ebackup/bricks**命令解挂载存储单元。  
    >对备份代理执行注销操作（包括相关解挂载存储单元操作）后，请停止eBackup服务并卸载eBackup备份软件，以确保该备份代理后续不再与备份服务器自动建立连接。如果后续需要再次使用该备份代理，请重新安装软件并配置备份代理。  

5.  **可选： **当需要将eBackup配置为高可用系统时，设置HA参数。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >系统中至少存在两个eBackup服务器，即至少存在一个独立的备份代理服务器，才能够将其设置为高可用系统。  


