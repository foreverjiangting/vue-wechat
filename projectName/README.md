#项目结构
├── README.md           
├── dist                     // 项目build目录，最终只需要dist文件即可
├── config                   // 环境变量和入口，出口配置
├── static                   // 静态资源目录
├── build                    // 项目的配置文件目录
│   ├── dev-server.js        // 开发的服务配置
│   ├── webpack.dev-conf.js  // 开发的Webpack 配置文件
│   ├── webpack.prod-conf.js // 生产的Webpack 配置文件
│   ├── webpack.base-conf.js // 基本的Webpack 配置文件
├── package.json             // 项目配置文件
├── src                      // 生产目录
│   ├── assets               // css js 和图片资源
│   ├── data                 // 数据文件
│   ├── components           // 各种组件
│   ├── views                // 各种页面
│   ├── directives           // 各种指令
│   ├── filters           // 各种过滤器
│   ├── router            // 路由配置
│   └── APP.vue             // 根组件
│   └── main.js               // Webpack 预编译入口         
├── index.html               // 项目入口文件

# 项目启动

npm install

# serve with hot reload at localhost:8080
npm run dev

#手动在主目录中创建一个dist文件，用来容乃打包压缩后的文件
npm run build

npm run build --report

```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
