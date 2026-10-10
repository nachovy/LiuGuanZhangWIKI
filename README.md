# 《魂穿东汉末年》人物志

请从左侧目录进入分集剧情或人物百科。

## 本地构建

本项目使用 HonKit，不再依赖已经停止维护的全局 `gitbook-cli`。请在项目根目录执行：

```bash
npm install
npm run build     # 生成 _book
npm run serve     # 本地预览
```

如果需要安装 `book.json` 中声明的插件，使用 `npm run install-book`。Node.js 18 或更高版本均可；依赖由项目本地的 `honkit` 提供，避免调用旧版全局 GitBook 的 `graceful-fs`。
