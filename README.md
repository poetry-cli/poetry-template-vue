<p align="center"><a href="https://github.com/poetry-cli/poetry-template-vueCli3" target="_blank"><img width="100"src="https://vuejs.org/images/logo.png"></a></p>

<h1 align="center"><strong>Awesome Vue-Cli3 Example </strong></h1>

<div align="center">
  <strong>
    🦅 (Vue Webpack Vuex Vue-router Element-ui/...) out of the box
  </strong>
</div>

<div align="center">
 🦅 Awesome example for rapid Vue.js development using <a href="https://github.com/vuejs/vue-cli" target="_blank">vue-cli3</a>.
</div>


## Usage

```bash
npm i -g poetry-cli

# 创建RN项目
poetry init my-project

# ? 请选择使用的模板
  umi
❯ vueCli3
  taro
  electron
  next

# ➕ install dependencies & start dev
yarn && yarn start
```

## Advantage

- [x] Import & configure [Vue-router](https://router.vuejs.org/zh/) to make the building of a single-page application (SPA) breeze;
- [x] Import & configure [Vuex](https://vuex.vuejs.org/zh/) to handle the management of status for application development;
- [x] Import [Element-ui](http://element.eleme.io/#/zh-CN) to build a website quickly without paying too much attention to the UI;
- [x] Import & encapsulating [Axios](https://github.com/axios/axios) to response the Http requests more elegant;
- [x] Import [Dayjs](https://github.com/iamkun/dayjs) to handle date-time correlation in a slight cost;
- [x] Import & encapsulate the [Marked]() plugin so that it can be used as a rich text editor,and it also can achieve `Markdown` to draw the page due to its parsing function.
- [x] Import [vue-meta](https://github.com/declandewet/vue-meta) plugin so that allows you to manage your app's meta information, much like [react-helmet](https://github.com/nfl/react-helmet) does for React. It'm awesome for `SEO`.
- [x] Making the optimization based on the new features of `Webepack 4.*`. Getting the details on `vue.config.js`;
- [x] Opening & using [Jest](https://jestjs.io/) to test the component with the Demo;
- [x] Integrate & configure the [Prettier](https://prettier.io/) plugin to enable the team to code with better and consistent style. Getting the details on the [使用 ESLint ＆ Prettier美化Vue代码](https://www.jeffjade.com/2018/06/18/142-beautify-vue-by-eslint-and-prettier/);
- [x] Import [cli-plugin-pwa](https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-pwa) plugin，and configure in \`vue.config.js\` ，you can get started easily with [PWA](https://github.com/nicejade/nice-front-end-tutorial/blob/master/tutorial/pwa-tutorial.md) using Vue;
- [x] Import the [prerender-spa-plugin](https://github.com/chrisvfritz/prerender-spa-plugin) plugin to pre-render static HTML, optimizing SEO and first-screen rendering in a single-page application .
- [x] Import the [webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) plugin so that to get the contents of the building packages with optimization while running `Yarn analyz`. Getting the details: [Webpack 打包优化之体积篇](https://jeffjade.com/2017/08/06/124-webpack-packge-optimization-for-volume/#%E5%AE%9A%E4%BD%8D-webpack-%E5%A4%A7%E7%9A%84%E5%8E%9F%E5%9B%A0).
- [x] Import the [size-plugin](https://github.com/GoogleChromeLabs/size-plugin)  plugin to print the Gzip size of the Webpack asset and the changes since the last building while building the app.
- [x] Import the [hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) plugin for webpack to provide an intermediate caching step for modules. It make the second build will be signficantly faster.
- [x] The combination of this scaffolding with Node.js (Koa2) Nginx MondoDb Redis is integrated into Docker to make Front-End Developer build easily the entire web application.Its currently open sourced in [Docker Vue Node Nginx Mongodb Redis](https://github.com/nicejade/docker-vue-node-nginx-mongodb-redis).
-  [ ] Optimizing the built-in `Icon` (Svg) component so that you can receive input in different ways and extract Svg into a separate file to avoid repeated loading of resources;

>**TIP**: [prerender-spa-plugin](https://github.com/chrisvfritz/prerender-spa-plugin): Prerenders static HTML in a single-page application. But, it is not required. If you don't need it, you can remove it. Because it requires a lot of dependencies([puppeteer](https://github.com/GoogleChrome/puppeteer)，Chromium: ~170MB Mac, ~282MB Linux, ~280MB Win) to download, this is time consuming.
