# Changelog

## 2018-02-28

- [UPGRADE] [wxml-loader](https://github.com/Cap32/wxml-loader) 更新至 `v0.1.2`


## 2017-12-31

- [FIXED] 修复打包压缩代码时 `<inline><block/></inline>` 的问题
- [UPGRADE] [create-wxapp-page](https://github.com/cantonjs/create-wxapp-page) 更新至 `v2.0.2`
- [NEW] 增加 `create-component` script, 支持创建 `Component`


## 2017-12-2

- [NEW] 支持自动打包 `tabbar` 图标，无需 `copy-webpack-plugin` 等额外配置
- [UPGRADE] [wxapp-webpack-plugin](https://github.com/Cap32/wxapp-webpack-plugin) 更新至 `v0.17.1`


## 2017-11-30

- [FIXED] 修复 `yarn build` 提示 ['Component' is not defined](https://github.com/cantonjs/wxapp-boilerplate/issues/15) 问题 (@julytian)


## 2017-11-18

- [NEW] 支持微信小程序 [Components](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/custom-component/)
- [UPGRADE] [wxapp-webpack-plugin](https://github.com/Cap32/wxapp-webpack-plugin) 更新至 `v0.16.0`
- [UPGRADE] [node-sass](https://github.com/sass/node-sass) 更新至 `v4.6.1`
- [UPGRADE] [sass-loader](https://github.com/webpack-contrib/sass-loader) 更新至 `v6.0.6`


## 2017-10-27

- [NEW] 增加默认采用 [webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) 来展示 webpack 状态
- [UPGRADE] webpack 更新至 `v3.8.1`
- [UPGRADE] [create-wxapp-page](https://github.com/cantonjs/create-wxapp-page) 更新至 `v1.2.0`


## 2017-10-26

- [BREAKING] 非 `.js` （如 `.json`, `.wxss`, `.wxml`, `.png` 等等 ）文件在编译后将保持原来的文件目录结构
- [BREAKING] 资源文件引用也支持使用相对路径，例如 `pages/index/index.wxml` 里，可以使用相对路径 `../../templates/test.wxml` 来引用，保持小程序原生的开发行为
- [FIXED] 修复最新版微信开发者工具自动检测编译时出现错误
- [FIXED] 修复 `Can not resolve "vertx"` 警告


## 2017-09-22

- [NEW] 支持兼容支付宝小程序
- [FIXED] 修复 stylelint 错误提示
