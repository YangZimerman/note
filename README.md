# note - 个人笔记

### basis 基础类
- markdown语法
- html
- css
- javascript

### reading note 读书笔记类
- 高性能网站建设指南 《高性能网站建设指南》
- js精粹笔记 《javascript语言精粹》 

---
> github ssh代理
```
# ~/.ssh/config
Host github.com
    ProxyCommand=socat - PROXY:127.0.0.1:%h:%p,proxyport=7890
```