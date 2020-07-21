# web-live-quickstart

### 配置

修改 config.js

```js
const Config = {
  appkey: '', // appkey
  server: '',
};
```

### 主播端

使用 `localhost` 或 `https` 打开 anchor.html

1、点击加入房间

2、点击发布音视频流

3、点击发布屏幕共享

4、点击设置混流

### 观众端

使用 `localhost` 或 `https` 打开 audience.html

1、将主播端 LiveUrl 复制到观众端输入框内

2、点击观看直播

### server 启动

server 用户获取用户 token

#### 安装依赖
```
npm install
```

#### 启动
```
npm run serve
```

#### 启动成功

得到 server 地址填写到 config.js 中。