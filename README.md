
## 启动步骤

```
npm install
npm run serve  // 开发模式
npm run build  // 打包
```


## 目录结构说明

```
ui-vue-pc
├── README.md
├── babel.config.js
├── doc               // 组件使用演示
│   ├── doc-item.vue  // 文档模板组件
│   ├── doc.vue       // 组件文档集合
│   └── ...
├── package-lock.json
├── package.json
├── postcss.config.js
├── public
│   ├── favicon.ico
│   └── index.html
├── src
│   ├── App.vue     // 根组件
│   ├── assets      // 静态资源文件夹
│   │   ├── iconfont
│   │   │   └── ...
│   │   ├── images
│   │   │   └── ...
│   │   └── sass
│   │       ├── _common.scss  // 全局公用样式
│   │       ├── _mixin.scss   // 所有的公用 mixin
│   │       ├── _resetPc.scss // 重置样式
│   │       └── main.scss     // 样式主入口
│   ├── components  // 公共组件 本项目的重点文件夹，组件源码都在这里
│   │   └── ...
│   ├── main.js     // 脚本主入口
│   ├── router.js   // 路由
│   ├── store       // vuex
│   │   ├── actions.js
│   │   ├── index.js
│   │   ├── modules
│   │   └── mutations.js
│   ├── views  // 视图文件夹，存放所有的页面文件
│   │   └── ...
└── test       // 测试文件夹
    └── ...
```


## 说明
在工作中用了社区的一些成熟的UI框架，因而有些心得，于是自己写了一些练练手
