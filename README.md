# vueAdmin-template
vue-admin
#目录结构

├── build                      // 构建相关  
├── config                     // 配置相关
├── src                        // 源代码
│   ├── common                // 公共样式
│         ├── assets          // 主题 字体等静态资源
│         ├── icon            // 图标
│         ├── styles          // 全局样式
│   ├── components             // 全局公用组件
│   ├── filtres                // 全局filter
│   ├── router                 // 路由
│   ├── store                  // 全局store管理
│   ├── utils                  // 全局公用方法
│   ├── view                   // view
│   ├── App.vue                // 入口页面
│   └── main.js                // 入口 加载组件 初始化等
├── static                     // 第三方不打包资源
│   ├── jquery
├── .babelrc                   // babel-loader 配置
├── eslintrc.js                // eslint 配置项
├── .gitignore                 // git 忽略项
├── favicon.ico                // favicon图标
├── index.html                 // html模板
└── package.json               // package.json


## Build Setup

``` bash
# Install dependencies
npm install

# 可以通过如下操作解决npm速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# serve with hot reload at localhost:80
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

