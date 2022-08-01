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
    
3.BBR 加速脚本

```shell
bash <(curl -Lso- https://git.io/kernel.sh)
```
            
</details>

<details>
    <summary>JetBrains 激活</summary>
    
```sh
-javaagent:C:\Tools\jetbra\ja-netfilter.jar=jetbrains
```
    
</details>
    
<details>
    <summary>Typecho 多域名设置</summary>
* 在Typecho网站根目录下config.inc.php中加上
    
```php
/**开启动态域名/跨域补救**/
define('__TYPECHO_DYNAMIC_SITE_URL__',true);
```
    
</details>
