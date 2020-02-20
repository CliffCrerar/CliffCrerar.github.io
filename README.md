> ### ABOUT DEV DOCS
> go wiki: [dev docs wiki](https://github.com/CliffCrerar/CliffCrerar.github.io/wiki)
>
> In the process of migrating to this [vuepress site](https://my-docspress-git-vue-press-conversion.c1i44.now.sh/)

#### Ultimate HTML Page Boiler

https://github.com/h5bp/html5-boilerplate/blob/master/README.md

`npm install html5-boilerplate`

[Modernizer](https://modernizr.com/)

[Test Website](https://www.webpagetest.org/)

#### CORS FIGHTER CODE

```js
app.use(function(req, res, next) {
  res.header("Access-Control-Allow-Origin", "*");
  res.header("Access-Control-Allow-Headers", "Origin, X-Requested-With, Content-Type, Accept");
  next();
});
```


# Go github

* [Repositories](https://github.com/CliffCrerar?tab=repositories)
* [Profile](https://github.com/CliffCrerar)


# Quick Links

* [Dev docs pages](https://github.com/CliffCrerar/dev-docz/tree/master/src/pages) (deprecated)
* [Dev docs wiki](https://github.com/CliffCrerar/CliffCrerar.github.io/wiki)
* [OWASP Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Content_Security_Policy_Cheat_Sheet.html)
* [Github Primer](https://primer.style:)
* [Search domain](https://www.namesilo.com/domain_results.php)
* [Mocky Api](https://www.mocky.io/)
* [Apple Script](https://www.macosxautomation.com/applescript/firsttutorial/index.html)
* [CSS Libraries 2019](https://cliffcrerar.github.io/list-of-css-libs-2019/)
* [Google Code Labs](https://codelabs.developers.google.com/)
* [Bideo.js](https://rishabhp.github.io/bideo.js/)
* [Aos](https://michalsnik.github.io/aos/)
* [Anime Animation Lib](https://animejs.com/documentation/)
* [Workbox](https://developers.google.com/web/tools/workbox/modules/workbox-build#full_generatesw_config)
* [Content Security](https://www.html5rocks.com/en/tutorials/security/content-security-policy/)
* [12 Factor Application](https://12factor.net)


# [About ng-tempalte, ng-content, ng-container](https://www.freecodecamp.org/news/everything-you-need-to-know-about-ng-temaplate-ng-content-ng-container-and-ngtemplateoutlet-4b7b51223691/)

# [Project Rome Azure ](https://docs.microsoft.com/en-us/graph/cross-device-app-configuration)



# Articles
 - [Post angular cloud app errors to slack](https://medium.com/dailyjs/how-to-send-errors-into-slack-dc552e30506f)

# Web resource inventory

#### Public profiles

|Site|Link|
|---|--|
|Facebook|https://www.facebook.com/cliff.crerar|
|LinkedId|https://www.linkedin.com/in/cliff-crerar/|
|Twitter|https://twitter.com/Cliffenator|
|Instagram|https://www.instagram.com/cliffenator/|
|Stack Overflow|https://stackoverflow.com/users/5599914/cliff-crerar?tab=profile|
|Github|https://github.com/CliffCrerar|
|Dribble|https://dribbble.com/cliffenator#|
|Behance|https://www.behance.net/cliff-crerar|
|Mastodon|https://mastodon.social/@cliffcrerar|
|Hashnode|https://hashnode.com/@Cliff|
|Medium|Closed account|
|Quora|https://www.quora.com/profile/Cliff-Crerar|
|Google|[google cliff crerar](https://www.google.com/search?sxsrf=ACYBGNRssPKQus3D9lC8poTEg20unGadng%3A1573726423777&source=hp&ei=1yjNXavULM3bwQLK_bDADg&q=cliff+crerar&oq=cliff+crerar&gs_l=psy-ab.3..35i39l2.834.3064..3317...0.0..0.234.2378.2-11......0....1..gws-wiz.......0i67j0i131j0i131i67j0i131i20i263j0i20i263j0.tf_MeH5vD7I&ved=0ahUKEwjrm9fju-nlAhXNbVAKHco-DOgQ4dUDCAY&uact=5)|
|youyube|https://www.youtube.com/user/MrBeamerguy|
|Telegram|https://t.me/cliffcrerar|
|Gitfolio|https://cliffcrerar.github.io/gitfolio/|
|StackShare|https://stackshare.io/CliffCrerar|

#### Personal Resources

|Site|Link|
|-----|----|
| Portal| www.cliff-crerar.tech |
|GitFolio |https://cliffcrerar.github.io/gitfolio/|
| Resume | resume.cliff-crerar.tech |
| Privacy | https://policies.cliff-crerar.tech/portal-privacy |
| Terms of Use | https://policies.cliff-crerar.tech/portal-terms |

## NPM Publications

!TODO

## Projects 

| Project Name | Project Status |
|--------------|----------------|
| - [Demo phonebook application](https://github.com/CliffCrerar/phone-book-demo/projects/1?fullscreen=true)| released/ongoing |
| - [learn transact sql and database fundamentals](learntransactsql.now.sh) | released/ongoing |
| - [next-app-starter-preconfigured](https://github.com/CliffCrerar/next-app-pre-configured-starter) | failed/archived |
| - [Dev Docs](https://mydevdocs.now.sh) | migrating to vuepress |

## Learn Azure functions

https://docs.microsoft.com/en-us/learn/browse/?products=azure-functions

Other

https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference#folder-structure
https://docs.microsoft.com/en-us/azure/azure-functions/functions-how-to-use-azure-function-app-settings
https://docs.microsoft.com/en-us/azure/azure-functions/functions-best-practices

## HTTP ERRORS

# http-errors

[![NPM Version][npm-version-image]][npm-url]
[![NPM Downloads][npm-downloads-image]][node-url]
[![Node.js Version][node-image]][node-url]
[![Build Status][travis-image]][travis-url]
[![Test Coverage][coveralls-image]][coveralls-url]

Create HTTP errors for Express, Koa, Connect, etc. with ease.

## Install

This is a [Node.js](https://nodejs.org/en/) module available through the
[npm registry](https://www.npmjs.com/). Installation is done using the
[`npm install` command](https://docs.npmjs.com/getting-started/installing-npm-packages-locally):

```bash
$ npm install http-errors
```

## Example

```js
var createError = require('http-errors')
var express = require('express')
var app = express()

app.use(function (req, res, next) {
  if (!req.user) return next(createError(401, 'Please login to view this page.'))
  next()
})
```

## API

This is the current API, currently extracted from Koa and subject to change.

### Error Properties

- `expose` - can be used to signal if `message` should be sent to the client,
  defaulting to `false` when `status` >= 500
- `headers` - can be an object of header names to values to be sent to the
  client, defaulting to `undefined`. When defined, the key names should all
  be lower-cased
- `message` - the traditional error message, which should be kept short and all
  single line
- `status` - the status code of the error, mirroring `statusCode` for general
  compatibility
- `statusCode` - the status code of the error, defaulting to `500`

### createError([status], [message], [properties])

Create a new error object with the given message `msg`.
The error object inherits from `createError.HttpError`.

<!-- eslint-disable no-undef, no-unused-vars -->

```js
var err = createError(404, 'This video does not exist!')
```

- `status: 500` - the status code as a number
- `message` - the message of the error, defaulting to node's text for that status code.
- `properties` - custom properties to attach to the object

### createError([status], [error], [properties])

Extend the given `error` object with `createError.HttpError`
properties. This will not alter the inheritance of the given
`error` object, and the modified `error` object is the
return value.

<!-- eslint-disable no-redeclare, no-undef, no-unused-vars -->

```js
fs.readFile('foo.txt', function (err, buf) {
  if (err) {
    if (err.code === 'ENOENT') {
      var httpError = createError(404, err, { expose: false })
    } else {
      var httpError = createError(500, err)
    }
  }
})
```

- `status` - the status code as a number
- `error` - the error object to extend
- `properties` - custom properties to attach to the object

### new createError\[code || name\](\[msg]\))

Create a new error object with the given message `msg`.
The error object inherits from `createError.HttpError`.

<!-- eslint-disable no-undef, no-unused-vars -->

```js
var err = new createError.NotFound()
```

- `code` - the status code as a number
- `name` - the name of the error as a "bumpy case", i.e. `NotFound` or `InternalServerError`.

#### List of all constructors

|Status Code|Constructor Name             |
|-----------|-----------------------------|
|400        |BadRequest                   |
|401        |Unauthorized                 |
|402        |PaymentRequired              |
|403        |Forbidden                    |
|404        |NotFound                     |
|405        |MethodNotAllowed             |
|406        |NotAcceptable                |
|407        |ProxyAuthenticationRequired  |
|408        |RequestTimeout               |
|409        |Conflict                     |
|410        |Gone                         |
|411        |LengthRequired               |
|412        |PreconditionFailed           |
|413        |PayloadTooLarge              |
|414        |URITooLong                   |
|415        |UnsupportedMediaType         |
|416        |RangeNotSatisfiable          |
|417        |ExpectationFailed            |
|418        |ImATeapot                    |
|421        |MisdirectedRequest           |
|422        |UnprocessableEntity          |
|423        |Locked                       |
|424        |FailedDependency             |
|425        |UnorderedCollection          |
|426        |UpgradeRequired              |
|428        |PreconditionRequired         |
|429        |TooManyRequests              |
|431        |RequestHeaderFieldsTooLarge  |
|451        |UnavailableForLegalReasons   |
|500        |InternalServerError          |
|501        |NotImplemented               |
|502        |BadGateway                   |
|503        |ServiceUnavailable           |
|504        |GatewayTimeout               |
|505        |HTTPVersionNotSupported      |
|506        |VariantAlsoNegotiates        |
|507        |InsufficientStorage          |
|508        |LoopDetected                 |
|509        |BandwidthLimitExceeded       |
|510        |NotExtended                  |
|511        |NetworkAuthenticationRequired|

## Azure JS SDK

https://docs.microsoft.com/en-us/azure/javascript/


PouchDB

[authentication](https://github.com/pouchdb-community/pouchdb-authentication)

https://github.com/jo/pouch-box

https://github.com/dahjelle/pouch-datalog

https://github.com/pouchdb-community/pouchdb-dump-cli

https://github.com/pouchdb-community/pouchdb-load

https://github.com/redgeoff/delta-pouch

https://github.com/pouchdb-community/pouchdb-full-sync

https://github.com/jo/pouch-resolve-conflicts

https://github.com/pouchdb-community/relational-pouch

https://github.com/pouchdb/upsert

https://github.com/pouchdb-community/worker-pouch

https://github.com/jrhicks/ngPouch

https://github.com/nolanlawson/blob-util

http://cdaringe.github.io/pouchy/

- TESTING
https://gist.github.com/nolanlawson/816f138a51b86785d3e6

http://docs.couchdb.org/en/latest/api/database/security.html

http://docs.couchdb.org/en/latest/intro/overview.html#security-and-validation

http://docs.couchdb.org/en/latest/intro/security.html

https://github.com/pouchdb/pouchdb-search

https://github.com/pouchdb/pouchdb-fauxton

## License

[MIT](LICENSE)

[coveralls-image]: https://badgen.net/coveralls/c/github/jshttp/http-errors/master
[coveralls-url]: https://coveralls.io/r/jshttp/http-errors?branch=master
[node-image]: https://badgen.net/npm/node/http-errors
[node-url]: https://nodejs.org/en/download
[npm-downloads-image]: https://badgen.net/npm/dm/http-errors
[npm-url]: https://npmjs.org/package/http-errors
[npm-version-image]: https://badgen.net/npm/v/http-errors
[travis-image]: https://badgen.net/travis/jshttp/http-errors/master
[travis-url]: https://travis-ci.org/jshttp/http-errors
