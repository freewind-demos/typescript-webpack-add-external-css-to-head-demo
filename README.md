TypeScript Webpack Add External Css To Head Demo
================================================

没有找到好的webpack插件来插入一个css link：
- webpack-require-http: 感觉配置有点奇怪，放在`externals`里而不是`plugins`里
- webpack-external-import: GPL 3，另外配置很多，对于我的需求有点过于强大

所以直接使用loadjs这个库，也是webpack issues里推荐的一种做法。

```
npm install
npm run demo
```
