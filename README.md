https://segmentfault.com/a/1190000039157365#item-4-6

- 子后台技术栈不一致那么根目录的能做什么，lint、babel 这些东西也不一样。而且子后台的意义就是让历史项目可以跑，好像不适用于 mono repo
- 每个项目有自己的 lint，那根目录需要安装 lint 不 

## 技术栈
- 锁定环境：Volta
- 统一命令脚本：scripty
- lerna
- npm 包本地发布：Verdaccio
