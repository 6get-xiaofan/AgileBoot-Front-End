<h1>vue-pure-admin精简版（非国际化版本）</h1>

[![license](https://img.shields.io/github/license/pure-admin/vue-pure-admin.svg)](LICENSE)

**中文** | [English](./README.en-US.md)

## 介绍

精简版是基于 [vue-pure-admin](https://github.com/pure-admin/vue-pure-admin) 提炼出的架子，包含主体功能，更适合实际项目开发，打包后的大小在全局引入 [element-plus](https://element-plus.org) 的情况下仍然低于 `2.3MB`，并且会永久同步完整版的代码。开启 `brotli` 压缩和 `cdn` 替换本地库模式后，打包大小低于 `350kb`

## 版本选择

当前是非国际化版本哦，如果您需要国际化版本 [请点击](https://github.com/pure-admin/pure-admin-thin/tree/i18n)

## 配套视频

- [点我查看教程](https://www.bilibili.com/video/BV1kg411v7QT)
- [点我查看 UI 设计](https://www.bilibili.com/video/BV17g411T7rq)

## 配套文档

- [点我查看国内文档站](https://yiming_chang.gitee.io/pure-admin-doc)
- [点我查看国外文档站](https://pure-admin.github.io/pure-admin-doc)

## 预览

- [点我查看预览站](https://pure-admin-thin.netlify.app/#/login)

## 维护者

[xiaoxian521](https://github.com/xiaoxian521)

## 支持

如果你觉得这个项目对您有帮助，可以帮作者买一杯果汁 🍹 表示支持

<img src="https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/f69bf13c5b854ed5b699807cafa0e3ce~tplv-k3u1fbpfcp-zoom-in-crop-mark:1304:0:0:0.awebp?" width="150px" height="150px" />

## `QQ` 交流群

[点击去加入](https://yiming_chang.gitee.io/pure-admin-doc/pages/support/#qq-%E4%BA%A4%E6%B5%81%E7%BE%A4)

## 开发环境

node 版本应不小于 16 ，pnpm 版本应不小于 6  
如果您还没安装 pnpm，请执行下面命令进行安装（mac 用户遇到安装报错请在命令前加上 sudo） 如果是 windows 用户 用使用管理员 power shell 来执行

```
npm install -g pnpm
```

安装依赖

```
pnpm install
```

启动平台

```
pnpm dev
```

不管是什么源，我们都可以不用管，直接执行下面命令即可

npm config set registry https://registry.npmmirror.com

上面的命令是将本地的源换成国内源 npmmirror
(opens new window)，经过几轮测试，发现它的下载速度快且同步率高，同步频率 10 分钟一次，如果您之前的源是这个 http://registry.npm.taobao.org ，那您必须换成 npmmirror 啦，因为原淘宝 npm 域名即将停止解析

## 用法

### 安装依赖

pnpm install

### 安装一个包

pnpm add 包名

### 卸载一个包

pnpm remove 包名

我认为你应该先 `fork` 项目去开发，以便我更新时您可以同步拉取更新！！！

## ⚠️ 注意

- 精简版不接受任何 `issues` 和 `pr`，如果有问题请到完整版 [issues](https://github.com/pure-admin/vue-pure-admin/issues/new/choose) 去提，谢谢！！！

## 许可证

原则上不收取任何费用及版权，可以放心使用，不过如需二次开源（比如用此平台二次开发并开源）请联系作者获取许可！

[MIT © 2020-present, pure-admin](./LICENSE)
