# Backend Development

+ node.js
    + [Installation paths](https://gist.github.com/579814): use one of these techniques to install node and npm without having to sudo.
    + [Node.js HOWTO: Install Node+NPM as user (not root) under Unix OSes](http://tnovelli.net/blog/blog.2011-08-27.node-npm-user-install.html)
    + [Felix's Node.js Guide](http://nodeguide.com)
    + [Creating a REST API using Node.js, Express, and MongoDB](http://coenraets.org/blog/2012/10/creating-a-rest-api-using-node-js-express-and-mongodb/)
    + [Node Cellar Sample Application with Backbone.js, Twitter Bootstrap, Node.js, Express, and MongoDB](https://github.com/ccoenraets/nodecellar)
    + [JavaScript Event Loop](http://thomashunter.name/blog/the-javascript-event-loop-presentation/)
    + Node.js for PHP programmers
        1. [Event driven Programming](http://redotheweb.com/2012/01/23/nodejs-for-php-programmers-1-event-driven-programming-and-pasta.html)
        2. [Modules and Packages](http://redotheweb.com/2012/02/07/nodejs-for-php-programmers-2-modules-packages-and-the-strawberry-house.html)
        3. [Exceptions and Errors](http://redotheweb.com/2012/04/15/nodejs-for-php-programmers-3-exceptions-and-errors.html)
        4. [Streams](http://redotheweb.com/2012/06/17/nodejs-for-php-programmers-4-streams.html)
    + State of Node
        + [Node.js Infographic :: The State of Node](http://strongloop.com/community/nodejs-infographic)
        + [Can You Count on Node?](http://joyent.com/blog/can-you-count-on-node)
        + Experiences
            + [Experiences with Node.js: Researching Node](http://www.ziggytech.net/technology/web-development/experiences-with-nodejs-researching-node/)
            + [Experiences with Node.js: Porting a RESTful Service Written in Java](http://www.ziggytech.net/technology/web-development/experiences-with-node-js-porting-a-restful-service-written-in-java/)
            + [Experiences with Node.js: Final Thoughts](http://www.ziggytech.net/technology/web-development/experiences-with-node-js-final-thoughts/)
        + Peformance and V8 Debate (dated)
            + [NodeJS: To V8 or not to V8](http://www.olympum.com/future/nodejs-to-v8-or-not-to-v8/)
            + [On Bruno's Concern About the Current Coupling of node.js and V8](http://joyent.com/blog/on-brunos-concern-about-the-current-coupling-of-node-js-and-v8)
            + [Answering Jason on V8 governance and impact to NodeJS](http://www.olympum.com/future/answering-jason-on-v8-governance-and-impact-to-nodejs/)
            + [NodeJS and V8](http://blog.std.in/2011/02/06/nodejs-and-v8/)
            + [Ahead with Node.JS and Google V8](http://www.olympum.com/architecture/ahead-with-node-js-and-google-v8/)
+ Frameworks
    + Express.js
        + [Hello Boilderplate](https://github.com/vdrnn/expressjs-hello-boilerplate) is a bootstrap web app including Bower, Grunt, Twitter Bootstrap, jQuery and EJS.
    + [Hapi](http://walmartlabs.github.com/hapi/): A rich framework for building restful API services.
    + [Deployd](http://www.deployd.com/)
+ Queues and Workers
    + [node-worker-farm](https://github.com/rvagg/node-worker-farm)
        + Distribute processing tasks to child processes with an über-simple API and baked-in durability & custom concurrency options. Available in npm as worker-farm.
    + [Kue](http://learnboost.github.com/kue/) is a feature rich priority job queue for node.js backed by redis. A key feature of Kue is its clean user-interface for viewing and managing queued, active, failed, and completed jobs.
+ Databases
    + [Migrating your WebSQL DB to IndexedDB](http://www.html5rocks.com/en/tutorials/webdatabase/websql-indexeddb/)
    + [Common Uses of CUBRID Node.js API with Examples](http://www.cubrid.org/blog/cubrid-appstools/common-uses-of-cubrid-nodejs-api-with-examples/)
    + [node-pool](https://github.com/coopernurse/node-pool): Generic resource pooling for node.js
    + [node-msgpack](https://github.com/pgriess/node-msgpack) is an addon for NodeJS that provides an API for serializing and de-serializing JavaScript objects using the [MessagePack](http://msgpack.org/) library. The performance of this addon compared to the native JSON object is quite good, and the space required for serialized data is far less than JSON.
    + [The Node.JS MongoDB Driver Manual](http://mongodb.github.com/node-mongodb-native/)
    + [Bookshelf](http://bookshelfjs.org/) is a promise based ORM for Node.js, built on Knex query builder. It extends the Model & Collection foundations of Backbone.js, providing transaction support, eager/nested-eager relation loading, and support for one-to-one, one-to-many, and many-to-many relations.
    + [Mongoose Middleware](https://github.com/PlayNetwork/mongoose-middleware)
    + [Martin Fowler: Introduction to NoSQL](http://youtu.be/qI_g07C_Q5I)
    + [TokuMX: High Performance for MongoDB](http://www.tokutek.com/products/tokumx-for-mongodb/)
    + [The MongoDB tool belt](http://blog.comsysto.com/2012/09/19/the-mongodb-tool-belt/)
    + [Why MongoDB Never Worked Out at Etsy](http://mcfunley.com/why-mongodb-never-worked-out-at-etsy)
    + [MongoDB: Tutorial](http://blog.codecentric.de/en/2012/12/mongodb-tutorial/)
    + [Репликация MongoDb на Amazon EC2](http://habrahabr.ru/post/168691/)
    + [Easily Replicate your MySQL Database!](http://lynkly.tumblr.com/post/25268061482/easily-replicate-your-mysql-database)
    + [Hybrid Applications with MongoDB and RDBMS](http://www.databasetube.com/nosql/hybrid-applications-with-mongodb-and-rdbms/)
+ Content Management Systems
+ Static Site Generators
    + [An Introduction to Static Site Generators](http://www.mickgardner.com/2012/12/an-introduction-to-static-site.html)
    + [Hexo](http://zespia.tw/hexo/): A fast, simple & powerful blog framework, powered by Node.js.
    + [Punch](http://laktek.github.com/punch/): Punch is a simple, intuitive web publishing framework that will delight both designers and developers built on Node.js.
    + [jott](https://github.com/jonsherrard/jott): Minimum viable blog generator. Markup in Jade. Static HTML output.
+ CLI
    + [Master the CLI with Node](http://michaelbrooks.ca/deck/jsconf2013/)
    + [global-npm-seed](https://github.com/andrewjmead/global-npm-seed): Learn to create a global npm module with a CLI interface.
    + [Shell.js](https://github.com/arturadib/shelljs) is a portable (**Windows included**) implementation of Unix shell commands on top of the Node.js API. You can use it to eliminate your shell script's dependency on Unix while still keeping its familiar and powerful commands.
+ Dependency Injection
    + [Dependency Injection with Node.js](http://www.joezimjs.com/javascript/dependency-injection-with-node-js/)
    + [Dependency Injection in NodeJS](http://www.panosru.com/dependency-injection-in-nodejs/)
    + [node-pool](https://github.com/coopernurse/node-pool)
        + Generic resource pool. Can be used to reuse or throttle expensive resources such as database connections.
+ Error Handling
    + [connect error handler middleware](http://www.senchalabs.org/connect/errorHandler.html)
    + [node-errormailer](https://github.com/mcollina/node-errormailer):Sending email for each error in your node app was never easier! It fully support connect and express
    + [outcome](https://npmjs.org/package/outcome)
    + [node-bunyan](https://github.com/trentm/node-bunyan): a simple and fast JSON logging module for node.js services
    + [Chrome Logger](http://craig.is/writing/chrome-logger/)
+ Events
    + [Comparison between different Observer Pattern implementations](https://github.com/millermedeiros/js-signals/wiki/Comparison-between-different-Observer-Pattern-implementations)
    + [js-signals](http://millermedeiros.github.com/js-signals/)
    + [Signal Emitter](http://blog.millermedeiros.com/signal-emitter/)
    + [EventEmitter](https://github.com/Wolfy87/EventEmitter)
    + [MicroEvent.js](https://github.com/jeromeetienne/microevent.js)
    + [gator.js](http://craig.is/riding/gators)
+ Image Manipulation
    + [node-gd](https://github.com/mikesmullin/node-gd): GD graphic library (libgd) C++ bindings for Node.js.
    + [node-image](https://github.com/pkrumins/node-image): This is a node.js module that unifies node-png, node-gif and node-jpeg modules.
    + [node-o3-canvas](https://github.com/ajaxorg/node-o3-canvas): This is a HTML5 spec Canvas component for NodeJS based on LibAGG and Freetype. It is implemented using the Ajax.org O3 component system, and should be easy to extend and fix.
    + [node-canvas](https://github.com/LearnBoost/node-canvas): Node canvas is a Cairo backed Canvas implementation for NodeJS.
    + [node-vips](https://github.com/dosx/node-vips): A node.js module that provides access to the VIPS library and Exiv2 in order to resize and rotate images.
    + [node-imagemagick](https://github.com/seanmcgary/node-imagemagick): Imagemagick module for NodeJS
    + [node-imageinfo](https://github.com/NorgannasAddOns/node-imageinfo): A package that returns information about an image or flash file such as type, dimensions etc.
    + [js-imagediff](https://github.com/HumbleSoftware/js-imagediff): JavaScript / HTML5 Canvas based image diff utility.
    + [gm](http://aheckmann.github.com/gm/): GraphicsMagick for node.
    + [Obscura](https://github.com/OiNutter/Obscura)
+ Internationalisation
    + [A Strategy for i18n and Node.js](http://ejohn.org/blog/a-strategy-for-i18n-and-node/)
    + [Multilingual database design approaches](http://fczaja.blogspot.de/2010/08/multilanguage-database-design.html)
    + [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!)](http://www.joelonsoftware.com/articles/Unicode.html)
+ Websockets
    + [Binary.js](http://binaryjs.com/)
+ Authentication
    + [Passport](http://passportjs.org)
+ Testing
    + [PhantomJS](http://phantomjs.org/)
    + [Node.js testing RESTful API (vows.js?)](http://stackoverflow.com/questions/7127226/node-js-testing-restful-api-vows-js)
    + [Insanely fast, headless full-stack testing using Node.js](http://zombie.labnotes.org/)
    + [Writing Testable JavaScript](http://alistapart.com/article/writing-testable-javascript)
    + [Testing / Spec Frameworks List](https://github.com/joyent/node/wiki/modules#wiki-testing)
    + [CasperJS](http://casperjs.org/)
    + [APIeasy](https://github.com/flatiron/api-easy): A fluent (i.e. chainable) syntax for generating vows tests against RESTful APIs.
    + [Expresso](http://visionmedia.github.io/expresso/)
        + Expresso is a JavaScript TDD framework written for nodejs. Expresso is extremely fast, and is packed with features such as additional assertion methods, code coverage reporting, CI support, and more.
    + [Jasmine](http://pivotal.github.io/jasmine/)
        + Jasmine is a behavior-driven development framework for testing JavaScript code. It does not depend on any other JavaScript frameworks. It does not require a DOM. And it has a clean, obvious syntax so that you can easily write tests.
    + [frisby.js](http://frisbyjs.com/)
        + Frisby is a REST API testing framework built on node.js and Jasmine that makes testing API endpoints easy, fast, and fun.
    + [mocha](http://visionmedia.github.io/mocha/)
        + Mocha is a feature-rich JavaScript test framework running on node and the browser, making asynchronous testing simple and fun. Mocha tests run serially, allowing for flexible and accurate reporting, while mapping uncaught exceptions to the correct test cases. Hosted on GitHub.
    + [lab](https://github.com/spumko/lab)
        + lab is a simple test utility for node. Unlike other test frameworks, lab does not attempt to cover many use cases or provide rich functionality and extensibility. In fact, this project started as a fork off mocha and was repeatedly refactored until only the very basic functionality was left which was then rewritten into a handful of functions.
    + [should](https://github.com/visionmedia/should.js)
        + should is an expressive, readable, test framework agnostic, assertion library for node. It extends the Object prototype with a single non-enumerable getter that allows you to express how that object should behave.
    + [chai](http://chaijs.com/)
        + Chai is a BDD / TDD assertion library for node and the browser that can be delightfully paired with any javascript testing framework.
    + [supertest](https://github.com/visionmedia/supertest)
        + Super-agent driven library for testing HTTP servers
    + [Joe](https://github.com/bevry/joe)
        + Joe is a javascript testing framework that actually works. Unlike Mocha, we won't die on you abruptly when executing dynamically created tests and are always able to associate the correct test to the correct corresponding test suite. Switching from Mocha is trivial and only takes a few minutes.
+ Web Scraping
    + [pjScrape](http://nrabinowitz.github.com/pjscrape/)
    + [PhantomJS](http://phantomjs.org/)
+ Connect
    + [Just Connect it Already](http://howtonode.org/connect-it)
    + [A short guide to Connect Middleware](http://stephensugden.com/middleware_guide/)
    + [Understanding Connect And Middleware](http://project70.com/nodejs/understanding-connect-and-middleware/)
+ Streams
    + [Official Documentation](http://nodejs.org/api/stream.html)
    + [Streams, Pipes and Mega Pipes](http://felixge.s3.amazonaws.com/11/nodejs-streams.pdf): a presentation by Felix Geisendörfer
    + [Understanding Stream](http://nodemanual.org/latest/nodejs_dev_guide/understanding_streams.html): Article at nodemanual.org
    + [Stream Handbook](https://github.com/substack/stream-handbook)
    + [Daddy, what's a stream?](http://howtonode.org/streams-explained)
+ Package Management
    + [parcel](https://github.com/sifteo/parcel) is easy package management using a file server and path conventions, with built in support for Amazon S3. It is designed to encode package metadata, including name, version and OS within a path. The conventions allow this metadata to be queried, without the need for a database.
    + npm
        + [package.json](http://package.json.jit.su/): a cheat sheet for writing npm package files.
        + [Package.json dependencies done right](http://blog.nodejitsu.com/package-dependencies-done-right)
        + [How to fork & patch npm modules](http://www.debuggable.com/posts/how-to-fork-patch-npm-modules:4e2eb9f3-e584-44be-b1a9-3db7cbdd56cb)
        + [npm cheatsheet](http://blog.nodejitsu.com/npm-cheatsheet) by nodejitsu
+ Refactoring
    + [Refactoring Javascript with kratko.js](http://perfectionkills.com/refactoring-javascript-with-kratko-js/)
+ Routing
    + [expressjs re-routing](http://shtylman.com/post/expressjs-re-routing/)
    + [express-resource](https://github.com/visionmedia/express-resource) provides resourceful routing to express.
    + [journey](https://github.com/cloudhead/journey): liberal JSON-only HTTP request routing for node.
    + [urlrouter](https://github.com/fengmk2/urlrouter): http url router, `connect` missing router middleware
    + [connect-rest](https://github.com/imrefazekas/connect-rest): Restful web services middleware for connect node.js
+ Security
    + Authentication
        + [everyauth](https://npmjs.org/package/everyauth)
            + Authentication and authorization (password, facebook, & more) for your node.js Connect and Express apps.
    + Authorisation
        + [ability.js](https://github.com/scottkf/ability-js)
            + A simple route-based ACL component for express.js. This won't handle actual authentication, you can use everyauth for that.
        + [acl](https://npmjs.org/package/acl)
            + This module provides a minimalistic ACL implementation inspired by Zend_ACL
        + [xoauth2](https://github.com/andris9/xoauth2)
            + XOAuth2 token generation with node.js
        + [mashape-oauth](https://github.com/Mashape/mashape-oauth#using-oauth2)
            + OAuth Modules for Node.js - Supporting RSA, HMAC, PLAINTEXT, 2,3-Legged, 1.0a, Echo, XAuth, and 2.0
    + General
        + [helmet](https://github.com/evilpacket/helmet): Collection of middleware to implement various security headers for Express / Connect
        + [meteor accounts system](http://docs.meteor.com/#accounts_passwords)
        + [node-http-signature](https://github.com/joyent/node-http-signature): This document describes a way to add origin authentication, message integrity, and replay resistance to HTTP REST requests. It is intended to be used over the HTTPS protocol.
    + Cryptography
        + [node.bcrypt.js](https://github.com/ncb000gt/node.bcrypt.js)
+ Performance
    + [Fully Loaded Node](https://hacks.mozilla.org/2012/11/fully-loaded-node-a-node-js-holiday-season-part-2/)
    + [Using secure client-side sessions to build simple and scalable Node.JS applications](https://hacks.mozilla.org/2012/12/using-secure-client-side-sessions-to-build-simple-and-scalable-node-js-applications-a-node-js-holiday-season-part-3/)
    + [Building A Node.JS Server That Won’t Melt](https://hacks.mozilla.org/2013/01/building-a-node-js-server-that-wont-melt-a-node-js-holiday-season-part-5/)
    + [Optimising NginX, Node.JS and networking for heavy workloads](https://engineering.gosquared.com/optimising-nginx-node-js-and-networking-for-heavy-workloads)
    + [Every Programmer Should Know These Latency Numbers](http://architects.dzone.com/articles/every-programmer-should-know)
    + [loader.io](http://loader.io/) is a free load testing service that allows you to stress test your web-apps/apis with thousands of concurrent connections.
+ Source Control
    + [git-wrapper](https://npmjs.org/package/git-wrapper)
+ Networks
    + [Difference between a socket and a port](http://programmers.stackexchange.com/questions/171734/difference-between-a-socket-and-a-port)

--------------------------------------------------------------------------

+ [App.js](http://appjs.org/)
+ [LiveReload на Node.js](http://habrahabr.ru/post/168091/)
+ [Scientific Online Calculator](http://ostermiller.org/calc/calculator.html)
