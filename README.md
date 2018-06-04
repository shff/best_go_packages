Sources:
 - https://awesome-go.com/
 - https://golanglibs.com/

## Basics

### Router/Framework:

 - https://github.com/labstack/echo
 - https://github.com/gin-gonic/gin (Sinatra-like)
 - https://github.com/astaxie/beego (Rails-like)
 - https://github.com/gorilla/mux
 - https://github.com/julienschmidt/httprouter
 - https://github.com/bmizerany/pat
 - Docs: https://www.nicolasmerouze.com/guide-routers-golang/
 - Docs: https://husobee.github.io/golang/url-router/2015/06/15/why-do-all-golang-url-routers-suck.html

### ORM:

 - https://github.com/jinzhu/gorm (relationships with `Related` keyword, callbacks, auto-migrations)
 - https://github.com/go-gorp/gorp (relationships but requires join by hand, callbacks, auto-migrations)
 - https://github.com/go-xorm/xorm (relationships but requires join by hand, migrations, map[string]string, callbacks)
 - https://github.com/astaxie/beego/tree/master/orm
 - https://github.com/gobuffalo/pop (complete toolkit, with yaml configuration, true migrations, etc)
 - https://github.com/coocood/qbs (very fast, automatic joins)
 - http://upper.io/ (no joins)
 - Blogpost about it: http://jmoiron.net/blog/golang-orms/
 - Reddit: https://www.reddit.com/r/golang/comments/3ajqa6/golang_which_orm_is_better/

### Not-ORM:

 - https://github.com/jmoiron/sqlx (query builder)
 - https://github.com/gocraft/dbr (query builder)
 - https://github.com/Masterminds/squirrel (query builder)
 - https://github.com/elgris/sqrl (query builder)

### Migrations

 - https://github.com/mattes/migrate
 - https://bitbucket.org/liamstask/goose
 - https://github.com/markbates/pop/tree/master/fizz

### Queue:

 - https://stackoverflow.com/a/45990039 (same process - with goroutines)
 - https://github.com/gocraft/work
 - https://github.com/RichardKnop/machinery
 - https://github.com/benmanns/goworker (resque compatible)
 - https://github.com/jrallison/go-workers (Sidekiq compatible)
 - https://gist.github.com/harlow/dbcd639cf8d396a2ab73 (how to)
 - https://github.com/serdmanczyk/Bifrost
 - ~~https://github.com/iamduo/workq~~ (alpha)
 - ~~https://github.com/ajvb/kala~~ (not production-ready)
 - https://golanglibs.com/category/job-queue?sort=top (list of libraries)

### Goroutine Pool

 - https://github.com/ivpusic/grpool
 - https://github.com/Jeffail/tunny
 - https://github.com/go-playground/pool

## Web Layer

### Oauth Server:

 - https://github.com/nasa9084/oauth-example/blob/master/provider/main.go (single file example)
 - https://github.com/RangelReale/osin
 - https://github.com/go-oauth2/oauth2
 - https://github.com/RichardKnop/go-oauth2-server
 - https://github.com/ory/fosite
 - https://github.com/coreos/dex (authentication service)
 - https://github.com/earaujoassis/space (authentication service)
 - https://github.com/hkolasani/goauth (simpler)
 - https://github.com/jmcvetta/o2pro (deprecated)

### Oauth Client:

 - https://github.com/shferreira/minimal_go_website/blob/echo-oauth2/app.go (using the standard library)
 - https://github.com/dghubble/gologin (Light)
 - https://github.com/markbates/goth (Lots of providers)
 - https://github.com/volatiletech/authboss/tree/master/oauth2 (too heavy apparently)
 - https://github.com/Medium/medium-sdk-go
 - https://github.com/huandu/facebook
 - https://github.com/go-macaron/oauth2 (middleare)

### Websockets:

 - https://github.com/gobwas/ws/
   - https://medium.freecodecamp.org/million-websockets-and-go-cc58418460bb (article)
 - https://github.com/gorilla/websocket
   - http://arlimus.github.io/articles/gin.and.gorilla/ (example)
 - Examples:
   - https://echo.labstack.com/cookbook/websocket#using-net-websocket (example)
   - https://github.com/golang-samples/websocket/blob/master/websocket-chat/src/chat/server.go (example)
   - https://github.com/knowthen/rtsupportserver (example)
   - https://github.com/scotch-io/go-realtime-chat (example)
   - https://github.com/SimonWaldherr/GoRealtimeWeb (example)
   - https://jacobmartins.com/2016/03/07/practical-golang-using-websockets/ (article)
 - https://github.com/centrifugal/centrifugo (standalone)
 
### Server-side Events

 - https://github.com/appleboy/gorush/tree/master/vendor/github.com/gin-contrib/sse

### Amazon S3 Presign:

 - http://docs.aws.amazon.com/sdk-for-go/v1/developer-guide/s3-example-presigned-urls.html
 - https://blog.golang.org/go-image-package (resizing)
 - https://github.com/fawick/speedtest-resize/commit/27b41a8d2cd4de868fbf522c20921762c0e478c1 (resize example)

