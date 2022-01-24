## webpack

#### 安装

```shell
npm i webpack webpack-cli -D
```

#### Loaders

> webpack只支持js和json两种类型的文件，通过Loaders去支持其他格式的文件类型，并将其转化为有效的模块，并且可以添加到依赖图中。
> **本身是一个函数，接受源文件作为参数，返回转化结果**



#### babel

```shell
npm i @babel/core @babel/preset-env babel-loader -D
```

#### style-loader css-loader less-loader
```shell
npm i style-loader css-loader less less-loader@5.0.0 -D
```


#### file-loader & url-loader
- file-loader
- url-loader
  > url-loader相对file-loader,可以将小文件自动转为base64文件
```shell
npm i file-loader -D
```

#### WDS（热更新策略）
> webpack-dev-server
> https://webpack.docschina.org/api/webpack-dev-server/#root