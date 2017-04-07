
## 项目结构

* build/                         【开发的服务配置】
    - dev-server.js              【开发的服务配置】
    - webpack.dev-conf.js        【开发的Webpack 配置文件】
    - webpack.prod-conf.js       【生产的Webpack 配置文件】
    - webpack.base-conf.js       【基本的Webpack 配置文件】
* config/                        【环境变量和入口，出口配置】                       
* node_modules/                  【node 依赖】
* dist/                          【项目build目录，最终只需要dist文件即可】
* src/                           【源文件】
    - data/                      【测试数据】
    - assets/                    【资源文件】
    - components/                【组件文件】
      - common/                  【公共组件】
      - login/                   【用户登录组件】
    - views/                     【页面文件】
    - router /                   【路由文件】
    - directives/                【指令文件】
    - filters/                   【过滤器文件】
*  static                        【静态资源目录】
* .babelrc                       【配置一些文件】
* .editorconfig                  【编辑器统一配置文件】
* .gitignore                     【gitignore 文件】
* package.json                   【npm 配置文件】
* README.md                      【项目说明】
* index.html                     【项目人口文件】
* LICENSE

## 项目启动

 * npm install
 * npm run dev
 * serve with hot reload at localhost:8080
 
## 打包项目

 * 手动在主目录中创建一个dist文件，用来容乃打包压缩后的文件
 * npm run build
 * npm run build --report

## 细节问题

 >这里所有的页面全部封装成了组件,所以我们需要写组件!!!!!!
 >组件需要模块化，我目录结构可能不完整，你们看下
 >写代码的时候，注意命名规则，驼峰或者下划线都行
 >这里使用的是webpack打包，我们最终只需要得到dist文件即可，然后直接将dist进行发布上线


