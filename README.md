# webapp-starter 🧰

一直使用 React 和 Vue 的脚手架开始项目的你，突然开始使用 Three.js 或 Pixi.js 引擎写起了图形交互应用甚至是小游戏，是不是突然手足无措？

> “我该怎么搭一个 TypeScript、Babel、Webpack 加上 eslint、jest 等各种工具集成的环境？最好还有一个支持热加载的开发服务器？”🤔

其实配置起来也是很简单的，麻烦之处在于这些配置可能不是经常用到（通常配置完成之后到下一个项目开始可能都不需要怎么修改到），这意味着你会忘掉。而要捡起来这些配置，少不了又去搜索一大堆资料研究研究。

没关系，这里是一个最低配置的开发环境。需要时 clone 一下，修改一下 `package.json`，开箱即用 📦。

### Command

Install.

```js
npm install
```

Or.

```js
yarn
```

Start a dev server.

```js
npm start
```

Or.

```js
yarn start
```

### Configuration

这个 Starter 简单的整合了下面这些包。

- `TypeScript`
- `Babel`
- `Webpack`

支持 TypeScript，且使用 `webpack-dev-server` 部署一个热加载的服务器，启动之后通过 `http://localhost:3003` 即可访问，用起来和 CRA 差不多 😆。

下面的插件也准备就绪。

**`eslint`**

已经为 TypeScript 特别配置。具体参照 `.eslintrc.js`。

**`autoprefixer`**

自动添加 CSS 浏览器前缀。

**`.prettierrc`**

格式化工具选择了 `prettier`，根据个人习惯做了一些配置。这里请按需修改。

```json
{
  "trailingComma": "es5",
  "tabWidth": 2,
  "semi": false,
  "singleQuote": true,
  "printWidth": 80,
  "bracketSpacing": true
}
```
