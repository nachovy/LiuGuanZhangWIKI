# 《魂穿东汉末年》人物志

合集地址：[https://space.bilibili.com/592204565/lists/8021520?type=season](https://space.bilibili.com/592204565/lists/8021520?type=season)

请从左侧目录进入分集剧情或人物百科。

## 本地构建

本项目使用 HonKit，不再依赖已经停止维护的全局 `gitbook-cli`。请在项目根目录执行：

```bash
npm install
npm run build     # 生成 _book
npm run serve     # 本地预览
```

HonKit 6 没有旧版 GitBook 的 `install` 子命令，插件随项目依赖一起安装；如需保留旧操作习惯，可使用 `npm run install-book`（它等同于 `npm install`）。项目支持 Node.js 18 或更高版本，依赖由项目本地的 `honkit` 提供。
