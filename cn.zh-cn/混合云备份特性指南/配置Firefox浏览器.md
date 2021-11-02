# 配置Firefox浏览器<a name="cbr_03_0098"></a>

在不同的浏览器中使用https访问eBackup时，浏览器将提示网站的证书安全问题，请根据以下提示进行配置。同时由于SSL 3.0存在安全问题，可能导致设备信息泄露。因此在登录eBackup前，需要关闭浏览器对SSL 3.0的支持。

## 背景信息<a name="zh-cn_topic_0174994052_zh-cn_topic_0170955401_section10302646"></a>

本节以Mozilla FireFox 26版本为例进行说明。

## 操作步骤<a name="zh-cn_topic_0174994052_zh-cn_topic_0170955401_section25614956"></a>

1.  如果页面显示“此连接不受信任”，单击“我已充分了解可能的风险 \> 添加例外”。
2.  在弹出的对话框中单击“确认安全例外”。
3.  关闭浏览器对SSL 3.0的支持。

    >![](public_sys-resources/icon-notice.gif) **须知：** 
    >SSL 3.0存在安全问题，可能导致设备信息泄露。请在登录eBackup前，关闭浏览器对SSL 3.0的支持。

    1.  在浏览器地址栏中输入**about:config**。
    2.  将“security.tls.version.min”值设置为“1”。


