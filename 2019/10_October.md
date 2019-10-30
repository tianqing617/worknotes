## 10月08日 -- 10月13日

### 10.08 Tuesday
1. 新建账套时，会计参数数据同步问题。
2. 系统管理状态下无菜单，则切换账套隐藏系统管理。

### 10.09 Wednesday
1. 新建账套时，会计参数数据同步问题。完成！
2. 系统管理状态下无菜单，则切换账套隐藏系统管理。

### 10.10 Tuesday
1. 调试对账接口，能做的什么程度就做到什么程度。

## 10月14日 -- 10月20日

### 10.14 Monday
1. 收银交款单详情页面。

### 10.18 Friday
1. 保存之前合法性检验。
2. 保存功能。
3. 汇总表展示。

## 10月21日 -- 10月27日

### 10.24 Thursday
1. 对账页面完结。

### 10.25 Friday
1. bug

## 10月28日 -- 11月03日

### 10.28 Monday
1. 收银日期、收银门店、备注保存失败问题。
2. 制单人、打印次数不展示。
3. 打印功能。
4. 每个按钮一个一个测试。

### 10.29 Tuesday
1. 禅道BUG。

### 10.30 Wednesday
1. 凭证导出模版对标用友U8凭证导入模版。



1. 缓存优化vuex。
1. 每次上线删除hview的 ^ 符号。
优化：
1. 联查优化。
1. url地址与页面表现不一致问题。
1. api地址重复打包和按业务分模块。
1. 开发环境可以查看服务器状态。
1. 无论登陆还是系统单页面，manifest打包在一起。
1. 使用vuex进行更规范的全局状态管理。利用全局状态管理，实现发布订阅模式。
1. 缓存数据也应放入vuex当中。
1. pending数组中的数据也应放在vuex中维护。
1. 文件夹不是独立的模块，依赖模块外项目的其它文件，容易形成循环依赖问题。
1. vue错误追踪https://sentry.io/for/vue/