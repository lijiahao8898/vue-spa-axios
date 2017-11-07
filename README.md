## vue-spa-axios
vue单页面的架子工程 - 欢迎初次学习和使用vue

期望：
* 满足快速开发需求，直接能进行使用开发。
* 满足`SPA`的开发。
* 满足api接口调用的方式请求。
* 是一个后台页面工程。
* etc...

#### Getting Started
just clone this pro

```
git clone https://github.com/lijiahao8898/vue-spa-axios.git

cd vue-spa-axios

npm install / sudo npm install

npm start
```

#### webpack
plugin：
* copy-webpack-plugin - 复制文件和目录
* html-webpack-plugin - 快速生成html
* webpack-dev-server - 开发环境的模块热替换
* CommonsChunkPlugin - 提取公共部分
* uglifyjs-webpack-plugin - 压缩代码
* extract-text-webpack-plugin - 提取css到单独的文件

#### introduce branch
* master - vue spa + axios + elementUI2.0

#### what did i use ?
* vue
* vue-router
* elementUI
* webpack
* axios

#### question
* 使用 `mode: 'history',` 的时候，在此刷新当前路径会报错。具体报错如下：
```
VM2662:47 Refused to apply inline style because it violates the following Content Security Policy directive: "default-src 'self'". Either the 'unsafe-inline' keyword, a hash ('sha256-cEmJ9wfQpnZLR35+jGeZk1WmknBbXo0CyiXREeJHUGo='), or a nonce ('nonce-...') is required to enable inline execution. Note also that 'style-src' was not explicitly set, so 'default-src' is used as a fallback.
```


