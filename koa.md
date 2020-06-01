```js
//  https://github.com/venables/koa-helmet
"use strict";

const Koa = require("koa");
const helmet = require("koa-helmet");
const app = new Koa();

app.use(helmet());
```