### Form deserializer:

 - https://github.com/go-playground/form (FormEncoding to Struct)
 - https://github.com/monoculum/formam (slower)

### Struct Validator:

 - https://github.com/go-playground/validator (with echo: https://echo.labstack.com/guide/request#validate-data)
 - https://github.com/asaskevich/govalidator
 - https://github.com/monoculum/valider

### CSRF:

 - https://github.com/josephspurrier/csrfbanana
 - https://github.com/justinas/nosurf

### GraphQL:

 - https://github.com/vektah/gqlgen
 - https://github.com/graphql-go/graphql

### Swagger:

 - https://github.com/go-swagger/go-swagger

### JWT

 - Don' use JWT: https://news.ycombinator.com/item?id=13867089
   - Use Fernet instead: https://news.ycombinator.com/item?id=13869207
   - https://github.com/fernet/fernet-go / https://github.com/fernet/fernet-go/blob/master/example_test.go
 - ~~https://github.com/dgrijalva/jwt-go~~

### HTML Sanitizers

 - https://github.com/microcosm-cc/bluemonday

## Backend Tools

### Distributed Messaging:

 - https://github.com/nsqio/nsq

### Microservices

 - https://github.com/nytimes/gizmo

### Scheduler / Cron:

 - https://github.com/jasonlvhit/gocron
 - https://github.com/welcome-to-shire/gron
 - https://github.com/robfig/cron
 - ~~https://github.com/ajvb/kala~~ (not production-ready)

### Fulltext Search

 - https://github.com/blevesearch/bleve
 - https://github.com/go-ego/riot
 - https://github.com/huichen/wukong

### App statistics middleware

 - https://github.com/thoas/stats

## APIs etc

### Recaptcha:

 - https://github.com/steambap/captcha

### SMTP:

 - https://github.com/nilslice/email/blob/master/email.go (Sender)
 - https://github.com/flashmob/go-guerrilla/blob/master/server.go (Receiver)

### Sendgrid etc:

 - https://github.com/sendgrid/sendgrid-go
   - Webhook: https://sendgrid.com/docs/API_Reference/Webhooks/event.html
 - https://github.com/mailgun/mailgun-go
 - https://github.com/keighl/mandrill/blob/master/mandrill.go
 - https://github.com/mailjet/mailjet-apiv3-go

### Mobile App Notifications:

 - https://github.com/smancke/guble
 - https://github.com/appleboy/gorush (standalone)

### Error Logging APIs:

 - https://github.com/getsentry/raven-go
 - https://github.com/bugsnag/bugsnag-go
 - https://github.com/yvasiyarov/newrelic_platform_go
 
### Webapp Monitoring:

 - https://github.com/sourcegraph/checkup

### Slack Bots:

 - https://github.com/sbstjn/hanu
 
### Google Authenticator

 - https://github.com/dgryski/dgoogauth (Example: https://github.com/yoshiotu/2fa)

### Apple Notification Service

 - https://github.com/sideshow/apns2
 - https://github.com/blackbeans/apns
 - https://github.com/edganiukov/apns (uses stdlib for keepalive)

## File Formats, etc

### Inline CSS for e-mails:

 - https://github.com/aymerick/douceur
 - https://github.com/vanng822/go-premailer

### XLSX Generator:

 - https://github.com/tealeg/xlsx
 - https://github.com/360EntSecGroup-Skylar/excelize

### PDF:

 - https://github.com/jung-kurt/gofpdf#gofpdf

### Markdown:

 - https://github.com/golang-commonmark/markdown
 - https://github.com/russross/blackfriday
 - https://github.com/madari/goskirt
 - https://github.com/madari/goskirt
 - http://mates.vs.uni-due.de
 - https://github.com/buu700/upskirt.go

### Bar Codes:

 - https://github.com/boombuler/barcode
 - https://github.com/skip2/go-qrcode
 - https://github.com/rsc/qr

### Image Processing

 - https://github.com/esimov/caire (Content-aware resizing)
 - https://github.com/nfnt/resize
 - https://github.com/anthonynsimon/bild
 - https://github.com/h2non/bimg

### Charts

 - https://github.com/wcharczuk/go-chart

## Important Utilities

### Debugging

 - https://github.com/y0ssar1an/q

## Experimental

### Expression Parser

 - https://github.com/Knetic/govaluate
 - https://github.com/elgs/jsonql/blob/master/exparser.go
 - https://github.com/mattn/anko (complete language)

## Applications Written in Golang

### Web Applications

 - https://github.com/markbates/buffla (url shortener)
 - https://github.com/appleboy/gorush (app notifications service)
 - https://github.com/rocajuan/go-img-upload/ (very simple image uploader/resizer service)
 - https://github.com/willnorris/imageproxy (complex image uploader/resizer service)
