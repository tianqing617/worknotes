## 5月6日 -- 5月12日

### 5.6 Monday
1. 编码替换工作。基础数据部分编码问题。完成！
2. 版本号提醒功能。完成！
3. 凭证状态支持，不需要生成凭证。完成！

### 5.7 Tuesday
1. npm run build时，theme文件夹不会参与打包，样式入口为styles中的index.scss。
2. npm run theme时，遍历theme中的文件，生成对应的样式文件。
3. 样式内容包含两部分：vue文件中的样式和styles文件夹中的样式。
3. 实现步骤：
   1. 测试样式按需加载和全量加载打包配置上的区别。
   2. 配置最简单的webpack配置，运行npm run themes时从index.scss中提取样式，生成css文件。
   3. 注意：生成的css文件要包含vue文件和styles文件夹中的样式；若生成除css文件外，还有其它多余文件，则删除。
   4. 运行指令时，根据themes文件夹中的文件，生成一个主题样式。
   5. 运行指令，根据themes文件分别生成各个主题样式。

### 5.8 Wednesday
1. 测试样式按需加载和全量加载打包配置上的区别。
2. 配置最简单的webpack配置，运行npm run themes时从index.scss中提取样式，生成css文件。

优化：
1. url地址与页面表现不一致问题。
1. api地址重复打包和按业务分模块。
1. 搭建自动化测试框架。
1. 开发环境可以查看服务器状态。
1. 无论登陆还是系统单页面，manifest打包在一起。
1. 联查优化。
1. 使用vuex进行更规范的全局状态管理。利用全局状态管理，实现发布订阅模式。
1. 路由name优化，不和path是一样的。
1. 文件夹不是独立的模块，依赖模块外项目的其它文件，容易形成循环依赖问题.