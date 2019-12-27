# Expressjs Boilerplate

参照如下链接搭建
https://softwareontheroad.com/ideal-nodejs-project-structure/

## 代码结构

`app.js`为入口

```
src
├─api           # Express route controllers for all the endpoints of the app
├─config        # 环境变量和配置相关
├─jobs          # agenda.js任务调度定义
├─loaders       # 启动过程拆分为模块
├─models        # 数据库模型
├─services      # 所有的业务逻辑
├─subscriers    # 异步任务的事件处理程序
└─types         # 对于 Typescript 的类型声明文件 ( d.ts)

```