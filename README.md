# Typecho 多域名设置
* 在Typecho网站根目录下config.inc.php中加上

```php
/**开启动态域名/跨域补救**/
define('__TYPECHO_DYNAMIC_SITE_URL__',true);
```

# Hax-V2ray

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

3.WARP 脚本
```shell
wget -N --no-check-certificate https://raw.githubusercontents.com/Misaka-blog/Misaka-WARP-Script/master/misakawarp.sh && bash misakawarp.sh
```

4.Xray 脚本
```shell
wget -N --no-check-certificate https://raw.githubusercontents.com/Misaka-blog/Xray-script/master/xray.sh && bash xray.sh
```

快捷方式:
```shell
bash xray.sh
```

```sh
x-ui              - 显示管理菜单 (功能更多)
x-ui start        - 启动 x-ui 面板
x-ui stop         - 停止 x-ui 面板
x-ui restart      - 重启 x-ui 面板
x-ui status       - 查看 x-ui 状态
x-ui enable       - 设置 x-ui 开机自启
x-ui disable      - 取消 x-ui 开机自启
x-ui log          - 查看 x-ui 日志
x-ui v2-ui        - 迁移本机器的 v2-ui 账号数据至 x-ui
x-ui update       - 更新 x-ui 面板
x-ui install      - 安装 x-ui 面板
x-ui uninstall    - 卸载 x-ui 面板

```
