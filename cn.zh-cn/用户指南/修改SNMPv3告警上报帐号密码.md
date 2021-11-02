# 修改SNMPv3告警上报帐号密码<a name="cbr_03_0043"></a>

该任务指导用户修改客户端SNMP v3协议告警上报帐号的密码，以提升系统运维安全性。

## 前提条件<a name="section1431331911012"></a>

-   已获取管理控制台的登录帐号和密码。
-   已获取服务器的登录帐号和密码。

## 背景信息<a name="section8483709169"></a>

本节介绍如何修改安装在Windows操作系统和Linux操作系统的客户端的SNMPv3告警上报帐号密码。

>![](public_sys-resources/icon-notice.gif) **须知：** 
>客户端SNMP v3的授权认证密码和数据加密密码设置为相同密码时，存在安全风险，为了确保系统安全，建议将客户端SNMP v3的授权认证密码和数据加密密码设置为不同的密码。

初始的授权认证密码请联系技术人员获取。

>![](public_sys-resources/icon-note.gif) **说明：** 
>密码必须符合密码复杂度要求，复杂度要求如下：
>-   密码长度为8到16个字符
>-   密码必须含特殊字符\`\~!@\#$%^ &\*\(\)-\_=+\\|\[\{\}\];:'",<.\>/?
>-   密码必须含有如下至少两种字符组合：
>    -   大写字母
>    -   小写字母
>    -   数字
>-   密码不与帐号或者帐号的倒写一样
>-   密码不与旧密码一样
>-   密码中不能包含空格

## Windows系统操作步骤<a name="section559135917224"></a>

1.  登录已安装客户端的云服务器。
2.  打开命令行窗口，进入“_安装路径_**\\bin**”目录。
3.  输入**agentcli.exe chgsnmp**命令，输入客户端登录帐号的密码，按“Enter”。

    ```
    Please choose operation: 
    1: Change authentication password 
    2: Change private password 
    3: Change authentication protocol 
    4: Change private protocol 
    5: Change security name 
    6: Change security Level 
    7: Change security model 
    8: Change context engine ID 
    9: Change context name 
    Other: Quit 
    Please choose:
    ```

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >“admin”为安装客户端时设置的用户名。

4.  选择需要修改的授权认证密码或数据加密密码对应序号，按“Enter”。
5.  输入旧密码，按“Enter”。
6.  输入新密码，按“Enter”。
7.  再次输入新密码，“Enter”。完成修改密码。

## Linux系统操作步骤<a name="section366159192216"></a>

1.  使用服务器密码登录Linux系统服务器。
2.  执行**TMOUT=0**命令，防止“PuTTY”超时退出。

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >执行该命令后，当前系统在无操作时会保持运行状态，存在安全风险，为了确保系统安全，请在完成相应操作后，执行**exit**退出当前系统。

3.  执行**su - rdadmin**命令，切换为“rdadmin”用户。
4.  执行**/home/rdadmin/Agent/bin/agentcli chgsnmp**命令，输入客户端登录帐号的密码，按“Enter”。

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >客户端安装路径固定为“/home/rdadmin/Agent”。

    ```
    Please choose operation: 
    1: Change authentication password 
    2: Change private password 
    3: Change authentication protocol 
    4: Change private protocol 
    5: Change security name 
    6: Change security Level 
    7: Change security model 
    8: Change context engine ID 
    9: Change context name 
    Other: Quit 
    Please choose:
    ```

5.  选择需要修改的授权认证密码或数据加密密码对应序号，按“Enter”。
6.  输入旧密码，按“Enter”。
7.  输入新密码，按“Enter”。
8.  再次输入新密码，按“Enter”。完成修改密码。

