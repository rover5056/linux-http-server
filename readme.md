# 欢迎使用Linux-http-server
Linux上将静态文件目录变成服务器的工具

A tool on Linux that turns static folders into accessible servers
## 安装 installation

```
npm i linux-http-server -g
```

## 启动  start


```
linux-http-server
```
>  会在当前目录下开设端口，默认index.html为首页，也可自定义      
>  index.html is the default entry and you can set it yourself

---



## 参数

```
linux-http-server -p 3000               //设置端口为3000             Set the port to 3000
linux-http-server -d /usr               //设置 /usr 目录为根目录      Set the / usr directory to the root directory
linux-http-server -f /usr/local/         //启动目录为/usr/local/     The boot directory is / usr / local /
```

