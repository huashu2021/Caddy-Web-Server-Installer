This is a simple script to setup Caddy web server and maintain on Linux based OS

![](https://i.imgur.com/VetlQdc.png)

**v2 not supported**

### Quick Installation

`wget https://git.io/vra5C -O - -o /dev/null|sudo bash`

See [Installation](https://github.com/sayem314/Caddy-Web-Server-Installer/wiki/Installation) for detailed instructions.

#### Tested Operating System

- Ubuntu - 14.x, 15.x, 16.x, 18.x

- Debian - 7.x, 8.x, 9.x, 10.x

- CentOS - 6.8 and 7.2

#### 然后使用下列命令进行操作
caddy start  #开启Caddy Web Server
caddy stop  #停止Caddy Web Server
caddy reload  #重载Caddy Web Server
caddy restart  #重启Caddy Web Server
caddy status  #查看Caddy Web Server状态
caddy install  #安装Caddy Web Server
caddy edit  #编辑配置文件Caddyfile
caddy service  #使Caddy Web Server成为一项服务(upstart/systemd)
caddy update  #升级Caddy Web Server
caddy delete  #卸载Caddy and data
caddy about  #关于Caddy Web Server
caddy version  #检测脚本/Caddy/PHP5-fpm版本信息

#### Example command to install with plugins:

`caddy install http.cache,http.filemanager,http.ipfilter,http.ratelimit`

See list of available commands [here.](https://github.com/sayem314/Caddy-Web-Server-Installer/wiki/Command-List)

#### Contribute?

Contributions are always welcome - if you have any code to contribute, simply fork this, create a new branch and submit a pull request! Otherwise, if you find any bugs or issues, please open an issue!

### Donations

If you want to show your appreciation, you can donate me on [ko-fi](https://ko-fi.com/Z8Z5KDA6) or [buy me a coffee](https://www.buymeacoffee.com/sayem). Thanks!

> Made with :heart: & :coffee: by Sayem
