# Awesome Koa

## Framework
- [egg](https://github.com/eggjs/egg) - Born to build better enterprise frameworks and apps with Node.js & Koa --From 阿里
- [strapi](https://github.com/strapi/strapi) - Node.js Content Management Framework (headless-CMS) to build powerful API with no effort. 
- [Lad](https://github.com/ladjs/lad) - Lad scaffolds a Koa webapp and API framework for Node.js
- [Gracejs](https://github.com/xiongwilee/Gracejs) - A Nodejs SFB(Separation of Front and Back ends) framework, build with koa2（基于koa2的标准前后端分离框架）--From 趣店
- [koahub](https://github.com/koahubjs/koahub) - KoaHub.js -- 中文最佳实践Node.js Web快速开发框架
- [plover](https://github.com/alibaba/plover) - 专注于模块化的NodeJs Web框架 --From 阿里
- [zan-node](https://github.com/youzan/zan-node) - Zan is a Nodejs SFB(Separation of Front and Back ends) framework, built on koa2. --From 有赞
## Middleware

### Router & Validate
- [koa-router](https://github.com/ZijianHe/koa-router) - Router middleware for koa.
- [koa-route](https://github.com/koajs/route) - Simple route middleware
- [koa-restql](https://github.com/Meituan-Dianping/koa-restql) - Build real RESTful APIs without writing one line of code.
- [koa-validate](https://github.com/RocksonZeta/koa-validate) - validate koa request params and format request params
- [koa-joi-router](https://github.com/koajs/joi-router) - Configurable, input and output validated routing for koa
- [koa-trie-router](https://github.com/koajs/trie-router) - Trie-routing for Koa
- [koa-path-match](https://github.com/koajs/path-match) - koa route middleware
- [koa-rewrite](https://github.com/koajs/rewrite) - URL rewriting middleware

### Body Parser
- [koa-bodyparser](https://github.com/koajs/bodyparser) - a body parser for koa
- [koa-body](https://github.com/dlau/koa-body) - koa body parser middleware
- [koa-better-body](https://github.com/tunnckoCore/koa-better-body) - Full-featured koa body parser! Support parsing text, buffer, json, json patch, json api, csp-report, multipart, form and urlencoded bodies. Works for koa@1, koa@2 and will work for koa@3 with `koa-convert`.
- [koa-multer](https://github.com/koa-modules/multer) - Middleware for handling `multipart/form-data` for koa, based on Express's multer.
- [koa-is-json](https://github.com/koajs/is-json) - check if a koa body should be interpreted as JSON
- [koa-qs](https://github.com/koajs/qs) - qs for koa, and use querystring more safely.

### Auth
- [koa-jwt](https://github.com/koajs/jwt) - Koa middleware for validating JSON Web Tokens
- [koa-passport](https://github.com/rkusa/koa-passport) - Passport middleware for Koa
- [koa-ctx-basic-auth](https://github.com/koajs/ctx-basic-auth) - Augments Koa with ctx.basicAuth
- [koa-userauth](https://github.com/koajs/userauth) - koa user auth middleware
- [koa-roles](https://github.com/koajs/koa-roles) - koa version of Connect-Roles

### Session
- [koa-session](https://github.com/koajs/session) - Simple session middleware for koa
- [koa-generic-session](https://github.com/koajs/generic-session) - koa session store with memory, redis or others.
- [koa-redis](https://github.com/koajs/koa-redis) - koa session with redis
- [koa-redis-session-sets](https://github.com/koajs/redis-session-sets) - Koa Redis sessions with field-referencing cross sets

### View
- [koa-views](https://github.com/queckezz/koa-views) - Template rendering middleware for koa (hbs, swig, pug, anything! sparkles)
- [koa-react-view](https://github.com/koajs/react-view) - A Koa view engine which renders React components on server
- [koa-ejs](https://github.com/koajs/ejs) - a koa view render middleware, support all feature of ejs
- [koa-hbs](https://github.com/koajs/koa-hbs) - Handlebars templates for Koa.js
- [koa-markdown](https://github.com/koajs/koa-markdown) - Auto convert markdown to html for koa. Inspired by connect-markdown

### Response
- [koa-compress](https://github.com/koajs/compress) - Compress middleware for koa
- [koa-etag](https://github.com/koajs/etag) - ETag support for Koa responses
- [koa-ctx-cache-control](https://github.com/koajs/ctx-cache-control) - Augment Koa with ctx.cacheControl(maxAge)
- [koa-conditional-get](https://github.com/koajs/conditional-get) - Conditional GET middleware for koa
- [koa-html-minifier](https://github.com/koajs/html-minifier) - minify HTML responses like some crazy guy
- [koa-response-time](https://github.com/koajs/response-time) - X-Response-Time middleware
- [koa-json-filter](https://github.com/koajs/json-filter) - Middleware allowing the client to filter the response to only what they need, reducing the amount of traffic over the wire.
- [koa-range](https://github.com/koajs/koa-range) - range request implementation for koa, see http://tools.ietf.org/html/rfc7233
- [koa-ratelimit](https://github.com/koajs/ratelimit) - Rate limiter middleware
- [koa-cash](https://github.com/koajs/cash) - HTTP response caching for Koa
- [koa-json](https://github.com/koajs/json) - pretty-printed JSON response middleware
- [koa-safe-jsonp](https://github.com/koajs/koa-safe-jsonp) - Safe jsonp plusins for koa.
- [koa-charset](https://github.com/koajs/charset) - use iconv-lite to encode the body and set charset to content-type
- [koa-fresh](https://github.com/koajs/koa-fresh) - koa-fresh: HTTP response freshness testing middleware base on koa and node-fresh

### Cookies
- [koa-cookie](https://github.com/varunpal/koa-cookie) - Cookie parser middleware for koa
- [cross-cookies](https://github.com/koajs/cross-cookies) - Easily set cookies across subdomains

### Error
- [koa-error](https://github.com/koajs/error) - Error response middleware (text, json, html)
- [koa-onerror](https://github.com/koajs/onerror) - an error handler for koa, hack ctx.onerror
- [koa-json-error](https://github.com/koajs/json-error) - Error handler for pure-JSON apps

### Security
- [koa-helmet](https://github.com/venables/koa-helmet) - Important security headers for koa
- [@koa/cors](https://github.com/koajs/cors) - Cross-Origin Resource Sharing(CORS) for koa
- [koa-cors](https://github.com/evert0n/koa-cors) - CORS middleware for Koa
- [koa-csrf](https://github.com/koajs/csrf) - CSRF tokens for koa
- [koa-lusca](https://github.com/koajs/koa-lusca) - koa version of lusca. Application security for koa.

### Log & Debug
- [koa-logger](https://github.com/koajs/logger) - Development style logging middleware
- [cabin](https://github.com/cabinjs/cabin) - Logging/analytics service and middleware for Node.js, Lad, Koa, Express, and Passport
- [koa-bunyan-logger](https://github.com/koajs/bunyan-logger) - Koa middleware for bunyan request logging
- [koa-timer](https://github.com/koajs/timer) - time your middleware
- [koa-accesslog](https://github.com/koajs/accesslog) - Middleware for common log format access logs
- [koa-trace](https://github.com/koajs/trace) - generic tracing for koa
- [koa-pino-logger](https://github.com/pinojs/koa-pino-logger) - pino logging koa middleware

### Locale
- [koa-locales](https://github.com/koajs/locales) - koa locales, i18n solution for koa

### Static Server
- [koa-static](https://github.com/koajs/static) - Static file server middleware
- [koa-send](https://github.com/koajs/send) - Transfer static files
- [koa-sendfile](https://github.com/koajs/sendfile) - basic file-sending utility for koa
- [koa-static-cache](https://github.com/koajs/static-cache) - Static cache for koa
- [bundle](https://github.com/koajs/bundle) - Generic asset pipeline with caching, etags, minification, gzipping and sourcemaps.
- [koa-favicon](https://github.com/koajs/favicon) - Koa middleware for serving a favicon
- [koa-mock](https://github.com/koajs/mock) - Simple web page mock middleware
- [koa-resource](https://github.com/koajs/resourcer) - A simple resource directory mounter for koa.

### Proxy
- [koa-proxy](https://github.com/popomore/koa-proxy) - Proxy middleware for koa

### GraphQL
- [koa-graphql](https://github.com/chentsulin/koa-graphql) - Create a GraphQL HTTP server with Koa.

### Others
- [koa-compose](https://github.com/koajs/compose) - Middleware composition utility
- [koa-mount](https://github.com/koajs/mount) - Mount other Koa applications or middleware to a given pathname
- [koa-convert](https://github.com/koajs/convert) - Convert koa generator-based middleware to promise-based middleware
- [koa-cluster](https://github.com/koajs/cluster) - Koa clustering and error handling utility
- [koa-ctx-paginate](https://github.com/koajs/ctx-paginate) - Augments Koa with ctx.paginate (forked from `express-paginate`)

## Boilerplate
- [koan](https://github.com/soygul/koan) - KOAN (Koa, Angular, Node, Mongo) starter kit for full-stack JavaScript web development.
- [koa-generator](https://github.com/17koa/koa-generator) - Koa' application generator for 1.x and 2.x（ Express-style and support all middlewares include async/await ）
- [koa-boiler](https://github.com/llambda/koa-boiler) - Koa 2.3 boilerplate for a production-ready Node.js app. Now with async/await!
- [koa2-startkit](https://github.com/17koa/koa2-startkit) - Koa2 简单开发脚手架
- [koa2-API-scaffold](https://github.com/yi-ge/koa2-API-scaffold) - 一个基于Koa2的轻量级RESTful API Server脚手架。
- [javascript-boilerplate](https://github.com/marmelab/javascript-boilerplate) - Node.js+Koa.js+PostgreSQL+React.js+Webpack+Mocha+Makefile, a starter kit for new apps
- [koa2-boilerplate](https://github.com/superalsrk/koa2-boilerplate) - Enhanced koa2 boilerplate in ES7 with Babel
- [KoaJS + Nuxt.js](https://github.com/nuxt-community/koa-template) - Starter template for Nuxt.js with KoaJS

## Demos
- [examples](https://github.com/koajs/examples) - Example Koa apps
- [bilibili-vue](https://github.com/lybenson/bilibili-vue) - 前端vue+后端koa，全栈式开发bilibili首页
- [koa-react-full-example](https://github.com/dozoisch/koa-react-full-example) - Full example using Koa, React, Passport, Mongoose, Webpack, Mocha, Babel
- [kov-blog](https://github.com/Ma63d/kov-blog) - A blog platform built with koa,vue and mongoose. 
- [N-club](https://github.com/nswbmw/N-club) - 使用 Koa + MongoDB + Redis 搭建论坛系统
- [vue-chat](https://github.com/microzz/vue-chat) - Vue全家桶+Socket.io+Express/Koa2打造一个智能聊天室。
- [vue-koa-demo](https://github.com/Molunerfinn/vue-koa-demo) - A simple full stack demo(CSR & SSR & Docker Support) written by Vue2 & Koa2(Koa1 verson also completed)
- [easyclub](https://github.com/k-dylan/easyclub) - 基于koa2的论坛系统
- [Koa2-blog](https://github.com/wclimb/Koa2-blog) - node+koa2+mysql
- [jackblog-api-koa](https://github.com/jackhutu/jackblog-api-koa) - Jackblog API Server Koa 版, 个人博客系统, 基于RESTful架构, 使用Node.js, Koa, MongoDB, Redis, Token Auth, 七牛云存储等.
- [koa2-jwt-demo](https://github.com/yunzaifei/koa2-jwt-demo) - koa2开发的api示例，使用用jwt验证
- [koa-passport-example](https://github.com/rkusa/koa-passport-example) - koa-passport usage example
- [koa-rest](https://github.com/hemanth/koa-rest) - REST demo with koa. 
- [todo](https://github.com/koajs/todo) - a todo example write with koa and react

## Document
- [koa中文文档](https://github.com/guo-yu/koa-guide) - koa guide in Chinese
- [Koa2进阶学习笔记](https://github.com/chenshenhai/koa2-note) - 《Koa2进阶学习笔记》持续更新...
- [koa-generator-examples](https://github.com/17koa/koa-generator-examples) - 一起学koa 
- [koa-book](https://github.com/minghe/koa-book) - koa.js实战
- [php-co-koa](https://github.com/youzan/php-co-koa) - PHP异步编程: 手把手教你实现co与Koa
- [koa2-tutorial](https://github.com/ikcamp/koa2-tutorial) - Node Koa2 实战 iKcamp 出品
- [koa-docs-Zh-CN](https://github.com/demopark/koa-docs-Zh-CN) - Koa 文档的中文版本 , 更新至 v2.5 版本.
- [stuq-koa](https://github.com/i5ting/stuq-koa) - 和StuQ合作的《下一代Web框架Koajs》在线课程文档
