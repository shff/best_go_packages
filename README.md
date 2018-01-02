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

 - https://github.com/jinzhu/gorm (relationships with `Related` keyword, callbacks, migrations)
 - https://github.com/go-gorp/gorp (relationships but requires join by hand, callbacks, migrations)
 - https://github.com/go-xorm/xorm (relationships but requires join by hand, migrations, map[string]string, callbacks)
 - https://github.com/astaxie/beego/tree/master/orm
 - http://upper.io/ (no joins)
 - Blogpost about it: http://jmoiron.net/blog/golang-orms/
 - Reddit: https://www.reddit.com/r/golang/comments/3ajqa6/golang_which_orm_is_better/

### Not-ORM:

 - https://github.com/coocood/qbs (mostly struct mapping, but has automatic joins)
 - https://github.com/jmoiron/sqlx (query builder)
 - https://github.com/gocraft/dbr (query builder)
 - https://github.com/Masterminds/squirrel (query builder)
 - https://github.com/elgris/sqrl (query builder)

### Queue:

 - https://github.com/gocraft/work (with script)
 - https://github.com/benmanns/goworker (resque compatible)
 - https://github.com/jrallison/go-workers (Sidekiq compatible)
 - https://gist.github.com/harlow/dbcd639cf8d396a2ab73 (how to)
 - https://github.com/serdmanczyk/Bifrost
 - ~~https://github.com/iamduo/workq~~ (alpha)
 - ~~https://github.com/ajvb/kala~~ (not production-ready)
 - https://golanglibs.com/category/job-queue?sort=top (list of libraries)

## Web Layer

### Oauth Server:

 - https://github.com/RangelReale/osin
 - https://github.com/go-oauth2/oauth2/blob/master/example/server/server.go
 - https://github.com/RichardKnop/go-oauth2-server

### Oauth Client:

 - https://github.com/shferreira/minimal_go_website/blob/echo-oauth2/app.go
 - https://github.com/dghubble/gologin (Light)
 - https://github.com/markbates/goth (Lots of providers)
 - https://github.com/volatiletech/authboss/tree/master/oauth2 (too heavy apparently)
 - https://github.com/Medium/medium-sdk-go
 - https://github.com/huandu/facebook

### Websockets:

 - https://echo.labstack.com/cookbook/websocket#using-net-websocket
 - https://github.com/golang-samples/websocket/blob/master/websocket-chat/src/chat/server.go (example)
 - https://github.com/knowthen/rtsupportserver (example)
 - https://github.com/scotch-io/go-realtime-chat (example)
 - https://github.com/SimonWaldherr/GoRealtimeWeb (example)
 - https://jacobmartins.com/2016/03/07/practical-golang-using-websockets/ (article)
 - https://github.com/centrifugal/centrifugo

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

 - https://github.com/graphql-go/graphql

### Swagger:

 - https://github.com/go-swagger/go-swagger

### JWT

 - Don' use JWT: https://news.ycombinator.com/item?id=13867089
   - Use Fernet instead: https://news.ycombinator.com/item?id=13869207
   - https://github.com/fernet/fernet-go / https://github.com/fernet/fernet-go/blob/master/example_test.go
 - ~~https://github.com/dgrijalva/jwt-go~~

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
 - https://github.com/appleboy/gorush
 - Apple: https://github.com/sideshow/apns2

### Error Logging APIs:

 - https://github.com/getsentry/raven-go
 - https://github.com/bugsnag/bugsnag-go
 - https://github.com/yvasiyarov/newrelic_platform_go

### Slack Bots:

 - https://github.com/sbstjn/hanu

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

## Experimental

### Expression Parser

 - https://github.com/Knetic/govaluate
 - https://github.com/elgs/jsonql/blob/master/exparser.go
