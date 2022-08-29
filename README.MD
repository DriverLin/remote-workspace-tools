## WSTUNNEL

https://github.com/erebe/wstunnel

基于websocket的隧道

在远端开启服务端

```
wstunnel --server ws://0.0.0.0:8080
```

服务端映射后URL为 https://8080-harlequin-koi-m6ker0oz.ws-us47.gitpod.io/

则对应的WSURL为 wss://8080-harlequin-koi-m6ker0oz.ws-us47.gitpod.io

https改为wss 最后的/去掉

本地执行 
```
wstunnel -D 8888 wss://8080-harlequin-koi-m6ker0oz.ws-us47.gitpod.io 
```

即可开启本地SOCKS5代理