# zan-uitest
本项目使用 `jest` 作为测试框架，将 `uitest` 录制的代码放在本地的 `puppeteer` 回放。请使用 `node` 版本大于`8.9.0`。
## 使用
```
git clone git@github.com:wulv/zan-uitest.git
cd zan-uitest
# 下载依赖，如果未安装，使用npm install -g yarn安装
yarn
# 将uitest 代码贴入index.test.js
npm test
```
## 链接
- [jest](http://jestjs.io/docs/en/getting-started) 
- [puppeteer](https://github.com/GoogleChrome/puppeteer)
