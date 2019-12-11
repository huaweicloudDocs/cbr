# 配置Chrome浏览器<a name="cbr_03_0099"></a>

在不同的浏览器中使用https访问eBackup时，浏览器将提示网站的证书安全问题，请根据以下提示进行配置。同时由于SSL 3.0存在安全问题，可能导致设备信息泄露。因此在登录eBackup前，需要关闭浏览器对SSL 3.0的支持。

## 背景信息<a name="zh-cn_topic_0174994053_zh-cn_topic_0170955568_section27159916"></a>

本节以Google Chrome 37版本为例进行说明。

## 操作步骤<a name="zh-cn_topic_0174994053_zh-cn_topic_0170955568_section43112656"></a>

1.  如果页面提示“您的连接不是私密连接”时，依次单击“高级”和“继续前往xxx.xxx.xxx.xxx（不安全）”。
2.  关闭浏览器对SSL 3.0的支持。

    >![](public_sys-resources/icon-notice.gif) **须知：**   
    >SSL 3.0存在安全问题，可能导致设备信息泄露。请在登录eBackup前，关闭浏览器对SSL 3.0的支持。  

    1.  完全关闭Chrome浏览器。
    2.  复制并粘贴一个Chrome浏览器的快捷方式。
    3.  在新的快捷方式上单击鼠标右键，在弹出的快捷菜单中选择“属性”，弹出“属性”对话框。
    4.  在“目标”输入框中字段的末尾输入一个空格和“--ssl-version-min=tls1”。


