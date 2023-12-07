# macha-server
with Express.js, FireBase

[![Express Logo](https://i.cloudup.com/zfY6lL7eFa-3000x3000.png)](http://expressjs.com/)

```js
const express = require('express')
const app = express()

app.use('/api/user', userRouter);
app.use('/api/data', dataRouter);

app.get('/', async (req, res) => {
    res.send('macha-server!');
})
```

## 기본


1. .env 파일 필요합니다 (개인 소유 - 요청해야함)
2. 시작하세요
```console
$ npm install
$ npm run start
```


## 문서 & 커뮤니티

  * [Website and Documentation](http://expressjs.com/) - [[website repo](https://github.com/expressjs/expressjs.com)]
  * [#express](https://web.libera.chat/#express) on [Libera Chat](https://libera.chat) IRC
  * [GitHub Organization](https://github.com/expressjs) for Official Middleware & Modules
  * Visit the [Wiki](https://github.com/expressjs/express/wiki)
  * [Google Group](https://groups.google.com/group/express-js) for discussion
  * [Gitter](https://gitter.im/expressjs/express) for support and discussion
