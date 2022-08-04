<details>
    <summary>Hax - Woiden</summary>
1.需要卸载 Apache2
    
```shell
service apache2 stop 
systemctl disable apache2
```
    
2.安装 Curl
* Ubuntu/Debian 系统
    
```shell
apt-get update -y && apt-get install curl -y
```
    
* Centos 系统
    
```shell
yum update -y && yum install curl -y
```
    
3.UFW 防火墙

```sh
apt-get install ufw
    
```sh
ufw enable
    
ufw default deny
    
ufw allow 22
    
ufw allow 443
    
ufw allow 8443
    
ufw delete allow 8443
    
ufw status
```
    
4.BBR 加速脚本

```shell
bash <(curl -Lso- https://git.io/kernel.sh)
```
            
</details>

<details>
    <summary>iPV6 - aaPanel</summary>
        
```sh
echo "2606:4700:3034::ac43:ab07 brandnew.aapanel.com
2606:4700:3034::ac43:ab07 www.aapanel.com
2606:4700:3034::ac43:ab07 aapanel.com" >> /etc/hosts
```
</details>
    
<details>
    <summary>JetBrains 激活</summary>
    
```sh
-javaagent:C:/Tools/jetbra/ja-netfilter.jar=jetbrains
--add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED
--add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED
```
    
</details>
    
<details>
    <summary>Typecho 动态域名</summary>
    
* 在Typecho网站根目录下config.inc.php中加上
    
```php
/**开启动态域名/跨域补救**/
define('__TYPECHO_DYNAMIC_SITE_URL__',true);
```
    
</details>
