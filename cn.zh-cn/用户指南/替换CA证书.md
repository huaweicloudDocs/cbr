# 替换CA证书<a name="cbr_03_0045"></a>

## 操作场景<a name="section22941543135013"></a>

CA证书相关的数字文件，由认证权威经过数字签名，包含公开密钥拥有者信息、公开密钥签发者信息、有效期以及一些扩展信息。通过CA证书在客户端和服务器之间建立安全通道保证双方传递信息的安全性。

当CA证书不能满足当前的安全需求，或者CA证书已经过期时，需要替换新的CA证书，以保证系统的安全性。

## 前提条件<a name="section396119314550"></a>

-   已获取弹性云服务器的登录帐号和密码。
-   已获取新的CA证书。

## Linux系统操作步骤<a name="section11610114511246"></a>

1.  登录已安装客户端的Linux服务器。
2.  执行以下命令，防止系统超时退出。

    **TMOUT=0**

3.  执行以下命令，切换至“rdadmin”用户。

    **su - rdadmin**

4.  执行以下命令，进入客户端启动/停止脚本所在路径。

    **cd /home/rdadmin/Agent/bin**

5.  执行以下命令，停止客户端运行。

    **sh agent\_stop.sh**

6.  执行以下命令，进入CA证书所在路径。

    **cd /home/rdadmin/Agent/bin/nginx/conf**

7.  执行以下命令，将原来的CA证书文件删除。

    **rm bcmagentca.crt**

8.  将新的CA证书文件拷贝至**/home/rdadmin/Agent/bin/nginx/conf**目录中，并重命名为**bcmagentca.crt**。
9.  执行以下命令，修改CA证书属主。

    **chown rdadmin:rdadmin bcmagentca.crt**

10. 执行以下命令，修改CA证书权限。

    **chmod 400 bcmagentca.crt**

11. 执行以下命令，进入客户端启动/停止脚本。

    **cd /home/rdadmin/Agent/bin**

12. 执行以下命令，启动客户端。

    **sh agent\_start.sh**


## Windows系统操作步骤<a name="section146172455243"></a>

1.  登录到已安装客户端的弹性云服务器。
2.  进入“_安装路径_**\\bin**”目录中。
3.  执行**agent\_stop.bat**脚本，停止客户端运行。
4.  进入“_安装路径_**\\nginx\\conf**”目录。
5.  删除**bcmagentca.crt**证书文件。
6.  将新的CA证书文件拷贝到“_安装路径_**\\nginx\\conf**”目录中，并重命名为**bcmagentca.crt**。
7.  再次进入“_安装路径_**\\bin**”目录。
8.  执行**agent\_stop.bat**脚本，启动客户端。

