# lerna-test
:busts_in_silhouette: a monorepo with lerna demo

### lerna 作用
帮你解决多 package 相互依赖的版本问题——发布繁琐，有牵一发而动全身内味

### 主要流程
1. 任何一个由`git`托管的项目文件夹
2. `lerna init`：初始化一个 lerna monorepo 项目，生成基本的项目骨架
3. 在`packages`文件夹中添加您的子`package`，然后终端进入该文件夹`npm init -y`初始化该`package`
4. 在该子`package`的`package.json`文件中添加依赖文件
5. 然后终端回到项目根目录，执行`lerna bootstrap`，便可发现您的子`package`的依赖都已经装上了

### 参考文档：
[lerna官方中文文档](https://www.lernajs.cn/)
[掘金博客：lerna管理前端模块最佳实践](https://juejin.cn/post/6844903568751722509)
