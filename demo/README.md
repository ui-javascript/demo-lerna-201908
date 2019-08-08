# README

- lerna管理package https://juejin.im/post/5d231eac6fb9a07ea33c398f

```shell 
lerna init

# 创建几个小项目
cd packages
npm init

# cd melt-ext 添加一些依赖
lerna add melt-core --scope=melt-ext
lerna add axios --scope=melt-ext
...


```
