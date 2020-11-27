# Nexus

### why privite npm
>为了项目组内生态的建设，减少重复开发的问题，引入了私有的npm仓库。试想一下，当你仅需要开发一个组件，并发布这个组件到私有npm上，其他项目租成员都能享受到这个组件带来的便利。

### 如何查看线上仓库依赖包
+ [访问Nexus地址](http://all.bnuz.edu.cn:8606/#browse/browse)
+ 使用账号密码登录
+ 点击Browse
+ 点击zhsj-local-npm进入查看npm包

### 如何使用
+ 将npm源指向私有仓库  http://all.bnuz.edu.cn:8606/repository/zhsj-local-npm/
+ npm install 你想要的依赖包

:::warning
值得注意的是你在安装完私有仓库包时需要把你的npm源指向回官方源或淘宝源,以面其他的npm包安装失败
:::