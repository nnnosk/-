# HAX - Woiden

<details>
    <summary>Woiden 需要卸载 Apache2</summary>
    
```shell
service apache2 stop 
systemctl disable apache2
```
    
</details>

1.Ubuntu/Debian 系统安装 Curl

```shell
apt-get update -y && apt-get install curl -y
```

<details>
    <summary>Centos 系统安装 Curl</summary>
    
```shell
yum update -y && yum install curl -y
```
    
</details>

2.BBR 加速脚本

```shell
bash <(curl -Lso- https://git.io/kernel.sh)
```

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


