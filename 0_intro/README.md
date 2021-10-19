# 了解 OpenResty 目录结构

```
├── bin    存放 OpenResty 可执行文件, openresty 本身，以及resty restydoc 等周边工具
├── luajit LuaJIT，OpenResty 基石之一   
├── lualib 存放 Lua 库，nginx-lua-module 就位于这个位置
├── nginx  NGINX，OpenResty 基石之二
├── pod    存放文档，这里的 pod 是 perl 的一种标记语言，和 k8s 的 pod 没有关系
└── site   根据站点对库和文档进行分类？
```

