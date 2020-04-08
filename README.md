1、安装node.js，安装完node.js之后，npm也会自动安装

查询是否安装成功的命令：

node -v

npm -v

2、全局安装脚手架工具vue-cli，命令如下：

npm install --global vue-cli

3、vue项目初始化命令如下，若没有安装webpack，则先安装webpack

npm install -g webpack

vue init webpack myVue
注：安装过程 中有个选项（Use ESLint to line your code ?选择 No ）

4、进入到myVue目录下，使用npm install 安装package.json包中的依赖

命令如下：

cd myVue

npm install

5、运行项目：

npm run dev



项目目录：
uniapp.dcloud.io

app.vue应用配置，用来配置app全局样式以及监听
main.js vue初始化入口文件
mainfest.json 配置应用名称，appid，logo ,版本等打包信息
pages.json   配置页面路由，导航条，选项卡等页面类信息
uni.scss 内置sass变量 可以直接使用

pages--index----index.vue页面组件


static  静态资源
logo.png


https://uniapp.dcloud.io/

npm install sass-loader node-sass
在style标签中加入属性<style lang='scss'>
  
  
  
  
