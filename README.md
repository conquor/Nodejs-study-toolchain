# Nodejs-study-toolchain
Nodejs study toolchain
<br>
Express 

1. Cheerio https://github.com/cheeriojs/cheerio <br>
  Fast, flexible, and lean implementation of core jQuery designed specifically for the server
<br>
2. jsdom https://github.com/tmpvar/jsdom
  like with Cheerio

3. superagent(http://visionmedia.github.io/superagent/ ) 
<br>
是个 http 方面的库，可以发起 get 或 post 请求。

<h2> ASYNC </h2>
异步流程控制
<br>
1.eventproxy https://github.com/JacksonTian/eventproxy
<br>
An implementation of task/event based asynchronous pattern.
http://html5ify.com/eventproxy
<br>
2.async https://github.com/caolan/async 
<br>
当你需要去多个源(一般是小于 10 个)汇总数据的时候，用 eventproxy 方便；当你需要用到队列，需要控制并发数，或者你喜欢函数式编程思维时，使用 async。大部分场景是前者，所以我个人大部分时间是用 eventproxy 的。

<h2> ORM </h2>
1. Waterline https://github.com/balderdashy/waterline <br>
  An adapter-based ORM for Node.js with support for mysql, mongo, postgres, redis, and more <br>
2. Bookshelf https://github.com/tgriesser/bookshelf


<h2> Authentication </h2>
<span></span>
1. Passport https://github.com/jaredhanson/passport <br>
Simple, unobtrusive authentication for Node.js.
2. 

<h2>
Promise library
</h2>
1.Bluebird https://github.com/petkaantonov/bluebird
Bluebird is a full featured promise library with unmatched performance.<br>
Many other promise lib like:
Q, when, bluebird , jQuery's deferred, javascript's Promise
<br>
Blog:http://blog.getify.com/promises-part-1/

<h2>Utility library</h2>
1.Lodash  https://github.com/lodash/lodash <br>
A JavaScript utility library delivering consistency, modularity, performance, & extras.
<br>
2. Moment https://github.com/moment/moment
Parse, validate, manipulate, and display dates in javascript.
<br>
3. PM2 https://github.com/Unitech/PM2 <br>
Production process manager for Node.JS applications. Perfectly designed for microservice architecture.
<br>
4.Markdown-js https://github.com/evilstreak/markdown-js
<br>
A Markdown parser for javascript
5.to-markdown https://github.com/domchristie/to-markdown 
<br>
An HTML to Markdown converter written in JavaScript


<h2>Crypt</h2>
1.Node.bcrypt.js https://github.com/ncb000gt/node.bcrypt.js <br>
bcrypt for NodeJs

<h2>Upload</h2>
1.Skipper https://github.com/balderdashy/skipper <br>
Streaming multi-uploads for Sails/Express - supports disk, S3, gridfs, and custom file adapters

<h2>FS</h2>
1. Node-fs-extra https://github.com/jprichardson/node-fs-extra
<br>
Node.js: extra methods for the fs object.
2. 

<h2>Test</h2>
1. Mocha https://github.com/mochajs/mocha <br>
mocha - simple, flexible, fun javascript test framework for node.js & the browser. (BDD, TDD, QUnit styles via interfaces) 
<br>
2. Should https://github.com/tj/should.js <br>
BDD style assertions for node.js – test framework agnostic
<br>
3.Supertest https://github.com/tj/supertest <br>
Super-agent driven library for testing node.js HTTP servers using a fluent API
</br>
supertest 是 superagent 的孪生库,为什么说 supertest 是 superagent 的孪生库呢，因为他们的 API 是一模一样的。superagent 是用来抓取页面用的，而 supertest，是专门用来配合 express （准确来说是所有兼容 connect 的 web 框架）进行集成测试的。
</br>
4.测试率覆盖工具 istanbul : https://github.com/gotwarlost/istanbul
</br>

<h3>前端测试工具</h3>
测试框架 mocha 进行前端测试 : http://mochajs.org/
全栈的断言库 chai: http://chaijs.com/
headless 浏览器 phantomjs: http://phantomjs.org/



<h2>SNS</h2>
1.nodeclub https://github.com/cnodejs/nodeclub

</br>
<h2>other</h2>
1.nodemon https://github.com/remy/nodemon
这个库是专门调试时候使用的，它会自动检测 node.js 代码的改动，然后帮你自动重启应用。在调试时可以完全用 nodemon 命令代替 node 命令。
