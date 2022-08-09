<details>
    <summary>Hax - Woiden</summary>
1.卸载 Apache2
    
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
```   
    
```sh
ufw enable
```
    
```sh
ufw default deny
```
    
```sh
ufw allow 
```

```sh
ufw delete allow 
```
   
```sh
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

<details>
    <summary>Beyond Compare 4</summary>

1. 在搜索栏中输入 regedit, 打开注册表

2. 删除项目：

```sh
计算机\HKEY_CURRENT_USER\Software\Scooter Software\Beyond Compare 4\CacheId
```
    
</details>
