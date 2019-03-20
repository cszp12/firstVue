# firstVue
webpack的使用及vue的简单使用

npm的webpack安装：
npm i webpack vue vue-loader

webpack:
webpack.js.org/configuration/

npm删除包，安装包
npm uninstall webpack-dev-server
npm install webpack-dev-server@2.9.

没有发布的下个版本（beta版本)
npm i xxxx@next -D

更新到最新的版本
npm i webpack -D
webpack4的执行都在webpack-cli,升级
npm i webpack webpack-dev-server webpack-merge webpack-cli -D

optimization:{
splitChunks:{
chunks: 'all'
},
//区别于模块的id名称，适合缓存迭代
runtimeChunk: true
} 等同于
plugins: defaultPluins.concat([
new webpack.optimize.CommonsChunkPlugin({
name : 'vendor'
}),
new webpack.optimize.CommonsChunkPlugin({
name : 'vendor'
})
})


VUE2 
1、数据绑定
2、vue文件开发方式
3、render方法（每次修改更改文件）

npm i extract-text-webpack-plugin

web-pack-dev-server调试
es6\es7的语法

1、vue开发基于webpack
2、理解vue的过程
