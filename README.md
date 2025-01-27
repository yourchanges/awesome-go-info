# Awesome Go Info

go语言开源项目列表，项目分类及GitHub上的开源项目数据完全来自于 [awesome-go](https://github.com/avelino/awesome-go) 的 [README.md](https://github.com/avelino/awesome-go/blob/master/README.md) 文件，通过调用GitHub的API获取仓库信息，展示项目的star数、watch数等，方便查看go语言开源项目的一些相关信息。

_该文件仅包含 [awesome-go](https://github.com/avelino/awesome-go) 仓库中 [README.md](https://github.com/avelino/awesome-go/blob/master/README.md) 文件中列出的在GitHub上开源的优秀项目，不罗列其它golang相关的网站_
_该文件中的GitHub仓库信息数据会在每天凌晨1点左右更新,当前数据更新于2021-12-29 00:40:07_

- [Awesome Go](#awesome-go)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Blockchain](#blockchain)
    - [Bot Building](#bot-building)
    - [Build Automation](#build-automation)
    - [CSS Preprocessors](#css-preprocessors)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
        - [NoSQL Databases](#nosql-databases)
        - [Relational Databases](#relational-databases)
    - [Date and Time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Dynamic DNS](#dynamic-dns)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Error Handling](#error-handling)
    - [File Handling](#file-handling)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Functional](#functional)
    - [GUI](#gui)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Geographic](#geographic)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [Hardware](#hardware)
    - [Images](#images)
    - [IoT](#iot-internet-of-things)
    - [JSON](#json)
    - [Job Scheduler](#job-scheduler)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Microsoft Office](#microsoft-office)
        - [Microsoft Excel](#microsoft-excel)
    - [Miscellaneous](#miscellaneous)
        - [Dependency Injection](#dependency-injection)
        - [Project Layout](#project-layout)
        - [Strings](#strings)
        - [Uncategorized](#uncategorized)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
        - [HTTP Clients](#http-clients)
    - [ORM](#orm)
    - [OpenGL](#opengl)
    - [Package Management](#package-management)
    - [Performance](#performance)
    - [Query Language](#query-language)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Server Applications](#server-applications)
    - [Stream Processing](#stream-processing)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
        - [Fail injection](#fail-injection)
        - [Mock](#mock)
        - [Testing Frameworks](#testing-frameworks)
    - [Text Processing](#text-processing)
        - [Specific Formats](#specific-formats)
        - [Utility](#utility)
    - [Third-party APIs](#third-party-apis)
    - [UUID](#uuid)
    - [Utilities](#utilities)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        - [Routers](#routers)
    - [WebAssembly](#webassembly)
    - [Windows](#windows)
    - [XML](#xml)
    - [Zero Trust](#zero-trust)
- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
    - [Go Generate Tools](#go-generate-tools)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)
- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Gophers](#gophers)
    - [Meetups](#meetups)
    - [Style Guides](#style-guides)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)



**[⬆ back to top](#awesome-go-info)**

# Awesome Go
        
**[⬆ back to top](#awesome-go-info)**

## Audio and Music
        
*Libraries for manipulating audio.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [oto](https://github.com/hajimehoshi/oto) | 921 | 10 | 2017/05/04 | 1 day ago | A low-level library to play sound on multiple platforms. |
| [portaudio](https://github.com/gordonklaus/portaudio) | 487 | 12 | 2015/09/16 | 1 year ago | Go bindings for the PortAudio audio I/O library. |
| [music-theory](https://github.com/go-music-theory/music-theory) | 374 | 20 | 2016/03/17 | 1 year ago | Music theory models in Go. |
| [portmidi](https://github.com/rakyll/portmidi) | 262 | 11 | 2013/11/10 | 1 year ago | Go bindings for PortMidi. |
| [id3v2](https://github.com/bogem/id3v2) | 226 | 7 | 2016/05/15 | 1 week ago | ID3 decoding and encoding library for Go. |
| [GoAudio](https://github.com/DylanMeeus/GoAudio) | 191 | 6 | 2020/07/05 | 1 month ago | Native Go Audio Processing Library. |
| [flac](https://github.com/mewkiz/flac) | 185 | 11 | 2012/11/01 | 2 weeks ago | Native Go FLAC encoder/decoder with support for FLAC streams. |
| [malgo](https://github.com/gen2brain/malgo) | 160 | 5 | 2017/11/09 | 3 months ago | Mini audio library. |
| [mix](https://github.com/go-mix/mix) | 145 | 3 | 2016/01/03 | 1 year ago | Sequence-based Go-native audio mixer for music apps. |
| [gaad](https://github.com/Comcast/gaad) | 92 | 11 | 2016/07/11 | 2 months ago | Native Go AAC bitstream parser. |
| [minimp3](https://github.com/tosone/minimp3) | 68 | 4 | 2018/01/26 | 9 months ago | Lightweight MP3 decoder library. |
| [vorbis](https://github.com/mccoyst/vorbis) | 29 | 3 | 2013/07/12 | 2 years ago | "Native" Go Vorbis decoder (uses CGO, but has no dependencies). |
| [gosamplerate](https://github.com/dh1tw/gosamplerate) | 14 | 1 | 2016/11/20 | 1 year ago | libsamplerate bindings for go. |
**[⬆ back to top](#awesome-go-info)**

## Authentication and OAuth
        
*Libraries for implementing authentications schemes.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [casbin](https://github.com/casbin/casbin) | 10960 | 225 | 2017/04/08 | 1 week ago | Authorization library that supports access control models like ACL, RBAC, ABAC. |
| [oauth2](https://github.com/golang/oauth2) | 3952 | 101 | 2014/04/14 | 2 days ago | Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support. |
| [goth](https://github.com/markbates/goth) | 3453 | 58 | 2014/10/14 | 1 month ago | provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box. |
| [authboss](https://github.com/volatiletech/authboss) | 2963 | 56 | 2015/01/03 | 4 months ago | Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time. |
| [go-jose](https://github.com/square/go-jose) | 1856 | 58 | 2014/11/14 | 2 months ago | Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. |
| [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) | 1846 | 86 | 2015/11/01 | 11 months ago | Standalone, specification-compliant,  OAuth2 server written in Golang. |
| [loginsrv](https://github.com/tarent/loginsrv) | 1834 | 55 | 2016/11/11 | 10 months ago | JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam. |
| [osin](https://github.com/openshift/osin) | 1709 | 71 | 2013/09/10 | 1 month ago | Golang OAuth2 server library. |
| [gologin](https://github.com/dghubble/gologin) | 1460 | 27 | 2015/06/23 | 1 week ago | chainable handlers for login with OAuth1 and OAuth2 authentication providers. |
| [gorbac](https://github.com/mikespook/gorbac) | 1235 | 62 | 2013/12/26 | 7 months ago | provides a lightweight role-based access control (RBAC) implementation in Golang. |
| [scs](https://github.com/alexedwards/scs) | 1001 | 27 | 2016/08/08 | 1 week ago | Session Manager for HTTP servers. |
| [paseto](https://github.com/o1egl/paseto) | 565 | 23 | 2018/01/23 | 2 months ago | Golang implementation of Platform-Agnostic Security Tokens (PASETO). |
| [permissions2](https://github.com/xyproto/permissions2) | 442 | 14 | 2014/11/19 | 5 months ago | Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt. |
| [go-guardian](https://github.com/shaj13/go-guardian) | 329 | 5 | 2020/05/14 | 1 week ago | Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token and Certificate based authentication. |
| [jwt](https://github.com/cristalhq/jwt) | 307 | 12 | 2019/07/20 | 2 weeks ago | Safe, simple and fast JSON Web Tokens for Go. |
| [jwt](https://github.com/pascaldekloe/jwt) | 275 | 13 | 2018/03/21 | 1 month ago | Lightweight JSON Web Token (JWT) library. |
| [jeff](https://github.com/abraithwaite/jeff) | 234 | 4 | 2018/08/02 | 6 months ago | Simple, flexible, secure and idiomatic web session management with pluggable backends. |
| [httpauth](https://github.com/goji/httpauth) | 213 | 8 | 2014/05/26 | 3 months ago | HTTP Authentication middleware. |
| [jwt-auth](https://github.com/adam-hanna/jwt-auth) | 211 | 12 | 2016/07/05 | 4 months ago | JWT middleware for Golang http servers with many configuration options. |
| [branca](https://github.com/hako/branca) | 167 | 8 | 2018/01/09 | 1 year ago | Golang implementation of Branca Tokens. |
| [sessionup](https://github.com/swithek/sessionup) | 113 | 7 | 2019/07/23 | 4 months ago | Simple, yet effective HTTP session management and identification package. |
| [otpgen](https://github.com/RijulGulati/otpgen) | 111 | 2 | 2021/06/01 | 4 months ago | Library to generate TOTP/HOTP codes. |
| [session](https://github.com/icza/session) | 105 | 7 | 2016/02/08 | 5 months ago | Go session management for web servers (including support for Google App Engine - GAE). |
| [jwt](https://github.com/robbert229/jwt) | 94 | 9 | 2016/06/05 | 1 year ago | Clean and easy to use implementation of JSON Web Tokens (JWT). |
| [sjwt](https://github.com/brianvoe/sjwt) | 94 | 1 | 2019/06/20 | 2 years ago | Simple jwt generator and parser. |
| [rbac](https://github.com/zpatrick/rbac) | 88 | 3 | 2018/08/02 | 3 years ago | Minimalistic RBAC package for Go applications. |
| [sessions](https://github.com/adam-hanna/sessions) | 61 | 3 | 2017/04/29 | 1 year ago | Dead simple, highly performant, highly customizable sessions service for go http servers. |
| [securecookie](https://github.com/chmike/securecookie) | 54 | 5 | 2017/09/03 | 3 months ago | Efficient secure cookie encoding/decoding. |
| [go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) | 34 | 1 | 2020/08/21 | 3 months ago | Golang library for providing a canonical representation of email address. |
| [otpgo](https://github.com/jltorresm/otpgo) | 26 | 3 | 2020/08/19 | 10 months ago | Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go. |
| [scope](https://github.com/SonicRoshan/scope) | 17 | 1 | 2019/09/23 | 7 months ago | Easily Manage OAuth2 Scopes In Go. |
| [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) | 9 | 2 | 2017/10/20 | 3 years ago | Go session management using the SessionGate Redis module. |
| [cookiestxt](https://github.com/mengzhuo/cookiestxt) | 8 | 1 | 2017/10/09 | 9 months ago | provides parser of cookies.txt file format. |
**[⬆ back to top](#awesome-go-info)**

## Blockchain
        
*Tools for building blockchains.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-ethereum](https://github.com/ethereum/go-ethereum) | 34379 | 2130 | 2013/12/26 | 8 hours ago | Official Go implementation of the Ethereum protocol. |
| [tendermint](https://github.com/tendermint/tendermint) | 4511 | 262 | 2014/05/14 | 15 hours ago | High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols. |
| [cosmos-sdk](https://github.com/cosmos/cosmos-sdk) | 3181 | 208 | 2016/02/06 | 5 hours ago | A Framework for Building Public Blockchains in the Cosmos Ecosystem. |
| [gossamer](https://github.com/ChainSafe/gossamer) | 296 | 17 | 2019/01/28 | 3 hours ago | A Go implementation of the Polkadot Host. |
| [solana-go](https://github.com/gagliardetto/solana-go) | 164 | 9 | 2021/06/29 | 4 days ago | Go library to interface with Solana JSON RPC and WebSocket interfaces. |
**[⬆ back to top](#awesome-go-info)**

## Bot Building
        
*Libraries for building and working with bots.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [telegram-bot-api](https://github.com/go-telegram-bot-api/telegram-bot-api) | 3294 | 77 | 2015/06/25 | 1 week ago | Simple and clean Telegram bot client. |
| [olivia](https://github.com/olivia-ai/olivia) | 3119 | 83 | 2018/06/05 | 1 week ago | A chatbot built with an artificial neural network. |
| [telebot](https://github.com/tucnak/telebot) | 2246 | 54 | 2015/06/25 | 1 week ago | Telegram bot framework written in Go. |
| [kelp](https://github.com/stellar/kelp) | 822 | 53 | 2018/08/08 | 1 month ago | official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies. |
| [bot](https://github.com/go-chat-bot/bot) | 713 | 47 | 2015/09/22 | 1 year ago | IRC, Slack & Telegram bot written in Go. |
| [golang-crypto-trading-bot](https://github.com/saniales/golang-crypto-trading-bot) | 664 | 38 | 2017/05/14 | 6 months ago | A golang implementation of a console-based trading bot for cryptocurrency exchanges. |
| [slacker](https://github.com/shomali11/slacker) | 573 | 15 | 2017/05/20 | 1 week ago | Easy to use framework to create Slack bots. |
| [tbot](https://github.com/yanzay/tbot) | 321 | 10 | 2015/09/11 | 9 months ago | Telegram bot server with API similar to net/http. |
| [go-sarah](https://github.com/oklahomer/go-sarah) | 212 | 7 | 2016/11/06 | 9 hours ago | Framework to build bot for desired chat services including LINE, Slack, Gitter and more. |
| [go-twitch-irc](https://github.com/gempir/go-twitch-irc) | 208 | 10 | 2017/03/23 | 1 week ago | Library to write bots for twitch. |
| [tenyks](https://github.com/kyleterry/tenyks) | 171 | 14 | 2012/08/26 | 2 years ago | Service oriented IRC bot using Redis and JSON for messaging. |
| [hanu](https://github.com/sbstjn/hanu) | 134 | 7 | 2016/09/16 | 6 months ago | Framework for writing Slack bots. |
| [go-tgbot](https://github.com/olebedev/go-tgbot) | 111 | 9 | 2016/12/11 | 3 years ago | Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware. |
| [slack-bot](https://github.com/innogames/slack-bot) | 70 | 4 | 2019/07/19 | 6 days ago | Ready to use Slack Bot for lazy developers: Custom commands, Jenkins, Jira, Bitbucket, Github... |
| [margelet](https://github.com/zhulik/margelet) | 66 | 4 | 2015/11/21 | 5 years ago | Framework for building Telegram bots. |
| [ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) | 51 | 5 | 2017/12/19 | 2 weeks ago | A Discord bot for managing ephemeral roles based upon voice channel member presence. |
| [slackscot](https://github.com/alexandre-normand/slackscot) | 48 | 2 | 2015/10/22 | 1 month ago | Another framework for building Slack bots. |
| [echotron](https://github.com/NicoNex/echotron) | 45 | 5 | 2019/07/22 | 2 weeks ago | Concurrent library for Telegram Bots written in pure Go. |
| [govkbot](https://github.com/nikepan/govkbot) | 37 | 3 | 2016/07/11 | 4 months ago | Simple Go [VK](https://vk.com) bot library. |
| [larry](https://github.com/ezeoleaf/larry) | 29 | 1 | 2020/11/16 | 1 month ago | Larry 🐦 is a really simple Twitter bot generator that tweets random repositories from Github built in Go. |
| [micha](https://github.com/onrik/micha) | 17 | 4 | 2016/04/14 | 7 months ago | Go Library for Telegram bot api. |
| [teleterm](https://github.com/alfiankan/teleterm) | 4 | 1 | 2020/12/31 | 2 months ago | Telegram Bot Exec Terminal Command. |
**[⬆ back to top](#awesome-go-info)**

## Build Automation
        
*Libraries and tools helping with build automation.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [task](https://github.com/go-task/task) | 4357 | 61 | 2017/02/27 | 5 hours ago | simple "Make" alternative. |
| [realize](https://github.com/oxequa/realize) | 4175 | 72 | 2016/07/12 | 7 months ago | Go build system with file watchers and live reload. Run, build and watch file changes with custom paths. |
| [mmake](https://github.com/tj/mmake) | 1593 | 29 | 2017/02/15 | 1 year ago | Modern Make. |
| [goyek](https://github.com/goyek/goyek) | 269 | 5 | 2020/10/11 | 17 hours ago | Create build pipelines in Go. |
| [taskctl](https://github.com/taskctl/taskctl) | 148 | 7 | 2019/11/12 | 7 months ago | Concurrent task runner. |
| [1build](https://github.com/gopinath-langote/1build) | 118 | 8 | 2019/04/23 | 1 week ago | Command line tool to frictionlessly manage project-specific commands. |
| [gaper](https://github.com/maxcnunes/gaper) | 50 | 0 | 2018/06/16 | 1 week ago | Builds and restarts a Go project when it crashes or some watched file changes. |
| [anko](https://github.com/GuilhermeCaruso/anko) | 20 | 3 | 2021/03/02 | 9 months ago | Simple application watcher for multiple programming languages. |
**[⬆ back to top](#awesome-go-info)**

## CSS Preprocessors
        
*Libraries for preprocessing CSS files.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gcss](https://github.com/yosssi/gcss) | 445 | 16 | 2014/09/04 | 7 years ago | Pure Go CSS Preprocessor. |
| [go-libsass](https://github.com/wellington/go-libsass) | 182 | 8 | 2015/04/19 | 1 year ago | Go wrapper to the 100% Sass compatible libsass project. |
**[⬆ back to top](#awesome-go-info)**

## Command Line
        
**[⬆ back to top](#awesome-go-info)**

## Configuration
        
*Libraries for configuration parsing.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [viper](https://github.com/spf13/viper) | 17757 | 241 | 2014/04/02 | 6 hours ago | Go configuration with fangs. |
| [godotenv](https://github.com/joho/godotenv) | 4423 | 41 | 2013/07/30 | 2 months ago | Go port of Ruby's dotenv library (Loads environment variables from `.env`). |
| [envconfig](https://github.com/kelseyhightower/envconfig) | 3918 | 39 | 2013/11/06 | 2 weeks ago | Go library for managing configuration data from environment variables. |
| [ini](https://github.com/go-ini/ini) | 2798 | 75 | 2014/12/18 | 5 days ago | Go package to read and write INI files. |
| [env](https://github.com/caarlos0/env) | 2174 | 22 | 2015/07/28 | 3 weeks ago | Parse environment variables to Go structs (with defaults). |
| [kong](https://github.com/alecthomas/kong) | 754 | 15 | 2018/04/10 | 3 days ago | Command-line parser with support for arbitrarily complex command-line structures and additional sources of configuration such as YAML, JSON, TOML, etc (succesor to `kingpin`). |
| [koanf](https://github.com/knadh/koanf) | 674 | 13 | 2019/06/18 | 4 weeks ago | Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line. |
| [konfig](https://github.com/lalamove/konfig) | 617 | 14 | 2019/01/18 | 1 year ago | Composable, observable and performant config handling for Go for the distributed processing era. |
| [cleanenv](https://github.com/ilyakaznacheev/cleanenv) | 427 | 6 | 2019/07/12 | 6 days ago | Minimalistic configuration reader (from files, ENV, and wherever you want). |
| [confita](https://github.com/heetch/confita) | 419 | 23 | 2017/12/21 | 5 months ago | Load configuration in cascade from multiple backends into a struct. |
| [aconfig](https://github.com/cristalhq/aconfig) | 326 | 5 | 2020/06/26 | 1 month ago | Simple, useful and opinionated config loader. |
| [config](https://github.com/gookit/config) | 311 | 13 | 2018/07/07 | 1 month ago | application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge. |
| [config](https://github.com/JeremyLoy/config) | 285 | 2 | 2019/04/02 | 1 month ago | Cloud native application configuration. Bind ENV to structs in only two lines. |
| [store](https://github.com/tucnak/store) | 257 | 6 | 2015/10/03 | 4 years ago | Lightweight configuration manager for Go. |
| [hjson-go](https://github.com/hjson/hjson-go) | 250 | 9 | 2016/08/05 | 1 day ago | Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments. |
| [config](https://github.com/olebedev/config) | 241 | 8 | 2014/04/21 | 2 weeks ago | JSON or YAML configuration wrapper with environment variables and flags parsing. |
| [config](https://github.com/golobby/config) | 230 | 5 | 2019/10/15 | 3 weeks ago | A lightweight yet powerful config package for Go projects. |
| [envconfig](https://github.com/vrischmann/envconfig) | 220 | 6 | 2015/04/21 | 2 months ago | Read your configuration from environment variables. |
| [config](https://github.com/joshbetz/config) | 209 | 2 | 2017/04/02 | 1 month ago | Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP. |
| [fig](https://github.com/kkyr/fig) | 185 | 5 | 2020/01/16 | 1 day ago | Tiny library for reading configuration from a file and from environment variables (with validation & defaults). |
| [xdg](https://github.com/adrg/xdg) | 158 | 4 | 2014/08/22 | 2 months ago | Go implementation of the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) and [XDG user directories](https://wiki.archlinux.org/index.php/XDG_user_directories). |
| [gcfg](https://github.com/go-gcfg/gcfg) | 155 | 8 | 2015/08/17 | 5 months ago | read INI-style configuration files into Go structs; supports user-defined types and subsections. |
| [goconfig](https://github.com/gosidekick/goconfig) | 149 | 13 | 2016/12/18 | 2 months ago | Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file. |
| [envh](https://github.com/antham/envh) | 95 | 4 | 2017/01/12 | 8 months ago | Helpers to manage environment variables. |
| [envcfg](https://github.com/tomazk/envcfg) | 94 | 2 | 2014/11/29 | 4 years ago | Un-marshaling environment variables to Go structs. |
| [harvester](https://github.com/beatlabs/harvester) | 94 | 12 | 2019/04/09 | 1 week ago | Harvester, a easy to use static and dynamic configuration package supportig seeding, env vars and Consul integration. |
| [onion](https://github.com/goraz/onion) | 92 | 6 | 2015/07/22 | 4 months ago | Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP. |
| [configuro](https://github.com/sherifabdlnaby/configuro) | 79 | 4 | 2020/04/09 | 9 months ago | opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications. |
| [xdg](https://github.com/OpenPeeDeeP/xdg) | 65 | 3 | 2017/07/20 | 1 year ago | Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html). |
| [gofigure](https://github.com/ian-kent/gofigure) | 60 | 5 | 2014/11/25 | 2 years ago | Go application configuration made easy. |
| [configure](https://github.com/paked/configure) | 54 | 4 | 2015/06/14 | 2 years ago | Provides configuration through multiple sources, including JSON, flags and environment variables. |
| [configuration](https://github.com/BoRuDar/configuration) | 43 | 2 | 2019/11/27 | 1 month ago | Library for initializing configuration structs from env variables, files, flags and 'default' tag. |
| [go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) | 43 | 28 | 2019/01/24 | 9 months ago | Go package that fetches parameters from AWS System Manager - Parameter Store. |
| [uconfig](https://github.com/omeid/uconfig) | 40 | 2 | 2017/05/11 | 3 weeks ago | Lightweight, zero-dependency, and extendable configuration management. |
| [hocon](https://github.com/gurkankaymak/hocon) | 37 | 1 | 2020/03/01 | 1 month ago | Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files. |
| [go-up](https://github.com/ufoscout/go-up) | 35 | 1 | 2018/02/18 | 1 year ago | A simple configuration library with recursive placeholders resolution and no magic. |
| [ingo](https://github.com/schachmat/ingo) | 34 | 1 | 2016/02/07 | 4 years ago | Flags persisted in an ini-like config file. |
| [mini](https://github.com/sasbury/mini) | 28 | 1 | 2015/04/29 | 3 years ago | Golang package for parsing ini-style configuration files. |
| [genv](https://github.com/sakirsensoy/genv) | 25 | 2 | 2019/07/15 | 2 years ago | Read environment variables easily with dotenv support. |
| [conflate](https://github.com/the4thamigo-uk/conflate) | 21 | 0 | 2018/02/01 | 1 year ago | Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema. |
| [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) | 10 | 1 | 2019/12/02 | 1 year ago | Go utility for loading configuration parameters from AWS SSM (Parameter Store). |
| [envconf](https://github.com/ian-kent/envconf) | 9 | 1 | 2014/10/26 | 7 years ago | Configuration from environment. |
| [ini](https://github.com/wlevene/ini) | 8 | 1 | 2021/08/13 | 3 weeks ago | INI Parser & Write Library, Unmarshal to Struct,Marshal to Json,Write File,watch file. |
| [env](https://github.com/nasermirzaei89/env) | 7 | 0 | 2019/07/24 | 1 week ago | Simple useful package for read environment variables. |
| [go-ini](https://github.com/subpop/go-ini) | 5 | 2 | 2019/09/11 | 8 months ago | A Go package that marshals and unmarshals INI-files. |
| [swap](https://github.com/oblq/swap) | 4 | 2 | 2020/04/12 | 1 month ago | Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env). |
| [typenv](https://github.com/diegomarangoni/typenv) | 4 | 1 | 2020/06/30 | 1 year ago | Minimalistic, zero dependency, typed environment variables library. |
| [gonfig](https://github.com/miladabc/gonfig) | 2 | 1 | 2021/01/21 | 4 months ago | Tag-based configuration parser which loads values from different providers into typesafe struct. |
| [go-conf](https://github.com/ThomasObenaus/go-conf) | 1 | 1 | 2021/01/27 | 2 months ago | Simple library for application configuration based on annotated structs. It supports reading the configuration from environment variables, config files and command line parameters. |
**[⬆ back to top](#awesome-go-info)**

## Continuous Integration
        
*Tools for help with continuous integration.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [drone](https://github.com/harness/drone) | 24327 | 558 | 2014/02/07 | 2 hours ago | Drone is a Continuous Integration platform built on Docker, written in Go. |
| [cds](https://github.com/ovh/cds) | 3685 | 85 | 2016/10/11 | 2 hours ago | Enterprise-Grade CI/CD and DevOps Automation Open Source Platform. |
| [goveralls](https://github.com/mattn/goveralls) | 708 | 13 | 2013/04/17 | 3 months ago | Go integration for Coveralls.io continuous code coverage tracking system. |
| [gotestfmt](https://github.com/haveyoudebuggedit/gotestfmt) | 177 | 3 | 2021/04/29 | 2 weeks ago | go test output for humans. |
| [overalls](https://github.com/go-playground/overalls) | 108 | 4 | 2015/07/30 | 2 years ago | Multi-Package go project coverprofile for tools like goveralls. |
| [duci](https://github.com/duck8823/duci) | 71 | 3 | 2018/04/01 | 1 week ago | A simple ci server no needs domain specific languages. |
| [gomason](https://github.com/nikogura/gomason) | 51 | 1 | 2017/11/18 | 23 hours ago | Test, Build, Sign, and Publish your go binaries from a clean workspace. |
| [roveralls](https://github.com/lawrencewoodman/roveralls) | 15 | 2 | 2016/06/26 | 4 years ago | Recursive coverage testing tool. |
**[⬆ back to top](#awesome-go-info)**

## Data Structures
        
*Generic datastructures and algorithms in Go.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gods](https://github.com/emirpasic/gods) | 10915 | 343 | 2015/03/04 | 1 month ago | Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc. |
| [go-datastructures](https://github.com/Workiva/go-datastructures) | 6306 | 327 | 2014/10/29 | 8 months ago | Collection of useful, performant, and thread-safe data structures. |
| [golang-set](https://github.com/deckarep/golang-set) | 2194 | 44 | 2013/07/03 | 2 days ago | Thread-Safe and Non-Thread-Safe high-performance sets for Go. |
| [gota](https://github.com/go-gota/gota) | 1910 | 77 | 2016/02/06 | 1 month ago | Implementation of dataframes, series, and data wrangling methods for Go. |
| [roaring](https://github.com/RoaringBitmap/roaring) | 1431 | 40 | 2014/07/10 | 1 day ago | Go package implementing compressed bitsets. |
| [BoomFilters](https://github.com/tylertreat/BoomFilters) | 1397 | 39 | 2015/02/06 | 9 months ago | Probabilistic data structures for processing continuous, unbounded streams. |
| [bloom](https://github.com/bits-and-blooms/bloom) | 1397 | 36 | 2011/05/21 | 2 months ago | Go package implementing Bloom filters. |
| [gocache](https://github.com/eko/gocache) | 1027 | 19 | 2019/10/05 | 1 month ago | A complete Go cache library with mutiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more. |
| [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) | 855 | 19 | 2015/06/28 | 4 months ago | Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. |
| [bitset](https://github.com/bits-and-blooms/bitset) | 765 | 30 | 2011/05/11 | 3 months ago | Go package implementing bitsets. |
| [hyperloglog](https://github.com/axiomhq/hyperloglog) | 762 | 17 | 2017/06/18 | 2 months ago | HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction. |
| [algorithms](https://github.com/shady831213/algorithms) | 595 | 19 | 2018/01/31 | 9 months ago | Algorithms and data structures.CLRS study. |
| [trie](https://github.com/derekparker/trie) | 563 | 22 | 2014/03/06 | 1 year ago | Trie implementation in Go. |
| [gostl](https://github.com/liyue201/gostl) | 358 | 11 | 2019/10/12 | 3 months ago | Data structure and algorithm library for go, designed to provide functions similar to C++ STL. |
| [go-geoindex](https://github.com/hailocab/go-geoindex) | 332 | 65 | 2015/01/22 | 3 years ago | In-memory geo index. |
| [ttlcache](https://github.com/ReneKroon/ttlcache) | 323 | 14 | 2014/12/13 | 1 week ago | In-memory string-interface{} cache with various time-based expiration options and callbacks. |
| [merkletree](https://github.com/cbergoon/merkletree) | 299 | 8 | 2017/04/12 | 2 years ago | Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures. |
| [go-edlib](https://github.com/hbollon/go-edlib) | 297 | 10 | 2020/08/18 | 2 weeks ago | Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode. |
| [deque](https://github.com/gammazero/deque) | 268 | 7 | 2018/04/24 | 2 weeks ago | Fast ring-buffer deque (double-ended queue). |
| [hilbert](https://github.com/google/hilbert) | 238 | 22 | 2015/08/06 | 3 years ago | Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves. |
| [goskiplist](https://github.com/ryszard/goskiplist) | 230 | 16 | 2012/05/09 | 2 years ago | Skip list implementation in Go. |
| [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) | 218 | 8 | 2016/04/01 | 1 year ago | Go implementation of Adaptive Radix Tree. |
| [cuckoo-filter](https://github.com/linvon/cuckoo-filter) | 190 | 5 | 2021/02/19 | 2 months ago | Cuckoo filter: a comprehensive cuckoo filter, which is configurable and space optimized compared with other implements, and all features mentioned in original paper is available. |
| [skiplist](https://github.com/MauriceGit/skiplist) | 181 | 6 | 2018/06/23 | 1 month ago | Very fast Go Skiplist implementation. |
| [binpacker](https://github.com/zhuangsirui/binpacker) | 179 | 13 | 2016/02/02 | 2 months ago | Binary packer and unpacker helps user build custom binary stream. |
| [levenshtein](https://github.com/agnivade/levenshtein) | 167 | 4 | 2014/07/30 | 7 months ago | Implementation to calculate levenshtein distance in Go. |
| [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) | 155 | 3 | 2019/01/10 | 1 year ago | Concurrent FIFO queue. |
| [bloom](https://github.com/zentures/bloom) | 144 | 8 | 2013/09/03 | 3 years ago | Bloom filters implemented in Go. |
| [iter](https://github.com/disksing/iter) | 140 | 5 | 2019/10/20 | 2 years ago | Go implementation of C++ STL iterators and algorithms. |
| [ring](https://github.com/tannerryan/ring) | 121 | 1 | 2019/01/27 | 1 year ago | Go implementation of a high performance, thread safe bloom filter. |
| [go-rquad](https://github.com/arl/go-rquad) | 118 | 4 | 2016/09/12 | 1 year ago | Region quadtrees with efficient point location and neighbour finding. |
| [encoding](https://github.com/zentures/encoding) | 110 | 7 | 2013/09/20 | 4 years ago | Integer Compression Libraries for Go. |
| [bitmap](https://github.com/kelindar/bitmap) | 108 | 4 | 2021/05/28 | 4 days ago | Dense, zero-allocation, SIMD-enabled bitmap/bitset in Go. |
| [bit](https://github.com/yourbasic/bit) | 107 | 8 | 2017/05/03 | 3 years ago | Golang set data structure with bonus bit-twiddling functions. |
| [remember-go](https://github.com/rocketlaunchr/remember-go) | 107 | 5 | 2019/04/04 | 8 months ago | A universal interface for caching slow database queries (backed by redis, memcached, ristretto, or in-memory). |
| [conjungo](https://github.com/InVisionApp/conjungo) | 99 | 111 | 2016/12/29 | 1 year ago | A small, powerful and flexible merge library. |
| [skiplist](https://github.com/gansidui/skiplist) | 75 | 7 | 2014/11/18 | 7 years ago | Skiplist implementation in Go. |
| [go-mcache](https://github.com/OrlovEvgeny/go-mcache) | 74 | 4 | 2018/04/14 | 1 year ago | Fast in-memory key:value store/cache library. Pointer caches. |
| [bloom](https://github.com/yourbasic/bloom) | 63 | 3 | 2017/05/06 | 4 years ago | Golang Bloom filter implementation. |
| [levenshtein](https://github.com/agext/levenshtein) | 59 | 2 | 2016/04/08 | 1 year ago | Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. |
| [count-min-log](https://github.com/seiflotfy/count-min-log) | 54 | 2 | 2015/08/16 | 4 years ago | Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory). |
| [crunch](https://github.com/superwhiskers/crunch) | 47 | 6 | 2019/02/27 | 4 months ago | Go package implementing buffers for handling various datatypes easily. |
| [nan](https://github.com/kak-tus/nan) | 46 | 3 | 2020/05/05 | 3 months ago | Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers. |
| [goset](https://github.com/zoumo/goset) | 43 | 1 | 2017/08/25 | 1 year ago | A useful Set collection implementation for Go. |
| [hide](https://github.com/emvi/hide) | 42 | 4 | 2019/01/16 | 1 month ago | ID type with marshalling to/from hash to prevent sending IDs to clients. |
| [pipeline](https://github.com/hyfather/pipeline) | 38 | 2 | 2018/04/25 | 1 month ago | An implementation of pipelines with fan-in and fan-out. |
| [concurrent-writer](https://github.com/free/concurrent-writer) | 36 | 5 | 2017/09/18 | 4 years ago | Highly concurrent drop-in replacement for `bufio.Writer`. |
| [deque](https://github.com/edwingeng/deque) | 36 | 4 | 2019/02/01 | 7 months ago | A highly optimized double-ended queue. |
| [timedmap](https://github.com/zekroTJA/timedmap) | 36 | 2 | 2019/01/30 | 1 month ago | Map with expiring key-value pairs. |
| [typ](https://github.com/gurukami/typ) | 29 | 2 | 2019/03/03 | 2 months ago | Null Types, Safe primitive type conversion and fetching value from complex structures. |
| [null](https://github.com/emvi/null) | 23 | 3 | 2018/07/04 | 1 month ago | Nullable Go types that can be marshalled/unmarshalled to/from JSON. |
| [dict](https://github.com/srfrog/dict) | 22 | 2 | 2019/04/23 | 1 year ago | Python-like dictionaries (dict) for Go. |
| [cmap](https://github.com/lrita/cmap) | 21 | 2 | 2019/11/26 | 1 year ago | a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards. |
| [go-ef](https://github.com/amallia/go-ef) | 18 | 2 | 2017/09/22 | 4 years ago | A Go implementation of the Elias-Fano encoding. |
| [mspm](https://github.com/BlackRabbitt/mspm) | 16 | 3 | 2018/05/17 | 3 years ago | Multi-String Pattern Matching Algorithm for information retrieval. |
| [ptrie](https://github.com/viant/ptrie) | 16 | 8 | 2019/05/20 | 1 year ago | An implementation of prefix tree. |
| [set](https://github.com/StudioSol/set) | 16 | 21 | 2018/07/20 | 2 months ago | Simple set data structure implementation in Go using LinkedHashMap. |
| [parapipe](https://github.com/nazar256/parapipe) | 13 | 1 | 2021/04/09 | 6 months ago | FIFO Pipeline which parallels execution on each stage while maintaining the order of messages and results. |
| [fsm](https://github.com/cocoonspace/fsm) | 12 | 1 | 2021/10/11 | 2 months ago | Finite-State Machine package. |
| [ordered-concurrently](https://github.com/tejzpr/ordered-concurrently) | 12 | 1 | 2021/02/28 | 1 month ago | Go module that processes work concurrently and returns output in a channel in the order of input. |
| [treap](https://github.com/perdata/treap) | 12 | 3 | 2018/09/16 | 2 years ago | Persistent, fast ordered map using tree heaps. |
| [gofal](https://github.com/xxjwxc/gofal) | 9 | 2 | 2019/08/05 | 2 years ago | fractional api for Go. |
| [bloomfilter](https://github.com/OldPanda/bloomfilter) | 6 | 1 | 2021/01/01 | 6 months ago | Yet another Bloomfilter implementation in Go, compatible with Java's Guava library. |
| [gdcache](https://github.com/ulovecode/gdcache) | 6 | 1 | 2021/07/20 | 2 months ago | A pure non-intrusive cache library implemented by golang, you can use it to implement your own distributed cache. |
| [goterator](https://github.com/yaa110/goterator) | 6 | 1 | 2020/08/12 | 1 year ago | Iterator implementation to provide map and reduce functionalities. |
| [parsefields](https://github.com/MonaxGT/parsefields) | 6 | 1 | 2019/04/12 | 2 years ago | Tools for parse JSON-like logs for collecting unique fields and events. |
| [dsu](https://github.com/ihebu/dsu) | 5 | 1 | 2021/04/27 | 6 months ago | Disjoint Set data structure implementation in Go. |
| [slices](https://github.com/srfrog/slices) | 5 | 3 | 2020/07/02 | 1 year ago | Functions that operate on slices; like `package strings` but adapted to work with slices. |
| [merkle](https://github.com/bobg/merkle) | 1 | 2 | 2018/10/13 | 4 months ago | Space-efficient computation of Merkle root hashes and inclusion proofs. |
**[⬆ back to top](#awesome-go-info)**

## Database
        
*SQL query builder, libraries for building and using SQL.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [prometheus](https://github.com/prometheus/prometheus) | 40207 | 1139 | 2012/11/24 | 1 hour ago | Monitoring system and time series database. |
| [tidb](https://github.com/pingcap/tidb) | 29976 | 1320 | 2015/09/06 | 40 minutes ago | TiDB is a distributed SQL database. Inspired by the design of Google F1. |
| [cockroach](https://github.com/cockroachdb/cockroach) | 22754 | 725 | 2014/02/06 | 1 hour ago | Scalable, Geo-Replicated, Transactional Datastore. |
| [influxdb](https://github.com/influxdata/influxdb) | 22615 | 752 | 2013/09/26 | 5 days ago | Scalable datastore for metrics, events, and real-time analytics. |
| [dgraph](https://github.com/dgraph-io/dgraph) | 17164 | 374 | 2015/08/25 | 6 days ago | Scalable, Distributed, Low Latency, High Throughput Graph Database. |
| [vitess](https://github.com/vitessio/vitess) | 13110 | 514 | 2013/06/27 | 1 hour ago | vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. |
| [groupcache](https://github.com/golang/groupcache) | 11007 | 499 | 2013/07/22 | 7 months ago | Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. |
| [badger](https://github.com/dgraph-io/badger) | 10161 | 243 | 2017/01/26 | 4 days ago | Fast key-value store in Go. |
| [rqlite](https://github.com/rqlite/rqlite) | 9184 | 218 | 2014/08/23 | 3 days ago | The lightweight, distributed, relational database built on SQLite. |
| [milvus](https://github.com/milvus-io/milvus) | 9069 | 186 | 2019/09/16 | 1 hour ago | Milvus is a vector database for embedding management, analytics and search. |
| [migrate](https://github.com/golang-migrate/migrate) | 7760 | 78 | 2018/01/19 | 4 days ago | Database migrations. CLI and Golang library. |
| [pgweb](https://github.com/sosedoff/pgweb) | 7123 | 147 | 2014/10/09 | 2 days ago | Web-based PostgreSQL database browser. |
| [immudb](https://github.com/codenotary/immudb) | 6102 | 79 | 2019/11/07 | 23 hours ago | immudb is a lightweight, high-speed immutable database for systems and applications written in Go. |
| [kingshard](https://github.com/flike/kingshard) | 5893 | 405 | 2015/07/04 | 6 months ago | kingshard is a high performance proxy for MySQL powered by Golang. |
| [go-cache](https://github.com/patrickmn/go-cache) | 5697 | 114 | 2012/01/02 | 2 weeks ago | In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications. |
| [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) | 5609 | 108 | 2018/09/30 | 1 day ago | fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL. |
| [bigcache](https://github.com/allegro/bigcache) | 5334 | 117 | 2016/03/23 | 3 weeks ago | Efficient key/value cache for gigabytes of data. |
| [bbolt](https://github.com/etcd-io/bbolt) | 5035 | 119 | 2017/06/17 | 1 week ago | An embedded key/value database for Go. |
| [goleveldb](https://github.com/syndtr/goleveldb) | 4807 | 180 | 2013/01/23 | 5 days ago | Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go. |
| [squirrel](https://github.com/Masterminds/squirrel) | 4420 | 50 | 2014/01/18 | 4 weeks ago | Go library that helps you build SQL queries. |
| [orchestrator](https://github.com/openark/orchestrator) | 4355 | 266 | 2016/11/30 | 1 week ago | MySQL replication topology manager & visualizer. |
| [dtm](https://github.com/dtm-labs/dtm) | 4312 | 94 | 2021/05/16 | 3 hours ago | A distributed transaction manager. Support XA, TCC, SAGA, Reliable Messages. |
| [dtm](https://github.com/yedf/dtm) | 4207 | 92 | 2021/05/16 | 5 days ago | A distributed transaction manager. Support XA, TCC, SAGA, Reliable Messages. |
| [ledisdb](https://github.com/ledisdb/ledisdb) | 3774 | 185 | 2014/04/30 | 9 months ago | Ledisdb is a high performance NoSQL like Redis based on LevelDB. |
| [go-mysql-elasticsearch](https://github.com/go-mysql-org/go-mysql-elasticsearch) | 3683 | 180 | 2015/01/15 | 10 months ago | Sync your MySQL data into Elasticsearch automatically. |
| [buntdb](https://github.com/tidwall/buntdb) | 3594 | 98 | 2016/07/19 | 3 days ago | Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support. |
| [go-mysql](https://github.com/go-mysql-org/go-mysql) | 3389 | 158 | 2014/02/21 | 6 days ago | Go toolset to handle MySQL protocol and replication. |
| [prest](https://github.com/prest/prest) | 3033 | 82 | 2016/11/22 | 5 hours ago | Simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new. |
| [xo](https://github.com/xo/xo) | 2978 | 69 | 2016/02/05 | 1 day ago | Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server. |
| [tiedot](https://github.com/HouzuoGuo/tiedot) | 2648 | 159 | 2013/05/26 | 3 months ago | Your NoSQL database powered by Golang. |
| [sql-migrate](https://github.com/rubenv/sql-migrate) | 2337 | 34 | 2014/09/09 | 4 days ago | Database migration tool. Allows embedding migrations into the application using go-bindata. |
| [rosedb](https://github.com/flower-corp/rosedb) | 2150 | 27 | 2020/12/06 | 5 days ago | An embedded k-v database based on LSM+WAL, supports string, list, hash, set, zset. |
| [goose](https://github.com/pressly/goose) | 2132 | 46 | 2016/02/25 | 1 week ago | Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. |
| [nutsdb](https://github.com/xujiajun/nutsdb) | 1832 | 49 | 2018/12/07 | 2 weeks ago | Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set. |
| [gcache](https://github.com/bluele/gcache) | 1793 | 44 | 2015/01/24 | 4 months ago | Cache library with support for expirable Cache, LFU, LRU and ARC. |
| [cache2go](https://github.com/muesli/cache2go) | 1655 | 68 | 2013/11/11 | 1 month ago | In-memory key:value cache which supports automatic invalidation based on timeouts. |
| [godis](https://github.com/HDT3213/godis) | 1587 | 23 | 2019/06/01 | 9 hours ago | A Golang implemented high-performance Redis server and cluster. |
| [goqu](https://github.com/doug-martin/goqu) | 1349 | 36 | 2015/02/21 | 1 week ago | Idiomatic SQL builder and query library. |
| [gendry](https://github.com/didi/gendry) | 1323 | 65 | 2017/12/01 | 1 month ago | Non-invasive SQL builder and powerful data binder. |
| [fastcache](https://github.com/VictoriaMetrics/fastcache) | 1315 | 30 | 2018/11/22 | 3 weeks ago | fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead. |
| [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) | 1261 | 72 | 2018/04/11 | 4 months ago | CovenantSQL is a SQL database on blockchain. |
| [diskv](https://github.com/peterbourgon/diskv) | 1119 | 40 | 2012/03/21 | 1 month ago | Home-grown disk-backed key-value store. |
| [skeema](https://github.com/skeema/skeema) | 968 | 30 | 2016/10/31 | 20 hours ago | Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools. |
| [databunker](https://github.com/securitybunker/databunker) | 942 | 27 | 2019/12/08 | 4 days ago | Personally identifiable information (PII) storage service built to comply with GDPR and CCPA. |
| [eliasdb](https://github.com/krotik/eliasdb) | 861 | 25 | 2016/08/13 | 7 months ago | Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language. |
| [moss](https://github.com/couchbase/moss) | 845 | 76 | 2016/02/06 | 1 week ago | Moss is a simple LSM key-value storage engine written in 100% Go. |
| [column](https://github.com/kelindar/column) | 841 | 13 | 2021/05/26 | 3 hours ago | High-performance, columnar, embeddable in-memory store with bitmap indexing and transactions. |
| [pogreb](https://github.com/akrylysov/pogreb) | 838 | 26 | 2018/01/06 | 4 months ago | Embedded key-value store for read-heavy workloads. |
| [chproxy](https://github.com/ContentSquare/chproxy) | 774 | 32 | 2017/09/18 | 1 week ago | HTTP proxy for ClickHouse database. |
| [goavro](https://github.com/linkedin/goavro) | 765 | 23 | 2015/02/23 | 2 months ago | A Go package that encodes and decodes Avro data. |
| [gormigrate](https://github.com/go-gormigrate/gormigrate) | 708 | 7 | 2016/08/31 | 3 days ago | Database schema migration helper for Gorm ORM. |
| [dotsql](https://github.com/qustavo/dotsql) | 607 | 24 | 2014/11/20 | 4 months ago | Go library that helps you keep sql files in one place and use them with ease. |
| [pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) | 594 | 16 | 2018/12/19 | 3 days ago | Advanced scheduling for PostgreSQL. |
| [jet](https://github.com/go-jet/jet) | 581 | 15 | 2019/03/02 | 2 days ago | Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure. |
| [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) | 545 | 28 | 2015/12/10 | 3 weeks ago | Powerful data retrieval methods as well as DB-agnostic query building capabilities. |
| [levigo](https://github.com/jmhodges/levigo) | 402 | 23 | 2012/01/17 | 1 week ago | Levigo is a Go wrapper for LevelDB. |
| [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) | 328 | 7 | 2017/04/29 | 2 months ago | Collects small insterts and sends big requests to ClickHouse servers. |
| [dbq](https://github.com/rocketlaunchr/dbq) | 326 | 9 | 2019/07/11 | 10 months ago | Zero boilerplate database operations for Go. |
| [pudge](https://github.com/recoilme/pudge) | 304 | 11 | 2018/11/20 | 5 months ago | Fast and simple  key/value store written using Go's standard library. |
| [sqrl](https://github.com/elgris/sqrl) | 236 | 10 | 2014/06/25 | 2 months ago | SQL query builder, fork of Squirrel with improved performance. |
| [vasto](https://github.com/chrislusf/vasto) | 229 | 19 | 2018/01/16 | 2 years ago | A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption. |
| [kivik](https://github.com/go-kivik/kivik) | 217 | 5 | 2017/02/09 | 6 months ago | Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases. |
| [piladb](https://github.com/fern4lvarez/piladb) | 192 | 12 | 2015/09/08 | 1 year ago | Lightweight RESTful database engine based on stack data structures. |
| [sqlingo](https://github.com/lqs/sqlingo) | 192 | 13 | 2018/11/18 | 3 weeks ago | A lightweight DSL to build SQL in Go. |
| [myreplication](https://github.com/2tvenom/myreplication) | 176 | 21 | 2015/02/04 | 3 years ago | MySql binary log replication listener. Supports statement and row based replication. |
| [octillery](https://github.com/blastrain/octillery) | 148 | 19 | 2018/11/26 | 7 months ago | Go package for sharding databases ( Supports every ORM or raw SQL ). |
| [go-structured-query](https://github.com/bokwoon95/go-structured-query) | 145 | 1 | 2020/05/30 | 2 months ago | Type-safe SQL builder and struct mapper for Go. |
| [golang-scribble](https://github.com/nanobox-io/golang-scribble) | 141 | 5 | 2018/06/21 | 2 years ago | Tiny flat file JSON store. |
| [darwin](https://github.com/GuiaBolso/darwin) | 125 | 4 | 2016/04/05 | 9 months ago | Database schema evolution library for Go. |
| [migrator](https://github.com/lopezator/migrator) | 116 | 5 | 2019/02/04 | 1 year ago | Dead simple Go database migration library. |
| [slowpoke](https://github.com/recoilme/slowpoke) | 98 | 8 | 2018/02/19 | 2 years ago | Key-value store with persistence. |
| [cache](https://github.com/akyoto/cache) | 97 | 3 | 2019/05/11 | 1 year ago | In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage. |
| [igor](https://github.com/galeone/igor) | 84 | 7 | 2016/03/10 | 1 year ago | Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax. |
| [unitdb](https://github.com/unit-io/unitdb) | 81 | 8 | 2019/08/29 | 2 months ago | Fast timeseries database for IoT, realtime messaging  applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application. |
| [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) | 81 | 1 | 2018/08/11 | 4 months ago | A Go package to help write migrations with go-pg/pg. |
| [bcache](https://github.com/iwanbk/bcache) | 75 | 4 | 2018/12/26 | 2 years ago | Eventually consistent distributed in-memory  cache Go library. |
| [dbbench](https://github.com/sj14/dbbench) | 62 | 4 | 2018/11/24 | 2 weeks ago | Database benchmarking tool with support for several databases and scripts. |
| [couchcache](https://github.com/codingsince1985/couchcache) | 53 | 4 | 2015/04/05 | 2 months ago | RESTful caching micro-service backed by Couchbase server. |
| [godbal](https://github.com/xujiajun/godbal) | 52 | 4 | 2018/02/28 | 2 years ago | Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily. |
| [hare](https://github.com/jameycribbs/hare) | 48 | 6 | 2016/10/05 | 10 months ago | A simple database management system that stores each table as a text file of line-delimited JSON. |
| [datagen](https://github.com/codingconcepts/datagen) | 45 | 1 | 2019/04/18 | 1 year ago | A fast data generator that's multi-table aware and supports multi-row DML. |
| [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) | 39 | 6 | 2017/12/18 | 3 years ago | BigCache with clustering support and individual item expiration. |
| [buildsqlx](https://github.com/arthurkushman/buildsqlx) | 38 | 1 | 2019/08/18 | 8 months ago | Go database query builder library for PostgreSQL. |
| [sqlf](https://github.com/leporo/sqlf) | 36 | 4 | 2019/07/20 | 4 weeks ago | Fast SQL query builder. |
| [prep](https://github.com/hexdigest/prep) | 30 | 3 | 2017/12/11 | 4 years ago | Use prepared SQL statements without changing your code. |
| [coffer](https://github.com/claygod/coffer) | 28 | 5 | 2019/05/13 | 3 months ago | Simple ACID key-value database that supports transactions. |
| [sqlize](https://github.com/sunary/sqlize) | 27 | 1 | 2020/09/08 | 3 days ago | Database migration generator. Allows generate sql migration from model and existing sql by differ them. |
| [avro](https://github.com/khezen/avro) | 26 | 3 | 2019/04/07 | 1 year ago | Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes. |
| [go-fixtures](https://github.com/RichardKnop/go-fixtures) | 26 | 1 | 2015/12/24 | 2 years ago | Django style fixtures for Golang's excellent built-in database/sql library. |
| [bqb](https://github.com/nullism/bqb) | 26 | 1 | 2021/07/31 | 2 weeks ago | Lightweight and easy to learn query builder. |
| [pravasan](https://github.com/pravasan/pravasan) | 25 | 7 | 2015/01/03 | 3 years ago | Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc. |
| [qry](https://github.com/HnH/qry) | 19 | 3 | 2019/08/20 | 2 months ago | Tool that generates constants from files with raw SQL queries. |
| [gosql](https://github.com/twharmon/gosql) | 17 | 1 | 2020/01/08 | 1 year ago | SQL Query builder with better null values support. |
| [tempdb](https://github.com/rafaeljesus/tempdb) | 15 | 3 | 2017/03/17 | 3 years ago | Key-value store for temporary items. |
| [rwdb](https://github.com/andizzle/rwdb) | 13 | 2 | 2017/10/04 | 4 years ago | rwdb provides read replica capability for multiple database servers setup. |
| [migrator](https://github.com/larapulse/migrator) | 12 | 2 | 2020/06/27 | 8 months ago | MySQL database migrator designed to run migrations to your features and manage database schema update with intuitive go code. |
| [mpath-go](https://github.com/spacetab-io/mpath-go) | 10 | 4 | 2020/01/09 | 1 year ago | MPTT (Modified Preorder Tree Traversal) package for SQL records - materialized path realisation. |
| [schema](https://github.com/adlio/schema) | 9 | 3 | 2019/09/24 | 2 weeks ago | Library to embed schema migrations for database/sql-compatible databases inside your Go binaries. |
| [go-pg-migrate](https://github.com/lawzava/go-pg-migrate) | 6 | 1 | 2021/01/16 | 3 weeks ago | CLI-friendly package for go-pg migrations management. |
| [ttlcache](https://github.com/cheshir/ttlcache) | 3 | 1 | 2021/01/06 | 9 months ago | In-memory key value storage with TTL for each record. |
| [ormlite](https://github.com/pupizoid/ormlite) | 1 | 2 | 2018/06/28 | 11 months ago | Lightweight package containing some ORM-like features and helpers for sqlite databases. |
**[⬆ back to top](#awesome-go-info)**

## Database Drivers
        
*Libraries for connecting and operating databases.*
**[⬆ back to top](#awesome-go-info)**

### NoSQL Databases
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [cayley](https://github.com/cayleygraph/cayley) | 14024 | 600 | 2014/06/05 | 1 month ago | Graph database with support for multiple backends. |
| [redis](https://github.com/go-redis/redis) | 13173 | 247 | 2012/07/25 | 1 day ago | Redis client for Golang. |
| [redigo](https://github.com/gomodule/redigo) | 8800 | 291 | 2012/04/14 | 3 days ago | Redigo is a Go client for the Redis database. |
| [bleve](https://github.com/blevesearch/bleve) | 8110 | 249 | 2014/04/17 | 1 week ago | Modern text indexing library for go. |
| [elastic](https://github.com/olivere/elastic) | 6458 | 173 | 2012/12/06 | 1 week ago | Elasticsearch client for Go. |
| [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) | 6350 | 130 | 2017/02/08 | 5 days ago | Official MongoDB driver for the Go language. |
| [riot](https://github.com/go-ego/riot) | 6032 | 201 | 2017/06/21 | 1 year ago | Go Open Source, Distributed, Simple and efficient Search Engine. |
| [go-elasticsearch](https://github.com/elastic/go-elasticsearch) | 3830 | 323 | 2017/03/27 | 6 days ago | Official Elasticsearch client for Go. |
| [mgo](https://github.com/globalsign/mgo) | 1927 | 63 | 2017/04/13 | 2 months ago | (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms. |
| [rethinkdb-go](https://github.com/rethinkdb/rethinkdb-go) | 1587 | 49 | 2013/09/12 | 3 months ago | Go language driver for RethinkDB. |
| [elastigo](https://github.com/mattbaird/elastigo) | 946 | 47 | 2012/10/12 | 2 years ago | Elasticsearch client library. |
| [elasticsql](https://github.com/cch123/elasticsql) | 841 | 33 | 2016/08/24 | 1 month ago | Convert sql to elasticsearch dsl in Go. |
| [qmgo](https://github.com/qiniu/qmgo) | 755 | 20 | 2020/08/04 | 4 weeks ago | The MongoDB driver for Go. It‘s based on official MongoDB driver but easier to use like Mgo. |
| [mgm](https://github.com/Kamva/mgm) | 430 | 16 | 2019/12/27 | 2 weeks ago | MongoDB model-based ODM for Go (based on official MongoDB driver). |
| [redeo](https://github.com/bsm/redeo) | 409 | 26 | 2014/03/06 | 1 year ago | Redis-protocol compatible TCP servers/services. |
| [gokv](https://github.com/philippgille/gokv) | 384 | 10 | 2018/10/08 | 3 months ago | Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more). |
| [neoism](https://github.com/jmcvetta/neoism) | 382 | 24 | 2012/07/12 | 1 year ago | Neo4j client for Golang. |
| [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) | 371 | 42 | 2014/07/26 | 3 weeks ago | Aerospike client in Go language. |
| [gocb](https://github.com/couchbase/gocb) | 328 | 67 | 2015/01/15 | 1 week ago | Official Couchbase Go SDK. |
| [go-couchbase](https://github.com/couchbase/go-couchbase) | 312 | 25 | 2012/01/19 | 5 days ago | Couchbase client in Go. |
| [go-rejson](https://github.com/nitishm/go-rejson) | 224 | 7 | 2018/04/23 | 8 months ago | Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease. |
| [cachego](https://github.com/faabiosr/cachego) | 159 | 7 | 2016/10/05 | 3 months ago | Golang Cache component for multiple drivers. |
| [godis](https://github.com/piaohao/godis) | 99 | 10 | 2019/06/14 | 1 year ago | redis client implement by golang, inspired by jedis. |
| [skizze](https://github.com/seiflotfy/skizze) | 81 | 6 | 2016/01/17 | 5 years ago | probabilistic data-structures service and storage. |
| [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) | 77 | 7 | 2011/06/04 | 3 years ago | Neo4j REST Client in golang. |
| [arangolite](https://github.com/solher/arangolite) | 69 | 6 | 2015/10/04 | 9 months ago | Lightweight golang driver for ArangoDB. |
| [go-pilosa](https://github.com/pilosa/go-pilosa) | 50 | 20 | 2016/09/30 | 1 year ago | Go client library for Pilosa. |
| [goforestdb](https://github.com/couchbase/goforestdb) | 32 | 39 | 2014/05/14 | 5 years ago | Go bindings for ForestDB. |
| [neo4j](https://github.com/cihangir/neo4j) | 27 | 4 | 2013/05/18 | 6 years ago | Neo4j Rest API Bindings for Golang. |
| [goriak](https://github.com/zegl/goriak) | 25 | 4 | 2016/10/05 | 3 months ago | Go language driver for Riak KV. |
| [goes](https://github.com/OwnLocal/goes) | 25 | 34 | 2015/12/28 | 1 year ago | Library to interact with Elasticsearch. |
| [dsc](https://github.com/viant/dsc) | 23 | 16 | 2016/06/13 | 1 year ago | Datastore connectivity for SQL, NoSQL, structured files. |
| [xredis](https://github.com/shomali11/xredis) | 16 | 2 | 2017/06/14 | 2 years ago | Typesafe, customizable, clean & easy to use Redis client. |
| [godscache](https://github.com/defcronyke/godscache) | 9 | 3 | 2018/05/08 | 2 years ago | A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached. |
| [asc](https://github.com/viant/asc) | 6 | 11 | 2016/06/13 | 2 years ago | Datastore Connectivity for Aerospike for go. |
| [gocosmos](https://github.com/btnguyen2k/gocosmos) | 5 | 2 | 2020/12/06 | 5 months ago | REST client and standard `database/sql` driver for Azure Cosmos DB. |
**[⬆ back to top](#awesome-go-info)**

### Relational Databases
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [mysql](https://github.com/go-sql-driver/mysql) | 11762 | 405 | 2012/12/09 | 1 week ago | MySQL driver for Go. |
| [pq](https://github.com/lib/pq) | 6971 | 150 | 2012/03/12 | 1 month ago | Pure Go Postgres driver for database/sql. |
| [go-sqlite3](https://github.com/mattn/go-sqlite3) | 5327 | 148 | 2011/11/11 | 1 day ago | SQLite3 driver for go that uses database/sql. |
| [pgx](https://github.com/jackc/pgx) | 4869 | 87 | 2013/03/30 | 4 days ago | PostgreSQL driver supporting features beyond those exposed by database/sql. |
| [go-mssqldb](https://github.com/denisenkom/go-mssqldb) | 1488 | 67 | 2013/12/16 | 4 days ago | Microsoft MSSQL driver for Go. |
| [go-oci8](https://github.com/mattn/go-oci8) | 574 | 40 | 2012/02/29 | 2 months ago | Oracle driver for go that uses database/sql. |
| [sqlhooks](https://github.com/qustavo/sqlhooks) | 501 | 6 | 2016/04/20 | 3 hours ago | Attach hooks to any database/sql driver. |
| [godror](https://github.com/godror/godror) | 311 | 22 | 2019/11/21 | 4 hours ago | Oracle driver for Go, using the ODPI-C driver. |
| [firebirdsql](https://github.com/nakagami/firebirdsql) | 162 | 18 | 2013/08/27 | 2 weeks ago | Firebird RDBMS SQL driver for Go. |
| [go-adodb](https://github.com/mattn/go-adodb) | 124 | 12 | 2011/11/14 | 1 year ago | Microsoft ActiveX Object DataBase driver for go that uses database/sql. |
| [gofreetds](https://github.com/minus5/gofreetds) | 105 | 23 | 2012/12/06 | 1 year ago | Microsoft MSSQL driver. Go wrapper over [FreeTDS](https://www.freetds.org). |
| [sqinn-go](https://github.com/cvilsmeier/sqinn-go) | 90 | 2 | 2020/06/06 | 7 months ago | SQLite with pure Go. |
| [calcite-avatica-go](https://github.com/apache/calcite-avatica-go) | 85 | 25 | 2017/08/08 | 1 year ago | Apache Avatica/Phoenix SQL driver for database/sql. |
| [bgc](https://github.com/viant/bgc) | 15 | 11 | 2016/06/13 | 1 year ago | Datastore Connectivity for BigQuery for go. |
| [pig](https://github.com/alexeyco/pig) | 4 | 1 | 2021/04/15 | 8 months ago | Simple [pgx](https://github.com/jackc/pgx) wrapper to execute and [scan](https://github.com/georgysavva/scany) query results easily. |
**[⬆ back to top](#awesome-go-info)**

## Date and Time
        
*Libraries for working with dates and times.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [now](https://github.com/jinzhu/now) | 3515 | 66 | 2013/11/18 | 2 weeks ago | Now is a time toolkit for golang. |
| [dateparse](https://github.com/araddon/dateparse) | 1593 | 22 | 2014/04/21 | 1 month ago | Parse date's without knowing format in advance. |
| [carbon](https://github.com/golang-module/carbon) | 1534 | 13 | 2020/09/07 | 1 month ago | A simple, semantic and developer-friendly golang package for datetime. |
| [carbon](https://github.com/uniplaces/carbon) | 666 | 43 | 2016/08/03 | 1 month ago | Simple Time extension with a lot of util methods, ported from PHP Carbon library. |
| [durafmt](https://github.com/hako/durafmt) | 409 | 6 | 2016/05/20 | 6 months ago | Time duration formatting library for Go. |
| [timeutil](https://github.com/leekchan/timeutil) | 184 | 8 | 2015/08/02 | 2 years ago | Useful extensions (Timedelta, Strftime, ...) to the golang's time package. |
| [gostradamus](https://github.com/bykof/gostradamus) | 159 | 5 | 2020/04/07 | 1 month ago | A Go package for working with dates. |
| [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) | 113 | 5 | 2016/01/31 | 1 month ago | The implementation of the Persian (Solar Hijri) Calendar in Go (golang). |
| [iso8601](https://github.com/relvacode/iso8601) | 96 | 4 | 2017/04/25 | 5 months ago | Efficiently parse ISO8601 date-times without regex. |
| [date](https://github.com/rickb777/date) | 84 | 3 | 2015/11/23 | 1 week ago | Augments Time for working with dates, date ranges, time spans, periods, and time-of-day. |
| [timespan](https://github.com/SaidinWoT/timespan) | 75 | 6 | 2014/10/07 | 2 years ago | For interacting with intervals of time, defined as a start time and a duration. |
| [feiertage](https://github.com/wlbr/feiertage) | 40 | 3 | 2015/11/04 | 4 months ago | Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving... |
| [go-sunrise](https://github.com/nathan-osman/go-sunrise) | 39 | 5 | 2017/06/15 | 6 months ago | Calculate the sunrise and sunset times for a given location. |
| [go-str2duration](https://github.com/xhit/go-str2duration) | 34 | 3 | 2020/02/02 | 1 year ago | Convert string to duration. Support time.Duration returned string and more. |
| [kair](https://github.com/GuilhermeCaruso/kair) | 21 | 2 | 2018/10/03 | 1 year ago | Date and Time - Golang Formatting Library. |
| [cronrange](https://github.com/1set/cronrange) | 13 | 2 | 2019/11/10 | 4 months ago | Parses Cron-style time range expressions, checks if the given time is within any ranges. |
| [nulltime](https://github.com/kirillDanshin/nulltime) | 11 | 2 | 2016/03/06 | 4 years ago | Nullable `time.Time`. |
| [tuesday](https://github.com/osteele/tuesday) | 9 | 3 | 2017/08/10 | 6 months ago | Ruby-compatible Strftime function. |
| [go-week](https://github.com/stoewer/go-week) | 7 | 5 | 2018/02/23 | 1 month ago | An efficient package to work with ISO8601 week dates. |
| [strftime](https://github.com/awoodbeck/strftime) | 7 | 2 | 2018/02/10 | 3 years ago | C99-compatible strftime formatter. |
**[⬆ back to top](#awesome-go-info)**

## Distributed Systems
        
*Packages that help with building Distributed Systems.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [kit](https://github.com/go-kit/kit) | 21995 | 691 | 2015/02/03 | 1 month ago | Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc. |
| [go-micro](https://github.com/asim/go-micro) | 17402 | 506 | 2015/01/13 | 7 hours ago | A distributed systems development framework. |
| [kratos](https://github.com/go-kratos/kratos) | 15976 | 412 | 2019/01/10 | 2 hours ago | A modular-designed and easy-to-use microservices framework in Go. |
| [grpc-go](https://github.com/grpc/grpc-go) | 15107 | 479 | 2014/12/08 | 5 hours ago | The Go language implementation of gRPC. HTTP/2 based RPC. |
| [go-zero](https://github.com/zeromicro/go-zero) | 13513 | 237 | 2020/08/07 | 6 hours ago | A web and rpc framework. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity. |
| [micro](https://github.com/micro/micro) | 10815 | 335 | 2015/01/16 | 9 hours ago | A distributed systems runtime for the cloud and beyond. |
| [nats-server](https://github.com/nats-io/nats-server) | 10267 | 377 | 2012/10/29 | 20 hours ago | Lightweight, high performance messaging system for microservices, IoT, and cloud native systems. |
| [rpcx](https://github.com/smallnest/rpcx) | 6548 | 350 | 2016/05/18 | 10 hours ago | Distributed pluggable RPC service framework like alibaba Dubbo. |
| [raft](https://github.com/hashicorp/raft) | 5503 | 364 | 2013/11/05 | 1 week ago | Golang implementation of the Raft consensus protocol, by HashiCorp. |
| [lura](https://github.com/luraproject/lura) | 4774 | 124 | 2016/11/04 | 6 days ago | Ultra performant API Gateway framework with middlewares. |
| [torrent](https://github.com/anacrolix/torrent) | 4141 | 130 | 2015/01/08 | 15 hours ago | BitTorrent client package. |
| [dragonboat](https://github.com/lni/dragonboat) | 4001 | 144 | 2018/12/23 | 1 month ago | A feature complete and high performance multi-group Raft library in Go. |
| [emitter](https://github.com/emitter-io/emitter) | 3132 | 103 | 2016/10/29 | 2 days ago | High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love. |
| [glow](https://github.com/chrislusf/glow) | 3019 | 144 | 2015/06/14 | 3 years ago | Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go. |
| [gleam](https://github.com/chrislusf/gleam) | 2952 | 148 | 2016/08/26 | 7 months ago | Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed. |
| [liftbridge](https://github.com/liftbridge-io/liftbridge) | 2183 | 67 | 2017/10/13 | 16 hours ago | Lightweight, fault-tolerant message streams for NATS. |
| [hprose-golang](https://github.com/hprose/hprose-golang) | 1190 | 91 | 2014/02/14 | 3 weeks ago | Very newbility RPC Library, support 25+ languages now. |
| [ringpop-go](https://github.com/uber/ringpop-go) | 712 | 2458 | 2015/06/05 | 10 months ago | Scalable, fault-tolerant application-layer sharding for Go applications. |
| [rain](https://github.com/cenkalti/rain) | 660 | 17 | 2014/05/21 | 2 weeks ago | BitTorrent client and library. |
| [gorpc](https://github.com/valyala/gorpc) | 648 | 24 | 2014/11/20 | 2 years ago | Simple, fast and scalable RPC library for high load. |
| [go-health](https://github.com/InVisionApp/go-health) | 612 | 120 | 2017/11/29 | 1 year ago | Library for enabling asynchronous dependency health checks in your service. |
| [redislock](https://github.com/bsm/redislock) | 564 | 9 | 2019/06/24 | 2 months ago | Simplified distributed locking implementation using Redis. |
| [go-sundheit](https://github.com/AppsFlyer/go-sundheit) | 441 | 10 | 2019/04/08 | 4 months ago | A library built to provide support for defining async service health checks for golang services. |
| [arpc](https://github.com/lesismal/arpc) | 439 | 19 | 2020/05/19 | 1 week ago | More effective network communication, support two-way-calling, notify, broadcast. |
| [consistent](https://github.com/buraksezer/consistent) | 437 | 15 | 2018/03/25 | 6 months ago | Consistent hashing with bounded loads. |
| [digota](https://github.com/digota/digota) | 421 | 29 | 2017/08/14 | 10 months ago | grpc ecommerce microservice. |
| [sleuth](https://github.com/ursiform/sleuth) | 339 | 10 | 2016/04/23 | 3 years ago | Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)). |
| [go-jump](https://github.com/dgryski/go-jump) | 334 | 16 | 2014/06/15 | 2 months ago | Port of Google's "Jump" Consistent Hash function. |
| [go-doudou](https://github.com/unionj-cloud/go-doudou) | 223 | 13 | 2021/02/24 | 33 minutes ago | A gossip protocol and OpenAPI 3.0 spec based decentralized microservice framework. Built-in go-doudou cli focusing on low-code and rapid dev can power up your productivity. |
| [dht](https://github.com/anacrolix/dht) | 217 | 11 | 2016/12/14 | 15 hours ago | BitTorrent Kademlia DHT implementation. |
| [jsonrpc](https://github.com/ybbus/jsonrpc) | 197 | 9 | 2016/11/10 | 3 months ago | JSON-RPC 2.0 HTTP client implementation. |
| [jsonrpc](https://github.com/osamingo/jsonrpc) | 156 | 5 | 2016/10/28 | 2 months ago | The jsonrpc package helps implement of JSON-RPC 2.0. |
| [celeriac.v1](https://github.com/svcavallar/celeriac.v1) | 69 | 4 | 2015/10/10 | 1 year ago | Library for adding support for interacting and monitoring Celery workers, tasks and events in Go. |
| [doublejump](https://github.com/edwingeng/doublejump) | 67 | 5 | 2018/06/26 | 5 months ago | A revamped Google's jump consistent hash. |
| [semaphore](https://github.com/jexia/semaphore) | 65 | 14 | 2020/02/05 | 6 months ago | A straightforward (micro) service orchestrator. |
| [outboxer](https://github.com/italolelis/outboxer) | 60 | 0 | 2019/02/01 | 1 day ago | Outboxer is a go library that implements the outbox pattern. |
| [flowgraph](https://github.com/vectaport/flowgraph) | 43 | 1 | 2018/08/29 | 8 months ago | flow-based programming package. |
| [drmaa](https://github.com/dgruber/drmaa) | 36 | 3 | 2013/03/17 | 1 year ago | Job submission library for cluster schedulers based on the DRMAA standard. |
| [go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) | 35 | 1 | 2020/06/06 | 5 months ago | MySQL based distributed lock. |
| [go-pdu](https://github.com/pdupub/go-pdu) | 33 | 5 | 2018/10/08 | 4 days ago | A decentralized identity-based social network. |
| [micro](https://github.com/gmsec/micro) | 14 | 3 | 2020/05/03 | 2 months ago | A Go distributed systems development framework. |
| [dynatomic](https://github.com/tylfin/dynatomic) | 13 | 1 | 2019/02/08 | 1 year ago | A library for using DynamoDB as an atomic counter. |
| [consistenthash](https://github.com/mbrostami/consistenthash) | 9 | 1 | 2020/04/22 | 1 year ago | Consistent hashing with configurable replicas. |
| [failured](https://github.com/andy2046/failured) | 2 | 1 | 2021/07/26 | 4 months ago | adaptive accrual failure detector for distributed systems. |
**[⬆ back to top](#awesome-go-info)**

## Dynamic DNS
        
*Tools for updating dynamic DNS records.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [godns](https://github.com/TimothyYe/godns) | 931 | 33 | 2014/05/11 | 4 weeks ago | A dynamic DNS client tool, supports DNSPod & HE.net, written in Go. |
| [ddns](https://github.com/skibish/ddns) | 200 | 8 | 2017/03/13 | 2 months ago | Personal DDNS client with Digital Ocean Networking DNS as backend. |
**[⬆ back to top](#awesome-go-info)**

## Email
        
*Libraries and tools that implement email creation and sending.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [MailHog](https://github.com/mailhog/MailHog) | 9443 | 145 | 2014/04/16 | 2 weeks ago | Email and SMTP testing with web and API interface. |
| [hermes](https://github.com/matcornic/hermes) | 2388 | 28 | 2017/03/25 | 3 weeks ago | Golang package that generates clean, responsive HTML e-mails. |
| [email](https://github.com/jordan-wright/email) | 1890 | 50 | 2013/12/12 | 1 week ago | A robust and flexible email library for Go. |
| [go-imap](https://github.com/emersion/go-imap) | 1420 | 46 | 2016/04/26 | 6 days ago | IMAP library for clients and servers. |
| [sendgrid-go](https://github.com/sendgrid/sendgrid-go) | 778 | 197 | 2013/09/12 | 1 week ago | SendGrid's Go library for sending email. |
| [mailgun-go](https://github.com/mailgun/mailgun-go) | 572 | 72 | 2014/02/28 | 4 days ago | Go library for sending mail with the Mailgun API. |
| [email-verifier](https://github.com/AfterShip/email-verifier) | 345 | 22 | 2020/12/18 | 4 weeks ago | A Go library for email verification without sending any emails. |
| [go-simple-mail](https://github.com/xhit/go-simple-mail) | 241 | 4 | 2019/09/15 | 6 days ago | Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send. |
| [go-message](https://github.com/emersion/go-message) | 230 | 14 | 2016/12/31 | 1 month ago | Streaming library for the Internet Message Format and mail messages. |
| [hectane](https://github.com/hectane/hectane) | 212 | 14 | 2015/08/28 | 1 year ago | Lightweight SMTP client providing an HTTP API. |
| [douceur](https://github.com/aymerick/douceur) | 204 | 3 | 2015/04/09 | 6 months ago | CSS inliner for your HTML emails. |
| [mailchain](https://github.com/mailchain/mailchain) | 97 | 7 | 2019/04/11 | 1 day ago | Send encrypted emails to blockchain addresses written in Go. |
| [go-premailer](https://github.com/vanng822/go-premailer) | 78 | 2 | 2015/02/16 | 9 months ago | Inline styling for HTML mail in Go. |
| [go-dkim](https://github.com/toorop/go-dkim) | 73 | 4 | 2015/04/29 | 1 year ago | DKIM library, to sign & verify email. |
| [smtp](https://github.com/mailhog/smtp) | 65 | 9 | 2014/12/24 | 2 months ago | SMTP server protocol state machine. |
| [go-smtp-mock](https://github.com/mocktools/go-smtp-mock) | 22 | 2 | 2021/08/31 | 1 week ago | Lightweight configurable multithreaded fake SMTP server. Mimic any SMTP behaviour for your test environment. |
| [go-email-validator](https://github.com/go-email-validator/go-email-validator) | 17 | 4 | 2020/12/10 | 2 weeks ago | Modular email validator for syntax, disposable, smtp, etc... checking. |
**[⬆ back to top](#awesome-go-info)**

## Embeddable Scripting Languages
        
*Embedding other languages inside your go code.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gopher-lua](https://github.com/yuin/gopher-lua) | 4480 | 150 | 2015/02/15 | 6 days ago | Lua 5.1 VM and compiler written in Go. |
| [goja](https://github.com/dop251/goja) | 2588 | 65 | 2016/11/04 | 5 days ago | ECMAScript 5.1(+) implementation in Go. |
| [tengo](https://github.com/d5/tengo) | 2547 | 54 | 2019/01/09 | 2 weeks ago | Bytecode compiled script language for Go. |
| [go-lua](https://github.com/Shopify/go-lua) | 2219 | 368 | 2013/12/20 | 1 month ago | Port of the Lua 5.2 VM to pure Go. |
| [expr](https://github.com/antonmedv/expr) | 2206 | 46 | 2018/07/14 | 1 week ago | Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing. |
| [go-python](https://github.com/sbinet/go-python) | 1335 | 45 | 2012/07/09 | 8 months ago | naive go bindings to the CPython C-API. |
| [anko](https://github.com/mattn/anko) | 1194 | 47 | 2014/03/28 | 3 weeks ago | Scriptable interpreter written in Go. |
| [cel-go](https://github.com/google/cel-go) | 1005 | 30 | 2018/03/09 | 1 week ago | Fast, portable, non-Turing complete expression evaluation with gradual typing. |
| [core](https://github.com/metacall/core) | 837 | 17 | 2018/12/26 | 5 days ago | Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, WebAssembly, Java, Cobol and more. |
| [go-php](https://github.com/deuill/go-php) | 830 | 43 | 2015/09/17 | 1 month ago | PHP bindings for Go. |
| [go-duktape](https://github.com/olebedev/go-duktape) | 778 | 27 | 2015/01/08 | 2 months ago | Duktape JavaScript engine bindings for Go. |
| [golua](https://github.com/aarzilli/golua) | 575 | 35 | 2010/12/06 | 1 month ago | Go bindings for Lua C API. |
| [gisp](https://github.com/jcla1/gisp) | 476 | 22 | 2014/01/11 | 4 years ago | Simple LISP in Go. |
| [gval](https://github.com/PaesslerAG/gval) | 415 | 16 | 2017/09/27 | 3 weeks ago | A highly customizable expression language written in Go. |
| [gentee](https://github.com/gentee/gentee) | 85 | 3 | 2018/01/14 | 2 weeks ago | Embeddable scripting programming language. |
| [binder](https://github.com/alexeyco/binder) | 54 | 2 | 2017/04/02 | 3 years ago | Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua). |
| [purl](https://github.com/ian-kent/purl) | 34 | 3 | 2014/11/29 | 7 years ago | Perl 5.18.2 embedded in Go. |
| [ngaro](https://github.com/db47h/ngaro) | 20 | 2 | 2016/08/09 | 3 years ago | Embeddable Ngaro VM implementation enabling scripting in Retro. |
| [ecal](https://github.com/krotik/ecal) | 16 | 2 | 2020/11/30 | 7 months ago | A simple embeddable scripting language which supports concurrent event processing. |
**[⬆ back to top](#awesome-go-info)**

## Error Handling
        
*Libraries for handling errors.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [errors](https://github.com/pkg/errors) | 7538 | 112 | 2015/12/27 | 1 month ago | Package that provides simple error handling primitives. |
| [go-multierror](https://github.com/hashicorp/go-multierror) | 1460 | 245 | 2014/12/15 | 1 month ago | Go (golang) package for representing a list of errors as a single error. |
| [eris](https://github.com/rotisserie/eris) | 889 | 11 | 2019/09/07 | 5 months ago | A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors. |
| [errorx](https://github.com/joomcode/errorx) | 789 | 78 | 2018/08/17 | 8 months ago | A feature rich error package with stack traces, composition of errors and more. |
| [tracerr](https://github.com/ztrue/tracerr) | 694 | 11 | 2019/02/06 | 2 years ago | Golang errors with stack trace and source fragments. |
| [errlog](https://github.com/snwfdhmp/errlog) | 400 | 5 | 2019/02/16 | 1 year ago | Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place. |
| [emperror](https://github.com/emperror/emperror) | 238 | 4 | 2017/06/13 | 1 year ago | Error handling tools and best practices for Go libraries and applications. |
| [errors](https://github.com/emperror/errors) | 106 | 4 | 2019/07/09 | 9 months ago | Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives. |
| [errors](https://github.com/bnkamalesh/errors) | 25 | 2 | 2020/07/17 | 2 weeks ago | Drop-in replacement for builting Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions. |
| [falcon](https://github.com/SonicRoshan/falcon) | 7 | 2 | 2019/09/09 | 2 years ago | A Simple Yet Highly Powerful Package For Error Handling. |
| [errors](https://github.com/neuronlabs/errors) | 3 | 2 | 2019/07/26 | 2 years ago | Simple golang error handling with classification primitives. |
| [errors](https://github.com/PumpkinSeed/errors) | 3 | 1 | 2020/01/08 | 1 year ago | The most simple error wrapper with awesome performance and minimal memory overhead. |
**[⬆ back to top](#awesome-go-info)**

## File Handling
        
*Libraries for handling files and file systems.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [afero](https://github.com/spf13/afero) | 4128 | 89 | 2014/10/28 | 22 hours ago | FileSystem Abstraction System for Go. |
| [pdfcpu](https://github.com/pdfcpu/pdfcpu) | 2884 | 67 | 2017/06/18 | 5 days ago | PDF processor. |
| [gdu](https://github.com/dundee/gdu) | 1470 | 19 | 2018/02/24 | 2 weeks ago | Disk usage analyzer with console interface. |
| [notify](https://github.com/rjeczalik/notify) | 703 | 30 | 2014/09/08 | 4 months ago | File system event notification library with simple API, similar to os/signal. |
| [copy](https://github.com/otiai10/copy) | 365 | 7 | 2017/09/01 | 5 days ago | Copy directory recursively. |
| [bigfile](https://github.com/bigfile/bigfile) | 212 | 16 | 2019/07/15 | 1 year ago | A file transfer system, support to manage files with http api, rpc call and ftp client. |
| [afs](https://github.com/viant/afs) | 169 | 12 | 2019/08/19 | 2 months ago | Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go. |
| [vfs](https://github.com/C2FO/vfs) | 144 | 23 | 2017/08/01 | 23 hours ago | A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS. |
| [go-csv-tag](https://github.com/artonge/go-csv-tag) | 95 | 0 | 2017/06/18 | 1 month ago | Load csv file using tag. |
| [go-exiftool](https://github.com/barasher/go-exiftool) | 93 | 4 | 2019/05/12 | 4 months ago | Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...). |
| [opc](https://github.com/qmuntal/opc) | 68 | 3 | 2018/11/06 | 10 months ago | Load Open Packaging Conventions (OPC) files for Go. |
| [skywalker](https://github.com/dixonwille/skywalker) | 66 | 4 | 2017/08/01 | 3 months ago | Package to allow one to concurrently go through a filesystem with ease. |
| [checksum](https://github.com/codingsince1985/checksum) | 49 | 3 | 2014/11/05 | 4 weeks ago | Compute message digest, like MD5, SHA256, SHA1, CRC or BLAKE2s, for large files. |
| [tarfs](https://github.com/posener/tarfs) | 48 | 2 | 2017/03/10 | 1 year ago | Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files. |
| [parquet](https://github.com/parsyl/parquet) | 42 | 7 | 2019/01/29 | 2 months ago | Read and write [parquet](https://parquet.apache.org) files. |
| [baraka](https://github.com/xis/baraka) | 35 | 2 | 2020/07/12 | 4 months ago | A library to process http file uploads easily. |
| [go-gtfs](https://github.com/artonge/go-gtfs) | 30 | 2 | 2017/07/09 | 1 year ago | Load gtfs files in go. |
| [flop](https://github.com/homedepot/flop) | 29 | 18 | 2019/03/01 | 3 weeks ago | File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html). |
| [gut](https://github.com/1set/gut) | 19 | 3 | 2019/10/05 | 1 year ago | Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links. |
| [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) | 14 | 3 | 2018/10/16 | 2 years ago | Copy files for humans. |
| [todotxt](https://github.com/1set/todotxt) | 10 | 3 | 2020/11/06 | 6 days ago | Go library for Gina Trapani's [*todo.txt*](http://todotxt.org/) files, supports parsing and manipulating of task lists in the [*todo.txt* format](https://github.com/todotxt/todo.txt). |
| [higgs](https://github.com/dastoori/higgs) | 6 | 1 | 2020/12/13 | 8 months ago | A tiny cross-platform Go library to hide/unhide files and directories. |
| [pathtype](https://github.com/jonchun/pathtype) | 6 | 1 | 2021/08/03 | 4 months ago | Treat paths as their own type instead of using strings. |
**[⬆ back to top](#awesome-go-info)**

## Financial
        
*Packages for accounting and finance.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [ticker](https://github.com/achannarasappa/ticker) | 4001 | 63 | 2021/01/24 | 1 week ago | Terminal stock watcher and stock position tracker. |
| [decimal](https://github.com/shopspring/decimal) | 3607 | 63 | 2015/02/25 | 2 weeks ago | Arbitrary-precision fixed-point decimal numbers. |
| [go-money](https://github.com/Rhymond/go-money) | 1033 | 14 | 2017/03/20 | 4 weeks ago | Implementation of Fowler's Money pattern. |
| [accounting](https://github.com/leekchan/accounting) | 693 | 14 | 2015/08/10 | 2 months ago | money and currency formatting for golang. |
| [techan](https://github.com/sdcoffey/techan) | 574 | 47 | 2017/03/08 | 1 month ago | Technical analysis library with advanced market analysis and trading strategies. |
| [go-finance](https://github.com/FlashBoys/go-finance) | 536 | 27 | 2016/02/28 | 3 years ago | Comprehensive financial markets data in Go. |
| [ach](https://github.com/moov-io/ach) | 273 | 19 | 2016/12/14 | 5 days ago | A reader, writer, and valdiator for Automated Clearing House (ACH) files. |
| [currency](https://github.com/bojanz/currency) | 268 | 6 | 2020/04/16 | 1 month ago | Handles currency amounts, provides currency information and formatting. |
| [orderbook](https://github.com/i25959341/orderbook) | 235 | 20 | 2018/04/24 | 7 months ago | Matching Engine for Limit Order Book in Golang. |
| [go-finance](https://github.com/alpeb/go-finance) | 119 | 8 | 2017/06/01 | 3 weeks ago | Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations. |
| [transaction](https://github.com/claygod/transaction) | 99 | 9 | 2017/10/11 | 5 months ago | Embedded transactional database of accounts, running in multithreaded mode. |
| [ofxgo](https://github.com/aclindsa/ofxgo) | 94 | 10 | 2015/11/08 | 2 months ago | Query OFX servers and/or parse the responses (with example command-line client). |
| [vat](https://github.com/dannyvankooten/vat) | 85 | 3 | 2016/06/18 | 10 months ago | VAT number validation & EU VAT rates. |
| [sleet](https://github.com/BoltApp/sleet) | 78 | 50 | 2019/11/13 | 1 week ago | One unified interface for multiple Payment Service Providers (PsP) to process online payment. |
| [go-finnhub](https://github.com/m1/go-finnhub) | 63 | 6 | 2020/01/13 | 1 year ago | Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges. |
| [currency](https://github.com/bnkamalesh/currency) | 44 | 6 | 2017/05/09 | 1 month ago | High performant & accurate currency computation package. |
| [fastme](https://github.com/newity/fastme) | 26 | 4 | 2020/10/29 | 3 months ago | Fast extensible matching engine Go implementation. |
| [payme](https://github.com/jovandeginste/payme) | 8 | 1 | 2021/05/03 | 3 weeks ago | QR code generator (ASCII & PNG) for SEPA payments. |
| [go-finance](https://github.com/pieterclaerhout/go-finance) | 5 | 2 | 2019/09/30 | 2 years ago | Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers. |
**[⬆ back to top](#awesome-go-info)**

## Forms
        
*Libraries for working with forms.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [nosurf](https://github.com/justinas/nosurf) | 1232 | 35 | 2013/08/22 | 1 year ago | CSRF protection middleware for Go. |
| [binding](https://github.com/mholt/binding) | 783 | 32 | 2014/05/20 | 3 years ago | Binds form and JSON data from net/http Request to struct. |
| [csrf](https://github.com/gorilla/csrf) | 729 | 23 | 2015/08/03 | 2 months ago | CSRF protection for Go web applications & services. |
| [form](https://github.com/go-playground/form) | 507 | 13 | 2016/05/26 | 5 months ago | Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. |
| [conform](https://github.com/leebenson/conform) | 241 | 5 | 2016/01/05 | 2 months ago | Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags. |
| [formam](https://github.com/monoculum/formam) | 163 | 5 | 2014/10/25 | 2 months ago | decode form's values into a struct. |
| [forms](https://github.com/albrow/forms) | 128 | 8 | 2014/08/07 | 4 years ago | Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. |
| [qs](https://github.com/sonh/qs) | 60 | 3 | 2020/10/02 | 6 months ago | Go module for encoding structs into URL query parameters. |
| [bind](https://github.com/robfig/bind) | 26 | 4 | 2014/08/06 | 7 years ago | Bind form data to any Go values. |
| [queryparam](https://github.com/TomWright/queryparam) | 10 | 2 | 2018/06/14 | 1 year ago | Decode `url.Values` into usable struct values of standard or custom types. |
**[⬆ back to top](#awesome-go-info)**

## Functional
        
*Packages to support functional programming in Go.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-underscore](https://github.com/tobyhede/go-underscore) | 1222 | 30 | 2014/07/02 | 2 years ago | Useful collection of helpfully functional Go collection utilities. |
| [fpGo](https://github.com/TeaEntityLab/fpGo) | 214 | 7 | 2018/05/24 | 10 hours ago | Monad, Functional Programming features for Golang. |
| [fuego](https://github.com/seborama/fuego) | 101 | 3 | 2018/11/05 | 1 year ago | Functional Experiment in Go. |
| [gofp](https://github.com/rbrahul/gofp) | 100 | 3 | 2021/02/19 | 10 months ago | A lodash like powerful utility library for Golang. |
**[⬆ back to top](#awesome-go-info)**

## GUI
        
*Interaction*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fyne](https://github.com/fyne-io/fyne) | 15241 | 227 | 2018/02/04 | 2 days ago | Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android. |
| [webview](https://github.com/webview/webview) | 9258 | 225 | 2017/08/19 | 57 minutes ago | Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). |
| [qt](https://github.com/therecipe/qt) | 8978 | 318 | 2014/11/19 | 11 months ago | Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi). |
| [ui](https://github.com/andlabs/ui) | 8039 | 371 | 2014/02/17 | 5 months ago | Platform-native GUI library for Go. Cross platform. |
| [robotgo](https://github.com/go-vgo/robotgo) | 7112 | 234 | 2016/09/26 | 3 days ago | Go Native cross-platform GUI system automation. Control the mouse, keyboard and other. |
| [walk](https://github.com/lxn/walk) | 5833 | 262 | 2010/09/16 | 5 months ago | Windows application library kit for Go. |
| [go-app](https://github.com/maxence-charriere/go-app) | 5684 | 151 | 2016/10/12 | 1 day ago | Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. |
| [go-astilectron](https://github.com/asticode/go-astilectron) | 4159 | 135 | 2017/04/22 | 2 weeks ago | Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron). |
| [go-sciter](https://github.com/sciter-sdk/go-sciter) | 2288 | 129 | 2015/10/15 | 1 month ago | Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform. |
| [systray](https://github.com/getlantern/systray) | 2077 | 63 | 2014/11/12 | 8 months ago | Cross platform Go library to place an icon and menu in the notification area. |
| [gotk3](https://github.com/gotk3/gotk3) | 1666 | 65 | 2015/08/13 | 20 hours ago | Go bindings for GTK3. |
| [gosx-notifier](https://github.com/deckarep/gosx-notifier) | 553 | 16 | 2013/11/25 | 1 year ago | OSX Desktop Notifications library for Go. |
| [gowd](https://github.com/dtylman/gowd) | 337 | 26 | 2017/03/29 | 2 years ago | Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform. |
| [trayhost](https://github.com/shurcooL/trayhost) | 220 | 7 | 2014/04/25 | 2 years ago | Cross-platform Go library to place an icon in the host operating system's taskbar. |
| [zenity](https://github.com/ncruces/zenity) | 204 | 6 | 2019/12/10 | 2 months ago | Cross-platform Go library and CLI to create simple dialogs that interact graphically with the user. |
| [go-appindicator](https://github.com/dawidd6/go-appindicator) | 17 | 5 | 2019/05/04 | 11 months ago | Go bindings for libappindicator3 C library. |
| [activity-tracker](https://github.com/prashantgupta24/activity-tracker) | 13 | 3 | 2019/03/12 | 2 years ago | OSX library to notify about any (pluggable) activity on your machine. |
| [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) | 10 | 4 | 2019/03/30 | 2 years ago | OSX Sleep/Wake notifications in golang. |
**[⬆ back to top](#awesome-go-info)**

## Game Development
        
*Awesome game development libraries.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [ebiten](https://github.com/hajimehoshi/ebiten) | 5623 | 122 | 2013/06/16 | 1 day ago | dead simple 2D game library in Go. |
| [leaf](https://github.com/name5566/leaf) | 4254 | 320 | 2014/08/04 | 5 months ago | Lightweight game server framework. |
| [pixel](https://github.com/faiface/pixel) | 3767 | 101 | 2016/11/19 | 2 months ago | Hand-crafted 2D game library in Go. |
| [goworld](https://github.com/xiaonanln/goworld) | 2017 | 131 | 2017/06/03 | 6 months ago | Scalable game server engine, featuring space-entity framework and hot-swapping. |
| [nano](https://github.com/lonng/nano) | 1895 | 67 | 2017/08/02 | 5 months ago | Lightweight, facility, high performance golang based game server framework. |
| [engine](https://github.com/g3n/engine) | 1773 | 79 | 2017/03/07 | 3 hours ago | Go 3D Game Engine. |
| [go-sdl2](https://github.com/veandco/go-sdl2) | 1671 | 44 | 2013/06/05 | 1 month ago | Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/). |
| [engo](https://github.com/EngoEngine/engo) | 1461 | 48 | 2014/11/12 | 3 weeks ago | Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm. |
| [pitaya](https://github.com/topfreegames/pitaya) | 1277 | 72 | 2018/03/19 | 1 month ago | Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. |
| [termloop](https://github.com/JoelOtter/termloop) | 1252 | 31 | 2015/05/23 | 4 months ago | Terminal-based game engine for Go, built on top of Termbox. |
| [gonet](https://github.com/xtaci/gonet) | 1165 | 135 | 2013/04/11 | 4 years ago | Game server skeleton implemented with golang. |
| [oak](https://github.com/oakmound/oak) | 982 | 44 | 2017/07/15 | 1 week ago | Pure Go game engine. |
| [raylib-go](https://github.com/gen2brain/raylib-go) | 705 | 18 | 2017/01/27 | 1 month ago | Go bindings for [raylib](https://www.raylib.com/), a simple and easy-to-use library to learn videogames programming. |
| [engine](https://github.com/azul3d/engine) | 521 | 25 | 2016/02/29 | 2 months ago | 3D game engine written in Go. |
| [go-astar](https://github.com/beefsack/go-astar) | 467 | 10 | 2014/05/28 | 1 year ago | Go implementation of the A\* path finding algorithm. |
| [go3d](https://github.com/ungerik/go3d) | 217 | 9 | 2011/06/27 | 2 months ago | Performance oriented 2D/3D math package for Go. |
| [prototype](https://github.com/gonutz/prototype) | 66 | 3 | 2015/03/04 | 2 weeks ago | Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API. |
| [tile](https://github.com/kelindar/tile) | 38 | 1 | 2020/08/19 | 2 weeks ago | Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export. |
**[⬆ back to top](#awesome-go-info)**

## Generation and Generics
        
*Tools to enhance the language with features like generics via code generation.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-linq](https://github.com/ahmetb/go-linq) | 2805 | 73 | 2013/12/19 | 1 month ago | .NET LINQ-like query methods for Go. |
| [jennifer](https://github.com/dave/jennifer) | 2264 | 31 | 2016/12/04 | 1 week ago | Generate arbitrary Go code without templates. |
| [gen](https://github.com/clipperhouse/gen) | 1343 | 33 | 2013/10/13 | 1 year ago | Code generation tool for ‘generics’-like functionality. |
| [goderive](https://github.com/awalterschulze/goderive) | 945 | 18 | 2017/02/10 | 1 week ago | Derives functions from input types. |
| [gowrap](https://github.com/hexdigest/gowrap) | 555 | 12 | 2018/09/15 | 2 months ago | Generate decorators for Go interfaces using simple templates. |
| [interfaces](https://github.com/rjeczalik/interfaces) | 320 | 7 | 2015/12/06 | 8 months ago | Command line tool for generating interface definitions. |
| [go-enum](https://github.com/abice/go-enum) | 259 | 4 | 2017/08/10 | 3 weeks ago | Code generation for enums from code comments. |
| [pkgreflect](https://github.com/ungerik/pkgreflect) | 99 | 6 | 2012/09/03 | 4 years ago | Go preprocessor for package scoped reflection. |
| [goverter](https://github.com/jmattheis/goverter) | 93 | 2 | 2021/03/09 | 1 month ago | Generate converters by defining an interface. |
| [efaceconv](https://github.com/t0pep0/efaceconv) | 51 | 5 | 2016/11/18 | 4 years ago | Code generation tool for high performance conversion from interface{} to immutable type without allocations. |
| [gotype](https://github.com/wzshiming/gotype) | 36 | 4 | 2017/12/05 | 4 months ago | Golang source code parsing, usage like reflect package. |
| [GENERIS](https://github.com/senselogic/GENERIS) | 30 | 1 | 2019/03/10 | 4 months ago | Code generation tool providing generics, free-form macros, conditional compilation and HTML templating. |
| [go-xray](https://github.com/pieterclaerhout/go-xray) | 21 | 4 | 2019/10/01 | 2 years ago | Helpers for making the use of reflection easier. |
| [typeregistry](https://github.com/xiaoxin01/typeregistry) | 12 | 1 | 2020/01/14 | 1 year ago | A library to create type dynamically. |
**[⬆ back to top](#awesome-go-info)**

## Geographic
        
*Geographic tools and servers*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [tile38](https://github.com/tidwall/tile38) | 7889 | 207 | 2016/03/04 | 6 hours ago | Geolocation DB with spatial index and realtime geofencing. |
| [geo](https://github.com/golang/geo) | 1304 | 77 | 2014/12/03 | 1 month ago | S2 geometry library in Go. |
| [mbtileserver](https://github.com/consbio/mbtileserver) | 293 | 14 | 2014/11/01 | 11 hours ago | A simple Go-based server for map tiles stored in mbtiles format. |
| [osm](https://github.com/paulmach/osm) | 184 | 12 | 2016/02/02 | 3 months ago | Library for reading, writing and working with OpenStreetMap data and APIs. |
| [geoserver](https://github.com/hishamkaram/geoserver) | 66 | 2 | 2018/03/26 | 1 month ago | geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API. |
| [wgs84](https://github.com/wroge/wgs84) | 66 | 1 | 2019/06/08 | 2 weeks ago | Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM). |
| [godal](https://github.com/airbusgeo/godal) | 59 | 4 | 2021/02/05 | 2 days ago | Go wrapper for GDAL. |
| [gismanager](https://github.com/hishamkaram/gismanager) | 40 | 0 | 2018/09/29 | 3 years ago | Publish Your GIS Data(Vector Data) to PostGIS and Geoserver. |
| [simplefeatures](https://github.com/peterstace/simplefeatures) | 38 | 4 | 2019/06/07 | 2 weeks ago | simplesfeatures is a 2D geometry library that provides Go types that model geometries, as well as algorithms that operate on them. |
| [pbf](https://github.com/maguro/pbf) | 30 | 4 | 2017/09/18 | 8 months ago | OpenStreetMap PBF golang encoder/decoder. |
| [s2-geojson](https://github.com/pantrif/s2-geojson) | 15 | 1 | 2020/03/27 | 1 year ago | Convert geojson to s2 cells & demonstrating some S2 geometry features on map. |
**[⬆ back to top](#awesome-go-info)**

## Go Compilers
        
*Tools for compiling Go to other languages.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gopherjs](https://github.com/gopherjs/gopherjs) | 10747 | 249 | 2013/08/27 | 1 hour ago | Compiler from Go to JavaScript. |
| [tardisgo](https://github.com/tardisgo/tardisgo) | 414 | 30 | 2014/01/08 | 5 years ago | Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler. |
| [c4go](https://github.com/Konstantin8105/c4go) | 294 | 18 | 2018/03/28 | 1 month ago | Transpile C code to Go code. |
| [esp32-transpiler](https://github.com/andygeiss/esp32-transpiler) | 34 | 3 | 2018/03/14 | 5 months ago | Transpile Go into Arduino code. |
| [f4go](https://github.com/Konstantin8105/f4go) | 31 | 5 | 2018/07/08 | 4 weeks ago | Transpile FORTRAN 77 code to Go code. |
**[⬆ back to top](#awesome-go-info)**

## Goroutines
        
*Tools for managing and working with Goroutines.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [ants](https://github.com/panjf2000/ants) | 7279 | 157 | 2018/05/19 | 3 weeks ago | A high-performance and low-cost goroutine pool in Go. |
| [tunny](https://github.com/Jeffail/tunny) | 2777 | 74 | 2014/04/02 | 5 months ago | Goroutine pool for golang. |
| [goworker](https://github.com/benmanns/goworker) | 2625 | 73 | 2013/07/22 | 2 weeks ago | goworker is a Go-based background worker. |
| [workerpool](https://github.com/gammazero/workerpool) | 708 | 17 | 2016/05/17 | 2 months ago | Goroutine pool that limits the concurrency of task execution, not the number of tasks queued. |
| [grpool](https://github.com/ivpusic/grpool) | 667 | 29 | 2015/07/22 | 2 years ago | Lightweight Goroutine pool. |
| [pool](https://github.com/go-playground/pool) | 665 | 14 | 2015/10/28 | 6 months ago | Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation. |
| [pond](https://github.com/alitto/pond) | 399 | 10 | 2020/03/21 | 2 days ago | Minimalistic and High-performance goroutine worker pool written in Go. |
| [gowp](https://github.com/xxjwxc/gowp) | 349 | 18 | 2019/09/14 | 7 months ago | gowp is concurrency limiting goroutine pool. |
| [go-floc](https://github.com/workanator/go-floc) | 218 | 7 | 2017/07/03 | 4 months ago | Orchestrate goroutines with ease. |
| [go-flow](https://github.com/kamildrazkiewicz/go-flow) | 180 | 11 | 2016/09/25 | 2 years ago | Control goroutines execution order. |
| [semaphore](https://github.com/marusama/semaphore) | 133 | 2 | 2017/11/22 | 9 months ago | Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations). |
| [go-workers](https://github.com/catmullet/go-workers) | 126 | 4 | 2020/10/06 | 3 months ago | Easily and safely run workers for large data processing pipelines. |
| [artifex](https://github.com/mborders/artifex) | 122 | 7 | 2018/10/31 | 1 year ago | Simple in-memory job queue for Golang using worker-based dispatching. |
| [errgroup](https://github.com/neilotoole/errgroup) | 104 | 3 | 2020/06/26 | 3 months ago | Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines. |
| [async](https://github.com/StudioSol/async) | 96 | 13 | 2017/06/30 | 1 year ago | A safe way to execute functions asynchronously, recovering them in case of panic. |
| [cyclicbarrier](https://github.com/marusama/cyclicbarrier) | 89 | 2 | 2018/01/11 | 1 year ago | CyclicBarrier for golang. |
| [semaphore](https://github.com/kamilsk/semaphore) | 89 | 1 | 2016/10/08 | 1 year ago | Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context. |
| [gpool](https://github.com/sherifabdlnaby/gpool) | 82 | 1 | 2018/12/03 | 2 years ago | manages a resizeable pool of context-aware goroutines to bound concurrency. |
| [worker-pool](https://github.com/vardius/worker-pool) | 80 | 5 | 2017/10/04 | 11 months ago | goworker is a Go simple async worker pool. |
| [gollback](https://github.com/vardius/gollback) | 72 | 1 | 2019/05/11 | 4 weeks ago | asynchronous simple function utilities, for managing execution of closures and callbacks. |
| [Hunch](https://github.com/AaronJan/Hunch) | 70 | 1 | 2019/06/05 | 1 year ago | Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive. |
| [threadpool](https://github.com/shettyh/threadpool) | 62 | 2 | 2017/09/06 | 1 year ago | Golang threadpool implementation. |
| [routine](https://github.com/x-mod/routine) | 45 | 3 | 2019/03/04 | 1 year ago | go routine control with context, support: Main, Go, Pool and some useful Executors. |
| [goccm](https://github.com/zenthangplus/goccm) | 38 | 1 | 2019/08/16 | 2 months ago | Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently. |
| [nursery](https://github.com/arunsworld/nursery) | 38 | 4 | 2019/11/23 | 5 months ago | Structured concurrency in Go. |
| [kyoo](https://github.com/dirkaholic/kyoo) | 36 | 2 | 2020/01/06 | 1 year ago | Provides an unlimited job queue and concurrent worker pools. |
| [async](https://github.com/reugn/async) | 34 | 2 | 2019/12/28 | 1 month ago | An alternative sync library for Go (Future, Promise, Locks). |
| [parallel-fn](https://github.com/rafaeljesus/parallel-fn) | 31 | 3 | 2017/06/18 | 4 years ago | Run functions in parallel. |
| [gohive](https://github.com/loveleshsharma/gohive) | 28 | 3 | 2019/05/31 | 1 month ago | A highly performant and easy to use Goroutine pool for Go. |
| [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) | 23 | 2 | 2018/08/08 | 1 year ago | Like `sync.WaitGroup` with error handling and concurrency control. |
| [go-trylock](https://github.com/subchen/go-trylock) | 22 | 1 | 2018/04/26 | 7 months ago | TryLock support on read-write lock for Golang. |
| [stl](https://github.com/ssgreg/stl) | 20 | 2 | 2018/06/19 | 1 year ago | Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism. |
| [channelify](https://github.com/ddelizia/channelify) | 15 | 1 | 2020/10/05 | 10 months ago | Transform your function to return channels for easy and powerful parallel processing. |
| [gowl](https://github.com/hamed-yousefi/gowl) | 12 | 1 | 2021/04/12 | 5 months ago | Gowl is a process management and process monitoring tool at once. An infinite worker pool gives you the ability to control the pool and processes and monitor their status. |
| [conexec](https://github.com/ITcathyh/conexec) | 11 | 2 | 2019/12/24 | 1 year ago | A concurrent toolkit to help execute funcs concurrently in an efficient and safe way. It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency. |
| [queue](https://github.com/AnikHasibul/queue) | 10 | 0 | 2018/12/21 | 2 years ago | Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more. |
| [execpool](https://github.com/hexdigest/execpool) | 7 | 1 | 2021/06/17 | 5 months ago | A pool built around exec.Cmd that spins up a given number of processes in advance and attaches stdin and stdout to them when needed. Very similar to FastCGI or Apache Prefork MPM but works for any command. |
| [hands](https://github.com/duanckham/hands) | 7 | 1 | 2020/04/04 | 1 year ago | A process controller used to control the execution and return strategies of multiple goroutines. |
| [concurrency-limiter](https://github.com/vivek-ng/concurrency-limiter) | 5 | 1 | 2020/11/22 | 1 year ago | Concurrency limiter with support for timeouts , dynamic priority and context cancellation of goroutines. |
| [go-tools](https://github.com/nikhilsaraf/go-tools) | 5 | 2 | 2018/11/14 | 2 years ago | Manage a pool of goroutines using this lightweight library with a simple API. |
| [breaker](https://github.com/kamilsk/breaker) | 2 | 0 | 2021/07/11 | 5 months ago | Flexible mechanism to make execution flow interruptible. |
**[⬆ back to top](#awesome-go-info)**

## Hardware
        
*Libraries, tools, and tutorials for interacting with hardware.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [arduino-cli](https://github.com/arduino/arduino-cli) | 3182 | 106 | 2018/08/08 | 1 hour ago | Official Arduino CLI and library. Can run standalone, or be incorporated into larger Go projects. |
| [go-rpio](https://github.com/stianeikeland/go-rpio) | 1773 | 59 | 2013/07/30 | 3 weeks ago | GPIO for Go, doesn't require cgo. |
| [ghw](https://github.com/jaypipes/ghw) | 1087 | 25 | 2017/05/26 | 2 weeks ago | Golang hardware discovery/inspection library. |
| [emgo](https://github.com/ziutek/emgo) | 950 | 35 | 2014/07/09 | 3 weeks ago | Go-like language for programming embedded systems (e.g. STM32 MCU). |
| [sysinfo](https://github.com/zcalusic/sysinfo) | 304 | 14 | 2016/08/22 | 2 months ago | A pure Go library providing Linux OS / kernel / hardware system information. |
| [goroslib](https://github.com/aler9/goroslib) | 149 | 11 | 2020/01/19 | 6 days ago | Robot Operating System (ROS) library for Go. |
| [go-osc](https://github.com/hypebeast/go-osc) | 139 | 8 | 2013/08/26 | 4 months ago | Open Sound Control (OSC) bindings for Go. |
| [joystick](https://github.com/0xcafed00d/joystick) | 29 | 2 | 2015/07/24 | 1 year ago | a polled API to read the state of an attached joystick. |
**[⬆ back to top](#awesome-go-info)**

## Images
        
*Libraries for manipulating images.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gocv](https://github.com/hybridgroup/gocv) | 4529 | 137 | 2017/09/18 | 6 days ago | Go package for computer vision using OpenCV 3.3+. |
| [imaginary](https://github.com/h2non/imaginary) | 4125 | 77 | 2015/03/04 | 2 weeks ago | Fast and simple HTTP microservice for image resizing. |
| [imaging](https://github.com/disintegration/imaging) | 4041 | 78 | 2012/12/06 | 1 year ago | Simple Go image processing package. |
| [bild](https://github.com/anthonynsimon/bild) | 3437 | 72 | 2016/08/01 | 1 week ago | Collection of image processing algorithms in pure Go. |
| [gg](https://github.com/fogleman/gg) | 3186 | 91 | 2016/02/18 | 1 month ago | 2D rendering in pure Go. |
| [ln](https://github.com/fogleman/ln) | 3010 | 93 | 2016/01/10 | 2 years ago | 3D line art rendering in Go. |
| [resize](https://github.com/nfnt/resize) | 2769 | 80 | 2012/08/02 | 1 year ago | Image resizing for Go with common interpolation methods. |
| [pt](https://github.com/fogleman/pt) | 1984 | 58 | 2015/01/23 | 2 years ago | Path tracing engine written in Go. |
| [svgo](https://github.com/ajstarks/svgo) | 1783 | 49 | 2010/03/05 | 2 months ago | Go Language Library for SVG generation. |
| [bimg](https://github.com/h2non/bimg) | 1742 | 38 | 2015/03/17 | 1 week ago | Small package for fast and efficient image processing using libvips. |
| [picfit](https://github.com/thoas/picfit) | 1592 | 53 | 2014/12/06 | 3 months ago | An image resizing server written in Go. |
| [smartcrop](https://github.com/muesli/smartcrop) | 1569 | 33 | 2014/04/07 | 7 months ago | Finds good crops for arbitrary images and crop sizes. |
| [gift](https://github.com/disintegration/gift) | 1476 | 49 | 2014/07/12 | 1 year ago | Package of image processing filters. |
| [imagick](https://github.com/gographics/imagick) | 1381 | 54 | 2013/04/30 | 3 months ago | Go binding to ImageMagick's MagickWand C API. |
| [gowitness](https://github.com/sensepost/gowitness) | 1323 | 36 | 2017/10/31 | 3 months ago | Screenshoting webpages using go and headless chrome on command line. |
| [go-opencv](https://github.com/go-opencv/go-opencv) | 1256 | 63 | 2013/12/09 | 2 years ago | Go bindings for OpenCV. |
| [geopattern](https://github.com/pravj/geopattern) | 1154 | 22 | 2014/10/22 | 3 years ago | Create beautiful generative image patterns from a string. |
| [stegify](https://github.com/DimitarPetrov/stegify) | 972 | 22 | 2018/11/29 | 1 year ago | Go tool for LSB steganography, capable of hiding any file within an image. |
| [canvas](https://github.com/tdewolff/canvas) | 861 | 19 | 2017/05/20 | 1 day ago | Vector graphics to PDF, SVG or rasterized image. |
| [image2ascii](https://github.com/qeesung/image2ascii) | 615 | 9 | 2018/10/20 | 5 months ago | Convert image to ASCII. |
| [govips](https://github.com/davidbyttow/govips) | 597 | 13 | 2016/12/25 | 1 day ago | A lightning fast image processing and resizing library for Go. |
| [draft](https://github.com/lucasepe/draft) | 517 | 11 | 2020/06/05 | 3 months ago | Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax. |
| [govatar](https://github.com/o1egl/govatar) | 474 | 10 | 2016/01/18 | 9 months ago | Library and CMD tool for generating funny avatars. |
| [goimagehash](https://github.com/corona10/goimagehash) | 454 | 11 | 2017/07/28 | 10 months ago | Go Perceptual image hashing package. |
| [mort](https://github.com/aldor007/mort) | 443 | 18 | 2017/11/19 | 1 month ago | Storage and image processing server written in Go. |
| [go-nude](https://github.com/koyachi/go-nude) | 338 | 16 | 2014/05/02 | 3 years ago | Nudity detection with Go. |
| [rez](https://github.com/bamiaux/rez) | 203 | 9 | 2014/01/16 | 4 years ago | Image resizing in pure Go and SIMD. |
| [darkroom](https://github.com/gojek/darkroom) | 178 | 9 | 2019/07/01 | 6 months ago | An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency. |
| [mergi](https://github.com/noelyahan/mergi) | 159 | 8 | 2018/09/24 | 1 year ago | Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate). |
| [gltf](https://github.com/qmuntal/gltf) | 141 | 5 | 2019/01/15 | 2 months ago | Efficient and robust glTF 2.0 reader, writer and validator. |
| [img](https://github.com/hawx/img) | 137 | 5 | 2012/07/28 | 6 years ago | Selection of image manipulation tools. |
| [steganography](https://github.com/auyer/steganography) | 122 | 6 | 2018/05/21 | 5 months ago | Pure Go Library for LSB steganography. |
| [go-cairo](https://github.com/ungerik/go-cairo) | 116 | 5 | 2012/08/22 | 9 months ago | Go binding for the cairo graphics library. |
| [cameron](https://github.com/aofei/cameron) | 80 | 4 | 2018/05/05 | 1 month ago | An avatar generator for Go. |
| [go-gd](https://github.com/bolknote/go-gd) | 52 | 4 | 2011/05/12 | 3 years ago | Go binding for GD library. |
| [gridder](https://github.com/shomali11/gridder) | 49 | 4 | 2020/04/10 | 2 months ago | A Grid based 2D Graphics library. |
| [go-webp](https://github.com/kolesa-team/go-webp) | 41 | 5 | 2020/02/18 | 3 months ago | Library for encode and decode webp pictures, using libwebp. |
| [goimghdr](https://github.com/corona10/goimghdr) | 37 | 1 | 2018/02/25 | 2 years ago | The imghdr module determines the type of image contained in a file for Go. |
| [webp-server](https://github.com/mehdipourfar/webp-server) | 30 | 1 | 2020/11/22 | 11 months ago | Simple and minimal image server capable of storing, resizing, converting and caching images. |
| [tga](https://github.com/ftrvxmtrx/tga) | 28 | 3 | 2012/10/08 | 6 years ago | Package tga is a TARGA image format decoder/encoder. |
| [go-webcolors](https://github.com/jyotiska/go-webcolors) | 24 | 2 | 2014/04/24 | 6 years ago | Port of webcolors library from Python to Go. |
| [mpo](https://github.com/donatj/mpo) | 7 | 2 | 2015/04/14 | 1 year ago | Decoder and conversion tool for MPO 3D Photos. |
| [scout](https://github.com/jonoton/scout) | 1 | 1 | 2020/09/25 | 2 months ago | Scout is a standalone open source software solution for DIY video security. |
**[⬆ back to top](#awesome-go-info)**

## IoT
        
*Libraries for programming devices of the IoT.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [flogo](https://github.com/TIBCOSoftware/flogo) | 1894 | 155 | 2016/07/10 | 1 year ago | Project Flogo is an Open Source Framework for IoT Edge Apps & Integration. |
| [mainflux](https://github.com/mainflux/mainflux) | 1644 | 102 | 2015/07/06 | 2 hours ago | Industrial IoT Messaging and Device Management Server. |
| [gatt](https://github.com/paypal/gatt) | 1003 | 55 | 2014/04/23 | 1 year ago | Gatt is a Go package for building Bluetooth Low Energy peripherals. |
| [heedy](https://github.com/heedy/heedy) | 309 | 24 | 2015/01/16 | 3 weeks ago | Open-Source Platform for Quantified Self & IoT. |
| [devices](https://github.com/goiot/devices) | 248 | 16 | 2016/05/30 | 5 years ago | Suite of libraries for IoT devices, experimental for x/exp/io. |
| [sensorbee](https://github.com/sensorbee/sensorbee) | 208 | 19 | 2016/02/19 | 2 years ago | Lightweight stream processing engine for IoT. |
| [huego](https://github.com/amimof/huego) | 191 | 4 | 2017/05/16 | 1 week ago | An extensive Philips Hue client library for Go. |
| [eywa](https://github.com/xcodersun/eywa) | 50 | 8 | 2016/02/20 | 4 years ago | Project Eywa is essentially a connection manager that keeps track of connected devices. |
**[⬆ back to top](#awesome-go-info)**

## JSON
        
*Libraries for working with JSON.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gjson](https://github.com/tidwall/gjson) | 9494 | 154 | 2016/08/11 | 21 hours ago | Get a JSON value with one line of code. |
| [gojson](https://github.com/ChimeraCoder/gojson) | 2441 | 47 | 2012/12/27 | 5 months ago | Automatically generate Go (golang) struct definitions from example JSON. |
| [fastjson](https://github.com/valyala/fastjson) | 1406 | 26 | 2018/05/28 | 5 months ago | Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection. |
| [ojg](https://github.com/ohler55/ojg) | 444 | 6 | 2020/04/12 | 18 hours ago | Optimized JSON for Go is a high performance parser with a variety of additional JSON tools including JSONPath. |
| [kazaam](https://github.com/qntfy/kazaam) | 215 | 21 | 2016/07/19 | 5 months ago | API for arbitrary transformation of JSON documents. |
| [gojq](https://github.com/elgs/gojq) | 177 | 5 | 2015/12/30 | 1 year ago | JSON query in Golang. |
| [jsondiff](https://github.com/wI2L/jsondiff) | 141 | 2 | 2020/11/28 | 3 months ago | JSON diff library for Go based on RFC6902 (JSON Patch). |
| [jettison](https://github.com/wI2L/jettison) | 114 | 6 | 2019/08/30 | 6 days ago | Fast and flexible JSON encoder for Go. |
| [jsongo](https://github.com/ricardolonga/jsongo) | 98 | 1 | 2015/08/07 | 2 months ago | Fluent API to make it easier to create Json objects. |
| [gjo](https://github.com/skanehira/gjo) | 97 | 8 | 2019/02/23 | 8 months ago | Small utility to create JSON objects. |
| [json2go](https://github.com/m-zajac/json2go) | 94 | 3 | 2017/06/10 | 1 week ago | Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all. |
| [ajson](https://github.com/spyzhov/ajson) | 91 | 3 | 2019/03/07 | 20 hours ago | Abstract JSON for golang with JSONPath support. |
| [jaydiff](https://github.com/yazgazan/jaydiff) | 83 | 2 | 2017/04/24 | 11 months ago | JSON diff utility written in Go. |
| [jsonf](https://github.com/miolini/jsonf) | 62 | 3 | 2015/05/25 | 1 year ago | Console tool for highlighted formatting and struct query fetching JSON. |
| [ujson](https://github.com/olvrng/ujson) | 52 | 1 | 2019/02/27 | 4 months ago | Fast and minimal JSON parser and transformer that works on unstructured JSON. |
| [go-respond](https://github.com/nicklaw5/go-respond) | 43 | 1 | 2017/03/12 | 3 months ago | Go package for handling common HTTP JSON responses. |
| [mp](https://github.com/sanbornm/mp) | 43 | 2 | 2014/06/15 | 5 years ago | Simple cli email parser. It currently takes stdin and outputs JSON. |
| [jsoncolor](https://github.com/neilotoole/jsoncolor) | 26 | 1 | 2021/09/13 | 2 months ago | Drop-in replacement for `encoding/json` that outputs colorized JSON. |
| [vjson](https://github.com/miladibra10/vjson) | 23 | 1 | 2021/04/29 | 1 month ago | Go package for validating JSON objects with declaring a JSON schema with fluent API. |
| [ask](https://github.com/simonnilsson/ask) | 13 | 1 | 2020/09/13 | 10 months ago | Easy access to nested values in maps and slices. Works in combination with encoding/json and other packages that "Unmarshal" arbitrary data into Go data-types. |
| [go-jsonerror](https://github.com/ddymko/go-jsonerror) | 10 | 2 | 2018/10/18 | 2 years ago | Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec. |
| [dynjson](https://github.com/cocoonspace/dynjson) | 9 | 2 | 2020/05/06 | 2 months ago | Client-customizable JSON formats for dynamic APIs. |
| [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) | 9 | 2 | 2016/07/08 | 5 years ago | Go bindings based on the JSON API errors reference. |
| [jsonhal](https://github.com/RichardKnop/jsonhal) | 9 | 2 | 2016/01/15 | 1 year ago | Simple Go package to make custom structs marshal into HAL compatible JSON responses. |
| [mapslice-json](https://github.com/ake-persson/mapslice-json) | 8 | 1 | 2020/02/19 | 5 months ago | Go MapSlice for ordered marshal/ unmarshal of maps in JSON. |
| [epoch](https://github.com/vtopc/epoch) | 7 | 1 | 2019/12/15 | 9 months ago | Contains primitives for marshaling/unmarshaling Unix timestamp/epoch to/from build-in time.Time type in JSON. |
| [ej](https://github.com/lucassscaravelli/ej) | 6 | 2 | 2020/01/04 | 1 year ago | Write and read JSON from different sources succinctly. |
| [jsonic](https://github.com/sinhashubham95/jsonic) | 5 | 1 | 2021/01/09 | 11 months ago | Utilities to handle and query JSON without defining structs in a type safe manner. |
| [jzon](https://github.com/zerosnake0/jzon) | 5 | 1 | 2019/11/12 | 9 months ago | JSON library with standard compatible API/behavior. |
| [omg.jsonparser](https://github.com/dedalqq/omg.jsonparser) | 1 | 1 | 2021/07/08 | 2 months ago | Simple JSON parser with validation by condition via golang struct fields tags. |
**[⬆ back to top](#awesome-go-info)**

## Job Scheduler
        
*Libraries for scheduling jobs.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gocron](https://github.com/go-co-op/gocron) | 1448 | 20 | 2020/03/20 | 22 hours ago | Easy and fluent Go job scheduling. This is an actively maintained fork of [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron). |
| [jobrunner](https://github.com/bamzi/jobrunner) | 896 | 27 | 2015/10/21 | 1 year ago | Smart and featureful cron job scheduler with job queuing and live monitoring built in. |
| [gron](https://github.com/roylee0704/gron) | 877 | 15 | 2016/06/04 | 11 months ago | Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly. |
| [go-quartz](https://github.com/reugn/go-quartz) | 568 | 13 | 2019/04/14 | 3 weeks ago | Simple, zero-dependency scheduling library for Go. |
| [jobs](https://github.com/albrow/jobs) | 484 | 19 | 2015/02/09 | 3 years ago | Persistent and flexible background jobs library. |
| [scheduler](https://github.com/carlescere/scheduler) | 371 | 14 | 2015/02/03 | 1 year ago | Cronjobs scheduling made easy. |
| [go-cron](https://github.com/rk/go-cron) | 208 | 10 | 2011/04/15 | 1 year ago | Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. |
| [gronx](https://github.com/adhocore/gronx) | 181 | 3 | 2021/04/21 | 2 months ago | Cron expression parser, task runner and daemon consuming crontab like task list. |
| [clockwerk](https://github.com/onatm/clockwerk) | 114 | 2 | 2017/04/09 | 2 years ago | Go package to schedule periodic jobs using a simple, fluent syntax. |
| [leprechaun](https://github.com/kilgaloon/leprechaun) | 84 | 8 | 2018/04/08 | 1 month ago | Job scheduler that supports webhooks, crons and classic scheduling. |
| [tasks](https://github.com/madflojo/tasks) | 67 | 3 | 2019/12/24 | 9 months ago | An easy to use in-process scheduler for recurring tasks in Go. |
| [sched](https://github.com/romshark/sched) | 21 | 1 | 2021/06/19 | 5 months ago | A job scheduler with the ability to fast-forward time. |
| [cronticker](https://github.com/krayzpipes/cronticker) | 1 | 1 | 2020/11/28 | 1 year ago | A ticker implementation to support cron schedules. |
**[⬆ back to top](#awesome-go-info)**

## Logging
        
*Libraries for generating and working with log files.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [logrus](https://github.com/sirupsen/logrus) | 19535 | 312 | 2013/10/16 | 1 month ago | Structured logger for Go. |
| [zap](https://github.com/uber-go/zap) | 14470 | 246 | 2016/02/18 | 1 week ago | Fast, structured, leveled logging in Go. |
| [zerolog](https://github.com/rs/zerolog) | 5687 | 56 | 2017/05/12 | 1 week ago | Zero-allocation JSON logger. |
| [go-spew](https://github.com/davecgh/go-spew) | 4800 | 64 | 2013/01/09 | 5 days ago | Implements a deep pretty printer for Go data structures to aid in debugging. |
| [glog](https://github.com/golang/glog) | 3073 | 91 | 2013/07/16 | 4 months ago | Leveled execution logs for Go. |
| [lumberjack](https://github.com/natefinch/lumberjack) | 2995 | 58 | 2014/06/14 | 4 months ago | Simple rolling logger, implements io.WriteCloser. |
| [tail](https://github.com/hpcloud/tail) | 2240 | 103 | 2013/02/05 | 5 months ago | Go package striving to emulate the features of the BSD tail program. |
| [seelog](https://github.com/cihub/seelog) | 1575 | 92 | 2011/11/17 | 2 years ago | Logging functionality with flexible dispatching, filtering, and formatting. |
| [log](https://github.com/apex/log) | 1188 | 35 | 2015/12/21 | 1 month ago | Structured logging package for Go. |
| [log15](https://github.com/inconshreveable/log15) | 1034 | 25 | 2014/05/20 | 1 month ago | Simple, powerful logging for Go. |
| [log](https://github.com/phuslu/log) | 410 | 17 | 2019/07/07 | 1 month ago | Structured Logging Made Easy. |
| [onelog](https://github.com/francoispqt/onelog) | 399 | 9 | 2018/05/06 | 2 years ago | Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation. |
| [logxi](https://github.com/mgutz/logxi) | 349 | 10 | 2015/03/01 | 1 year ago | 12-factor app logger that is fast and makes you happy. |
| [logutils](https://github.com/hashicorp/logutils) | 305 | 257 | 2013/10/09 | 1 month ago | Utilities for slightly better logging in Go (Golang) extending the standard logger. |
| [log](https://github.com/go-playground/log) | 276 | 11 | 2016/02/07 | 2 years ago | Simple, configurable and scalable Structured Logging for Go. |
| [go-logger](https://github.com/apsdehal/go-logger) | 271 | 7 | 2014/09/26 | 2 years ago | Simple logger of Go Programs, with level handlers. |
| [httpretty](https://github.com/henvic/httpretty) | 246 | 6 | 2020/01/24 | 1 year ago | Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest). |
| [sqldb-logger](https://github.com/simukti/sqldb-logger) | 201 | 2 | 2019/11/02 | 7 months ago | A logger for Go SQL database driver without modify existing *sql.DB stdlib usage. |
| [rollingwriter](https://github.com/arthurkiller/rollingwriter) | 183 | 8 | 2017/02/12 | 1 week ago | RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation. |
| [logger](https://github.com/azer/logger) | 148 | 6 | 2014/09/30 | 1 month ago | Minimalistic logging library for Go. |
| [logur](https://github.com/logur/logur) | 144 | 7 | 2018/12/09 | 1 year ago | An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries ([logrus](https://github.com/sirupsen/logrus), [go-kit log](https://github.com/go-kit/kit/tree/master/log), [zap](https://github.com/uber-go/zap), [zerolog](https://github.com/rs/zerolog), etc). |
| [xlog](https://github.com/rs/xlog) | 135 | 8 | 2015/10/22 | 10 months ago | Structured logger for `net/context` aware HTTP handlers with flexible dispatching. |
| [glg](https://github.com/kpango/glg) | 134 | 6 | 2017/06/21 | 1 day ago | glg is simple and fast leveled logging library for Go. |
| [ozzo-log](https://github.com/go-ozzo/ozzo-log) | 116 | 12 | 2015/10/22 | 11 months ago | High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail). |
| [logvoyage](https://github.com/firstrow/logvoyage) | 89 | 5 | 2015/03/29 | 4 years ago | Full-featured logging saas written in golang. |
| [go-cronowriter](https://github.com/utahta/go-cronowriter) | 46 | 2 | 2017/02/04 | 9 months ago | Simple writer that rotate log files automatically based on current date and time, like cronolog. |
| [log](https://github.com/alexcesaro/log) | 45 | 6 | 2014/04/19 | 6 years ago | Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. |
| [gologger](https://github.com/sadlil/gologger) | 39 | 6 | 2015/09/02 | 3 years ago | Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch. |
| [go-log](https://github.com/ian-kent/go-log) | 38 | 2 | 2014/05/02 | 3 years ago | Log4j implementation in Go. |
| [logex](https://github.com/chzyer/logex) | 38 | 9 | 2014/10/10 | 2 days ago | Golang log lib, supports tracking and level, wrap by standard log lib. |
| [noodlog](https://github.com/gyozatech/noodlog) | 35 | 6 | 2021/04/09 | 2 months ago | Parametrized JSON logging library which lets you obfuscate sensitive data and marshal any kind of content. No more printed pointers instead of values, nor escape chars for the JSON strings. |
| [go-log](https://github.com/siddontang/go-log) | 29 | 6 | 2014/05/18 | 2 years ago | Log lib supports level and multi handlers. |
| [journald](https://github.com/ssgreg/journald) | 29 | 3 | 2017/08/23 | 9 months ago | Go implementation of systemd Journal's native API for logging. |
| [logrusly](https://github.com/sebest/logrusly) | 27 | 5 | 2014/09/11 | 5 months ago | [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). |
| [distillog](https://github.com/amoghe/distillog) | 25 | 2 | 2015/10/12 | 3 years ago | distilled levelled logging (think of it as stdlib + log levels). |
| [log](https://github.com/teris-io/log) | 24 | 2 | 2017/10/28 | 4 years ago | Structured log interface for Go cleanly separates logging facade from its implementation. |
| [mlog](https://github.com/jbrodriguez/mlog) | 24 | 1 | 2014/10/20 | 3 years ago | Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. |
| [gomol](https://github.com/aphistic/gomol) | 18 | 2 | 2015/08/30 | 2 years ago | Multiple-output, structured logging for Go with extensible logging outputs. |
| [zkits-logger](https://github.com/edoger/zkits-logger) | 15 | 1 | 2020/03/31 | 3 weeks ago | A powerful zero-dependency JSON logger. |
| [glo](https://github.com/lajosbencz/glo) | 14 | 1 | 2019/01/19 | 2 years ago | PHP Monolog inspired logging facility with identical severity levels. |
| [logrusiowriter](https://github.com/cabify/logrusiowriter) | 13 | 91 | 2019/08/09 | 1 year ago | `io.Writer` implementation using [logrus](https://github.com/sirupsen/logrus) logger. |
| [go-log](https://github.com/subchen/go-log) | 11 | 2 | 2017/05/07 | 3 years ago | Simple and configurable Logging in Go, with level, formatters and writers. |
| [logmatic](https://github.com/mborders/logmatic) | 11 | 2 | 2018/11/07 | 11 months ago | Colorized logger for Golang with dynamic log level configuration. |
| [log](https://github.com/aerogo/log) | 9 | 2 | 2017/06/10 | 2 years ago | An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection). |
| [logdump](https://github.com/ewwwwwqm/logdump) | 9 | 2 | 2017/01/13 | 3 years ago | Package for multi-level logging. |
| [logo](https://github.com/mbndr/logo) | 9 | 2 | 2017/02/07 | 1 year ago | Golang logger to different configurable writers. |
| [go-log](https://github.com/pieterclaerhout/go-log) | 8 | 3 | 2019/10/01 | 1 year ago | A logging library with strack traces, object dumping and optional timestamps. |
| [xlog](https://github.com/xfxdev/xlog) | 6 | 1 | 2016/05/05 | 2 years ago | Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format. |
| [kemba](https://github.com/clok/kemba) | 5 | 1 | 2020/07/13 | 1 week ago | A tiny debug logging tool inspired by [debug](https://github.com/visionmedia/debug), great for CLI tools and applications. |
| [yell](https://github.com/jfcg/yell) | 0 | 2 | 2021/02/07 | 4 months ago | Yet another minimalistic logging library. |
**[⬆ back to top](#awesome-go-info)**

## Machine Learning
        
*Libraries for Machine Learning.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [golearn](https://github.com/sjwhitworth/golearn) | 8137 | 430 | 2013/12/26 | 2 months ago | General Machine Learning library for Go. |
| [gorse](https://github.com/zhenghaoz/gorse) | 5051 | 51 | 2018/08/14 | 3 hours ago | An offline recommender system backend based on collaborative filtering written in Go. |
| [gorgonia](https://github.com/gorgonia/gorgonia) | 4312 | 193 | 2016/09/14 | 1 week ago | graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms. |
| [m2cgen](https://github.com/BayesWitnesses/m2cgen) | 1969 | 44 | 2019/01/13 | 1 day ago | A CLI tool to transpile trained classic ML models into a native Go code with zero dependencies, written in Python with Go language support. |
| [tfgo](https://github.com/galeone/tfgo) | 1857 | 60 | 2017/05/23 | 3 months ago | Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python. |
| [gosseract](https://github.com/otiai10/gosseract) | 1629 | 47 | 2013/10/11 | 3 weeks ago | Go package for OCR (Optical Character Recognition), by using Tesseract C++ library. |
| [goml](https://github.com/cdipaolo/goml) | 1283 | 74 | 2015/06/27 | 1 month ago | On-line Machine Learning in Go. |
| [eaopt](https://github.com/MaxHalford/eaopt) | 763 | 30 | 2016/01/31 | 8 months ago | An evolutionary optimization library. |
| [bayesian](https://github.com/jbrukh/bayesian) | 719 | 35 | 2011/11/23 | 1 year ago | Naive Bayesian Classification for Golang. |
| [CloudForest](https://github.com/ryanbressler/CloudForest) | 698 | 43 | 2012/10/22 | 1 year ago | Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. |
| [gobrain](https://github.com/goml/gobrain) | 500 | 27 | 2014/04/29 | 1 year ago | Neural Networks written in go. |
| [ocrserver](https://github.com/otiai10/ocrserver) | 450 | 15 | 2015/11/15 | 4 months ago | A simple OCR API server, seriously easy to be deployed by Docker and Heroku. |
| [onnx-go](https://github.com/owulveryck/onnx-go) | 363 | 12 | 2018/08/28 | 2 months ago | Go Interface to Open Neural Network Exchange (ONNX). |
| [go-deep](https://github.com/patrikeh/go-deep) | 335 | 16 | 2017/12/09 | 3 weeks ago | A feature-rich neural network library in Go. |
| [regommend](https://github.com/muesli/regommend) | 298 | 16 | 2014/02/05 | 2 years ago | Recommendation & collaborative filtering engine. |
| [goptuna](https://github.com/c-bata/goptuna) | 196 | 9 | 2019/07/24 | 1 month ago | Bayesian optimization framework for black-box functions written in Go. Everything will be optimized. |
| [go-galib](https://github.com/thoj/go-galib) | 188 | 15 | 2009/11/30 | 6 years ago | Genetic Algorithms library written in Go / golang. |
| [goRecommend](https://github.com/timkaye11/goRecommend) | 179 | 10 | 2014/07/16 | 7 years ago | Recommendation Algorithms library written in Go. |
| [shield](https://github.com/eaigner/shield) | 145 | 11 | 2013/04/10 | 1 year ago | Bayesian text classifier with flexible tokenizers and storage backends for Go. |
| [goga](https://github.com/tomcraven/goga) | 123 | 10 | 2015/10/20 | 4 days ago | Genetic algorithm library for Go. |
| [go-fann](https://github.com/vksnk/go-fann) | 104 | 9 | 2011/03/10 | 6 years ago | Go bindings for Fast Artificial Neural Networks(FANN) library. |
| [goscore](https://github.com/asafschers/goscore) | 72 | 7 | 2017/08/19 | 2 years ago | Go Scoring API for PMML. |
| [gonet](https://github.com/dathoangnd/gonet) | 70 | 5 | 2020/01/11 | 1 year ago | Neural Network for Go. |
| [go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) | 68 | 1 | 2020/12/18 | 6 months ago | Fast and convenient feature processing for low latency machine leraning in Go. |
| [libsvm](https://github.com/datastream/libsvm) | 68 | 11 | 2012/07/31 | 5 years ago | libsvm golang version derived work based on LIBSVM 3.14. |
| [neural-go](https://github.com/schuyler/neural-go) | 61 | 3 | 2011/10/17 | 1 year ago | Multilayer perceptron network implemented in Go, with training via backpropagation. |
| [neat](https://github.com/jinyeom/neat) | 60 | 13 | 2016/11/17 | 3 years ago | Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT). |
| [go-pr](https://github.com/daviddengcn/go-pr) | 59 | 7 | 2013/06/07 | 8 years ago | Pattern recognition package in Go lang. |
| [fonet](https://github.com/Fontinalis/fonet) | 51 | 5 | 2017/10/03 | 7 months ago | A Deep Neural Network library written in Go. |
| [golinear](https://github.com/danieldk/golinear) | 43 | 6 | 2013/04/05 | 3 years ago | liblinear bindings for Go. |
| [Varis](https://github.com/Xamber/Varis) | 38 | 8 | 2017/10/10 | 3 years ago | Golang Neural Network. |
| [godist](https://github.com/e-dard/godist) | 31 | 4 | 2014/09/05 | 6 years ago | Various probability distributions, and associated methods. |
| [go-cluster](https://github.com/e-XpertSolutions/go-cluster) | 29 | 8 | 2017/10/04 | 3 years ago | Go implementation of the k-modes and k-prototypes clustering algorithms. |
| [evoli](https://github.com/khezen/evoli) | 20 | 6 | 2015/06/12 | 2 months ago | Genetic Algorithm and Particle Swarm Optimization library. |
| [gomind](https://github.com/surenderthakran/gomind) | 20 | 4 | 2017/10/19 | 3 years ago | A simplistic Neural Network Library in Go. |
| [randomForest](https://github.com/malaschitz/randomForest) | 18 | 4 | 2018/10/25 | 2 months ago | Easy to use Random Forest library for Go. |
| [ddt](https://github.com/sgrodriguez/ddt) | 16 | 1 | 2020/05/20 | 10 months ago | Dynamic decision tree, create trees defining customizable rules. |
| [probab](https://github.com/ThePaw/probab) | 16 | 2 | 2015/09/14 | 6 years ago | Probability distribution functions. Bayesian inference. Written in pure Go. |
**[⬆ back to top](#awesome-go-info)**

## Messaging
        
*Libraries that implement messaging systems.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [sarama](https://github.com/Shopify/sarama) | 8000 | 513 | 2013/07/05 | 3 days ago | Go library for Apache Kafka. |
| [gorush](https://github.com/appleboy/gorush) | 5966 | 187 | 2016/03/22 | 1 week ago | Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm). |
| [machinery](https://github.com/RichardKnop/machinery) | 5850 | 152 | 2015/04/05 | 5 days ago | Asynchronous task queue/job queue based on distributed message passing. |
| [centrifugo](https://github.com/centrifugal/centrifugo) | 5690 | 196 | 2015/03/31 | 6 days ago | Real-time messaging (Websockets or SockJS) server in Go. |
| [go-socket.io](https://github.com/googollee/go-socket.io) | 4429 | 134 | 2013/07/13 | 2 weeks ago | socket.io library for golang, a realtime application framework. |
| [benthos](https://github.com/Jeffail/benthos) | 3725 | 90 | 2016/03/22 | 26 minutes ago | A message streaming bridge between a range of protocols. |
| [nats.go](https://github.com/nats-io/nats.go) | 3698 | 163 | 2012/08/15 | 1 day ago | Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library. |
| [confluent-kafka-go](https://github.com/confluentinc/confluent-kafka-go) | 3068 | 270 | 2016/07/12 | 2 weeks ago | confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform. |
| [mercure](https://github.com/dunglas/mercure) | 2614 | 54 | 2018/07/14 | 18 hours ago | Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events). |
| [apns2](https://github.com/sideshow/apns2) | 2571 | 77 | 2016/01/05 | 3 months ago | HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps. |
| [melody](https://github.com/olahol/melody) | 2313 | 60 | 2015/05/13 | 7 months ago | Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling. |
| [go-nsq](https://github.com/nsqio/go-nsq) | 2051 | 64 | 2013/08/29 | 4 weeks ago | the official Go package for NSQ. |
| [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) | 2018 | 231 | 2013/12/27 | 4 years ago | gopush-cluster is a go push server cluster. |
| [asynq](https://github.com/hibiken/asynq) | 1996 | 40 | 2019/11/15 | 1 day ago | A simple, reliable, and efficient distributed task queue for Go built on top of Redis. |
| [uniqush-push](https://github.com/uniqush/uniqush-push) | 1295 | 79 | 2011/08/29 | 1 year ago | Redis backed unified push service for server-side notifications to mobile devices. |
| [Beaver](https://github.com/Clivern/Beaver) | 1292 | 29 | 2018/10/20 | 1 week ago | A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps. |
| [EventBus](https://github.com/asaskevich/EventBus) | 1051 | 29 | 2014/12/19 | 6 months ago | The lightweight event bus with async compatibility. |
| [zmq4](https://github.com/pebbe/zmq4) | 950 | 43 | 2013/10/18 | 3 months ago | Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). |
| [gollum](https://github.com/trivago/gollum) | 908 | 39 | 2015/06/20 | 6 months ago | A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations. |
| [chanify](https://github.com/chanify/chanify) | 701 | 6 | 2021/02/25 | 2 months ago | A push notification server send message to your iOS devices. |
| [dbus](https://github.com/godbus/dbus) | 654 | 21 | 2014/03/27 | 1 week ago | Native Go bindings for D-Bus. |
| [golongpoll](https://github.com/jcuga/golongpoll) | 586 | 21 | 2015/11/02 | 8 months ago | HTTP longpoll server library that makes web pub-sub simple. |
| [mangos](https://github.com/nanomsg/mangos) | 470 | 21 | 2018/10/12 | 6 days ago | Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability. |
| [emitter](https://github.com/olebedev/emitter) | 415 | 10 | 2015/11/10 | 1 year ago | Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins. |
| [glue](https://github.com/desertbit/glue) | 390 | 17 | 2015/06/07 | 1 year ago | Robust Go and Javascript Socket Library (Alternative to Socket.io). |
| [pubsub](https://github.com/cskr/pubsub) | 364 | 9 | 2012/04/01 | 1 year ago | Simple pubsub package for go. |
| [bus](https://github.com/mustafaturan/bus) | 238 | 3 | 2019/04/27 | 7 months ago | Minimalist message bus implementation for internal communication. |
| [message-bus](https://github.com/vardius/message-bus) | 202 | 8 | 2017/10/04 | 11 months ago | messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD. |
| [rabtap](https://github.com/jandelgado/rabtap) | 199 | 8 | 2017/11/11 | 2 weeks ago | RabbitMQ swiss army knife cli app. |
| [amqp091-go](https://github.com/rabbitmq/amqp091-go) | 177 | 21 | 2021/06/09 | 2 weeks ago | Go RabbitMQ Client Library. |
| [guble](https://github.com/smancke/guble) | 149 | 13 | 2015/11/15 | 4 years ago | Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence. |
| [hub](https://github.com/leandro-lugaresi/hub) | 111 | 2 | 2018/04/13 | 1 year ago | A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges. |
| [oplog](https://github.com/dailymotion/oplog) | 110 | 92 | 2014/11/06 | 6 years ago | Generic oplog/replication system for REST APIs. |
| [rabbus](https://github.com/rafaeljesus/rabbus) | 92 | 8 | 2017/05/07 | 2 years ago | A tiny wrapper over amqp exchanges and queues. |
| [drone-line](https://github.com/appleboy/drone-line) | 76 | 5 | 2016/09/13 | 6 months ago | Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI. |
| [go-mq](https://github.com/cheshir/go-mq) | 73 | 6 | 2017/06/19 | 4 weeks ago | RabbitMQ client with declarative configuration. |
| [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) | 70 | 8 | 2017/01/15 | 3 years ago | A tiny wrapper around NSQ topic and channel. |
| [redisqueue](https://github.com/robinjoseph08/redisqueue) | 69 | 3 | 2019/07/07 | 5 months ago | redisqueue provides a producer and consumer of a queue that uses Redis streams. |
| [RapidMQ](https://github.com/sybrexsys/RapidMQ) | 63 | 5 | 2016/10/04 | 4 years ago | RapidMQ is a lightweight and reliable library for managing of the local messages queue. |
| [commander](https://github.com/jeroenrinzema/commander) | 57 | 1 | 2018/04/20 | 8 months ago | A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka. |
| [go-notify](https://github.com/TheCreeper/go-notify) | 56 | 2 | 2015/03/01 | 1 year ago | Native implementation of the freedesktop notification spec. |
| [go-res](https://github.com/jirenius/go-res) | 53 | 2 | 2018/07/15 | 3 months ago | Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate. |
| [event](https://github.com/agoalofalife/event) | 44 | 4 | 2017/07/02 | 3 years ago | Implementation of the pattern observer. |
| [hare](https://github.com/leozz37/hare) | 32 | 2 | 2020/12/01 | 4 months ago | A user friendly library for sending messages and listening to TCP sockets. |
| [ami](https://github.com/kak-tus/ami) | 21 | 1 | 2018/10/27 | 1 year ago | Go client to reliable queues based on Redis Cluster Streams. |
| [gosd](https://github.com/alexsniffin/gosd) | 18 | 1 | 2020/05/17 | 1 year ago | A library for scheduling when to dispatch a message to a channel. |
| [go-vitotrol](https://github.com/maxatome/go-vitotrol) | 16 | 7 | 2016/11/03 | 10 months ago | Client library to Viessmann Vitotrol web service. |
| [rmqconn](https://github.com/sbabiv/rmqconn) | 15 | 1 | 2019/01/14 | 1 year ago | RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed. |
| [jazz](https://github.com/socifi/jazz) | 13 | 4 | 2018/10/22 | 2 years ago | A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages. |
| [gaurun-client](https://github.com/osamingo/gaurun-client) | 9 | 1 | 2017/06/29 | 4 months ago | Gaurun Client written in Go. |
**[⬆ back to top](#awesome-go-info)**

## Microsoft Office
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [unioffice](https://github.com/unidoc/unioffice) | 3126 | 75 | 2017/08/29 | 1 month ago | Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents. |
**[⬆ back to top](#awesome-go-info)**

### Microsoft Excel
        
*Libraries for working with Microsoft Excel.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [excelize](https://github.com/qax-os/excelize) | 10344 | 207 | 2016/08/29 | 1 day ago | Golang library for reading and writing Microsoft Excel&trade; (XLSX) files. |
| [xlsx](https://github.com/tealeg/xlsx) | 5206 | 171 | 2011/06/28 | 1 week ago | Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs. |
| [xlsx](https://github.com/plandem/xlsx) | 146 | 13 | 2017/08/26 | 1 year ago | Fast and safe way to read/update your existing Microsoft Excel files in Go programs. |
| [go-excel](https://github.com/szyhf/go-excel) | 132 | 3 | 2017/09/03 | 3 weeks ago | A simple and light reader to read a relate-db-like excel as a table. |
| [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) | 17 | 2 | 2017/03/13 | 3 years ago | Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files. |
**[⬆ back to top](#awesome-go-info)**

## Miscellaneous
        
**[⬆ back to top](#awesome-go-info)**

### Dependency Injection
        
*Libraries for working with dependency injection.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fx](https://github.com/uber-go/fx) | 2401 | 65 | 2016/10/27 | 2 weeks ago | A dependency injection based application framework for Go (built on top of dig). |
| [dig](https://github.com/uber-go/dig) | 2271 | 50 | 2017/03/21 | 5 days ago | A reflection based dependency injection toolkit for Go. |
| [container](https://github.com/golobby/container) | 284 | 5 | 2019/09/23 | 3 weeks ago | A powerful IoC Container with fluent and easy-to-use interface. |
| [di](https://github.com/goioc/di) | 129 | 5 | 2020/06/11 | 4 months ago | Spring-inspired Dependency Injection Container. |
| [dingo](https://github.com/i-love-flamingo/dingo) | 119 | 26 | 2018/10/29 | 8 months ago | A dependency injection toolkit for Go, based on Guice. |
| [di](https://github.com/goava/di) | 115 | 8 | 2020/02/03 | 4 weeks ago | A dependency injection container for go programming language. |
| [alice](https://github.com/magic003/alice) | 43 | 2 | 2017/04/08 | 4 years ago | Additive dependency injection container for Golang. |
| [wire](https://github.com/Fs02/wire) | 35 | 2 | 2018/07/05 | 4 months ago | Strict Runtime Dependency Injection for Golang. |
| [linker](https://github.com/logrange/linker) | 32 | 4 | 2018/12/04 | 1 year ago | A reflection based dependency injection and inversion of control library with components lifecycle support. |
| [gocontainer](https://github.com/vardius/gocontainer) | 14 | 0 | 2019/06/06 | 1 year ago | Simple Dependency Injection Container. |
| [kinit](https://github.com/go-kata/kinit) | 5 | 3 | 2021/01/24 | 6 months ago | Customizable dependency injection container with the global mode, cascade initialization and panic-safe finalization. |
| [nject](https://github.com/muir/nject) | 5 | 1 | 2021/09/15 | 1 month ago | A type safe, reflective framework for libraries, tests, and http endpoints, and service startup. |
| [di](https://github.com/HnH/di) | 3 | 1 | 2021/10/13 | 3 weeks ago | DI container library that is focused on clean API and flexibility. |
**[⬆ back to top](#awesome-go-info)**

### Project Layout
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [project-layout](https://github.com/golang-standards/project-layout) | 28480 | 552 | 2017/09/09 | 8 hours ago | Set of common historical and emerging project layout patterns in the Go ecosystem. Note: despite the org-name they do not represent official golang standards, see [this issue](https://github.com/golang-standards/project-layout/issues/117) for more information. Nonetheless, some may find the layout useful. |
| [service](https://github.com/ardanlabs/service) | 2090 | 95 | 2017/11/20 | 2 weeks ago | A [starter kit](https://github.com/ardanlabs/service/wiki) for building production grade scalable web service applications. |
| [modern-go-application](https://github.com/sagikazarmark/modern-go-application) | 1115 | 26 | 2018/09/14 | 4 days ago | Go application boilerplate and example applying modern practices. |
| [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) | 488 | 10 | 2016/12/18 | 10 months ago | A Go application boilerplate template for quick starting projects following production best practices. |
| [seed](https://github.com/golang-templates/seed) | 231 | 5 | 2020/04/30 | 3 months ago | Go application GitHub repository template. |
| [go-starter](https://github.com/allaboutapps/go-starter) | 111 | 11 | 2020/05/08 | 1 week ago | An opinionated production-ready RESTful JSON backend template, highly integrated with VSCode DevContainers. |
| [go-todo-backend](https://github.com/Fs02/go-todo-backend) | 108 | 4 | 2020/06/25 | 3 months ago | Go Todo Backend example using modular project layout for product microservice. |
| [scaffold](https://github.com/catchplay/scaffold) | 103 | 5 | 2018/12/11 | 3 years ago | Scaffold generates a starter Go project layout. Lets you focus on business logic implemented. |
| [go-sample](https://github.com/zitryss/go-sample) | 95 | 1 | 2019/01/24 | 2 years ago | A sample layout for Go application projects with the real code. |
| [gobase](https://github.com/wajox/gobase) | 16 | 3 | 2020/12/15 | 3 months ago | A simple skeleton for golang application with basic setup for real golang application. |
| [go-project-layout](https://github.com/wangyoucao577/go-project-layout) | 11 | 2 | 2019/10/06 | 7 months ago | Set of practices and discussions on how to structure Go project layout. |
| [inizio](https://github.com/insidieux/inizio) | 9 | 1 | 2021/03/02 | 7 months ago | Golang project layout generator with plugins. |
**[⬆ back to top](#awesome-go-info)**

### Strings
        
*Libraries for working with strings.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [xstrings](https://github.com/huandu/xstrings) | 965 | 25 | 2015/01/06 | 1 week ago | Collection of useful string functions ported from other languages. |
| [sttr](https://github.com/abhimanyu003/sttr) | 318 | 5 | 2021/09/18 | 2 days ago | cross-platform, cli app to perform various operations on string. |
| [strutil](https://github.com/ozgio/strutil) | 147 | 4 | 2018/08/16 | 2 months ago | String utilities. |
| [stringy](https://github.com/gobeam/stringy) | 97 | 4 | 2020/04/03 | 1 month ago | String manipulation library to convert string to camel case, snake case, kebab case / slugify etc. |
| [bexp](https://github.com/mkungla/bexp) | 4 | 1 | 2020/12/15 | 2 months ago | Go implementation of Brace Expansion mechanism to generate arbitrary strings. |
**[⬆ back to top](#awesome-go-info)**

### Uncategorized
        
*These libraries were placed here because none of the other categories seemed to fit.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gopsutil](https://github.com/shirou/gopsutil) | 7160 | 207 | 2014/04/18 | 23 hours ago | Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). |
| [archiver](https://github.com/mholt/archiver) | 3380 | 52 | 2016/04/08 | 1 month ago | Library and command for making and extracting .zip and .tar.gz archives. |
| [gofakeit](https://github.com/brianvoe/gofakeit) | 2205 | 17 | 2015/04/24 | 17 hours ago | Random data generator written in go. |
| [gatus](https://github.com/TwiN/gatus) | 2052 | 20 | 2019/09/04 | 1 week ago | Automated service health dashboard. |
| [gosms](https://github.com/haxpax/gosms) | 1360 | 57 | 2015/01/23 | 10 months ago | Your own local SMS gateway in Go that can be used to send SMS. |
| [base64Captcha](https://github.com/mojocn/base64Captcha) | 1296 | 48 | 2017/12/12 | 3 weeks ago | Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha. |
| [go-resiliency](https://github.com/eapache/go-resiliency) | 1294 | 26 | 2014/11/29 | 3 months ago | Resiliency patterns for golang. |
| [go-commons-pool](https://github.com/jolestar/go-commons-pool) | 997 | 49 | 2015/12/28 | 8 months ago | Generic object pool for Golang. |
| [llvm](https://github.com/llir/llvm) | 829 | 33 | 2014/09/19 | 6 days ago | Library for interacting with LLVM IR in pure Go. |
| [shortid](https://github.com/teris-io/shortid) | 728 | 10 | 2016/01/04 | 1 year ago | Distributed generation of super short, unique, non-sequential, URL friendly IDs. |
| [health](https://github.com/alexliesenfeld/health) | 475 | 6 | 2021/07/02 | 2 weeks ago | A simple and flexible health check library for Go. |
| [health](https://github.com/dimiro1/health) | 425 | 6 | 2016/03/08 | 2 years ago | Easy to use, extensible health check library. |
| [stateless](https://github.com/qmuntal/stateless) | 390 | 9 | 2019/09/11 | 3 months ago | A fluent library for creating state machines. |
| [go-conv](https://github.com/cstockton/go-conv) | 373 | 8 | 2016/10/11 | 4 months ago | Package conv provides fast and intuitive conversions across Go types. |
| [banner](https://github.com/dimiro1/banner) | 372 | 6 | 2016/03/25 | 11 months ago | Add beautiful banners into your Go applications. |
| [gountries](https://github.com/pariz/gountries) | 332 | 11 | 2016/01/13 | 4 weeks ago | Package that exposes country and subdivision data. |
| [shoutrrr](https://github.com/containrrr/shoutrrr) | 276 | 8 | 2019/04/11 | 2 days ago | Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others. |
| [ffmt](https://github.com/go-ffmt/ffmt) | 247 | 7 | 2015/02/14 | 1 month ago | Beautify data display for Humans. |
| [lk](https://github.com/hyperboloide/lk) | 229 | 7 | 2016/07/14 | 1 year ago | A simple licensing library for golang. |
| [antch](https://github.com/antchfx/antch) | 224 | 16 | 2017/09/28 | 1 year ago | A fast, powerful and extensible web crawling & scraping framework. |
| [healthcheck](https://github.com/etherlabsio/healthcheck) | 208 | 10 | 2017/08/18 | 6 months ago | An opinionated and concurrent health-check HTTP handler for RESTful services. |
| [battery](https://github.com/distatus/battery) | 196 | 5 | 2016/03/12 | 2 months ago | Cross-platform, normalized battery information library. |
| [bitio](https://github.com/icza/bitio) | 174 | 8 | 2016/05/31 | 3 weeks ago | Highly optimized bit-level Reader and Writer for Go. |
| [go-unarr](https://github.com/gen2brain/go-unarr) | 160 | 6 | 2015/11/01 | 2 months ago | Decompression library for RAR, TAR, ZIP and 7z archives. |
| [stats](https://github.com/go-playground/stats) | 158 | 3 | 2015/09/14 | 5 years ago | Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... |
| [turtle](https://github.com/hackebrot/turtle) | 128 | 2 | 2017/09/08 | 2 months ago | Emojis for Go. |
| [gommit](https://github.com/antham/gommit) | 95 | 4 | 2016/08/30 | 1 week ago | Analyze git commit messages to ensure they follow defined patterns. |
| [gotoprom](https://github.com/cabify/gotoprom) | 92 | 94 | 2018/10/10 | 1 year ago | Type-safe metrics builder wrapper library for the official Prometheus client. |
| [indigo](https://github.com/osamingo/indigo) | 91 | 1 | 2016/08/31 | 10 months ago | Distributed unique ID generator of using Sonyflake and encoded by Base58. |
| [captcha](https://github.com/steambap/captcha) | 88 | 5 | 2017/09/12 | 3 months ago | Package captcha provides an easy to use, unopinionated API for captcha generation. |
| [morse](https://github.com/alwindoss/morse) | 72 | 2 | 2018/08/15 | 4 months ago | Library to convert to and from morse code. |
| [persian](https://github.com/mavihq/persian) | 61 | 6 | 2017/10/16 | 6 months ago | Some utilities for Persian language in go. |
| [pdfgen](https://github.com/hyperboloide/pdfgen) | 56 | 4 | 2015/11/30 | 3 years ago | HTTP service to generate PDF from Json requests. |
| [faker](https://github.com/pioz/faker) | 53 | 4 | 2020/07/22 | 2 months ago | Random fake data and struct generator for Go. |
| [xkg](https://github.com/go-xkg/xkg) | 52 | 2 | 2015/01/05 | 7 years ago | X Keyboard Grabber. |
| [browscap_go](https://github.com/digitalcrab/browscap_go) | 39 | 6 | 2014/09/18 | 3 months ago | GoLang Library for [Browser Capabilities Project](https://browscap.org/). |
| [datacounter](https://github.com/miolini/datacounter) | 37 | 1 | 2015/10/14 | 1 year ago | Go counters for readers/writer/http.ResponseWriter. |
| [autoflags](https://github.com/artyom/autoflags) | 36 | 5 | 2014/05/15 | 8 months ago | Go package to automatically define command line flags from struct fields. |
| [sandid](https://github.com/aofei/sandid) | 33 | 1 | 2018/06/12 | 1 month ago | Every grain of sand on earth has its own ID. |
| [url-shortener](https://github.com/pantrif/url-shortener) | 33 | 1 | 2018/06/04 | 3 years ago | A modern, powerful, and robust URL shortener microservice with mysql support. |
| [gosh](https://github.com/osamingo/gosh) | 29 | 0 | 2018/05/25 | 11 months ago | Provide Go Statistics Handler, Struct, Measure Method. |
| [xdg](https://github.com/rkoesters/xdg) | 28 | 3 | 2013/12/15 | 5 months ago | FreeDesktop.org (xdg) Specs implemented in Go. |
| [metrics](https://github.com/pascaldekloe/metrics) | 22 | 1 | 2019/01/29 | 9 months ago | Library for metrics instrumentation and Prometheus exposition. |
| [gtree](https://github.com/ddddddO/gtree) | 21 | 2 | 2021/05/30 | 2 weeks ago | Provide CLI and Package to generate tree from Markdown or programmatically, and the output is JSON/YAML/TOML/tree command. |
| [shellwords](https://github.com/Wing924/shellwords) | 16 | 1 | 2017/09/28 | 4 years ago | A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell. |
| [anagent](https://github.com/mudler/anagent) | 13 | 3 | 2017/12/29 | 3 years ago | Minimalistic, pluggable Golang evloop/timer handler with dependency-injection. |
| [avgRating](https://github.com/kirillDanshin/avgRating) | 11 | 2 | 2017/08/05 | 4 years ago | Calculate average score and rating based on Wilson Score Equation. |
| [hostutils](https://github.com/Wing924/hostutils) | 10 | 1 | 2017/09/26 | 3 years ago | A golang library for packing and unpacking FQDNs list. |
| [numa](https://github.com/lrita/numa) | 6 | 4 | 2018/12/10 | 1 year ago | NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code. |
| [go-commandbus](https://github.com/lana/go-commandbus) | 3 | 23 | 2019/10/03 | 1 year ago | A slight and pluggable command-bus for Go. |
| [varint](https://github.com/chmike/varint) | 2 | 1 | 2021/11/30 | 1 week ago | A faster varying length integer encoder/decoder than the one provided in the standard library. |
| [basexx](https://github.com/bobg/basexx) | 1 | 1 | 2019/06/08 | 2 months ago | Convert to, from, and between digit strings in various number bases. |
**[⬆ back to top](#awesome-go-info)**

## Natural Language Processing
        
*Libraries for working with human languages.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [prose](https://github.com/jdkato/prose) | 2844 | 60 | 2017/02/17 | 3 months ago | Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only. |
| [gojieba](https://github.com/yanyiwu/gojieba) | 1748 | 68 | 2015/09/12 | 6 months ago | This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm. |
| [gse](https://github.com/go-ego/gse) | 1708 | 60 | 2017/06/23 | 2 weeks ago | Go efficient text segmentation; support english, chinese, japanese and other. |
| [when](https://github.com/olebedev/when) | 1136 | 25 | 2016/12/27 | 2 weeks ago | Natural EN and RU language date/time parser with pluggable rules. |
| [spago](https://github.com/nlpodyssey/spago) | 1066 | 31 | 2020/01/05 | 3 weeks ago | Self-contained Machine Learning and Natural Language Processing library in Go. |
| [go-pinyin](https://github.com/mozillazg/go-pinyin) | 1055 | 38 | 2014/11/09 | 2 weeks ago | CN Hanzi to Hanyu Pinyin converter. |
| [kagome](https://github.com/ikawaha/kagome) | 597 | 22 | 2014/06/26 | 1 month ago | JP morphological analyzer written in pure Go. |
| [whatlanggo](https://github.com/abadojack/whatlanggo) | 516 | 15 | 2017/02/20 | 11 months ago | Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc). |
| [nlp](https://github.com/shixzie/nlp) | 376 | 23 | 2017/01/25 | 4 years ago | Extract values from strings and fill your structs with nlp. |
| [nlp](https://github.com/james-bowman/nlp) | 349 | 25 | 2017/03/15 | 7 months ago | Go Natural Language Processing library supporting LSA (Latent Semantic Analysis). |
| [sentences](https://github.com/neurosnap/sentences) | 315 | 14 | 2015/08/07 | 6 months ago | Sentence tokenizer:  converts text into a list of sentences. |
| [getlang](https://github.com/rylans/getlang) | 126 | 4 | 2018/03/01 | 1 year ago | Fast natural language detection package. |
| [go-nlp](https://github.com/nuance/go-nlp) | 90 | 7 | 2011/05/02 | 10 years ago | Utilities for working with discrete probability distributions and other tools useful for doing NLP work. |
| [go-unidecode](https://github.com/mozillazg/go-unidecode) | 89 | 2 | 2016/07/08 | 8 months ago | ASCII transliterations of Unicode text. |
| [RAKE.Go](https://github.com/afjoseph/RAKE.Go) | 86 | 7 | 2016/12/17 | 1 year ago | Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE). |
| [gounidecode](https://github.com/fiam/gounidecode) | 73 | 5 | 2012/05/01 | 6 years ago | Unicode transliterator (also known as unidecode) for Go. |
| [textcat](https://github.com/pebbe/textcat) | 65 | 7 | 2012/09/21 | 10 months ago | Go package for n-gram based text categorization, with support for utf-8 and raw text. |
| [go-stem](https://github.com/agonopol/go-stem) | 64 | 4 | 2011/09/23 | 3 years ago | Implementation of the porter stemming algorithm. |
| [MMSEGO](https://github.com/awsong/MMSEGO) | 59 | 5 | 2012/04/18 | 9 years ago | This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. |
| [stemmer](https://github.com/dchest/stemmer) | 50 | 4 | 2011/03/21 | 5 years ago | Stemmer packages for Go programming language. Includes English and German stemmers. |
| [go2vec](https://github.com/danieldk/go2vec) | 43 | 7 | 2015/01/27 | 3 years ago | Reader and utility functions for word2vec embeddings. |
| [address](https://github.com/bojanz/address) | 42 | 3 | 2020/10/07 | 1 month ago | Handles address representation, validation and formatting. |
| [porter2](https://github.com/zentures/porter2) | 41 | 3 | 2015/01/21 | 1 year ago | Really fast Porter 2 stemmer. |
| [petrovich](https://github.com/striker2000/petrovich) | 36 | 2 | 2016/12/26 | 10 months ago | Petrovich is the library which inflects Russian names to given grammatical case. |
| [go-localize](https://github.com/m1/go-localize) | 29 | 2 | 2019/12/23 | 1 month ago | Simple and easy to use i18n (Internationalization and localization) engine - used for translating locale strings. |
| [snowball](https://github.com/goodsign/snowball) | 28 | 1 | 2012/12/11 | 4 years ago | Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). |
| [mystem](https://github.com/dveselov/mystem) | 27 | 3 | 2016/08/30 | 5 years ago | CGo bindings to Yandex.Mystem - russian morphology analyzer. |
| [iuliia-go](https://github.com/mehanizm/iuliia-go) | 27 | 2 | 2020/04/27 | 6 months ago | Transliterate Cyrillic → Latin in every possible way. |
| [paicehusk](https://github.com/rookii/paicehusk) | 27 | 3 | 2012/09/29 | 8 years ago | Golang implementation of the Paice/Husk Stemming Algorithm. |
| [golibstemmer](https://github.com/rjohnsondev/golibstemmer) | 19 | 2 | 2012/08/06 | 7 years ago | Go bindings for the snowball libstemmer library including porter 2. |
| [icu](https://github.com/goodsign/icu) | 19 | 0 | 2012/12/11 | 4 years ago | Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1. |
| [govader](https://github.com/jonreiter/govader) | 17 | 1 | 2020/01/19 | 10 months ago | Go implementation of [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment). |
| [transliterator](https://github.com/alexsergivan/transliterator) | 17 | 1 | 2020/04/17 | 1 year ago | Provides one-way string transliteration with supporting of language-specific transliteration rules. |
| [gotokenizer](https://github.com/xujiajun/gotokenizer) | 13 | 1 | 2018/10/11 | 2 years ago | A tokenizer based on the dictionary and Bigram language models for Go. (Now only support chinese segmentation) |
| [shamoji](https://github.com/osamingo/shamoji) | 12 | 2 | 2017/07/23 | 11 months ago | The shamoji is word filtering package written in Go. |
| [detectlanguage-go](https://github.com/detectlanguage/detectlanguage-go) | 10 | 2 | 2019/12/14 | 1 year ago | Language Detection API Go Client. Supports batch requests, short phrase or single word language detection. |
| [libtextcat](https://github.com/goodsign/libtextcat) | 10 | 2 | 2012/12/10 | 9 years ago | Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. |
| [porter](https://github.com/a2800276/porter) | 8 | 1 | 2013/09/17 | 8 years ago | This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm. |
| [gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) | 7 | 1 | 2020/04/21 | 9 months ago | Sentiment analyzer using sentiwordnet lexicon in Go. |
| [t](https://github.com/youthlin/t) | 7 | 2 | 2021/06/04 | 2 months ago | Another i18n pkg for golang, which follows GNU gettext style and supports .po/.mo files: `t.T (gettext)`, `t.N (ngettext)`, etc. And it contains a cmd tool [xtemplate](https://github.com/youthlin/t/blob/main/cmd/xtemplate), which can extract messages as a pot file from text/html template. |
**[⬆ back to top](#awesome-go-info)**

## Networking
        
*Libraries for working with various layers of the network.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fasthttp](https://github.com/valyala/fasthttp) | 16653 | 399 | 2015/10/18 | 5 hours ago | Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http. |
| [kcptun](https://github.com/xtaci/kcptun) | 12723 | 594 | 2016/02/26 | 1 week ago | Extremely simple & fast udp tunnel based on KCP protocol. |
| [webrtc](https://github.com/pion/webrtc) | 8440 | 248 | 2018/05/18 | 1 hour ago | A pure Go implementation of the WebRTC API. |
| [quic-go](https://github.com/lucas-clemente/quic-go) | 6131 | 203 | 2016/04/06 | 1 week ago | An implementation of the QUIC protocol in pure Go. |
| [dns](https://github.com/miekg/dns) | 5958 | 177 | 2010/08/03 | 2 hours ago | Go library for working with DNS. |
| [gnet](https://github.com/panjf2000/gnet) | 5870 | 153 | 2019/02/24 | 29 minutes ago | `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go. |
| [gopacket](https://github.com/google/gopacket) | 4571 | 141 | 2015/03/16 | 2 weeks ago | Go library for packet processing with libpcap bindings. |
| [httplab](https://github.com/qustavo/httplab) | 3755 | 63 | 2017/02/08 | 2 years ago | HTTPLabs let you inspect HTTP requests and forge responses. |
| [kcp-go](https://github.com/xtaci/kcp-go) | 3184 | 151 | 2015/06/16 | 2 months ago | KCP - Fast and Reliable ARQ Protocol. |
| [gobgp](https://github.com/osrg/gobgp) | 2369 | 118 | 2014/09/14 | 6 hours ago | BGP implemented in the Go Programming Language. |
| [ssh](https://github.com/gliderlabs/ssh) | 2265 | 55 | 2016/10/03 | 1 month ago | Higher-level API for building SSH servers (wraps crypto/ssh). |
| [fortio](https://github.com/fortio/fortio) | 2213 | 46 | 2017/10/10 | 3 days ago | Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC. |
| [water](https://github.com/songgao/water) | 1349 | 45 | 2013/03/25 | 8 months ago | Simple TUN/TAP library. |
| [gev](https://github.com/Allenxuxu/gev) | 1316 | 40 | 2019/09/01 | 3 weeks ago | gev is a lightweight, fast non-blocking TCP network library based on Reactor mode. |
| [go-getter](https://github.com/hashicorp/go-getter) | 1275 | 250 | 2015/10/12 | 5 days ago | Go library for downloading files or directories from various sources using a URL. |
| [nff-go](https://github.com/intel-go/nff-go) | 1142 | 79 | 2017/03/29 | 3 months ago | Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF). |
| [sftp](https://github.com/pkg/sftp) | 1077 | 54 | 2013/11/05 | 4 days ago | Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt. |
| [grab](https://github.com/cavaliergopher/grab) | 959 | 17 | 2016/01/05 | 2 weeks ago | Go package for managing file downloads. |
| [ftp](https://github.com/jlaffaye/ftp) | 869 | 26 | 2011/05/06 | 1 month ago | Package ftp implements a FTP client as described in [RFC 959](https://tools.ietf.org/html/rfc959). |
| [mdns](https://github.com/hashicorp/mdns) | 833 | 253 | 2014/01/29 | 1 month ago | Simple mDNS (Multicast DNS) client/server library in Golang. |
| [gosnmp](https://github.com/gosnmp/gosnmp) | 786 | 48 | 2012/08/27 | 1 month ago | Native Go library for performing SNMP actions. |
| [vssh](https://github.com/yahoo/vssh) | 758 | 20 | 2020/06/09 | 1 year ago | Go library for building network and server automation over SSH protocol. |
| [cidranger](https://github.com/yl2chen/cidranger) | 656 | 17 | 2017/08/21 | 1 month ago | Fast IP to CIDR lookup for Go. |
| [lhttp](https://github.com/fanux/lhttp) | 647 | 59 | 2015/12/29 | 3 years ago | Powerful websocket framework, build your IM server more easily. |
| [gmqtt](https://github.com/DrmagicE/gmqtt) | 538 | 28 | 2018/09/16 | 1 week ago | Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1. |
| [peerdiscovery](https://github.com/schollz/peerdiscovery) | 516 | 19 | 2018/04/22 | 1 week ago | Pure Go library for cross-platform local peer discovery using UDP multicast. |
| [gotcp](https://github.com/gansidui/gotcp) | 486 | 39 | 2014/04/13 | 4 years ago | Go package for quickly writing tcp applications. |
| [stun](https://github.com/gortc/stun) | 474 | 21 | 2016/04/24 | 7 months ago | Go implementation of RFC 5389 STUN protocol. |
| [go-stun](https://github.com/ccding/go-stun) | 464 | 15 | 2013/08/17 | 8 months ago | Go implementation of the STUN client (RFC 3489 and RFC 5389). |
| [gopcap](https://github.com/akrennmair/gopcap) | 436 | 23 | 2009/11/19 | 7 months ago | Go wrapper for libpcap. |
| [nbio](https://github.com/lesismal/nbio) | 430 | 12 | 2020/01/25 | 5 days ago | Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use. |
| [raw](https://github.com/mdlayher/raw) | 412 | 13 | 2015/07/06 | 1 month ago | Package raw enables reading and writing data at the device driver level for a network interface. |
| [gaio](https://github.com/xtaci/gaio) | 409 | 17 | 2019/12/20 | 3 months ago | High performance async-io networking for Golang in proactor mode. |
| [tcp_server](https://github.com/firstrow/tcp_server) | 403 | 19 | 2014/10/13 | 1 month ago | Go library for building tcp servers faster. |
| [winrm](https://github.com/masterzen/winrm) | 342 | 18 | 2013/12/30 | 1 week ago | Go WinRM client to remotely execute commands on Windows machines. |
| [ftpserverlib](https://github.com/fclairamb/ftpserverlib) | 275 | 12 | 2016/09/25 | 1 month ago | Fully featured FTP server library. |
| [arp](https://github.com/mdlayher/arp) | 267 | 10 | 2015/07/06 | 2 years ago | Package arp implements the ARP protocol, as described in RFC 826. |
| [buffstreams](https://github.com/StabbyCutyou/buffstreams) | 246 | 14 | 2015/06/29 | 1 year ago | Streaming protocolbuffer data over TCP made easy. |
| [ethernet](https://github.com/mdlayher/ethernet) | 235 | 12 | 2015/07/03 | 2 years ago | Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. |
| [easytcp](https://github.com/DarthPestilane/easytcp) | 218 | 1 | 2021/04/26 | 3 weeks ago | A light-weight TCP framework written in Go (Golang), built with message router. EasyTCP helps you build a TCP server easily fast and less painful. |
| [gnxi](https://github.com/google/gnxi) | 198 | 32 | 2017/09/26 | 5 days ago | A collection of tools for Network Management that use the gNMI and gNOI protocols. |
| [jazigo](https://github.com/udhos/jazigo) | 172 | 14 | 2016/06/07 | 2 years ago | Jazigo is a tool written in Go for retrieving configuration for multiple network devices. |
| [utp](https://github.com/anacrolix/utp) | 161 | 19 | 2015/03/20 | 11 months ago | Go uTP micro transport protocol implementation. |
| [canopus](https://github.com/zubairhamed/canopus) | 147 | 14 | 2015/02/24 | 3 years ago | CoAP Client/Server implementation (RFC 7252). |
| [sslb](https://github.com/eduardonunesp/sslb) | 134 | 9 | 2015/10/18 | 2 years ago | It's a Super Simples Load Balancer, just a little project to achieve some kind of performance. |
| [xtcp](https://github.com/xfxdev/xtcp) | 129 | 14 | 2016/03/31 | 1 year ago | TCP Server Framework with simultaneous full duplex communication, graceful shutdown, and custom protocol. |
| [dnsmonster](https://github.com/mosajjal/dnsmonster) | 117 | 8 | 2020/02/09 | 2 days ago | Passive DNS Capture/Monitoring Framework. |
| [dhcp6](https://github.com/mdlayher/dhcp6) | 71 | 4 | 2015/05/22 | 2 years ago | Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. |
| [ether](https://github.com/songgao/ether) | 71 | 4 | 2014/05/21 | 5 years ago | Cross-platform Go package for sending and receiving ethernet frames. |
| [packet](https://github.com/aerogo/packet) | 60 | 5 | 2017/10/29 | 2 years ago | Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed. |
| [linkio](https://github.com/ian-kent/linkio) | 49 | 2 | 2014/12/24 | 4 years ago | Network link speed simulation for Reader/Writer interfaces. |
| [go-powerdns](https://github.com/joeig/go-powerdns) | 47 | 4 | 2018/06/21 | 1 month ago | PowerDNS API bindings for Golang. |
| [portproxy](https://github.com/aybabtme/portproxy) | 46 | 0 | 2014/12/13 | 7 years ago | Simple TCP proxy which adds CORS support to API's which don't support it. |
| [panoptes-stream](https://github.com/yahoo/panoptes-stream) | 30 | 8 | 2020/10/09 | 9 months ago | A cloud native distributed streaming network telemetry (gNMI, Juniper JTI and Cisco MDT). |
| [graval](https://github.com/koofr/graval) | 27 | 8 | 2014/04/22 | 1 year ago | Experimental FTP server framework. |
| [publicip](https://github.com/polera/publicip) | 24 | 4 | 2016/12/28 | 5 years ago | Package publicip returns your public facing IPv4 address (internet egress). |
| [golibwireshark](https://github.com/sunwxg/golibwireshark) | 21 | 2 | 2015/11/16 | 4 years ago | Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data. |
| [gohooks](https://github.com/averageflow/gohooks) | 14 | 1 | 2020/10/30 | 5 months ago | GoHooks make it easy to send and consume secured web-hooks from a Go application. Inspired by Spatie's Laravel Webhook Client and Server. |
| [goshark](https://github.com/sunwxg/goshark) | 14 | 1 | 2015/11/01 | 4 years ago | Package goshark use tshark to decode IP packet and create data struct to analyse packet. |
| [llb](https://github.com/kirillDanshin/llb) | 11 | 1 | 2016/02/21 | 5 years ago | It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response. |
| [httpproxy](https://github.com/wzshiming/httpproxy) | 10 | 2 | 2018/07/18 | 1 month ago | HTTP proxy handler and dialer. |
| [tspool](https://github.com/two/tspool) | 10 | 1 | 2018/10/27 | 3 years ago | A TCP Library use worker pool to improve performance and protect your server. |
**[⬆ back to top](#awesome-go-info)**

### HTTP Clients
        
*Libraries for making HTTP requests.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [resty](https://github.com/go-resty/resty) | 5426 | 92 | 2015/08/28 | 1 week ago | Simple HTTP and REST client for Go inspired by Ruby rest-client. |
| [heimdall](https://github.com/gojek/heimdall) | 2135 | 52 | 2018/01/19 | 2 months ago | An enhanced http client with retry and hystrix capabilities. |
| [grequests](https://github.com/levigross/grequests) | 1844 | 35 | 2015/06/11 | 1 year ago | A Go "clone" of the great and famous Requests library. |
| [sling](https://github.com/dghubble/sling) | 1396 | 29 | 2015/04/02 | 2 months ago | Sling is a Go HTTP client library for creating and sending API requests. |
| [gentleman](https://github.com/h2non/gentleman) | 928 | 20 | 2016/02/21 | 10 months ago | Full-featured plugin-driven HTTP client library. |
| [pester](https://github.com/sethgrid/pester) | 565 | 6 | 2015/05/20 | 1 year ago | Go HTTP client calls with retries, backoff, and concurrency. |
| [requests](https://github.com/carlmjohnson/requests) | 208 | 7 | 2021/05/20 | 1 day ago | HTTP requests for Gophers. Uses context.Context and doesn't hide the underlying net/http.Client, making it compatible with standard Go APIs. Also includes testing tools. |
| [request](https://github.com/monaco-io/request) | 156 | 10 | 2020/03/25 | 13 hours ago | HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency. |
| [rq](https://github.com/ddo/rq) | 38 | 3 | 2017/12/26 | 2 years ago | A nicer interface for golang stdlib HTTP client. |
| [go-http-client](https://github.com/bozd4g/go-http-client) | 32 | 2 | 2019/12/14 | 7 months ago | Make http calls simply and easily. |
| [httpretry](https://github.com/ybbus/httpretry) | 14 | 2 | 2020/02/05 | 1 year ago | Enriches the default go HTTP client with retry functionality. |
| [go-req](https://github.com/wenerme/go-req) | 12 | 1 | 2021/07/11 | 3 months ago | Declarative golang HTTP client. |
| [httpc](https://github.com/valord577/httpc) | 2 | 1 | 2021/08/11 | 1 month ago | A customizable and simple HTTP client library. Only depend on the stdlib HTTP client. |
**[⬆ back to top](#awesome-go-info)**

## ORM
        
*Libraries that implement Object-Relational Mapping or datamapping techniques.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [beego](https://github.com/beego/beego) | 27459 | 1231 | 2012/02/29 | 1 week ago | Powerful orm framework for go. Support: pq/mysql/sqlite3. |
| [gorm](https://github.com/go-gorm/gorm) | 26305 | 496 | 2013/10/25 | 6 hours ago | The fantastic ORM library for Golang, aims to be developer friendly. |
| [ent](https://github.com/ent/ent) | 9501 | 138 | 2019/06/12 | 4 hours ago | An entity framework for Go. Simple, yet powerful ORM for modeling and querying data. |
| [pg](https://github.com/go-pg/pg) | 4934 | 87 | 2013/04/24 | 1 week ago | PostgreSQL ORM with focus on PostgreSQL specific features and performance. |
| [sqlboiler](https://github.com/volatiletech/sqlboiler) | 4525 | 80 | 2016/02/21 | 1 week ago | ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema. |
| [gorp](https://github.com/go-gorp/gorp) | 3535 | 111 | 2012/01/04 | 9 months ago | Go Relational Persistence, ORM-ish library for Go. |
| [db](https://github.com/upper/db) | 2840 | 63 | 2013/10/23 | 2 weeks ago | Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. |
| [gormt](https://github.com/xxjwxc/gormt) | 1605 | 21 | 2019/05/05 | 4 days ago | Mysql database to golang gorm struct. |
| [reform](https://github.com/go-reform/reform) | 1213 | 24 | 2016/02/25 | 3 weeks ago | Better ORM for Go, based on non-empty interfaces and code generation. |
| [pop](https://github.com/gobuffalo/pop) | 1151 | 25 | 2018/02/07 | 1 week ago | Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. |
| [prisma-client-go](https://github.com/prisma/prisma-client-go) | 1085 | 22 | 2019/09/24 | 2 days ago | Prisma Client Go, Typesafe database access for Go. |
| [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) | 681 | 13 | 2017/12/27 | 2 weeks ago | A flexible and powerful SQL string builder library plus a zero-config ORM. |
| [go-queryset](https://github.com/jirfag/go-queryset) | 645 | 24 | 2017/09/03 | 5 months ago | 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM. |
| [rel](https://github.com/go-rel/rel) | 463 | 10 | 2019/10/06 | 1 month ago | Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API. |
| [zoom](https://github.com/albrow/zoom) | 283 | 20 | 2013/07/17 | 1 year ago | Blazing-fast datastore and querying engine built on Redis. |
| [grimoire](https://github.com/Fs02/grimoire) | 156 | 6 | 2018/03/05 | 2 months ago | Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3). |
| [gosql](https://github.com/rushteam/gosql) | 149 | 7 | 2020/04/27 | 6 months ago | A easy ORM for mysql. |
| [go-store](https://github.com/gosuri/go-store) | 106 | 9 | 2015/03/22 | 4 years ago | Simple and fast Redis backed key-value store library for Go. |
| [go-firestorm](https://github.com/jschoedt/go-firestorm) | 26 | 1 | 2018/12/04 | 2 weeks ago | A simple ORM for Google/Firebase Cloud Firestore. |
| [cacheme-go](https://github.com/Yiling-J/cacheme-go) | 17 | 1 | 2021/10/03 | 1 week ago | Schema based, typed Redis caching/memoize framework for Go. |
| [lore](https://github.com/abrahambotros/lore) | 10 | 1 | 2017/04/29 | 4 years ago | Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go. |
| [marlow](https://github.com/marlow/marlow) | 9 | 3 | 2020/08/11 | 1 year ago | Generated ORM from project structs for compile time safety assurances. |
**[⬆ back to top](#awesome-go-info)**

## OpenGL
        
*Libraries for using OpenGL in Go.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [glfw](https://github.com/go-gl/glfw) | 1193 | 38 | 2013/05/19 | 2 weeks ago | Go bindings for GLFW 3. |
| [gl](https://github.com/go-gl/gl) | 855 | 40 | 2015/02/22 | 2 weeks ago | Go bindings for OpenGL (generated via glow). |
| [mathgl](https://github.com/go-gl/mathgl) | 402 | 28 | 2013/02/13 | 1 year ago | Pure Go math package specialized for 3D math, with inspiration from GLM. |
| [gl](https://github.com/goxjs/gl) | 153 | 15 | 2015/05/18 | 11 months ago | Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). |
| [glfw](https://github.com/goxjs/glfw) | 71 | 7 | 2014/12/27 | 1 year ago | Go cross-platform glfw library for creating an OpenGL context and receiving events. |
| [go-glmatrix](https://github.com/technohippy/go-glmatrix) | 2 | 1 | 2020/07/02 | 10 months ago | Go port of [glMatrix](https://glmatrix.net/) library. |
**[⬆ back to top](#awesome-go-info)**

## Package Management
        
*Unofficial libraries for package and dependency management.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [dep](https://github.com/golang/dep) | 13102 | 260 | 2016/10/07 | 1 year ago | Go dependency tool. |
| [glide](https://github.com/Masterminds/glide) | 8143 | 189 | 2014/07/09 | 10 months ago | Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip. |
| [godep](https://github.com/tools/godep) | 5610 | 149 | 2013/05/01 | 3 years ago | dependency tool for go, godep helps build packages reproducibly by fixing their dependencies. |
| [govendor](https://github.com/kardianos/govendor) | 4989 | 97 | 2015/04/12 | 1 year ago | Go Package Manager. Go vendor tool that works with the standard vendor file. |
| [gopm](https://github.com/gpmgo/gopm) | 2493 | 86 | 2013/05/15 | 2 years ago | Go Package Manager. |
| [gom](https://github.com/mattn/gom) | 1397 | 35 | 2013/09/11 | 2 years ago | Go Manager - bundle for go. |
| [gpm](https://github.com/pote/gpm) | 1199 | 32 | 2013/09/05 | 4 years ago | Barebones dependency manager for Go. |
| [goop](https://github.com/petejkim/goop) | 779 | 36 | 2014/06/18 | 6 years ago | Simple dependency manager for Go (golang), inspired by Bundler. |
| [modgv](https://github.com/lucasepe/modgv) | 399 | 7 | 2020/09/12 | 1 year ago | Converts 'go mod graph' output into Graphviz's DOT language. |
| [nut](https://github.com/owenthereal/nut) | 239 | 6 | 2015/01/23 | 6 years ago | Vendor Go dependencies. |
| [johnny-deps](https://github.com/VividCortex/johnny-deps) | 212 | 21 | 2013/07/19 | 1 year ago | Minimal dependency version using Git. |
| [mvn-golang](https://github.com/raydac/mvn-golang) | 132 | 11 | 2016/03/24 | 1 week ago | plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure. |
| [VenGO](https://github.com/DamnWidget/VenGO) | 120 | 9 | 2014/10/17 | 5 years ago | create and manage exportable isolated go virtual environments. |
| [gop](https://github.com/lunny/gop) | 48 | 8 | 2017/02/18 | 2 years ago | Build and manage your Go applications out of GOPATH. |
**[⬆ back to top](#awesome-go-info)**

## Performance
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [jaeger](https://github.com/jaegertracing/jaeger) | 14882 | 346 | 2016/04/15 | 5 days ago | A distributed tracing system. |
| [pixie](https://github.com/pixie-io/pixie) | 2672 | 63 | 2020/02/27 | 2 days ago | No instrumentation tracing for Golang applications via eBPF. |
| [statsviz](https://github.com/arl/statsviz) | 1748 | 21 | 2020/08/14 | 2 weeks ago | Live visualization of your Go application runtime statistics. |
| [profile](https://github.com/pkg/profile) | 1641 | 40 | 2014/10/22 | 1 month ago | Simple profiling support package for Go. |
| [tracer](https://github.com/kamilsk/tracer) | 61 | 4 | 2019/06/22 | 10 months ago | Simple, lightweight tracing. |
**[⬆ back to top](#awesome-go-info)**

## Query Language
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [graphql](https://github.com/graphql-go/graphql) | 8191 | 152 | 2015/07/19 | 1 month ago | Implementation of GraphQL for Go. |
| [gqlgen](https://github.com/99designs/gqlgen) | 6903 | 152 | 2018/02/11 | 23 hours ago | go generate based graphql server library. |
| [graphql-go](https://github.com/graph-gophers/graphql-go) | 4009 | 88 | 2016/10/18 | 3 hours ago | GraphQL server with a focus on ease of use. |
| [gojsonq](https://github.com/thedevsaddam/gojsonq) | 1797 | 33 | 2018/05/19 | 4 months ago | A simple Go package to Query over JSON Data. |
| [dasel](https://github.com/TomWright/dasel) | 1731 | 10 | 2020/09/22 | 6 days ago | Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies. |
| [jsonql](https://github.com/elgs/jsonql) | 248 | 11 | 2015/12/29 | 1 year ago | JSON query expression library in Golang. |
| [rql](https://github.com/a8m/rql) | 241 | 10 | 2018/06/05 | 3 weeks ago | Resource Query Language for REST API. |
| [jsonslice](https://github.com/bhmj/jsonslice) | 59 | 0 | 2018/05/02 | 1 month ago | Jsonpath queries with advanced filters. |
| [graphql](https://github.com/tmc/graphql) | 54 | 11 | 2015/04/18 | 4 years ago | graphql parser + utilities. |
| [api-fu](https://github.com/ccbrown/api-fu) | 37 | 2 | 2019/07/30 | 1 week ago | Comprehensive GraphQL implementation. |
| [straf](https://github.com/SonicRoshan/straf) | 32 | 1 | 2019/08/16 | 1 year ago | Easily Convert Golang structs to GraphQL objects. |
| [rest-query-parser](https://github.com/timsolov/rest-query-parser) | 29 | 2 | 2020/02/10 | 1 month ago | Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query. |
| [jsonpath](https://github.com/AsaiYusuke/jsonpath) | 9 | 2 | 2020/11/29 | 1 month ago | A query library for retrieving part of JSON based on JSONPath syntax. |
| [gws](https://github.com/Zaba505/gws) | 4 | 1 | 2020/06/08 | 1 year ago | Apollos' "GraphQL over Websocket" client and server implementation. |
**[⬆ back to top](#awesome-go-info)**

## Resource Embedding
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [statik](https://github.com/rakyll/statik) | 3353 | 51 | 2014/02/04 | 1 year ago | Embeds static files into a Go executable. |
| [packr](https://github.com/gobuffalo/packr) | 3331 | 48 | 2017/03/15 | 3 weeks ago | The simple and easy way to embed static files into Go binaries. |
| [go.rice](https://github.com/GeertJohan/go.rice) | 2266 | 55 | 2013/10/23 | 2 months ago | go.rice is a Go package that makes working with resources such as HTML, JS, CSS, images, and templates very easy. |
| [vfsgen](https://github.com/shurcooL/vfsgen) | 937 | 20 | 2015/05/18 | 1 year ago | Generates a vfsdata.go file that statically implements the given virtual filesystem. |
| [esc](https://github.com/mjibson/esc) | 605 | 15 | 2014/01/26 | 2 years ago | Embeds files into Go programs and provides http.FileSystem interfaces to them. |
| [fileb0x](https://github.com/UnnoTed/fileb0x) | 602 | 18 | 2016/01/23 | 10 months ago | Simple tool to embed files in go with focus on "customization" and ease to use. |
| [go-resources](https://github.com/omeid/go-resources) | 173 | 9 | 2015/02/21 | 7 months ago | Unfancy resources embedding with Go. |
| [statics](https://github.com/go-playground/statics) | 64 | 3 | 2015/10/07 | 5 years ago | Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks. |
| [templify](https://github.com/wlbr/templify) | 26 | 3 | 2016/05/22 | 4 months ago | Embed external template files into Go code to create single file binaries. |
| [rebed](https://github.com/soypat/rebed) | 19 | 2 | 2021/02/17 | 9 months ago | Recreate folder structures and files from Go 1.16's `embed. |
| [debme](https://github.com/leaanthony/debme) | 12 | 1 | 2021/04/16 | 6 months ago | Create an `embed.FS` from an existing `embed.FS` subdirectory. |
| [mule](https://github.com/wlbr/mule) | 9 | 2 | 2020/01/17 | 4 months ago | Embed external resources like images, movies ... into Go source code to create single file binaries using `go generate`. Focussed on simplicity. |
**[⬆ back to top](#awesome-go-info)**

## Science and Data Analysis
        
*Libraries for scientific computing and data analyzing.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gonum](https://github.com/gonum/gonum) | 5402 | 114 | 2017/03/25 | 1 week ago | Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more. |
| [stats](https://github.com/montanaflynn/stats) | 2202 | 52 | 2014/12/16 | 1 month ago | Statistics package with common functions missing from the Golang standard library. |
| [plot](https://github.com/gonum/plot) | 2069 | 57 | 2013/07/23 | 3 months ago | gonum/plot provides an API for building and drawing plots in Go. |
| [gosl](https://github.com/cpmech/gosl) | 1631 | 72 | 2015/02/09 | 1 month ago | Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more. |
| [streamtools](https://github.com/nytlabs/streamtools) | 1317 | 70 | 2013/07/05 | 6 years ago | general purpose, graphical tool for dealing with streams of data. |
| [go-dsp](https://github.com/mjibson/go-dsp) | 761 | 29 | 2011/11/02 | 3 years ago | Digital Signal Processing for Go. |
| [chart](https://github.com/vdobler/chart) | 707 | 44 | 2011/06/27 | 6 months ago | Simple Chart Plotting library for Go. Supports many graphs types. |
| [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) | 704 | 32 | 2018/10/01 | 2 months ago | Dataframes for machine-learning and statistics (similar to pandas). |
| [goraph](https://github.com/gyuho/goraph) | 652 | 39 | 2014/02/27 | 4 years ago | Pure Go graph theory library(data structure, algorithm visualization). |
| [graph](https://github.com/yourbasic/graph) | 511 | 21 | 2017/04/27 | 3 months ago | Library of basic graph algorithms. |
| [orb](https://github.com/paulmach/orb) | 455 | 24 | 2016/03/28 | 1 month ago | 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support. |
| [ewma](https://github.com/VividCortex/ewma) | 342 | 24 | 2013/07/05 | 4 months ago | Exponentially-weighted moving averages. |
| [calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) | 332 | 9 | 2020/07/01 | 2 months ago | Calendar heatmap in plain Go inspired by Github contribution activity. |
| [gohistogram](https://github.com/VividCortex/gohistogram) | 158 | 17 | 2013/07/02 | 1 year ago | Approximate histograms for data streams. |
| [TextRank](https://github.com/DavidBelicza/TextRank) | 147 | 8 | 2018/01/09 | 5 months ago | TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support. |
| [sparse](https://github.com/james-bowman/sparse) | 123 | 8 | 2017/05/16 | 5 months ago | Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries. |
| [go-estimate](https://github.com/milosgajdos/go-estimate) | 87 | 5 | 2018/11/04 | 4 months ago | State estimation and filtering algorithms in Go. |
| [pagerank](https://github.com/alixaxel/pagerank) | 72 | 8 | 2015/08/06 | 6 months ago | Weighted PageRank algorithm implemented in Go. |
| [jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) | 53 | 2 | 2021/06/26 | 1 month ago | Tool to manipulate JSONL graphs with graphviz support. |
| [geom](https://github.com/skelterjohn/geom) | 48 | 5 | 2011/06/07 | 4 years ago | 2D geometry for golang. |
| [evaler](https://github.com/soniah/evaler) | 45 | 5 | 2012/09/04 | 3 years ago | Simple floating point arithmetic expression evaluator. |
| [goent](https://github.com/kzahedi/goent) | 25 | 1 | 2017/08/08 | 2 years ago | GO Implementation of Entropy Measures. |
| [decimal](https://github.com/db47h/decimal) | 23 | 4 | 2020/05/27 | 1 year ago | Package decimal implements arbitrary-precision decimal floating-point arithmetic. |
| [triangolatte](https://github.com/tchayen/triangolatte) | 23 | 2 | 2018/07/18 | 4 months ago | 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs. |
| [piecewiselinear](https://github.com/sgreben/piecewiselinear) | 20 | 4 | 2018/10/21 | 1 year ago | Tiny linear interpolation library. |
| [GoStats](https://github.com/OGFris/GoStats) | 18 | 3 | 2018/07/22 | 2 years ago | GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions. |
| [godesim](https://github.com/soypat/godesim) | 17 | 2 | 2020/12/16 | 1 month ago | Extended/multivariable ODE solver framework for event-based simulations with simple API. |
| [PiHex](https://github.com/claygod/PiHex) | 14 | 3 | 2016/07/22 | 1 year ago | Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi. |
| [ode](https://github.com/ChristopherRabotin/ode) | 13 | 5 | 2016/11/11 | 4 years ago | Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions. |
| [rootfinding](https://github.com/khezen/rootfinding) | 6 | 5 | 2018/10/30 | 1 year ago | root-finding algorithms library for finding roots of quadratic functions. |
| [assocentity](https://github.com/ndabAP/assocentity) | 5 | 2 | 2018/12/21 | 1 year ago | Package assocentity returns the average distance from words to a given entity. |
| [go-gt](https://github.com/ThePaw/go-gt) | 5 | 0 | 2015/09/14 | 6 years ago | Graph theory algorithms written in "Go" language. |
| [bradleyterry](https://github.com/seanhagen/bradleyterry) | 4 | 2 | 2019/04/30 | 2 years ago | Provides a Bradley-Terry Model for pairwise comparisons. |
**[⬆ back to top](#awesome-go-info)**

## Security
        
*Libraries that are used to help make your application more secure.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [age](https://github.com/FiloSottile/age) | 9510 | 115 | 2019/05/18 | 18 hours ago | A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability. |
| [lego](https://github.com/go-acme/lego) | 5001 | 96 | 2015/06/08 | 2 days ago | Pure Go ACME client library and CLI tool (for use with Let's Encrypt). |
| [certmagic](https://github.com/caddyserver/certmagic) | 3874 | 53 | 2018/12/10 | 16 hours ago | Mature, robust, and powerful ACME client integration for fully-managed TLS certificate issuance and renewal. |
| [cameradar](https://github.com/Ullaakut/cameradar) | 2782 | 129 | 2016/05/20 | 1 month ago | Tool and library to remotely hack RTSP streams from surveillance cameras. |
| [memguard](https://github.com/awnumar/memguard) | 2036 | 49 | 2017/04/22 | 9 months ago | A pure Go library for handling sensitive values in memory. |
| [acmetool](https://github.com/hlandau/acmetool) | 1886 | 63 | 2015/11/15 | 9 months ago | ACME (Let's Encrypt) client tool with automatic renewal. |
| [secure](https://github.com/unrolled/secure) | 1859 | 36 | 2014/05/20 | 1 month ago | HTTP middleware for Go that facilitates some quick security wins. |
| [themis](https://github.com/cossacklabs/themis) | 1400 | 41 | 2015/05/06 | 5 days ago | high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps. |
| [acra](https://github.com/cossacklabs/acra) | 897 | 41 | 2016/11/14 | 23 hours ago | Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system. |
| [nacl](https://github.com/kevinburke/nacl) | 517 | 13 | 2017/07/20 | 8 months ago | Go implementation of the NaCL set of API's. |
| [ssh-vault](https://github.com/ssh-vault/ssh-vault) | 331 | 10 | 2016/09/29 | 5 months ago | encrypt/decrypt using ssh keys. |
| [firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) | 312 | 10 | 2020/06/12 | 1 year ago | A rest application to dynamically update firewalld rules on a linux server. |
| [go-password-validator](https://github.com/wagslane/go-password-validator) | 309 | 9 | 2020/10/14 | 1 week ago | Password validator based on raw cryptographic entropy values. |
| [badactor](https://github.com/jaredfolkins/badactor) | 303 | 8 | 2014/12/12 | 1 year ago | In-memory, application-driven jailer built in the spirit of fail2ban. |
| [optimus-go](https://github.com/pjebs/optimus-go) | 294 | 5 | 2015/05/05 | 1 year ago | ID hashing and Obfuscation using Knuth's Algorithm. |
| [passlib](https://github.com/hlandau/passlib) | 259 | 11 | 2014/12/21 | 9 months ago | Futureproof password hashing library. |
| [go-yara](https://github.com/hillu/go-yara) | 239 | 20 | 2015/01/25 | 2 days ago | Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)". |
| [simple-scrypt](https://github.com/elithrar/simple-scrypt) | 173 | 7 | 2015/04/14 | 8 months ago | Scrypt package with a simple, obvious API and automatic cost calibration built-in. |
| [argon2pw](https://github.com/raja/argon2pw) | 88 | 4 | 2018/03/13 | 3 months ago | Argon2 password hash generation with constant-time password comparison. |
| [dongle](https://github.com/golang-module/dongle) | 67 | 1 | 2021/08/11 | 4 months ago | A simple, semantic and developer-friendly golang package for encoding&decoding and encryption&decryption. |
| [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) | 44 | 2 | 2017/10/19 | 1 year ago | A probably paranoid package for securely hashing and encrypting passwords. |
| [go-generate-password](https://github.com/m1/go-generate-password) | 29 | 2 | 2019/11/14 | 4 months ago | Password generator that can be used on the cli or as a library. |
| [secureio](https://github.com/xaionaro-go/secureio) | 22 | 3 | 2018/12/25 | 1 year ago | An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519. |
| [certificates](https://github.com/mvmaasakkers/certificates) | 21 | 0 | 2019/03/04 | 1 year ago | An opinionated tool for generating tls certificates. |
| [go-htpasswd](https://github.com/tg123/go-htpasswd) | 17 | 1 | 2015/06/18 | 2 months ago | Apache htpasswd Parser for Go. |
| [argon2-hashing](https://github.com/andskur/argon2-hashing) | 14 | 2 | 2019/01/02 | 1 year ago | light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package. |
| [goArgonPass](https://github.com/dwin/goArgonPass) | 13 | 2 | 2018/05/30 | 1 year ago | Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations. |
| [sslmgr](https://github.com/adrianosela/sslmgr) | 11 | 2 | 2019/04/02 | 2 years ago | SSL certificates made easy with a high level wrapper around acme/autocert. |
**[⬆ back to top](#awesome-go-info)**

## Serialization
        
*Libraries and tools for binary serialization.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go](https://github.com/json-iterator/go) | 10289 | 234 | 2016/11/30 | 1 month ago | High-performance 100% compatible drop-in replacement of "encoding/json". |
| [protobuf](https://github.com/golang/protobuf) | 8134 | 211 | 2014/11/23 | 3 months ago | Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers. |
| [mapstructure](https://github.com/mitchellh/mapstructure) | 5234 | 71 | 2013/05/20 | 5 days ago | Go library for decoding generic map values into native Go structures. |
| [protobuf](https://github.com/gogo/protobuf) | 5014 | 105 | 2014/12/03 | 1 month ago | Protocol Buffers for Go with Gadgets. |
| [go](https://github.com/ugorji/go) | 1615 | 55 | 2013/05/30 | 1 month ago | High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support. |
| [colfer](https://github.com/pascaldekloe/colfer) | 644 | 33 | 2015/09/05 | 3 months ago | Code generation for the Colfer binary format. |
| [csvutil](https://github.com/jszwec/csvutil) | 639 | 10 | 2017/10/30 | 1 month ago | High Performance, idiomatic CSV record encoding and decoding to native Go structures. |
| [cbor](https://github.com/fxamacker/cbor) | 358 | 9 | 2019/05/15 | 1 day ago | Small, safe, and easy CBOR encoding and decoding library. |
| [go-capnproto](https://github.com/glycerine/go-capnproto) | 279 | 11 | 2013/11/07 | 1 year ago | Cap'n Proto library and parser for go. |
| [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) | 152 | 10 | 2012/12/23 | 3 years ago | GoLang library for working with PHP session format and PHP Serialize/Unserialize functions. |
| [structomap](https://github.com/danhper/structomap) | 130 | 7 | 2015/05/13 | 2 years ago | Library to easily and dynamically generate maps from static structures. |
| [bambam](https://github.com/glycerine/bambam) | 62 | 3 | 2014/09/17 | 5 years ago | generator for Cap'n Proto schemas from go. |
| [asn1](https://github.com/Logicalis/asn1) | 47 | 9 | 2016/02/29 | 2 years ago | Asn.1 BER and DER encoding library for golang. |
| [binstruct](https://github.com/ghostiam/binstruct) | 38 | 2 | 2018/10/23 | 1 day ago | Golang binary decoder for mapping data into the structure. |
| [bel](https://github.com/csweichel/bel) | 16 | 2 | 2019/02/20 | 1 year ago | Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC. |
| [fwencoder](https://github.com/o1egl/fwencoder) | 16 | 2 | 2017/12/25 | 1 year ago | Fixed width file parser (encoding and decoding library) for Go. |
| [elastic](https://github.com/epiclabs-io/elastic) | 15 | 1 | 2020/02/25 | 7 months ago | Convert slices, maps or any other unknown value across different types at run-time, no matter what. |
| [pletter](https://github.com/vimeda/pletter) | 14 | 6 | 2019/07/09 | 3 months ago | A standard way to wrap a proto message for message brokers. |
| [fixedwidth](https://github.com/huydang284/fixedwidth) | 5 | 1 | 2019/08/11 | 2 years ago | Fixed-width text formatting (UTF-8 supported). |
| [unitpacking](https://github.com/recolude/unitpacking) | 3 | 2 | 2021/01/17 | 8 months ago | Library to pack unit vectors into as fewest bytes as possible. |
| [go-lctree](https://github.com/sbourlon/go-lctree) | 2 | 1 | 2020/05/04 | 1 year ago | Provides a CLI and primitives to serialize and deserialize [LeetCode binary trees](https://support.leetcode.com/hc/en-us/articles/360011883654-What-does-1-null-2-3-mean-in-binary-tree-representation). |
**[⬆ back to top](#awesome-go-info)**

## Server Applications
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [etcd](https://github.com/etcd-io/etcd) | 38320 | 1354 | 2013/07/06 | 7 hours ago | Highly-available key value store for shared configuration and service discovery. |
| [caddy](https://github.com/caddyserver/caddy) | 36102 | 759 | 2015/01/13 | 1 hour ago | Caddy is an alternative, HTTP/2 web server that's easy to configure and use. |
| [minio](https://github.com/minio/minio) | 30848 | 589 | 2015/01/14 | 8 hours ago | Minio is a distributed object storage server. |
| [roadrunner](https://github.com/spiral/roadrunner) | 6141 | 157 | 2017/12/26 | 2 days ago | High-performance PHP application server, load-balancer and process manager. |
| [easegress](https://github.com/megaease/easegress) | 4143 | 100 | 2021/05/28 | 6 hours ago | A cloud native high availability/performance traffic orchestration system with observability and extensibility. |
| [sftpgo](https://github.com/drakkan/sftpgo) | 3581 | 70 | 2019/07/20 | 5 hours ago | Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage. |
| [devd](https://github.com/cortesi/devd) | 3188 | 69 | 2015/09/27 | 4 months ago | Local webserver for developers. |
| [algernon](https://github.com/xyproto/algernon) | 1885 | 51 | 2015/03/10 | 1 week ago | HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. |
| [flagr](https://github.com/checkr/flagr) | 1782 | 75 | 2017/10/03 | 2 months ago | Flagr is an open-source feature flagging and A/B testing service. |
| [fider](https://github.com/getfider/fider) | 1781 | 35 | 2017/01/17 | 4 days ago | Fider is an open platform to collect and organize customer feedback. |
| [flipt](https://github.com/markphelps/flipt) | 1626 | 15 | 2016/11/05 | 17 hours ago | A self contained feature flag solution written in Go and Vue. |
| [trickster](https://github.com/trickstercache/trickster) | 1595 | 43 | 2018/03/29 | 1 month ago | HTTP reverse proxy cache and time series accelerator. |
| [discovery](https://github.com/bilibili/discovery) | 1573 | 61 | 2018/04/20 | 1 month ago | A registry for resilient mid-tier load balancing and failover. |
| [jackal](https://github.com/ortuman/jackal) | 1176 | 39 | 2017/11/13 | 8 hours ago | An XMPP server written in Go. |
| [go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) | 381 | 1 | 2020/12/11 | 3 weeks ago | A feature flag solution, with only a YAML file in the backend (S3, GitHub, HTTP, local file ...), no server to install, just add a file in a central system and refer to it. |
| [euterpe](https://github.com/ironsmile/euterpe) | 363 | 8 | 2014/01/01 | 2 months ago | Self-hosted music streaming server with built-in web UI and REST API. |
| [dudeldu](https://github.com/krotik/dudeldu) | 131 | 3 | 2016/09/07 | 2 years ago | A simple SHOUTcast server. |
| [lets-proxy2](https://github.com/rekby/lets-proxy2) | 59 | 5 | 2019/04/12 | 3 weeks ago | Reverse proxy for handle https with issue certificates in fly from lets-encrypt. |
| [psql-streamer](https://github.com/blind-oracle/psql-streamer) | 36 | 4 | 2019/04/28 | 1 year ago | Stream database events from PostgreSQL to Kafka. |
| [go-proxy-cache](https://github.com/fabiocicerchia/go-proxy-cache) | 33 | 1 | 2020/11/12 | 2 weeks ago | Simple Reverse Proxy with Caching, written in Go, using Redis. |
| [cortex-tenant](https://github.com/blind-oracle/cortex-tenant) | 28 | 1 | 2020/10/06 | 1 month ago | Prometheus remote write proxy that adds add Cortex tenant ID header based on metric labels. |
| [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) | 27 | 1 | 2018/10/23 | 1 year ago | Nginx log parser and exporter to Prometheus. |
| [simple-jwt-provider](https://github.com/leberKleber/simple-jwt-provider) | 20 | 2 | 2019/12/18 | 1 week ago | Simple and lightweight provider which exhibits JWTs, supports login, password-reset (via mail) and user management. |
| [protoxy](https://github.com/camgraff/protoxy) | 19 | 2 | 2020/09/03 | 1 year ago | A proxy server that converts JSON request bodies to Protocol Buffers. |
| [moxy](https://github.com/sinhashubham95/moxy) | 3 | 1 | 2021/07/17 | 2 weeks ago | Moxy is a simple mocker and proxy application server, you can create mock endpoints as well as proxy requests in case no mock exists for the endpoint. |
| [riemann-relay](https://github.com/blind-oracle/riemann-relay) | 0 | 1 | 2019/04/23 | 2 years ago | Relay to load-balance Riemann events and/or convert them to Carbon. |
**[⬆ back to top](#awesome-go-info)**

## Stream Processing
        
*Libraries and tools for stream processing and reactive programming.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-streams](https://github.com/reugn/go-streams) | 811 | 21 | 2019/04/30 | 3 days ago | Go stream processing library. |
| [machine](https://github.com/whitaker-io/machine) | 101 | 6 | 2020/10/13 | 2 weeks ago | Go library for writing and generating stream workers with built in metrics and traceability. |
| [stream](https://github.com/youthlin/stream) | 50 | 2 | 2020/11/12 | 1 year ago | Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce... |
**[⬆ back to top](#awesome-go-info)**

## Template Engines
        
*Libraries and tools for templating and lexing.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gofpdf](https://github.com/jung-kurt/gofpdf) | 3913 | 104 | 2015/03/13 | 1 month ago | PDF document generator with high level support for text, drawing and images. |
| [sprig](https://github.com/Masterminds/sprig) | 2717 | 34 | 2013/11/22 | 1 week ago | Useful template functions for Go templates. |
| [quicktemplate](https://github.com/valyala/quicktemplate) | 2291 | 59 | 2016/03/06 | 3 months ago | Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it. |
| [pongo2](https://github.com/flosch/pongo2) | 2117 | 63 | 2013/08/23 | 1 day ago | Django-like template-engine for Go. |
| [hero](https://github.com/shiyanhui/hero) | 1485 | 43 | 2017/01/15 | 1 year ago | Hero is a handy, fast and powerful go template engine. |
| [mustache](https://github.com/hoisie/mustache) | 1027 | 36 | 2009/12/30 | 2 weeks ago | Go implementation of the Mustache template language. |
| [amber](https://github.com/eknkc/amber) | 886 | 19 | 2012/10/31 | 1 year ago | Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade. |
| [jet](https://github.com/CloudyKit/jet) | 862 | 23 | 2016/03/31 | 2 months ago | Jet template engine. |
| [ace](https://github.com/yosssi/ace) | 807 | 22 | 2014/07/13 | 3 years ago | Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold. |
| [gorazor](https://github.com/sipin/gorazor) | 792 | 57 | 2014/05/01 | 1 year ago | Razor view engine for Golang. |
| [fasttemplate](https://github.com/valyala/fasttemplate) | 556 | 19 | 2015/08/19 | 11 months ago | Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](https://golang.org/pkg/text/template/). |
| [ego](https://github.com/benbjohnson/ego) | 513 | 14 | 2014/02/23 | 1 month ago | Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled. |
| [maroto](https://github.com/johnfercher/maroto) | 492 | 10 | 2019/05/20 | 2 months ago | A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple. |
| [raymond](https://github.com/aymerick/raymond) | 453 | 11 | 2015/04/22 | 1 month ago | Complete handlebars implementation in Go. |
| [goview](https://github.com/foolin/goview) | 255 | 6 | 2019/04/14 | 1 year ago | Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application. |
| [soy](https://github.com/robfig/soy) | 157 | 13 | 2013/12/15 | 3 months ago | Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/). |
| [liquid](https://github.com/osteele/liquid) | 143 | 6 | 2017/06/26 | 1 week ago | Go implementation of Shopify Liquid templates. |
| [velvet](https://github.com/gobuffalo/velvet) | 73 | 7 | 2016/12/29 | 4 years ago | Complete handlebars implementation in Go. |
| [kasia.go](https://github.com/ziutek/kasia.go) | 72 | 2 | 2010/12/07 | 6 years ago | Templating system for HTML and other text documents - go implementation. |
| [extemplate](https://github.com/dannyvankooten/extemplate) | 41 | 4 | 2018/08/10 | 6 months ago | Tiny wrapper around html/template to allow for easy file-based template inheritance. |
| [gospin](https://github.com/m1/gospin) | 28 | 3 | 2019/02/22 | 7 months ago | Article spinning and spintax/spinning syntax engine, useful for A/B, testing pieces of text/articles and creating more natural conversations. |
| [damsel](https://github.com/dskinner/damsel) | 24 | 4 | 2012/05/02 | 5 years ago | Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others. |
| [tbd](https://github.com/lucasepe/tbd) | 16 | 1 | 2021/05/21 | 4 months ago | A really simple way to create text templates with placeholders - exposes extra builtin Git repo metadata. |
**[⬆ back to top](#awesome-go-info)**

## Testing
        
*Libraries for testing codebases and generating test data.*
**[⬆ back to top](#awesome-go-info)**

### Fail injection
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [failpoint](https://github.com/pingcap/failpoint) | 649 | 104 | 2019/04/02 | 3 months ago | An implementation of [failpoints](https://www.freebsd.org/cgi/man.cgi?query=fail) for Golang. |
**[⬆ back to top](#awesome-go-info)**

### Mock
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [chromedp](https://github.com/chromedp/chromedp) | 7079 | 153 | 2017/01/24 | 2 weeks ago | a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol. |
| [mock](https://github.com/golang/mock) | 6585 | 84 | 2015/06/12 | 4 days ago | Mocking framework for the Go programming language. |
| [go-fuzz](https://github.com/dvyukov/go-fuzz) | 4228 | 84 | 2015/04/15 | 3 weeks ago | Randomized testing system. |
| [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) | 4047 | 41 | 2014/02/07 | 2 weeks ago | Mock SQL driver for testing database interactions. |
| [mockery](https://github.com/vektra/mockery) | 3153 | 30 | 2014/09/02 | 1 week ago | Tool to generate Go interfaces. |
| [selenoid](https://github.com/aerokube/selenoid) | 2073 | 99 | 2016/08/22 | 1 month ago | alternative Selenium hub server that launches browsers within containers. |
| [rod](https://github.com/go-rod/rod) | 2017 | 31 | 2020/01/21 | 2 days ago | A Devtools driver to make web automation and scraping easy. |
| [hoverfly](https://github.com/SpectoLabs/hoverfly) | 1817 | 60 | 2015/11/30 | 1 month ago | HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI. |
| [gock](https://github.com/h2non/gock) | 1540 | 19 | 2016/03/02 | 4 months ago | Versatile HTTP mocking made easy. |
| [httpmock](https://github.com/jarcoal/httpmock) | 1268 | 9 | 2014/02/24 | 6 days ago | Easy mocking of HTTP responses from external resources. |
| [gofuzz](https://github.com/google/gofuzz) | 1203 | 27 | 2014/07/31 | 3 months ago | Library for populating go objects with random values. |
| [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) | 602 | 10 | 2014/05/21 | 3 weeks ago | Tool for generating self-contained mock objects. |
| [cdp](https://github.com/mafredri/cdp) | 588 | 19 | 2017/03/12 | 5 months ago | Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it. |
| [playwright-go](https://github.com/mxschmitt/playwright-go) | 587 | 18 | 2020/08/16 | 4 weeks ago | browser automation library to control Chromium, Firefox and WebKit with a single API. |
| [minimock](https://github.com/gojuno/minimock) | 436 | 10 | 2016/08/03 | 3 months ago | Mock generator for Go interfaces. |
| [go-txdb](https://github.com/DATA-DOG/go-txdb) | 402 | 7 | 2015/07/08 | 1 hour ago | Single transaction based database driver mainly for testing purposes. |
| [ggr](https://github.com/aerokube/ggr) | 276 | 26 | 2016/06/16 | 1 month ago | a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs. |
| [tavor](https://github.com/zimmski/tavor) | 231 | 13 | 2014/05/18 | 3 years ago | Generic fuzzing and delta-debugging framework. |
| [govcr](https://github.com/seborama/govcr) | 99 | 2 | 2016/07/10 | 2 years ago | HTTP mock for Golang: record and replay HTTP interactions for offline testing. |
| [timex](https://github.com/cabify/timex) | 58 | 79 | 2020/01/02 | 1 year ago | A test-friendly replacement for the native `time` package. |
| [go-localstack](https://github.com/elgohr/go-localstack) | 28 | 1 | 2020/03/18 | 3 days ago | Tool for using localstack in AWS testing. |
| [mockhttp](https://github.com/tv42/mockhttp) | 22 | 2 | 2011/06/11 | 7 years ago | Mock object for Go http.ResponseWriter. |
| [mockit](https://github.com/pasdam/mockit) | 8 | 1 | 2020/01/01 | 1 day ago | Allows functions and method easy mocking, without defining new types; it's similar to Mockito for Java. |
**[⬆ back to top](#awesome-go-info)**

### Testing Frameworks
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [testify](https://github.com/stretchr/testify) | 15071 | 174 | 2012/10/16 | 2 hours ago | Sacred extension to the standard go testing package. |
| [go-cmp](https://github.com/google/go-cmp) | 2625 | 28 | 2017/07/07 | 2 weeks ago | Package for comparing Go values in tests. |
| [httpexpect](https://github.com/gavv/httpexpect) | 1830 | 36 | 2016/04/29 | 4 months ago | Concise, declarative, and easy to use end-to-end HTTP and REST API testing. |
| [godog](https://github.com/cucumber/godog) | 1524 | 99 | 2015/06/10 | 1 week ago | Cucumber or Behat like BDD framework for Go. |
| [is](https://github.com/matryer/is) | 1294 | 18 | 2016/12/06 | 2 weeks ago | Professional lightweight testing mini-framework for Go. |
| [go-vcr](https://github.com/dnaeon/go-vcr) | 827 | 14 | 2015/12/14 | 2 months ago | Record and replay your HTTP interactions for fast, deterministic and accurate tests. |
| [goblin](https://github.com/franela/goblin) | 820 | 16 | 2013/09/19 | 2 months ago | Mocha like testing framework fo Go. |
| [testfixtures](https://github.com/go-testfixtures/testfixtures) | 726 | 6 | 2016/04/05 | 3 weeks ago | A helper for Rails' like test fixtures to test database applications. |
| [baloo](https://github.com/h2non/baloo) | 716 | 11 | 2016/05/29 | 3 years ago | Expressive and versatile end-to-end HTTP API testing made easy. |
| [gnomock](https://github.com/orlangure/gnomock) | 611 | 12 | 2020/01/31 | 4 days ago | integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks. |
| [go-mutesting](https://github.com/zimmski/go-mutesting) | 495 | 11 | 2014/12/26 | 2 weeks ago | Mutation testing for Go source code. |
| [goc](https://github.com/qiniu/goc) | 469 | 20 | 2020/05/07 | 1 week ago | Goc is a comprehensive coverage testing system for The Go Programming Language. |
| [gofight](https://github.com/appleboy/gofight) | 397 | 14 | 2016/03/29 | 6 months ago | API Handler Testing for Golang Router framework. |
| [embedded-postgres](https://github.com/fergusstrange/embedded-postgres) | 317 | 4 | 2019/11/16 | 1 week ago | Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test. |
| [testza](https://github.com/MarvinJWendt/testza) | 310 | 3 | 2021/07/05 | 1 month ago | Full-featured test framework with nice colorized output. |
| [frisby](https://github.com/hofstadter-io/frisby) | 271 | 10 | 2015/09/15 | 1 year ago | REST API testing framework. |
| [gotest.tools](https://github.com/gotestyourself/gotest.tools) | 264 | 8 | 2017/08/08 | 1 month ago | A collection of packages to augment the go testing package and support common patterns. |
| [go-testdeep](https://github.com/maxatome/go-testdeep) | 237 | 3 | 2018/05/26 | 1 month ago | Extremely flexible golang deep comparison, extends the go testing package. |
| [go-carpet](https://github.com/msoap/go-carpet) | 216 | 4 | 2016/02/28 | 1 month ago | Tool for viewing test coverage in terminal. |
| [endly](https://github.com/viant/endly) | 200 | 17 | 2017/08/28 | 2 weeks ago | Declarative end to end functional testing. |
| [cupaloy](https://github.com/bradleyjkemp/cupaloy) | 198 | 3 | 2017/08/07 | 1 month ago | Simple snapshot testing addon for your test framework. |
| [charlatan](https://github.com/percolate/charlatan) | 194 | 52 | 2017/10/06 | 2 years ago | Tool to generate fake interface implementations for tests. |
| [commander](https://github.com/commander-cli/commander) | 191 | 7 | 2019/02/22 | 1 week ago | Tool for testing cli applications on windows, linux and osx. |
| [dbcleaner](https://github.com/khaiql/dbcleaner) | 133 | 3 | 2017/01/17 | 1 month ago | Clean database for testing purpose, inspired by `database_cleaner` in Ruby. |
| [gospec](https://github.com/luontola/gospec) | 114 | 4 | 2009/11/24 | 7 years ago | BDD-style testing framework for the Go programming language. |
| [wstest](https://github.com/posener/wstest) | 86 | 2 | 2017/03/31 | 1 year ago | Websocket client for unit-testing a websocket http.Handler. |
| [gocrest](https://github.com/corbym/gocrest) | 81 | 4 | 2017/12/23 | 1 year ago | Composable hamcrest-like matchers for Go assertions. |
| [testcase](https://github.com/adamluzsi/testcase) | 80 | 3 | 2019/04/22 | 1 month ago | Idiomatic testing framework for Behavior Driven Development. |
| [jsonassert](https://github.com/kinbiko/jsonassert) | 75 | 2 | 2018/10/26 | 2 weeks ago | Package for verifying that your JSON payloads are serialized correctly. |
| [go-hit](https://github.com/Eun/go-hit) | 61 | 1 | 2019/06/04 | 1 week ago | Hit is an http integration test framework written in golang. |
| [restit](https://github.com/go-restit/restit) | 55 | 7 | 2014/06/25 | 2 years ago | Go micro framework to help writing RESTful API integration test. |
| [gospecify](https://github.com/stesla/gospecify) | 52 | 6 | 2009/11/20 | 10 years ago | This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec. |
| [covergates](https://github.com/covergates/covergates) | 46 | 5 | 2020/05/29 | 11 months ago | Self-hosted code coverage report review and management service. |
| [gomatch](https://github.com/jfilipczyk/gomatch) | 41 | 2 | 2019/01/27 | 11 months ago | library created for testing JSON against patterns. |
| [dsunit](https://github.com/viant/dsunit) | 39 | 10 | 2016/06/13 | 1 year ago | Datastore testing for SQL, NoSQL, structured files. |
| [assert](https://github.com/go-playground/assert) | 35 | 2 | 2015/07/20 | 1 year ago | Basic Assertion Library used along side native go testing, with building blocks for custom assertions. |
| [hamcrest](https://github.com/rdrdr/hamcrest) | 27 | 3 | 2010/12/22 | 11 months ago | fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results. |
| [flute](https://github.com/suzuki-shunsuke/flute) | 15 | 0 | 2019/07/06 | 2 weeks ago | HTTP client testing framework. |
| [schema](https://github.com/jgroeneveld/schema) | 15 | 1 | 2015/08/13 | 2 years ago | Quick and easy expression matching for JSON schemas used in requests and responses. |
| [gogiven](https://github.com/corbym/gogiven) | 11 | 5 | 2017/12/31 | 5 months ago | YATSPEC-like BDD testing framework for Go. |
| [testsql](https://github.com/zhulongcheng/testsql) | 11 | 2 | 2018/09/22 | 2 years ago | Generate test data from SQL files before testing and clear it after finished. |
| [gosuite](https://github.com/pavlo/gosuite) | 10 | 2 | 2016/10/15 | 5 years ago | Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests. |
| [badio](https://github.com/cavaliergopher/badio) | 9 | 0 | 2016/02/11 | 5 years ago | Extensions to Go's `testing/iotest` package. |
| [biff](https://github.com/fulldump/biff) | 9 | 1 | 2018/03/28 | 5 months ago | Bifurcation testing framework, BDD compatible. |
| [stop-and-go](https://github.com/elgohr/stop-and-go) | 6 | 1 | 2020/11/06 | 4 months ago | Testing helper for concurrency. |
| [trial](https://github.com/jgroeneveld/trial) | 5 | 0 | 2015/06/18 | 2 years ago | Quick and easy extendable assertions without introducing much boilerplate. |
| [tt](https://github.com/vcaesar/tt) | 4 | 1 | 2018/04/03 | 3 months ago | Simple and colorful test tools. |
| [fixenv](https://github.com/rekby/fixenv) | 3 | 1 | 2021/08/27 | 3 months ago | Fixture manage engine, inspired by pytest fixtures. |
| [go-testpredicate](https://github.com/maargenton/go-testpredicate) | 3 | 2 | 2018/11/23 | 1 month ago | Test predicate style assertions library with extensive diagnostics output. |
| [omg.testingtools](https://github.com/dedalqq/omg.testingtools) | 0 | 1 | 2021/10/13 | 2 months ago | The simple library for change a values of private fields for testing. |
**[⬆ back to top](#awesome-go-info)**

## Text Processing
        
*Libraries for parsing and manipulating texts.*
**[⬆ back to top](#awesome-go-info)**

### Specific Formats
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [colly](https://github.com/gocolly/colly) | 15626 | 324 | 2017/09/29 | 3 days ago | Fast and Elegant Scraping Framework for Gophers. |
| [goquery](https://github.com/PuerkitoBio/goquery) | 10964 | 255 | 2012/08/29 | 2 months ago | GoQuery brings a syntax and a set of features similar to jQuery to the Go language. |
| [blackfriday](https://github.com/russross/blackfriday) | 4844 | 89 | 2011/05/27 | 2 months ago | Markdown processor in Go. |
| [sh](https://github.com/mvdan/sh) | 4368 | 52 | 2016/01/16 | 5 hours ago | Shell parser and formatter. |
| [toml](https://github.com/BurntSushi/toml) | 3711 | 85 | 2013/02/26 | 2 days ago | TOML configuration format (encoder/decoder with reflection). |
| [go-humanize](https://github.com/dustin/go-humanize) | 2984 | 35 | 2012/01/13 | 2 months ago | Formatters for time, numbers, and memory size to human readable format. |
| [bluemonday](https://github.com/microcosm-cc/bluemonday) | 2140 | 30 | 2013/11/20 | 2 months ago | HTML Sanitizer. |
| [gofeed](https://github.com/mmcdole/gofeed) | 1771 | 42 | 2016/01/23 | 3 weeks ago | Parse RSS and Atom feeds in Go. |
| [inject](https://github.com/facebookarchive/inject) | 1354 | 45 | 2013/10/21 | 2 years ago | Package inject provides a reflect based injector. |
| [go-toml](https://github.com/pelletier/go-toml) | 1138 | 30 | 2013/02/24 | 12 hours ago | Go library for the TOML format with query support and handy cli tools. |
| [commonregex](https://github.com/mingrammer/commonregex) | 788 | 21 | 2017/03/23 | 2 years ago | A collection of common regular expressions for Go. |
| [slug](https://github.com/gosimple/slug) | 760 | 13 | 2014/03/31 | 4 days ago | URL-friendly slugify with multiple languages support. |
| [dataflowkit](https://github.com/slotix/dataflowkit) | 504 | 22 | 2017/02/09 | 1 year ago | Web scraping Framework to turn websites into structured data. |
| [mxj](https://github.com/clbanning/mxj) | 496 | 27 | 2014/02/03 | 1 week ago | Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. |
| [gographviz](https://github.com/awalterschulze/gographviz) | 458 | 12 | 2015/03/14 | 4 months ago | Parses the Graphviz DOT language. |
| [htmlquery](https://github.com/antchfx/htmlquery) | 436 | 12 | 2017/12/05 | 1 month ago | An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression. |
| [omniparser](https://github.com/jf-tech/omniparser) | 405 | 9 | 2020/08/16 | 1 month ago | A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema. |
| [go-runewidth](https://github.com/mattn/go-runewidth) | 396 | 13 | 2013/06/21 | 1 month ago | Functions to get fixed width of the character or string. |
| [gotext](https://github.com/leonelquinteros/gotext) | 312 | 7 | 2016/06/19 | 1 week ago | GNU gettext utilities for Go. |
| [html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) | 299 | 10 | 2018/05/15 | 3 months ago | Convert HTML to Markdown. Even works with entire websites and can be extended through rules. |
| [goq](https://github.com/andrewstuart/goq) | 204 | 7 | 2017/02/20 | 3 months ago | Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery). |
| [goribot](https://github.com/zhshch2002/goribot) | 203 | 11 | 2019/09/08 | 1 year ago | [Crawler/Scraper for Golang]🕷A lightweight distributed friendly Golang crawler framework.一个轻量的分布式友好的 Golang 爬虫框架。 |
| [go-nmea](https://github.com/adrianmo/go-nmea) | 160 | 7 | 2015/07/22 | 3 days ago | NMEA parser library for the Go language. |
| [sdp](https://github.com/gortc/sdp) | 110 | 8 | 2016/05/13 | 1 year ago | SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)]. |
| [podcast](https://github.com/eduncan911/podcast) | 100 | 5 | 2017/02/02 | 1 year ago | iTunes Compliant and RSS 2. |
| [go-zero-width](https://github.com/trubitsyn/go-zero-width) | 96 | 1 | 2018/06/18 | 1 year ago | Zero-width character detection and removal for Go. |
| [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) | 89 | 10 | 2016/07/05 | 3 weeks ago | Editorconfig file parser and manipulator for Go. |
| [align](https://github.com/Guitarbum722/align) | 72 | 5 | 2017/04/29 | 3 months ago | A general purpose application that aligns text. |
| [go-slugify](https://github.com/mozillazg/go-slugify) | 69 | 2 | 2016/07/16 | 1 year ago | Make pretty slug with multiple languages support. |
| [go-vcard](https://github.com/emersion/go-vcard) | 64 | 4 | 2017/03/21 | 7 months ago | Parse and format vCard. |
| [genex](https://github.com/alixaxel/genex) | 62 | 3 | 2015/03/09 | 2 years ago | Count and expand Regular Expressions into all matching Strings. |
| [goregen](https://github.com/zach-klippenstein/goregen) | 60 | 3 | 2014/12/27 | 5 months ago | Library for generating random strings from regular expressions. |
| [did](https://github.com/ockam-network/did) | 56 | 15 | 2018/11/02 | 11 months ago | DID (Decentralized Identifiers) Parser and Stringer in Go. |
| [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) | 54 | 3 | 2017/11/15 | 6 months ago | Fixed-width text formatting (encoder/decoder with reflection). |
| [guesslanguage](https://github.com/endeveit/guesslanguage) | 52 | 1 | 2014/12/16 | 4 years ago | Functions to determine the natural language of a unicode text. |
| [allot](https://github.com/sbstjn/allot) | 49 | 2 | 2016/10/16 | 8 months ago | Placeholder and wildcard text parsing for CLI tools and bots. |
| [pagser](https://github.com/foolin/pagser) | 46 | 2 | 2020/04/19 | 1 year ago | Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler. |
| [bafi](https://github.com/mmalcek/bafi) | 45 | 4 | 2021/07/13 | 2 weeks ago | Universal JSON, BSON, YAML, XML translator to ANY format using templates. |
| [gonameparts](https://github.com/polera/gonameparts) | 32 | 1 | 2015/05/17 | 2 years ago | Parses human names into individual name parts. |
| [slugify](https://github.com/avelino/slugify) | 30 | 2 | 2015/04/13 | 3 years ago | Go slugify application that handles string. |
| [normalize](https://github.com/avito-tech/normalize) | 23 | 3 | 2021/03/22 | 9 months ago | Sanitize, normalize and compare fuzzy text. |
| [codetree](https://github.com/aerogo/codetree) | 17 | 3 | 2016/11/26 | 2 years ago | Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure. |
| [enca](https://github.com/endeveit/enca) | 10 | 1 | 2014/12/17 | 5 years ago | Minimal cgo bindings for [libenca](https://cihar.com/software/enca/). |
| [syndfeed](https://github.com/zhengchun/syndfeed) | 7 | 1 | 2017/04/07 | 3 years ago | A syndication feed for Atom 1.0 and RSS 2.0. |
| [ltsv](https://github.com/Wing924/ltsv) | 6 | 1 | 2019/05/12 | 2 years ago | High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go. |
| [bbConvert](https://github.com/CalebQ42/bbConvert) | 5 | 1 | 2016/04/15 | 5 years ago | Converts bbCode to HTML that allows you to add support for custom bbCode tags. |
| [doi](https://github.com/hscells/doi) | 5 | 1 | 2017/08/02 | 4 years ago | Document object identifier (doi) parser in Go. |
| [encoding](https://github.com/ake-persson/encoding) | 4 | 1 | 2018/04/06 | 2 years ago | Package provides a generic interface to encoders and decodersa. |
| [go-wildcard](https://github.com/IGLOU-EU/go-wildcard) | 4 | 2 | 2021/03/28 | 8 months ago | Simple and lightweight wildcard pattern matching. |
| [go-output-format](https://github.com/drewstinnett/go-output-format) | 2 | 1 | 2021/04/08 | 2 months ago | Output go structures into multiple formats (YAML/JSON/etc) in your command line app. |
**[⬆ back to top](#awesome-go-info)**

### Utility
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [xurls](https://github.com/mvdan/xurls) | 849 | 17 | 2015/01/12 | 3 days ago | Extract urls from text. |
| [gotabulate](https://github.com/bndr/gotabulate) | 273 | 9 | 2014/08/21 | 10 months ago | Easily pretty-print your tabular data with Go. |
| [radix](https://github.com/yourbasic/radix) | 169 | 7 | 2017/06/09 | 3 years ago | fast string sorting algorithm. |
| [regroup](https://github.com/oriser/regroup) | 98 | 1 | 2020/09/08 | 5 months ago | Match regex expression named groups into go struct using struct tags and automatic parsing. |
| [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) | 40 | 2 | 2018/09/09 | 6 months ago | A sanitization-based swear filter for Go. |
| [parth](https://github.com/codemodus/parth) | 39 | 4 | 2015/04/06 | 2 years ago | URL path segmentation parsing. |
| [xj2go](https://github.com/wk30/xj2go) | 21 | 2 | 2017/09/19 | 2 months ago | Convert xml or json to go struct. |
| [tagify](https://github.com/zoomio/tagify) | 17 | 2 | 2018/03/20 | 1 month ago | Produces a set of tags from given source. |
| [kace](https://github.com/codemodus/kace) | 16 | 2 | 2015/06/04 | 3 years ago | Common case conversions covering common initialisms. |
| [TySug](https://github.com/Dynom/TySug) | 9 | 1 | 2018/06/05 | 1 year ago | Alternative suggestions with respect to keyboard layouts. |
| [parseargs-go](https://github.com/txgruppi/parseargs-go) | 8 | 0 | 2016/02/24 | 4 years ago | string argument parser that understands quotes and backslashes. |
| [textwrap](https://github.com/isbm/textwrap) | 1 | 2 | 2019/07/26 | 2 years ago | Implementation of `textwrap` module from Python. |
**[⬆ back to top](#awesome-go-info)**

## Third-party APIs
        
*Libraries for accessing third party APIs.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-github](https://github.com/google/go-github) | 8010 | 211 | 2013/05/24 | 18 hours ago | Go library for accessing the GitHub REST API v3. |
| [aws-sdk-go](https://github.com/aws/aws-sdk-go) | 7284 | 256 | 2014/12/05 | 2 days ago | The official AWS SDK for the Go programming language. |
| [slack](https://github.com/slack-go/slack) | 3755 | 60 | 2015/01/24 | 3 days ago | Slack API in Go. |
| [google-api-go-client](https://github.com/googleapis/google-api-go-client) | 2866 | 173 | 2014/11/24 | 51 minutes ago | Auto-generated Google APIs for Go. |
| [google-cloud-go](https://github.com/googleapis/google-cloud-go) | 2725 | 250 | 2014/05/09 | 1 hour ago | Google Cloud APIs Go Client Library. |
| [discordgo](https://github.com/bwmarrin/discordgo) | 2604 | 54 | 2015/11/01 | 14 hours ago | Go bindings for the Discord Chat API. |
| [stripe-go](https://github.com/stripe/stripe-go) | 1480 | 40 | 2014/06/05 | 18 hours ago | Go client for the Stripe API. |
| [minio-go](https://github.com/minio/minio-go) | 1477 | 47 | 2015/05/02 | 1 day ago | Minio Go Library for Amazon S3 compatible cloud storage. |
| [go-twitter](https://github.com/dghubble/go-twitter) | 1366 | 28 | 2015/04/11 | 1 month ago | Go client library for the Twitter v1.1 APIs. |
| [anaconda](https://github.com/ChimeraCoder/anaconda) | 1107 | 22 | 2013/03/04 | 5 months ago | Go client library for the Twitter 1.1 API. |
| [facebook](https://github.com/huandu/facebook) | 1021 | 119 | 2012/07/28 | 1 week ago | Go Library that supports the Facebook Graph API. |
| [githubv4](https://github.com/shurcooL/githubv4) | 829 | 20 | 2017/05/27 | 1 month ago | Go library for accessing the GitHub GraphQL API v4. |
| [webhooks](https://github.com/go-playground/webhooks) | 688 | 15 | 2015/10/25 | 1 month ago | Webhook receiver for GitHub and Bitbucket. |
| [paypal](https://github.com/plutov/paypal) | 460 | 25 | 2015/10/14 | 1 month ago | Wrapper for PayPal payment API. |
| [geo-golang](https://github.com/codingsince1985/geo-golang) | 421 | 13 | 2014/12/04 | 4 months ago | Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](https://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](https://opencagedata.com/api), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs. |
| [ethrpc](https://github.com/onrik/ethrpc) | 220 | 14 | 2017/01/24 | 1 year ago | Go bindings for Ethereum JSON RPC API. |
| [go-marathon](https://github.com/gambol99/go-marathon) | 196 | 14 | 2015/02/11 | 1 year ago | Go library for interacting with Mesosphere's Marathon PAAS. |
| [trello](https://github.com/adlio/trello) | 190 | 8 | 2016/09/24 | 6 months ago | Go wrapper for the Trello API. |
| [twitter-scraper](https://github.com/n0madic/twitter-scraper) | 160 | 5 | 2018/11/29 | 3 weeks ago | Scrape the Twitter Frontend API without authentication and limits. |
| [medium-sdk-go](https://github.com/Medium/medium-sdk-go) | 130 | 139 | 2015/09/26 | 3 years ago | Golang SDK for Medium's OAuth2 API. |
| [gostorm](https://github.com/jsgilmore/gostorm) | 128 | 12 | 2013/07/22 | 4 years ago | GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. |
| [lark](https://github.com/chyroc/lark) | 120 | 3 | 2021/04/21 | 4 hours ago | [Feishu](https://open.feishu.cn/)/[Lark](https://open.larksuite.com/) Open API Go SDK, Support ALL Open API and Event Callback. |
| [go-trending](https://github.com/andygrunwald/go-trending) | 118 | 7 | 2015/07/04 | 2 months ago | Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github. |
| [hipchat](https://github.com/daneharrigan/hipchat) | 111 | 7 | 2013/04/28 | 4 years ago | A golang package to communicate with HipChat over XMPP. |
| [wit-go](https://github.com/wit-ai/wit-go) | 110 | 20 | 2018/08/20 | 3 months ago | Go client for wit.ai HTTP API. |
| [pushover](https://github.com/gregdel/pushover) | 108 | 5 | 2015/02/19 | 2 months ago | Go wrapper for the Pushover API. |
| [hipchat](https://github.com/andybons/hipchat) | 105 | 6 | 2012/10/20 | 5 years ago | This project implements a golang client library for the Hipchat API. |
| [cachet](https://github.com/andygrunwald/cachet) | 89 | 7 | 2015/10/31 | 6 months ago | Go client library for [Cachet (open source status page system)](https://cachethq.io/). |
| [gosip](https://github.com/koltyakov/gosip) | 70 | 4 | 2019/01/26 | 1 month ago | Go client library SharePoint API. |
| [simples3](https://github.com/rhnvrm/simples3) | 70 | 2 | 2018/12/06 | 1 month ago | Simple no frills AWS S3 Library using REST with V4 Signing written in Go. |
| [lark](https://github.com/go-lark/lark) | 69 | 1 | 2021/04/20 | 1 week ago | An easy-to-use unofficial SDK for [Feishu](https://open.feishu.cn/) and [Lark](https://open.larksuite.com/) Open Platform. |
| [igdb](https://github.com/Henry-Sarabia/igdb) | 68 | 2 | 2017/08/24 | 9 months ago | Go client for the [Internet Game Database API](https://api.igdb.com/). |
| [go-circleci](https://github.com/jszwedko/go-circleci) | 61 | 3 | 2015/08/14 | 2 years ago | Go client library for interacting with CircleCI's API. |
| [go-unsplash](https://github.com/hbagdi/go-unsplash) | 58 | 2 | 2017/01/19 | 9 months ago | Go client library for the [Unsplash.com](https://unsplash.com) API. |
| [gogtrends](https://github.com/groovili/gogtrends) | 58 | 1 | 2018/12/27 | 3 months ago | Google Trends Unofficial API. |
| [clarifai-go](https://github.com/Clarifai/clarifai-go) | 55 | 37 | 2015/09/28 | 4 years ago | Go client library for interfacing with the Clarifai API. |
| [megos](https://github.com/andygrunwald/megos) | 54 | 5 | 2015/10/02 | 6 months ago | Client library for accessing an [Apache Mesos](https://mesos.apache.org/) cluster. |
| [go-amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) | 51 | 1 | 2016/11/15 | 3 years ago | Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html). |
| [gads](https://github.com/emiddleton/gads) | 49 | 7 | 2014/01/20 | 2 weeks ago | Google Adwords Unofficial API. |
| [ynab.go](https://github.com/brunomvsouza/ynab.go) | 49 | 2 | 2018/07/13 | 3 months ago | Go wrapper for the YNAB API. |
| [golang-tmdb](https://github.com/cyruzin/golang-tmdb) | 47 | 1 | 2019/01/11 | 5 days ago | Golang wrapper for The Movie Database API v3. |
| [go-xkcd](https://github.com/nishanths/go-xkcd) | 45 | 3 | 2016/02/26 | 2 months ago | Go client for the xkcd API. |
| [uptimerobot](https://github.com/bitfield/uptimerobot) | 45 | 4 | 2018/05/29 | 1 year ago | Go wrapper and command-line client for the Uptime Robot v2 API. |
| [gomusicbrainz](https://github.com/michiwend/gomusicbrainz) | 43 | 6 | 2014/09/10 | 10 months ago | Go MusicBrainz WS2 client library. |
| [fcm](https://github.com/maddevsio/fcm) | 42 | 5 | 2017/01/06 | 1 year ago | Go library for Firebase Cloud Messaging. |
| [mixpanel](https://github.com/dukex/mixpanel) | 42 | 4 | 2014/05/20 | 4 months ago | Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications. |
| [go-spotify](https://github.com/rapito/go-spotify) | 41 | 3 | 2014/10/30 | 1 year ago | Go Library to access Spotify WEB API. |
| [go-postman-collection](https://github.com/rbretecher/go-postman-collection) | 36 | 2 | 2019/11/16 | 1 month ago | Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia). |
| [golyrics](https://github.com/mamal72/golyrics) | 36 | 4 | 2016/11/18 | 3 years ago | Golyrics is a Go library to fetch music lyrics data from the Wikia website. |
| [translate](https://github.com/nuveo/translate) | 31 | 31 | 2015/07/13 | 5 years ago | Go online translation package. |
| [gami](https://github.com/bit4bit/gami) | 30 | 4 | 2014/05/14 | 3 years ago | Go library for Asterisk Manager Interface. |
| [gcm](https://github.com/TheOrioli/gcm) | 30 | 3 | 2015/11/09 | 6 years ago | Go library for Google Cloud Messaging. |
| [airtable](https://github.com/mehanizm/airtable) | 29 | 1 | 2020/04/12 | 4 days ago | Go client library for the [Airtable API](https://airtable.com/api). |
| [patreon-go](https://github.com/mxpv/patreon-go) | 27 | 4 | 2017/08/06 | 2 years ago | Go library for Patreon API. |
| [go-myanimelist](https://github.com/nstratos/go-myanimelist) | 25 | 1 | 2015/05/03 | 1 month ago | Go client library for accessing the [MyAnimeList API](https://myanimelist.net/apiconfig/references/api/v2). |
| [go-steam](https://github.com/sostronk/go-steam) | 24 | 11 | 2014/11/23 | 3 months ago | Go Library to interact with Steam game servers. |
| [google-play-scraper](https://github.com/n0madic/google-play-scraper) | 23 | 1 | 2019/09/20 | 2 months ago | Get data from Google Play Store. |
| [lastpass-go](https://github.com/ansd/lastpass-go) | 23 | 4 | 2019/07/11 | 2 weeks ago | Go client library for the [LastPass](https://www.lastpass.com/) API. |
| [go-shopify](https://github.com/rapito/go-shopify) | 22 | 2 | 2014/10/28 | 1 year ago | Go Library to make CRUD request to the Shopify API. |
| [go-twitch](https://github.com/knspriggs/go-twitch) | 21 | 5 | 2016/06/28 | 4 years ago | Go client for interacting with the Twitch v3 API. |
| [codeship-go](https://github.com/codeship/codeship-go) | 18 | 20 | 2017/09/08 | 1 year ago | Go client library for interacting with Codeship's API v2. |
| [brewerydb](https://github.com/naegelejd/brewerydb) | 17 | 3 | 2015/04/15 | 6 years ago | Go library for accessing the BreweryDB API. |
| [textbelt](https://github.com/farmergreg/textbelt) | 17 | 2 | 2015/09/01 | 6 years ago | Go client for the textbelt.com txt messaging API. |
| [coinpaprika-api-go-client](https://github.com/coinpaprika/coinpaprika-api-go-client) | 14 | 8 | 2018/09/25 | 1 year ago | Go client library for interacting with Coinpaprika's API. |
| [go-hacknews](https://github.com/PaulRosset/go-hacknews) | 14 | 2 | 2017/08/10 | 4 years ago | Tiny Go client for HackerNews API. |
| [go-aws-news](https://github.com/circa10a/go-aws-news) | 13 | 3 | 2020/01/08 | 1 month ago | Go application and library to fetch what's new from AWS. |
| [go-google-analytics](https://github.com/chonthu/go-google-analytics) | 12 | 2 | 2015/06/01 | 6 years ago | Simple wrapper for easy google analytics reporting. |
| [jokeapi](https://github.com/Icelain/jokeapi) | 12 | 2 | 2020/11/22 | 5 days ago | Go client for [JokeAPI](https://sv443.net/jokeapi/v2/). |
| [gopaapi5](https://github.com/utekaravinash/gopaapi5) | 11 | 3 | 2020/02/15 | 1 year ago | Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/). |
| [device-check-go](https://github.com/rinchsan/device-check-go) | 10 | 1 | 2019/04/11 | 2 months ago | Go client library for interacting with [iOS DeviceCheck API](https://developer.apple.com/documentation/devicecheck) v1. |
| [go-here](https://github.com/abdullahselek/go-here) | 10 | 0 | 2019/07/07 | 1 year ago | Go client library around the HERE location based APIs. |
| [smitego](https://github.com/sergiotapia/smitego) | 10 | 0 | 2013/12/11 | 7 years ago | Go package to wraps access to the Smite game API. |
| [go-openproject](https://github.com/manuelbcd/go-openproject) | 9 | 1 | 2021/02/13 | 8 months ago | Go client library for interacting with [OpenProject](https://docs.openproject.org/api/) API. |
| [go-sophos](https://github.com/esurdam/go-sophos) | 8 | 2 | 2018/09/05 | 1 year ago | Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies. |
| [rrdaclient](https://github.com/Omie/rrdaclient) | 8 | 2 | 2014/09/15 | 7 years ago | Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP. |
| [bqwriter](https://github.com/OTA-Insight/bqwriter) | 7 | 2 | 2021/10/12 | 3 weeks ago | High Level Go Library to write data into [Google BigQuery](https://cloud.google.com/bigquery) at a high throughout. |
| [go-google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) | 7 | 0 | 2016/10/24 | 5 years ago | Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/). |
| [go-zooz](https://github.com/gojuno/go-zooz) | 7 | 14 | 2017/07/04 | 1 week ago | Go client for the Zooz API. |
| [go-sptrans](https://github.com/sergioaugrod/go-sptrans) | 6 | 3 | 2017/09/11 | 1 year ago | Go client library for the SPTrans Olho Vivo API. |
| [gumblr](https://github.com/mattcunningham/gumblr) | 6 | 1 | 2015/07/09 | 5 years ago | Go wrapper for the Tumblr v2 API. |
| [go-chronos](https://github.com/axelspringer/go-chronos) | 4 | 9 | 2017/10/23 | 3 years ago | Go library for interacting with the [Chronos](https://mesos.github. |
| [go-swagger-ui](https://github.com/esurdam/go-swagger-ui) | 4 | 1 | 2021/05/25 | 6 months ago | Go library containing precompiled [Swagger UI](https://swagger.io/tools/swagger-ui/) for serving swagger json. |
| [libgoffi](https://github.com/clevabit/libgoffi) | 4 | 12 | 2019/08/03 | 1 year ago | Library adapter toolbox for native [libffi](https://sourceware. |
| [go-restcountries](https://github.com/chriscross0/go-restcountries) | 3 | 1 | 2021/08/01 | 2 months ago | Go library for the [REST Countries API](https://restcountries.eu/). |
| [kanka](https://github.com/Henry-Sarabia/kanka) | 3 | 3 | 2019/12/26 | 1 year ago | Go client for the [Kanka API](https://kanka.io/en-US/docs/1.0). |
| [rawg-sdk-go](https://github.com/dimuska139/rawg-sdk-go) | 3 | 1 | 2020/10/16 | 1 week ago | Go library for the [RAWG Video Games Database](https://rawg. |
| [appstore-sdk-go](https://github.com/Kachit/appstore-sdk-go) | 2 | 1 | 2020/06/11 | 10 months ago | Unofficial Golang SDK for AppStore Connect API. |
| [playlyfe-go-sdk](https://github.com/playlyfe/playlyfe-go-sdk) | 1 | 5 | 2015/05/25 | 5 years ago | The Playlyfe Rest API Go SDK. |
| [tripadvisor-golang](https://github.com/mrbenosborne/tripadvisor-golang) | 1 | 2 | 2019/04/15 | 2 years ago | Go wrapper for the TripAdvisor API. |
| [vl-go](https://github.com/verifid/vl-go) | 1 | 2 | 2019/02/09 | 7 months ago | Go client library around the VerifID identity verification layer API. |
**[⬆ back to top](#awesome-go-info)**

## UUID
        
*Libraries for working with UUIDs.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [uuid](https://github.com/google/uuid) | 3258 | 46 | 2016/02/12 | 3 weeks ago | Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services. |
| [ulid](https://github.com/oklog/ulid) | 2474 | 45 | 2016/12/06 | 2 months ago | Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier). |
| [xid](https://github.com/rs/xid) | 2355 | 31 | 2015/11/10 | 6 days ago | Xid is a globally unique id generator library, ready to be safely used directly in your server code. |
| [uuid](https://github.com/gofrs/uuid) | 1049 | 19 | 2018/07/13 | 2 weeks ago | Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid. |
| [wuid](https://github.com/edwingeng/wuid) | 443 | 17 | 2018/01/27 | 4 months ago | An extremely fast unique number generator, 10-135 times faster than UUID. |
| [sno](https://github.com/muyo/sno) | 54 | 3 | 2019/05/26 | 1 month ago | Compact, sortable and fast unique IDs with embedded metadata. |
| [nanoid](https://github.com/aidarkhanov/nanoid) | 40 | 1 | 2019/07/02 | 3 months ago | A tiny and efficient Go unique string ID generator. |
| [Goid](https://github.com/JakeHL/Goid) | 29 | 5 | 2017/05/19 | 2 years ago | Generate and Parse RFC4122 compliant V4 UUIDs. |
| [uuid](https://github.com/agext/uuid) | 13 | 3 | 2016/02/03 | 1 year ago | Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier. |
| [gouid](https://github.com/twharmon/gouid) | 10 | 1 | 2020/10/08 | 7 months ago | Generate cryptographically secure random string IDs with just one allocation. |
| [goflake](https://github.com/Hart87/goflake) | 8 | 1 | 2021/05/03 | 7 months ago | A small, scalable, & serverless unique ID generator for use in distributed systems. Inspired by Twitters Snowflake. |
**[⬆ back to top](#awesome-go-info)**

## Utilities
        
*General utilities and tools to make your life easier.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fzf](https://github.com/junegunn/fzf) | 41119 | 392 | 2013/10/23 | 3 days ago | Command-line fuzzy finder written in Go. |
| [hub](https://github.com/github/hub) | 21435 | 510 | 2009/12/05 | 2 weeks ago | wrap git commands with additional functionality to interact with github from the terminal. |
| [ctop](https://github.com/bcicen/ctop) | 12216 | 166 | 2016/12/27 | 2 weeks ago | [Top-like](https://ctop.sh) interface (e.g. htop) for container metrics. |
| [sqlx](https://github.com/jmoiron/sqlx) | 11233 | 190 | 2013/01/28 | 3 weeks ago | provides a set of extensions on top of the excellent built-in database/sql package. |
| [wuzz](https://github.com/asciimoo/wuzz) | 9849 | 170 | 2017/01/30 | 4 months ago | Interactive cli tool for HTTP inspection. |
| [goreleaser](https://github.com/goreleaser/goreleaser) | 9326 | 111 | 2016/12/21 | 3 hours ago | Deliver Go binaries as fast and easily as possible. |
| [usql](https://github.com/xo/usql) | 6884 | 116 | 2017/03/02 | 3 days ago | usql is a universal command-line interface for SQL databases. |
| [peco](https://github.com/peco/peco) | 6672 | 136 | 2014/06/06 | 5 months ago | Simplistic interactive filtering tool. |
| [godropbox](https://github.com/dropbox/godropbox) | 4006 | 245 | 2014/06/22 | 1 year ago | Common libraries for writing Go services/applications from Dropbox. |
| [hystrix-go](https://github.com/afex/hystrix-go) | 3489 | 92 | 2013/12/15 | 3 months ago | Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker. |
| [go-funk](https://github.com/thoas/go-funk) | 3109 | 38 | 2016/12/30 | 3 weeks ago | Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...). |
| [panicparse](https://github.com/maruel/panicparse) | 2961 | 37 | 2015/02/02 | 3 weeks ago | Groups similar goroutines and colorizes stack dump. |
| [goreporter](https://github.com/qax-os/goreporter) | 2948 | 100 | 2017/03/27 | 3 years ago | Golang tool that does static analysis, unit testing, code review and generate code quality report. |
| [minify](https://github.com/tdewolff/minify) | 2826 | 56 | 2014/05/21 | 1 week ago | Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats. |
| [mc](https://github.com/minio/mc) | 1972 | 53 | 2015/01/16 | 16 hours ago | Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems. |
| [storm](https://github.com/asdine/storm) | 1820 | 43 | 2016/01/10 | 7 months ago | Simple and powerful toolkit for BoltDB. |
| [mergo](https://github.com/imdario/mergo) | 1815 | 23 | 2013/03/11 | 1 month ago | Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements. |
| [mole](https://github.com/davrodpin/mole) | 1524 | 28 | 2018/10/04 | 2 months ago | cli app to easily create ssh tunnels. |
| [filetype](https://github.com/h2non/filetype) | 1462 | 28 | 2015/09/24 | 1 week ago | Small package to infer the file type checking the magic numbers signature. |
| [boilr](https://github.com/tmrts/boilr) | 1418 | 28 | 2015/12/19 | 1 week ago | Blazingly fast CLI tool for creating projects from boilerplate templates. |
| [jump](https://github.com/gsamokovarov/jump) | 1279 | 20 | 2015/08/16 | 3 weeks ago | Jump helps you navigate faster by learning your habits. |
| [cli](https://github.com/create-go-app/cli) | 1203 | 18 | 2019/12/30 | 1 week ago | A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command. |
| [circuitbreaker](https://github.com/rubyist/circuitbreaker) | 972 | 21 | 2014/07/17 | 2 years ago | Circuit Breakers in Go. |
| [gtm](https://github.com/git-time-metric/gtm) | 884 | 29 | 2016/06/19 | 1 year ago | Simple, seamless, lightweight time tracking for Git. |
| [immortal](https://github.com/immortal/immortal) | 716 | 19 | 2016/06/30 | 1 year ago | \*nix cross-platform (OS agnostic) supervisor. |
| [hostctl](https://github.com/guumaster/hostctl) | 704 | 9 | 2020/03/14 | 2 weeks ago | A CLI tool to manage /etc/hosts with easy commands. |
| [mimetype](https://github.com/gabriel-vasile/mimetype) | 633 | 9 | 2018/07/02 | 6 days ago | Package for MIME type detection based on magic numbers. |
| [circuit](https://github.com/cep21/circuit) | 620 | 14 | 2017/12/23 | 1 week ago | An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern. |
| [htcat](https://github.com/htcat/htcat) | 536 | 19 | 2013/08/05 | 2 years ago | Parallel and Pipelined HTTP GET Utility. |
| [ergo](https://github.com/cristianoliveira/ergo) | 489 | 5 | 2017/08/19 | 1 month ago | The management of multiple local services running over different ports made easy. |
| [godaemon](https://github.com/VividCortex/godaemon) | 481 | 28 | 2013/08/01 | 6 months ago | Utility to write daemons. |
| [koazee](https://github.com/wesovilabs/koazee) | 479 | 11 | 2018/11/09 | 1 year ago | Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays. |
| [go-dry](https://github.com/ungerik/go-dry) | 472 | 14 | 2014/02/28 | 1 month ago | DRY (don't repeat yourself) package for Go. |
| [scany](https://github.com/georgysavva/scany) | 463 | 6 | 2020/07/02 | 10 minutes ago | Library for scanning data from a database into Go structs and more. |
| [gopencils](https://github.com/bndr/gopencils) | 438 | 14 | 2014/06/23 | 2 years ago | Small and simple package to easily consume REST APIs. |
| [delve](https://github.com/derekparker/delve) | 430 | 9 | 2020/02/18 | 4 days ago | Go debugger. |
| [request](https://github.com/mozillazg/request) | 404 | 15 | 2014/12/21 | 2 years ago | Go HTTP Requests for Humans™. |
| [gubrak](https://github.com/novalagung/gubrak) | 382 | 7 | 2018/03/09 | 1 year ago | Golang utility library with syntactic sugar. It's like lodash, but for golang. |
| [deepcopier](https://github.com/ulule/deepcopier) | 373 | 20 | 2015/07/24 | 1 year ago | Simple struct copying for Go. |
| [clockwork](https://github.com/jonboulle/clockwork) | 369 | 6 | 2014/09/09 | 4 weeks ago | A simple fake clock for golang. |
| [go-rate](https://github.com/beefsack/go-rate) | 347 | 11 | 2014/08/25 | 1 year ago | Timed rate limiter for Go. |
| [retry](https://github.com/kamilsk/retry) | 312 | 6 | 2016/11/02 | 10 months ago | The most advanced functional mechanism to perform actions repetitively until successful. |
| [gohper](https://github.com/cosiner/gohper) | 255 | 20 | 2015/03/23 | 4 years ago | Various tools/modules help for development. |
| [serve](https://github.com/syntaqx/serve) | 255 | 6 | 2019/01/10 | 5 months ago | A static http server anywhere you need. |
| [scan](https://github.com/blockloop/scan) | 240 | 6 | 2017/11/27 | 2 months ago | Scan golang `sql.Rows` directly to structs, slices, or primitive types. |
| [util](https://github.com/shomali11/util) | 230 | 12 | 2017/05/24 | 1 year ago | Collection of useful utility functions. (strings, concurrency, manipulations, ...). |
| [go-trigger](https://github.com/sadlil/go-trigger) | 225 | 14 | 2015/10/19 | 4 years ago | Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project. |
| [gotenv](https://github.com/subosito/gotenv) | 209 | 3 | 2013/08/27 | 3 months ago | Load environment variables from `.env` or any `io.Reader` in Go. |
| [grofer](https://github.com/pesos/grofer) | 186 | 8 | 2020/08/01 | 3 weeks ago | A system and resource monitoring tool written in Golang! |
| [death](https://github.com/vrecan/death) | 175 | 4 | 2015/03/09 | 5 days ago | Managing go application shutdown with signals. |
| [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) | 175 | 5 | 2016/11/08 | 2 years ago | go:generate tool for wrapping symbols exported by golang plugins (1.8 only). |
| [mani](https://github.com/alajmo/mani) | 172 | 5 | 2019/10/22 | 1 week ago | CLI tool to help you manage multiple repositories. |
| [toolbox](https://github.com/viant/toolbox) | 168 | 15 | 2016/06/13 | 4 months ago | Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer. |
| [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) | 166 | 6 | 2015/10/12 | 4 days ago | XML Sitemap generator written in Go. |
| [rerun](https://github.com/ivpusic/rerun) | 161 | 7 | 2014/12/10 | 3 years ago | Recompiling and rerunning go apps when source changes. |
| [moldova](https://github.com/StabbyCutyou/moldova) | 160 | 5 | 2016/01/30 | 4 years ago | Utility for generating random data based on an input template. |
| [apm](https://github.com/topfreegames/apm) | 154 | 19 | 2015/11/18 | 5 years ago | Process manager for Golang applications with an HTTP API. |
| [robustly](https://github.com/VividCortex/robustly) | 151 | 16 | 2013/07/08 | 8 months ago | Runs functions resiliently, catching and restarting panics. |
| [changie](https://github.com/miniscruff/changie) | 140 | 3 | 2020/12/05 | 4 days ago | Automated changelog tool for preparing releases with lots of customization options. |
| [chyle](https://github.com/antham/chyle) | 139 | 7 | 2016/11/17 | 1 week ago | Changelog generator using a git repository with multiple configuration possibilities. |
| [countries](https://github.com/biter777/countries) | 136 | 6 | 2019/04/22 | 1 week ago | Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standarts. |
| [go-pattern-match](https://github.com/alexpantyukhin/go-pattern-match) | 135 | 2 | 2018/12/11 | 1 year ago | Pattern matching libray. |
| [clipboard](https://github.com/golang-design/clipboard) | 129 | 3 | 2020/11/19 | 3 months ago | 📋 cross-platform clipboard package in Go. |
| [onecache](https://github.com/adelowo/onecache) | 125 | 7 | 2017/04/14 | 1 year ago | Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc). |
| [go-bsdiff](https://github.com/gabstv/go-bsdiff) | 122 | 3 | 2019/02/23 | 2 years ago | Pure Go bsdiff and bspatch libraries and CLI tools. |
| [lrserver](https://github.com/jaschaephraim/lrserver) | 120 | 5 | 2014/07/15 | 4 years ago | LiveReload server for Go. |
| [cryptgo](https://github.com/Gituser143/cryptgo) | 98 | 2 | 2021/05/20 | 2 months ago | Crytpgo is a TUI based application written purely in Go to monitor and observe cryptocurrency prices in real time! |
| [sorty](https://github.com/jfcg/sorty) | 94 | 4 | 2019/02/18 | 17 hours ago | Fast Concurrent / Parallel Sorting. |
| [goseaweedfs](https://github.com/linxGnu/goseaweedfs) | 91 | 8 | 2017/07/20 | 1 month ago | SeaweedFS client library with almost full features. |
| [nostromo](https://github.com/pokanop/nostromo) | 91 | 5 | 2019/07/13 | 1 month ago | CLI for building powerful aliases. |
| [mssqlx](https://github.com/linxGnu/mssqlx) | 89 | 9 | 2016/12/26 | 3 months ago | Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind. |
| [xferspdy](https://github.com/monmohan/xferspdy) | 89 | 4 | 2015/05/22 | 8 months ago | Xferspdy provides binary diff and patch library in golang. |
| [go-health](https://github.com/Talento90/go-health) | 85 | 3 | 2018/02/13 | 3 years ago | Health package simplifies the way you add health check to your services. |
| [rospo](https://github.com/ferama/rospo) | 82 | 4 | 2021/04/02 | 1 week ago | Simple and reliable ssh tunnels with embedded ssh server in Golang. |
| [mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) | 81 | 3 | 2020/02/04 | 1 month ago | Mongodb Pagination for official mongodb/mongo-go-driver package which supports  both normal queries and Aggregation pipelines. |
| [cmd](https://github.com/commander-cli/cmd) | 77 | 6 | 2019/09/27 | 1 year ago | Library for executing shell commands on osx, windows and linux. |
| [pm](https://github.com/VividCortex/pm) | 77 | 17 | 2013/11/17 | 1 year ago | Process (i.e. goroutine) manager with an HTTP API. |
| [repeat](https://github.com/ssgreg/repeat) | 76 | 6 | 2017/11/22 | 1 year ago | Go implementation of different backoff strategies useful for retrying operations and heartbeating. |
| [mimemagic](https://github.com/zRedShift/mimemagic) | 69 | 2 | 2018/10/11 | 2 weeks ago | Pure Go ultra performant MIME sniffing library/utility. |
| [netbug](https://github.com/e-dard/netbug) | 69 | 2 | 2015/03/05 | 6 years ago | Easy remote profiling of your services. |
| [unis](https://github.com/esemplastic/unis) | 67 | 5 | 2017/05/06 | 4 years ago | Common Architecture™ for String Utilities in Go. |
| [handy](https://github.com/miguelpragier/handy) | 66 | 8 | 2018/06/13 | 1 year ago | Many utilities and helpers like string handlers/formatters and validators. |
| [multitick](https://github.com/VividCortex/multitick) | 65 | 15 | 2013/12/10 | 8 months ago | Multiplexor for aligned tickers. |
| [goreadability](https://github.com/philipjkim/goreadability) | 62 | 6 | 2016/04/20 | 2 years ago | Webpage summary extractor using Facebook Open Graph and arc90's readability. |
| [pgo](https://github.com/arthurkushman/pgo) | 60 | 6 | 2018/12/26 | 4 days ago | Convenient functions for PHP community. |
| [goval](https://github.com/maja42/goval) | 59 | 5 | 2018/06/17 | 10 months ago | Evaluate arbitrary expressions in Go. |
| [limiters](https://github.com/mennanov/limiters) | 59 | 3 | 2019/08/28 | 4 months ago | Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks. |
| [minquery](https://github.com/icza/minquery) | 59 | 2 | 2016/11/16 | 5 months ago | MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off). |
| [go-astitodo](https://github.com/asticode/go-astitodo) | 58 | 2 | 2016/10/17 | 1 year ago | Parse TODOs in your GO code. |
| [golog](https://github.com/mlimaloureiro/golog) | 55 | 3 | 2016/01/09 | 2 years ago | Easy and lightweight CLI tool to time track your tasks. |
| [go-lock](https://github.com/viney-shih/go-lock) | 53 | 1 | 2020/04/30 | 5 months ago | go-lock is a lock library implementing read-write mutex and read-write trylock without starvation. |
| [filter](https://github.com/gookit/filter) | 50 | 6 | 2018/09/26 | 2 months ago | provide filtering, sanitizing, and conversion of Go data. |
| [retry](https://github.com/thedevsaddam/retry) | 50 | 1 | 2018/02/25 | 11 months ago | Simple and easy retry mechanism package for Go. |
| [copy-pasta](https://github.com/jutkko/copy-pasta) | 49 | 5 | 2017/01/28 | 1 year ago | Universal multi-workstation clipboard that uses S3 like backend for the storage. |
| [beyond](https://github.com/wesovilabs/beyond) | 46 | 1 | 2019/10/18 | 3 months ago | The Go tool that will drive you to the AOP world! |
| [golarm](https://github.com/msempere/golarm) | 45 | 2 | 2015/08/14 | 6 years ago | Fire alarms with system events. |
| [slice](https://github.com/psampaz/slice) | 45 | 1 | 2019/11/26 | 1 year ago | Type-safe functions for common Go slice operations. |
| [goback](https://github.com/carlescere/goback) | 44 | 1 | 2015/03/13 | 9 months ago | Go simple exponential backoff package. |
| [dbt](https://github.com/nikogura/dbt) | 43 | 1 | 2017/11/30 | 9 months ago | A framework for running self-updating signed binaries from a central, trusted repository. |
| [retry-go](https://github.com/rafaeljesus/retry-go) | 43 | 2 | 2017/06/09 | 3 years ago | Retrying made simple and easy for golang. |
| [intrinsic](https://github.com/mengzhuo/intrinsic) | 42 | 4 | 2017/06/13 | 4 years ago | Use x86 SIMD without writing any assembly code. |
| [gpath](https://github.com/tenntenn/gpath) | 40 | 3 | 2017/05/24 | 4 years ago | Library to simplify access struct fields with Go's expression in reflection. |
| [go-httpheader](https://github.com/mozillazg/go-httpheader) | 37 | 3 | 2017/06/24 | 3 weeks ago | Go library for encoding structs into Header fields. |
| [myhttp](https://github.com/inancgumus/myhttp) | 35 | 0 | 2017/09/13 | 3 years ago | Simple API to make HTTP GET requests with timeout support. |
| [equalizer](https://github.com/reugn/equalizer) | 34 | 2 | 2019/06/14 | 10 months ago | Quota manager and rate limiter collection for Go. |
| [backscanner](https://github.com/icza/backscanner) | 33 | 4 | 2017/10/18 | 2 months ago | A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. |
| [evaluator](https://github.com/nullne/evaluator) | 33 | 3 | 2017/04/27 | 5 months ago | Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend. |
| [gostrutils](https://github.com/ik5/gostrutils) | 32 | 3 | 2018/09/19 | 3 months ago | Collections of string manipulation and conversion functions. |
| [rclient](https://github.com/zpatrick/rclient) | 32 | 3 | 2017/02/28 | 2 years ago | Readable, flexible, simple-to-use client for REST APIs. |
| [slicer](https://github.com/leaanthony/slicer) | 29 | 2 | 2019/01/10 | 4 months ago | Makes working with slices easier. |
| [set](https://github.com/nofeaturesonlybugs/set) | 28 | 4 | 2020/12/16 | 1 week ago | Performant and flexible struct mapping and loose type conversion. |
| [throttle](https://github.com/yudppp/throttle) | 28 | 1 | 2019/10/25 | 4 months ago | Throttle is an object that will perform exactly one action per duration. |
| [tome](https://github.com/cyruzin/tome) | 28 | 1 | 2019/04/12 | 1 year ago | Tome was designed to paginate simple RESTful APIs. |
| [shutdown](https://github.com/ztrue/shutdown) | 26 | 1 | 2018/11/17 | 2 years ago | App shutdown hooks for `os.Signal` handling. |
| [ugo](https://github.com/alxrm/ugo) | 26 | 2 | 2016/02/17 | 5 years ago | ugo is slice toolbox with concise syntax for Go. |
| [sshman](https://github.com/shoobyban/sshman) | 25 | 1 | 2021/08/27 | 1 week ago | SSH Manager for authorized_keys files on multiple remote servers. |
| [generate](https://github.com/go-playground/generate) | 24 | 3 | 2015/11/15 | 5 years ago | runs go generate recursively on a specified path or environment variable and can filter by regex. |
| [goplaceholder](https://github.com/michiwend/goplaceholder) | 22 | 2 | 2014/10/12 | 6 years ago | a small golang lib to generate placeholder images. |
| [rerate](https://github.com/abo/rerate) | 21 | 4 | 2016/05/24 | 4 years ago | Redis-based rate counter and rate limiter for Go. |
| [ghokin](https://github.com/antham/ghokin) | 20 | 3 | 2018/08/03 | 4 days ago | Parallelized formatter with no external dependencies for gherkin (cucumber, behat...). |
| [mimesniffer](https://github.com/aofei/mimesniffer) | 18 | 1 | 2018/12/20 | 1 month ago | A MIME type sniffer for Go. |
| [structs](https://github.com/PumpkinSeed/structs) | 18 | 3 | 2017/08/26 | 4 years ago | Implement simple functions to manipulate structs. |
| [ctxutil](https://github.com/posener/ctxutil) | 17 | 1 | 2018/07/30 | 1 year ago | A collection of utility functions for contexts. |
| [filler](https://github.com/yaronsumel/filler) | 16 | 1 | 2017/04/05 | 4 years ago | small utility to fill structs using "fill" tag. |
| [rest-go](https://github.com/edermanoel94/rest-go) | 16 | 3 | 2019/07/29 | 1 year ago | A package that provide many helpful methods for working with rest api. |
| [dlog](https://github.com/kirillDanshin/dlog) | 15 | 2 | 2016/07/04 | 4 years ago | Compile-time controlled logger to make your release smaller without removing debug calls. |
| [go-convert](https://github.com/Eun/go-convert) | 15 | 1 | 2019/06/07 | 7 months ago | Package go-convert enables you to convert a value into another type. |
| [okrun](https://github.com/xta/okrun) | 15 | 3 | 2014/10/01 | 7 years ago | go run error steamroller. |
| [copy](https://github.com/gotidy/copy) | 14 | 3 | 2020/10/09 | 1 year ago | Package for fast copying structs of different types. |
| [jsend](https://github.com/clevergo/jsend) | 14 | 4 | 2020/01/14 | 6 months ago | JSend's implementation writen in Go. |
| [command](https://github.com/txgruppi/command) | 13 | 1 | 2015/08/24 | 5 years ago | Command pattern for Go with thread safe serial and parallel dispatcher. |
| [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) | 12 | 1 | 2019/05/16 | 1 year ago | Go package for working with Problem Details. |
| [go-types](https://github.com/mikekonan/go-types) | 12 | 1 | 2021/04/21 | 1 month ago | Library providing Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types. |
| [ptr](https://github.com/gotidy/ptr) | 11 | 2 | 2019/12/25 | 1 week ago | Package that provide functions for simplified creation of pointers from constants of basic types. |
| [retry](https://github.com/shafreeck/retry) | 10 | 0 | 2018/07/18 | 1 year ago | A pretty simple library to ensure your work to be done. |
| [silk](https://github.com/chrispassas/silk) | 10 | 1 | 2018/12/18 | 1 year ago | Read silk netflow files. |
| [go-countries](https://github.com/mikekonan/go-countries) | 9 | 3 | 2020/10/27 | 1 year ago | Lightweight lookup over ISO-3166 codes. |
| [statiks](https://github.com/janiltonmaciel/statiks) | 9 | 0 | 2018/06/26 | 1 year ago | Fast, zero-configuration, static HTTP filer server. |
| [blank](https://github.com/Henry-Sarabia/blank) | 7 | 2 | 2019/02/13 | 2 years ago | Verify or remove blanks and whitespace from strings. |
| [go-clip](https://github.com/prashantgupta24/go-clip) | 7 | 2 | 2020/11/18 | 10 months ago | A minimalistic clipboard manager for Mac. |
| [retry](https://github.com/percolate/retry) | 7 | 41 | 2018/06/15 | 2 years ago | A simple but highly configurable retry package for Go. |
| [sliceconv](https://github.com/Henry-Sarabia/sliceconv) | 7 | 1 | 2019/02/15 | 1 year ago | Slice conversion between primitive types. |
| [nfdump](https://github.com/chrispassas/nfdump) | 6 | 1 | 2020/04/08 | 4 months ago | Read nfdump netflow files. |
| [go-safe](https://github.com/kenkyu392/go-safe) | 5 | 0 | 2019/10/29 | 4 weeks ago | Panic-safe sandbox. |
| [go-actuator](https://github.com/sinhashubham95/go-actuator) | 3 | 1 | 2021/07/17 | 4 months ago | Production ready features for Go based web frameworks. |
| [lets-go](https://github.com/aplescia/lets-go) | 3 | 1 | 2020/02/19 | 8 months ago | Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities. |
| [olaf](https://github.com/btnguyen2k/olaf) | 3 | 1 | 2019/01/03 | 2 years ago | Twitter Snowflake implemented in Go. |
| [tik](https://github.com/andy2046/tik) | 3 | 1 | 2020/07/04 | 1 year ago | Simple and easy timing wheel package for Go. |
| [bleep](https://github.com/sinhashubham95/bleep) | 2 | 1 | 2021/01/02 | 11 months ago | Perform any number of actions on any set of OS signals in Go. |
| [goctx](https://github.com/zerosnake0/goctx) | 2 | 1 | 2020/11/14 | 1 year ago | Get your context value with high performance. |
**[⬆ back to top](#awesome-go-info)**

## Validation
        
*Libraries for validation.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [validator](https://github.com/go-playground/validator) | 9328 | 100 | 2015/02/12 | 1 week ago | Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving. |
| [govalidator](https://github.com/asaskevich/govalidator) | 5179 | 95 | 2014/06/20 | 2 months ago | Validators and sanitizers for strings, numerics, slices and structs. |
| [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) | 2491 | 29 | 2016/06/22 | 3 weeks ago | Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags. |
| [govalidator](https://github.com/thedevsaddam/govalidator) | 1037 | 21 | 2017/09/13 | 11 months ago | Validate Golang request data with simple rules. Highly inspired by Laravel's request validation. |
| [validate](https://github.com/gookit/validate) | 501 | 16 | 2018/07/16 | 1 month ago | Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features. |
| [checkdigit](https://github.com/osamingo/checkdigit) | 85 | 0 | 2019/04/05 | 1 year ago | Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.). |
| [terraform-validator](https://github.com/thazelart/terraform-validator) | 75 | 3 | 2019/05/29 | 1 year ago | A norms and conventions validator for Terraform. |
| [validate](https://github.com/gobuffalo/validate) | 66 | 10 | 2018/02/10 | 1 month ago | This package provides a framework for writing validations for Go applications. |
| [jio](https://github.com/faceair/jio) | 63 | 2 | 2018/10/28 | 1 year ago | jio is a json schema validator similar to [joi](https://github.com/hapijs/joi). |
| [gody](https://github.com/guiferpa/gody) | 52 | 0 | 2018/11/01 | 10 months ago | :balloon: A lightweight struct validator for Go. |
| [govalid](https://github.com/twharmon/govalid) | 23 | 1 | 2019/02/17 | 2 months ago | Fast, tag-based validation for structs. |
**[⬆ back to top](#awesome-go-info)**

## Version Control
        
*Libraries for version control.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-git](https://github.com/go-git/go-git) | 2905 | 39 | 2019/12/19 | 1 week ago | highly extensible Git implementation in pure Go. |
| [git2go](https://github.com/libgit2/git2go) | 1683 | 50 | 2013/03/05 | 6 days ago | Go bindings for libgit2. |
| [glab](https://github.com/profclems/glab) | 1631 | 20 | 2020/07/24 | 1 week ago | An open-source GitLab command line tool bringing GitLab's cool features to your command line. |
| [hercules](https://github.com/src-d/hercules) | 1631 | 21 | 2016/12/12 | 1 month ago | gaining advanced insights from Git repository history. |
| [gh](https://github.com/rjeczalik/gh) | 76 | 6 | 2015/03/08 | 3 years ago | Scriptable server and net/http middleware for GitHub Webhooks. |
| [go-vcs](https://github.com/sourcegraph/go-vcs) | 74 | 79 | 2013/06/02 | 9 months ago | manipulate and inspect VCS repositories in Go. |
| [Githooks](https://github.com/gabyx/Githooks) | 31 | 0 | 2019/06/28 | 17 hours ago | Per-repo and shared Git hooks with version control and auto update. |
| [hgo](https://github.com/beyang/hgo) | 13 | 4 | 2014/06/18 | 6 years ago | Hgo is a collection of Go packages providing read-access to local Mercurial repositories. |
**[⬆ back to top](#awesome-go-info)**

## Video
        
*Libraries for manipulating video.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [goav](https://github.com/giorgisio/goav) | 1780 | 49 | 2015/05/21 | 6 months ago | Comprehensive Go bindings for FFmpeg. |
| [m3u8](https://github.com/grafov/m3u8) | 885 | 39 | 2013/02/05 | 6 days ago | Parser and generator library of M3U8 playlists for Apple HLS. |
| [gmf](https://github.com/3d0c/gmf) | 729 | 30 | 2013/04/03 | 2 months ago | Go bindings for FFmpeg av\* libraries. |
| [go-astits](https://github.com/asticode/go-astits) | 381 | 15 | 2017/07/04 | 2 months ago | Parse and demux MPEG Transport Streams (.ts) natively in GO. |
| [go-astisub](https://github.com/asticode/go-astisub) | 362 | 7 | 2016/12/16 | 2 weeks ago | Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.). |
| [libvlc-go](https://github.com/adrg/libvlc-go) | 265 | 11 | 2015/01/06 | 3 months ago | Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player). |
| [gortsplib](https://github.com/aler9/gortsplib) | 167 | 8 | 2020/01/20 | 6 days ago | Pure Go RTSP server and client library. |
| [gst](https://github.com/ziutek/gst) | 163 | 10 | 2011/07/26 | 11 months ago | Go bindings for GStreamer. |
| [go-m3u8](https://github.com/quangngotan95/go-m3u8) | 83 | 2 | 2018/11/06 | 1 year ago | Parser and generator library for Apple m3u8 playlists. |
| [v4l](https://github.com/korandiz/v4l) | 63 | 6 | 2016/10/25 | 2 weeks ago | Video capture library for Linux, written in Go. |
| [libgosubs](https://github.com/wargarblgarbl/libgosubs) | 16 | 2 | 2017/05/03 | 1 year ago | Subtitle format support for go. Supports .srt, .ttml, and .ass. |
| [go-mpd](https://github.com/unki2aut/go-mpd) | 10 | 1 | 2018/11/02 | 1 year ago | Parser and generator library for MPEG-DASH manifest files. |
**[⬆ back to top](#awesome-go-info)**

## Web Frameworks
        
*Full stack web frameworks.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gin](https://github.com/gin-gonic/gin) | 54226 | 1354 | 2014/06/16 | 1 hour ago | Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity. |
| [echo](https://github.com/labstack/echo) | 21360 | 532 | 2015/03/01 | 1 week ago | High performance, minimalist Go web framework. |
| [fiber](https://github.com/gofiber/fiber) | 17459 | 243 | 2020/01/16 | 1 hour ago | An Express.js inspired web framework build on Fasthttp. |
| [revel](https://github.com/revel/revel) | 12468 | 536 | 2011/12/09 | 1 month ago | High-productivity web framework for the Go language. |
| [goa](https://github.com/goadesign/goa) | 4508 | 165 | 2014/12/05 | 1 day ago | Goa provides a holistic approach for developing remote APIs and microservices in Go. |
| [gizmo](https://github.com/nytimes/gizmo) | 3575 | 121 | 2015/12/15 | 4 months ago | Microservice toolkit used by the New York Times. |
| [go-json-rest](https://github.com/ant0ine/go-json-rest) | 3492 | 160 | 2013/02/19 | 11 months ago | Quick and easy way to setup a RESTful JSON API. |
| [macaron](https://github.com/go-macaron/macaron) | 3238 | 145 | 2014/07/10 | 1 week ago | Macaron is a high productive and modular design web framework in Go. |
| [utron](https://github.com/gernest/utron) | 2205 | 69 | 2015/09/16 | 3 years ago | Lightweight MVC framework for Go(Golang). |
| [go-tigertonic](https://github.com/rcrowley/go-tigertonic) | 997 | 46 | 2013/02/09 | 3 years ago | Go framework for building JSON web services inspired by Dropwizard. |
| [goyave](https://github.com/go-goyave/goyave) | 928 | 27 | 2019/10/21 | 1 day ago | Feature-complete REST API framework aimed at clean code and fast development, with powerful built-in functionalities. |
| [tango](https://github.com/lunny/tango) | 834 | 75 | 2014/12/17 | 2 years ago | Micro & pluggable web framework for Go. |
| [gearbox](https://github.com/gogearbox/gearbox) | 590 | 17 | 2020/04/25 | 3 weeks ago | A web framework written in Go with a focus on high performance and memory optimization. |
| [gongular](https://github.com/mustafaakin/gongular) | 447 | 21 | 2016/06/22 | 1 year ago | Fast Go web framework with input mapping/validation and (DI) Dependency Injection. |
| [aero](https://github.com/aerogo/aero) | 424 | 21 | 2016/11/09 | 1 month ago | High-performance web framework for Go, reaches top scores in Lighthouse. |
| [neo](https://github.com/ivpusic/neo) | 415 | 34 | 2015/02/04 | 4 years ago | Neo is minimal and fast Go Web Framework with extremely simple API. |
| [air](https://github.com/aofei/air) | 407 | 19 | 2016/07/20 | 8 months ago | An ideally refined web framework for Go. |
| [mango](https://github.com/paulbellamy/mango) | 359 | 21 | 2011/05/25 | 4 years ago | Mango is a modular web-application framework for Go, inspired by Rack, and PEP333. |
| [beego](https://github.com/astaxie/beego) | 329 | 9 | 2020/12/13 | 4 months ago | beego is an open-source, high-performance web framework for the Go programming language. |
| [gondola](https://github.com/rainycape/gondola) | 308 | 15 | 2014/07/25 | 2 years ago | The web framework for writing faster sites, faster. |
| [flamingo](https://github.com/i-love-flamingo/flamingo) | 263 | 26 | 2019/04/02 | 4 weeks ago | Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc. |
| [golf](https://github.com/dinever/golf) | 251 | 16 | 2015/11/18 | 4 months ago | Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library. |
| [flamingo-commerce](https://github.com/i-love-flamingo/flamingo-commerce) | 245 | 22 | 2019/04/02 | 3 weeks ago | Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications. |
| [webgo](https://github.com/bnkamalesh/webgo) | 211 | 9 | 2015/12/16 | 2 months ago | A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc). |
| [ginrpc](https://github.com/xxjwxc/ginrpc) | 199 | 8 | 2019/06/22 | 2 weeks ago | Gin parameter automatic binding tool,gin rpc tools. |
| [uadmin](https://github.com/uadmin/uadmin) | 166 | 14 | 2018/10/05 | 1 month ago | Fully featured web framework for Golang, inspired by Django. |
| [hiboot](https://github.com/hidevopsio/hiboot) | 162 | 14 | 2018/03/16 | 6 months ago | hiboot is a high performance web application framework with auto configuration and dependency injection support. |
| [go-rest](https://github.com/ungerik/go-rest) | 125 | 10 | 2012/07/13 | 5 years ago | Small and evil REST framework for Go. |
| [appy](https://github.com/appist/appy) | 114 | 4 | 2019/05/27 | 1 month ago | An opinionated productive web framework that helps scaling business easier. |
| [rk-boot](https://github.com/rookie-ninja/rk-boot) | 101 | 3 | 2020/07/31 | 4 days ago | A bootstrapper library for building enterprise go microservice with Gin and gRPC quickly and easily. |
| [patron](https://github.com/beatlabs/patron) | 86 | 15 | 2019/01/30 | 1 hour ago | Patron is a microservice framework following best cloud practices with a focus on productivity. |
| [microservice](https://github.com/claygod/microservice) | 76 | 9 | 2016/12/15 | 1 week ago | The framework for the creation of microservices, written in Golang. |
| [vox](https://github.com/aisk/vox) | 74 | 2 | 2014/12/24 | 7 months ago | A golang web framework for humans, inspired by Koa heavily. |
| [golax](https://github.com/fulldump/golax) | 72 | 7 | 2016/01/30 | 3 years ago | A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more. |
| [rux](https://github.com/gookit/rux) | 69 | 4 | 2018/08/05 | 2 months ago | Simple and fast web framework for build golang HTTP applications. |
| [yarf](https://github.com/yarf-framework/yarf) | 64 | 4 | 2015/09/02 | 2 years ago | Fast micro-framework designed to build REST APIs and web services in a fast and simple way. |
| [fireball](https://github.com/zpatrick/fireball) | 55 | 4 | 2016/07/20 | 3 years ago | More "natural" feeling web framework. |
| [goa](https://github.com/goa-go/goa) | 45 | 4 | 2019/07/26 | 2 years ago | goa is just like koajs for golang, it is a flexible, light, high-performance and extensible web framework based on middleware. |
| [gotuna](https://github.com/gotuna/gotuna) | 37 | 1 | 2021/04/08 | 5 months ago | Minimalistic web framework for Go with mux router, middlewares, sessions, templates, embedded views and static files. |
| [api](https://github.com/resoursea/api) | 31 | 6 | 2015/01/24 | 7 years ago | REST framework for quickly writing resource based services. |
| [rex](https://github.com/goanywhere/rex) | 31 | 2 | 2014/10/16 | 4 years ago | Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`. |
| [goweb](https://github.com/twharmon/goweb) | 25 | 1 | 2019/05/07 | 10 months ago | Web framework with routing, websockets, logging, middleware, static file server (optional gzip), and automatic TLS. |
| [banjo](https://github.com/n4Zz2/banjo) | 18 | 1 | 2017/12/09 | 3 years ago | Very simple and fast web framework for Go. |
**[⬆ back to top](#awesome-go-info)**

### Middlewares
        
**[⬆ back to top](#awesome-go-info)**

#### Actual middlewares
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [tollbooth](https://github.com/didip/tollbooth) | 2083 | 49 | 2015/05/17 | 3 weeks ago | Rate limit HTTP request handler. |
| [cors](https://github.com/rs/cors) | 1982 | 31 | 2014/10/25 | 6 days ago | Easily add CORS capabilities to your API. |
| [limiter](https://github.com/ulule/limiter) | 1462 | 29 | 2015/10/02 | 2 weeks ago | Dead simple rate limit middleware for Go. |
| [go-server-timing](https://github.com/mitchellh/go-server-timing) | 821 | 18 | 2018/02/12 | 1 year ago | Add/parse Server-Timing header. |
| [go-fault](https://github.com/github/go-fault) | 418 | 130 | 2020/05/14 | 3 months ago | Fault injection middleware for Go. |
| [ln-paywall](https://github.com/philippgille/ln-paywall) | 116 | 5 | 2018/06/29 | 2 years ago | Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin). |
| [xff](https://github.com/sebest/xff) | 85 | 3 | 2014/12/22 | 11 months ago | Handle `X-Forwarded-For` header and friends. |
| [formjson](https://github.com/rs/formjson) | 35 | 2 | 2015/03/19 | 6 years ago | Transparently handle JSON input as a standard form POST. |
| [client-timing](https://github.com/posener/client-timing) | 19 | 1 | 2018/02/23 | 1 year ago | An HTTP client for Server-Timing header. |
| [rk-grpc](https://github.com/rookie-ninja/rk-grpc) | 19 | 2 | 2020/07/25 | 7 hours ago | Middleware for gRPC with logging, metrics, auth, tracing etc. |
| [rk-gin](https://github.com/rookie-ninja/rk-gin) | 18 | 2 | 2020/10/12 | 18 hours ago | Middleware for Gin framework with logging, metrics, auth, tracing etc. |
| [mid](https://github.com/bobg/mid) | 2 | 1 | 2020/07/13 | 4 months ago | Miscellaneous HTTP middleware features: idiomatic error return from handlers; receive/respond with JSON data; request tracing; and more. |
**[⬆ back to top](#awesome-go-info)**

#### Libraries for creating HTTP middlewares
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [negroni](https://github.com/urfave/negroni) | 7123 | 236 | 2014/05/18 | 2 days ago | Idiomatic HTTP middleware for Golang. |
| [alice](https://github.com/justinas/alice) | 2439 | 48 | 2014/05/25 | 1 month ago | Painless middleware chaining for Go. |
| [render](https://github.com/unrolled/render) | 1568 | 36 | 2014/06/10 | 1 month ago | Go package for easily rendering JSON, XML, and HTML template responses. |
| [stats](https://github.com/thoas/stats) | 581 | 16 | 2015/03/05 | 2 years ago | Go middleware that stores various information about your web application. |
| [interpose](https://github.com/carbocation/interpose) | 295 | 12 | 2014/07/20 | 5 years ago | Minimalist net/http middleware for golang. |
| [renderer](https://github.com/thedevsaddam/renderer) | 231 | 7 | 2017/11/07 | 11 months ago | Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go. |
| [muxchain](https://github.com/stephens2424/muxchain) | 209 | 5 | 2014/05/03 | 2 years ago | Lightweight middleware for net/http. |
| [gores](https://github.com/alioygur/gores) | 96 | 5 | 2015/12/25 | 1 year ago | Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs. |
| [rye](https://github.com/InVisionApp/rye) | 95 | 203 | 2016/10/06 | 3 years ago | Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context. |
| [mediary](https://github.com/HereMobilityDevelopers/mediary) | 78 | 5 | 2020/03/23 | 1 year ago | add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses. |
| [chain](https://github.com/codemodus/chain) | 63 | 7 | 2015/05/14 | 3 years ago | Handler wrapper chaining with scoped data (net/context-based "middleware"). |
| [wrap](https://github.com/go-on/wrap) | 59 | 3 | 2014/02/16 | 3 years ago | Small middlewares package for net/http. |
| [catena](https://github.com/codemodus/catena) | 7 | 2 | 2015/07/30 | 3 years ago | http.Handler wrapper catenation (same API as "chain"). |
**[⬆ back to top](#awesome-go-info)**

### Routers
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [mux](https://github.com/gorilla/mux) | 15728 | 312 | 2012/10/02 | 6 days ago | Powerful URL router and dispatcher for golang. |
| [httprouter](https://github.com/julienschmidt/httprouter) | 13532 | 327 | 2013/12/05 | 1 month ago | High performance router. Use this and the standard http handlers to form a very high performance web framework. |
| [chi](https://github.com/go-chi/chi) | 10631 | 178 | 2015/10/15 | 3 weeks ago | Small, fast and expressive HTTP router built on net/context. |
| [web](https://github.com/gocraft/web) | 1453 | 59 | 2013/11/16 | 1 year ago | Mux and middleware package in Go. |
| [bone](https://github.com/go-zoo/bone) | 1276 | 35 | 2014/11/19 | 2 years ago | Lightning Fast HTTP Multiplexer. |
| [goji](https://github.com/goji/goji) | 893 | 42 | 2015/11/16 | 2 years ago | Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`. |
| [fasthttprouter](https://github.com/buaazp/fasthttprouter) | 870 | 34 | 2015/12/13 | 2 years ago | High performance router forked from `httprouter`. The first router fit for `fasthttp`. |
| [httptreemux](https://github.com/dimfeld/httptreemux) | 518 | 23 | 2014/05/14 | 1 month ago | High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter. |
| [gorouter](https://github.com/xujiajun/gorouter) | 510 | 16 | 2018/01/29 | 2 years ago | A simple and fast HTTP router for Go. |
| [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) | 423 | 29 | 2015/10/27 | 3 months ago | An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs. |
| [lars](https://github.com/go-playground/lars) | 384 | 15 | 2015/12/24 | 2 years ago | Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks. |
| [siesta](https://github.com/VividCortex/siesta) | 349 | 28 | 2014/09/23 | 8 months ago | Composable framework to write middleware and handlers. |
| [vestigo](https://github.com/husobee/vestigo) | 265 | 15 | 2015/09/22 | 1 year ago | Performant, stand-alone, HTTP compliant URL Router for go web applications. |
| [router](https://github.com/gowww/router) | 159 | 7 | 2017/05/25 | 1 year ago | Lightning fast HTTP router fully compatible with the net/http.Handler interface. |
| [pure](https://github.com/go-playground/pure) | 121 | 7 | 2016/09/23 | 1 year ago | Is a lightweight HTTP router that sticks to the std "net/http" implementation. |
| [alien](https://github.com/gernest/alien) | 120 | 4 | 2016/01/30 | 2 years ago | Lightweight and fast http router from outer space. |
| [gorouter](https://github.com/vardius/gorouter) | 103 | 6 | 2016/07/14 | 1 month ago | GoRouter is a Server/API micro framework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`. |
| [violetear](https://github.com/nbari/violetear) | 103 | 4 | 2015/06/19 | 7 months ago | Go HTTP router. |
| [Bxog](https://github.com/claygod/Bxog) | 101 | 8 | 2016/05/19 | 1 year ago | Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters. |
| [xmux](https://github.com/rs/xmux) | 92 | 6 | 2015/12/14 | 4 years ago | High performance muxer based on `httprouter` with `net/context` support. |
| [bellt](https://github.com/GuilhermeCaruso/bellt) | 51 | 6 | 2019/02/21 | 1 year ago | A simple Go HTTP router. |
| [ngamux](https://github.com/ngamux/ngamux) | 45 | 1 | 2021/08/22 | 2 months ago | Simple HTTP router for Go. |
| [fastrouter](https://github.com/razonyang/fastrouter) | 19 | 2 | 2017/11/01 | 4 years ago | a fast, flexible HTTP router written in Go. |
| [route](https://github.com/goroute/route) | 6 | 4 | 2019/07/06 | 2 years ago | Simple yet powerful HTTP request multiplexer. |
**[⬆ back to top](#awesome-go-info)**

## WebAssembly
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [tinygo](https://github.com/tinygo-org/tinygo) | 9116 | 160 | 2018/06/07 | 17 minutes ago | Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM. |
| [dom](https://github.com/dennwc/dom) | 438 | 17 | 2018/06/30 | 2 years ago | DOM library. |
| [go-canvas](https://github.com/markfarnan/go-canvas) | 149 | 7 | 2019/05/05 | 1 year ago | Library to use HTML5 Canvas, with all drawing within go code. |
| [wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) | 111 | 3 | 2018/07/14 | 1 month ago | Run Go WASM tests in your browser. |
| [webapi](https://github.com/gowebapi/webapi) | 91 | 8 | 2019/02/08 | 11 months ago | Bindings for DOM and HTML generated from WebIDL. |
| [vert](https://github.com/norunners/vert) | 57 | 6 | 2018/03/25 | 2 days ago | Interop between Go and JS values. |
**[⬆ back to top](#awesome-go-info)**

## Windows
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-ole](https://github.com/go-ole/go-ole) | 823 | 40 | 2011/01/21 | 1 week ago | Win32 OLE implementation for golang. |
| [d3d9](https://github.com/gonutz/d3d9) | 128 | 8 | 2015/12/12 | 2 weeks ago | Go bindings for Direct3D9. |
| [gosddl](https://github.com/MonaxGT/gosddl) | 8 | 2 | 2018/12/04 | 2 years ago | Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL. |
**[⬆ back to top](#awesome-go-info)**

## XML
        
*Libraries and tools for manipulating XML.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [zek](https://github.com/miku/zek) | 516 | 20 | 2017/11/23 | 3 months ago | Generate a Go struct from XML. |
| [xpath](https://github.com/antchfx/xpath) | 441 | 12 | 2016/10/09 | 3 months ago | XPath package for Go. |
| [xquery](https://github.com/antchfx/xquery) | 154 | 11 | 2016/10/09 | 3 years ago | XQuery lets you extract data from HTML/XML documents using XPath expression. |
| [xml2map](https://github.com/sbabiv/xml2map) | 37 | 3 | 2018/08/06 | 2 weeks ago | XML to MAP converter written Golang. |
| [xmlwriter](https://github.com/shabbyrobe/xmlwriter) | 20 | 2 | 2017/04/11 | 9 months ago | Procedural XML generation API based on libxml2's xmlwriter module. |
| [XML-Comp](https://github.com/XML-Comp/XML-Comp) | 15 | 2 | 2016/10/25 | 3 years ago | Simple command line XML comparer that generates diffs of folders, files and tags. |
**[⬆ back to top](#awesome-go-info)**

## Zero Trust
        
*Libraries and tools to implement Zero Trust architectures.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [cosign](https://github.com/sigstore/cosign) | 1389 | 34 | 2021/02/04 | 3 hours ago | Container Signing, Verification and Storage in an OCI registry. |
| [spire](https://github.com/spiffe/spire) | 1020 | 84 | 2017/08/11 | 6 days ago | SPIRE (the SPIFFE Runtime Environment) is a toolchain of APIs for establishing trust between software systems across a wide variety of hosting platforms. |
| [in-toto-golang](https://github.com/in-toto/in-toto-golang) | 46 | 10 | 2018/10/15 | 2 weeks ago | Go implementation of the in-toto (provides a framework to protect the integrity of the software supply chain) python reference implementation. |
| [spiffe-vault](https://github.com/philips-labs/spiffe-vault) | 8 | 1 | 2021/08/26 | 1 day ago | Utilizes Spiffe JWT authentication with Hashicorp Vault for secretless authentication. |
**[⬆ back to top](#awesome-go-info)**

# Tools
        
*Go software and plugins.*
**[⬆ back to top](#awesome-go-info)**

## Code Analysis
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [lint](https://github.com/golang/lint) | 3922 | 103 | 2013/06/02 | 7 months ago | Golint is a linter for Go source code. |
| [errcheck](https://github.com/kisielk/errcheck) | 1772 | 26 | 2013/02/24 | 5 days ago | Errcheck is a program for checking for unchecked errors in Go programs. |
| [go-critic](https://github.com/go-critic/go-critic) | 1201 | 20 | 2018/05/05 | 7 hours ago | source code linter that brings checks that are currently not implemented in other linters. |
| [gcvis](https://github.com/davecheney/gcvis) | 1050 | 35 | 2014/07/10 | 2 years ago | Visualise Go program GC trace data in real time. |
| [php-parser](https://github.com/z7zmey/php-parser) | 843 | 29 | 2017/11/07 | 8 months ago | A Parser for PHP written in Go. |
| [goplantuml](https://github.com/jfeliu007/goplantuml) | 617 | 11 | 2019/05/26 | 3 weeks ago | Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them. |
| [goast-viewer](https://github.com/yuroyoro/goast-viewer) | 564 | 16 | 2014/06/30 | 2 years ago | Web based Golang AST visualizer. |
| [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) | 552 | 5 | 2019/04/19 | 2 months ago | An easy way to find outdated dependencies of your Go projects. |
| [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) | 544 | 11 | 2017/04/12 | 1 month ago | go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects. |
| [todocheck](https://github.com/preslavmihaylov/todocheck) | 362 | 5 | 2020/07/18 | 2 months ago | Static code analyser which links TODO comments in code with issues in your issue tracker. |
| [unconvert](https://github.com/mdempsky/unconvert) | 313 | 8 | 2016/02/19 | 1 year ago | Remove unnecessary type conversions from Go source. |
| [golines](https://github.com/segmentio/golines) | 286 | 15 | 2019/10/01 | 1 week ago | Formatter that automatically shortens long lines in Go code. |
| [tickgit](https://github.com/augmentable-dev/tickgit) | 271 | 8 | 2019/10/12 | 1 year ago | CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author. |
| [dupl](https://github.com/mibk/dupl) | 267 | 8 | 2015/05/20 | 1 year ago | Tool for code clone detection. |
| [gostatus](https://github.com/shurcooL/gostatus) | 245 | 7 | 2013/11/27 | 2 years ago | Command line tool, shows the status of repositories that contain Go packages. |
| [apicompat](https://github.com/bradleyfalzon/apicompat) | 175 | 7 | 2016/07/10 | 4 years ago | Checks recent changes to a Go project for backwards incompatible changes. |
| [checkstyle](https://github.com/qiniu/checkstyle) | 118 | 12 | 2014/01/01 | 9 months ago | checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments. |
| [lint](https://github.com/surullabs/lint) | 66 | 5 | 2016/07/09 | 3 years ago | Run linters as part of go test. |
| [validate](https://github.com/mccoyst/validate) | 60 | 6 | 2013/11/22 | 5 years ago | Automatically validates struct fields with tags. |
| [go-outdated](https://github.com/firstrow/go-outdated) | 44 | 1 | 2015/06/29 | 2 years ago | Console application that displays outdated packages. |
| [blanket](https://github.com/verygoodsoftwarenotvirus/blanket) | 14 | 3 | 2017/09/04 | 3 years ago | tarp finds functions and methods without direct unit tests in Go source code. |
| [golang-ifood-sdk](https://github.com/arxdsilva/golang-ifood-sdk) | 7 | 1 | 2021/03/13 | 1 month ago | iFood API SDK. |
**[⬆ back to top](#awesome-go-info)**

## Editor Plugins
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [vim-go](https://github.com/fatih/vim-go) | 14117 | 268 | 2014/03/24 | 1 month ago | Go development plugin for Vim. |
| [gocode](https://github.com/nsf/gocode) | 4943 | 191 | 2010/07/05 | 2 months ago | Autocompletion daemon for the Go programming language. |
| [GoSublime](https://github.com/DisposaBoy/GoSublime) | 3420 | 117 | 2011/08/27 | 1 year ago | Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features. |
| [vscode-go](https://github.com/golang/vscode-go) | 2286 | 53 | 2020/03/06 | 2 days ago | Extension for Visual Studio Code (VS Code) which provides support for the Go language. |
| [go-plus](https://github.com/joefitzgerald/go-plus) | 1520 | 44 | 2014/03/13 | 7 months ago | Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting. |
| [go-mode.el](https://github.com/dominikh/go-mode.el) | 1214 | 52 | 2013/01/30 | 1 week ago | Go mode for GNU/Emacs. |
| [coc-go](https://github.com/josa42/coc-go) | 407 | 4 | 2019/04/25 | 5 days ago | This plugin adds [gopls](https://github.com/golang/tools/blob/master/gopls/README.md) features to Vim/Neovim. |
| [Watch](https://github.com/eaburns/Watch) | 188 | 13 | 2013/08/08 | 3 years ago | Runs a command in an acme win on file changes. |
| [goimports-reviser](https://github.com/incu6us/goimports-reviser) | 97 | 4 | 2020/04/08 | 1 week ago | Formatting tool for imports. |
| [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) | 88 | 5 | 2012/11/25 | 5 years ago | Vim plugin to highlight syntax errors on save. |
| [go-language-server](https://github.com/theia-ide/go-language-server) | 31 | 4 | 2017/11/21 | 2 years ago | A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol. |
| [gounit-vim](https://github.com/hexdigest/gounit-vim) | 22 | 2 | 2018/02/21 | 3 years ago | Vim plugin for generating Go tests based on the function's or method's signature. |
| [theia-go-extension](https://github.com/theia-ide/theia-go-extension) | 16 | 4 | 2017/11/30 | 2 years ago | Go language support for the Theia IDE. |
| [vscode-go-doc](https://github.com/msyrus/vscode-go-doc) | 5 | 2 | 2018/03/15 | 6 months ago | A Visual Studio Code extension for showing definition in output and generating go doc. |
**[⬆ back to top](#awesome-go-info)**

## Go Generate Tools
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gotests](https://github.com/cweill/gotests) | 3606 | 75 | 2016/01/19 | 2 months ago | Generate Go tests from your source code. |
| [genny](https://github.com/cheekybits/genny) | 1618 | 25 | 2014/10/27 | 4 months ago | Elegant generics for Go. |
| [re2dfa](https://github.com/opennota/re2dfa) | 190 | 9 | 2015/06/20 | 3 years ago | Transform regular expressions into finite state machines and output Go source code. |
| [xgen](https://github.com/xuri/xgen) | 125 | 11 | 2019/06/22 | 4 weeks ago | XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator. |
| [gonerics](https://github.com/bouk/gonerics) | 113 | 4 | 2014/09/29 | 7 years ago | Idiomatic Generics in Go. |
| [hasgo](https://github.com/DylanMeeus/hasgo) | 108 | 6 | 2019/05/16 | 8 months ago | Generate Haskell inspired functions for your slices. |
| [gocontracts](https://github.com/Parquery/gocontracts) | 78 | 8 | 2018/08/13 | 2 years ago | brings design-by-contract to Go by synchronizing the code with the documentation. |
| [gounit](https://github.com/hexdigest/gounit) | 61 | 5 | 2018/02/05 | 3 years ago | Generate Go tests using your own templates. |
| [generic](https://github.com/usk81/generic) | 41 | 3 | 2016/06/15 | 11 months ago | flexible data type for Go. |
| [godal](https://github.com/mafulong/godal) | 11 | 1 | 2021/03/16 | 2 months ago | Generate orm models corresponding to golang by specifying sql ddl file, which can be used by gorm. |
**[⬆ back to top](#awesome-go-info)**

## Go Tools
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-swagger](https://github.com/go-swagger/go-swagger) | 7082 | 120 | 2014/11/16 | 3 days ago | Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API. |
| [OctoLinker](https://github.com/OctoLinker/OctoLinker) | 4857 | 90 | 2013/12/27 | 1 week ago | Navigate through go files efficiently with the OctoLinker browser extension for GitHub. |
| [go-callvis](https://github.com/ofabry/go-callvis) | 3703 | 74 | 2016/09/03 | 1 month ago | Visualize call graph of your Go program using dot format. |
| [depth](https://github.com/KyleBanks/depth) | 665 | 13 | 2017/03/04 | 2 weeks ago | Visualize dependency trees of any package by analyzing imports. |
| [richgo](https://github.com/kyoh86/richgo) | 635 | 5 | 2017/01/04 | 2 weeks ago | Enrich `go test` outputs with text decorations. |
| [rts](https://github.com/galeone/rts) | 227 | 3 | 2016/04/04 | 3 months ago | RTS: response to struct. Generates Go structs from server responses. |
| [godbg](https://github.com/tylerwince/godbg) | 180 | 4 | 2019/01/23 | 2 years ago | Implementation of Rusts `dbg!` macro for quick and easy debugging during development. |
| [typex](https://github.com/dtgorski/typex) | 136 | 3 | 2020/03/24 | 11 months ago | Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration. |
| [colorgo](https://github.com/songgao/colorgo) | 108 | 4 | 2013/02/14 | 1 year ago | Wrapper around `go` command for colorized `go build` output. |
| [gothanks](https://github.com/psampaz/gothanks) | 107 | 3 | 2019/11/10 | 10 months ago | GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers. |
| [roumon](https://github.com/becheran/roumon) | 69 | 3 | 2021/03/02 | 9 months ago | Monitor current state of all active goroutines via a command line interface. |
| [igo](https://github.com/rocketlaunchr/igo) | 51 | 3 | 2018/11/17 | 1 year ago | Improved Go Syntax (transpiler) |
| [go-james](https://github.com/pieterclaerhout/go-james) | 50 | 3 | 2019/10/14 | 1 day ago | Go project skeleton creator, builds and tests your projects without the manual setup. |
| [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) | 39 | 2 | 2015/05/22 | 4 years ago | Bash completion for go and wgo. |
| [generator-go-lang](https://github.com/axelspringer/generator-go-lang) | 24 | 13 | 2017/09/13 | 1 year ago | A [Yeoman](https://yeoman.io) generator to get new Go projects started. |
| [docs](https://github.com/go-oas/docs) | 9 | 2 | 2021/01/28 | 9 months ago | Automatically generate RESTful API documentation for GO projects - aligned with Open API Specification standard. |
| [modver](https://github.com/bobg/modver) | 0 | 1 | 2021/07/17 | 3 days ago | Compare two versions of a Go module to check the version-number change required (major, minor, or patchlevel), according to [semver](https://semver.org/) rules. |
**[⬆ back to top](#awesome-go-info)**

## Software Packages
        
*Software written in Go.*
**[⬆ back to top](#awesome-go-info)**

### DevOps Tools
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [kubernetes](https://github.com/kubernetes/kubernetes) | 83948 | 3287 | 2014/06/06 | 1 hour ago | Container Cluster Manager from Google. |
| [moby](https://github.com/moby/moby) | 61880 | 3043 | 2013/01/18 | 13 hours ago | Collaborative project for the container ecosystem to assemble container-based systems. |
| [traefik](https://github.com/traefik/traefik) | 36208 | 695 | 2015/09/13 | 18 hours ago | Reverse proxy and load balancer with support for multiple backends. |
| [gitea](https://github.com/go-gitea/gitea) | 27516 | 480 | 2016/11/01 | 1 hour ago | Fork of Gogs, entirely community driven. |
| [vegeta](https://github.com/tsenart/vegeta) | 18814 | 319 | 2013/08/13 | 3 months ago | HTTP load testing tool and library. It's over 9000! |
| [packer](https://github.com/hashicorp/packer) | 13406 | 479 | 2013/03/23 | 4 days ago | Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. |
| [hey](https://github.com/rakyll/hey) | 12586 | 172 | 2016/09/02 | 4 weeks ago | Hey is a tiny program that sends some load to a web application. |
| [webhook](https://github.com/adnanh/webhook) | 7227 | 146 | 2015/01/12 | 1 week ago | Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server. |
| [gvm](https://github.com/moovweb/gvm) | 6878 | 155 | 2011/12/03 | 6 days ago | GVM provides an interface to manage Go versions. |
| [gaia](https://github.com/gaia-pipeline/gaia) | 4543 | 103 | 2017/12/28 | 3 months ago | Build powerful pipelines in any programming language. |
| [gox](https://github.com/mitchellh/gox) | 4161 | 75 | 2013/11/17 | 9 months ago | Dead simple, no frills Go cross compile tool. |
| [bosun](https://github.com/bosun-monitor/bosun) | 3228 | 146 | 2013/11/15 | 2 months ago | Time Series Alerting Framework. |
| [ddosify](https://github.com/ddosify/ddosify) | 3191 | 26 | 2021/08/04 | 6 days ago | High-performance load testing tool, written in Golang. |
| [bombardier](https://github.com/codesenberg/bombardier) | 2967 | 66 | 2016/05/29 | 5 days ago | Fast cross-platform HTTP benchmarking tool. |
| [pomerium](https://github.com/pomerium/pomerium) | 2868 | 36 | 2019/01/01 | 14 hours ago | Pomerium is an identity-aware access proxy. |
| [script](https://github.com/bitfield/script) | 1952 | 34 | 2019/04/20 | 2 weeks ago | Making it easy to write shell-like scripts in Go for DevOps and system administration tasks. |
| [kala](https://github.com/ajvb/kala) | 1740 | 63 | 2015/03/19 | 5 days ago | Simplistic, modern, and performant job scheduler. |
| [fac](https://github.com/mkchoi212/fac) | 1739 | 31 | 2017/12/29 | 2 years ago | Command-line user interface to fix git merge conflicts. |
| [goxc](https://github.com/laher/goxc) | 1672 | 49 | 2013/02/11 | 2 years ago | build tool for Go, with a focus on cross-compiling and packaging. |
| [statusok](https://github.com/sanathp/statusok) | 1519 | 50 | 2015/08/26 | 4 months ago | Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected. |
| [s3gof3r](https://github.com/rlmcpherson/s3gof3r) | 1114 | 33 | 2013/08/02 | 4 months ago | Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3. |
| [go-selfupdate](https://github.com/sanbornm/go-selfupdate) | 896 | 29 | 2013/11/13 | 3 months ago | Enable your Go applications to self update. |
| [s5cmd](https://github.com/peak/s5cmd) | 887 | 24 | 2016/11/16 | 1 day ago | Blazing fast S3 and local filesystem execution tool. |
| [skm](https://github.com/TimothyYe/skm) | 738 | 20 | 2017/10/11 | 2 hours ago | SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily! |
| [scaleway-cli](https://github.com/scaleway/scaleway-cli) | 716 | 33 | 2015/03/20 | 1 hour ago | Manage BareMetal Servers from Command Line (as easily as with Docker). |
| [ghorg](https://github.com/gabrie30/ghorg) | 644 | 15 | 2018/03/29 | 1 week ago | Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, Gitea, and Bitbucket. |
| [utask](https://github.com/ovh/utask) | 575 | 29 | 2019/11/05 | 4 days ago | Automation engine that models and executes business processes declared in yaml. |
| [kool](https://github.com/kool-dev/kool) | 568 | 11 | 2020/07/06 | 1 week ago | Command line tool for managing Docker environments as an easy way. |
| [cassowary](https://github.com/rogerwelin/cassowary) | 548 | 6 | 2019/08/25 | 1 month ago | Modern cross-platform HTTP load-testing tool written in Go. |
| [aurora](https://github.com/xuri/aurora) | 542 | 31 | 2016/10/09 | 4 months ago | Cross-platform web-based Beanstalkd queue server console. |
| [govvv](https://github.com/ahmetb/govvv) | 509 | 10 | 2016/08/02 | 1 year ago | “go build” wrapper to easily add version information into Go binaries. |
| [gonative](https://github.com/inconshreveable/gonative) | 326 | 8 | 2014/05/01 | 5 years ago | Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages. |
| [trubka](https://github.com/xitonix/trubka) | 308 | 14 | 2019/07/05 | 1 year ago | A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka. |
| [pewpew](https://github.com/bengadbois/pewpew) | 306 | 10 | 2016/10/12 | 1 week ago | Flexible HTTP command line stress tester. |
| [jenkins-cli](https://github.com/jenkins-zh/jenkins-cli) | 298 | 12 | 2019/06/21 | 6 days ago | Jenkins CLI allows you manage your Jenkins as an easy way. |
| [mora](https://github.com/emicklei/mora) | 297 | 25 | 2013/07/12 | 8 months ago | REST server for accessing MongoDB documents and meta data. |
| [lstags](https://github.com/ivanilves/lstags) | 284 | 11 | 2017/08/15 | 5 months ago | Tool and API to sync Docker images across different registries. |
| [balerter](https://github.com/balerter/balerter) | 240 | 7 | 2019/12/30 | 1 week ago | A self-hosted script-based alerting manager. |
| [dogo](https://github.com/liudng/dogo) | 238 | 19 | 2014/11/19 | 2 years ago | Monitoring changes in the source file and automatically compile and run (restart). |
| [manssh](https://github.com/xwjdsh/manssh) | 236 | 5 | 2017/10/08 | 3 years ago | manssh is a command line tool for managing your ssh alias config easily. |
| [godbg](https://github.com/sirnewton01/godbg) | 224 | 17 | 2013/08/09 | 3 years ago | Web-based gdb front-end application. |
| [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) | 216 | 9 | 2017/03/03 | 2 weeks ago | Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`. |
| [blast](https://github.com/dave/blast) | 202 | 5 | 2017/10/21 | 3 years ago | A simple tool for API load testing and batch jobs. |
| [gobrew](https://github.com/cryptojuice/gobrew) | 185 | 5 | 2013/11/13 | 1 year ago | gobrew lets you easily switch between multiple versions of go. |
| [terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) | 177 | 11 | 2017/10/17 | 4 days ago | Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed. |
| [abbreviate](https://github.com/dnnrly/abbreviate) | 174 | 5 | 2018/11/23 | 2 months ago | abbreviate is a tool turning long strings in to shorter ones with configurable seperaters, for example to embed branch names in to deployment stack IDs. |
| [ostent](https://github.com/ostrost/ostent) | 172 | 7 | 2014/03/31 | 3 years ago | collects and displays system metrics and optionally relays to Graphite and/or InfluxDB. |
| [kcli](https://github.com/cswank/kcli) | 163 | 6 | 2017/03/25 | 2 years ago | Command line tool for inspecting kafka topics/partitions/messages. |
| [grapes](https://github.com/yaronsumel/grapes) | 152 | 6 | 2016/09/01 | 1 year ago | Lightweight tool designed to distribute commands over ssh with ease. |
| [winrm-cli](https://github.com/masterzen/winrm-cli) | 134 | 5 | 2016/05/23 | 1 month ago | Cli tool to remotely execute commands on Windows machines. |
| [dockerfile-generator](https://github.com/ozankasikci/dockerfile-generator) | 119 | 5 | 2019/08/14 | 1 year ago | A go library and an executable that produces valid Dockerfiles using various input channels. |
| [drone-scp](https://github.com/appleboy/drone-scp) | 93 | 3 | 2016/10/16 | 2 months ago | Copy files and artifacts via SSH using a binary, docker or Drone CI. |
| [go-furnace](https://github.com/go-furnace/go-furnace) | 85 | 2 | 2016/10/09 | 2 months ago | Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean. |
| [s3-proxy](https://github.com/oxyno-zeta/s3-proxy) | 70 | 2 | 2019/09/22 | 6 days ago | S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth). |
| [dropship](https://github.com/ChrisMcKenzie/dropship) | 56 | 3 | 2015/09/03 | 3 years ago | Tool for deploying code via cdn. |
| [drone-jenkins](https://github.com/appleboy/drone-jenkins) | 32 | 3 | 2016/10/15 | 2 months ago | Trigger downstream Jenkins jobs using a binary, docker or Drone CI. |
| [rodent](https://github.com/alouche/rodent) | 31 | 2 | 2014/06/01 | 4 years ago | Rodent helps you manage Go versions, projects and track dependencies. |
| [awsenv](https://github.com/soniah/awsenv) | 27 | 2 | 2015/08/05 | 3 years ago | Small binary that loads Amazon (AWS) environment variables for a profile. |
| [lwc](https://github.com/timdp/lwc) | 25 | 4 | 2018/04/22 | 1 year ago | A live-updating version of the UNIX wc command. |
| [docker-go-mingw](https://github.com/x1unix/docker-go-mingw) | 23 | 3 | 2020/09/16 | 2 weeks ago | Docker image for building Go binaries for Windows with MinGW toolchain. |
| [depcharge](https://github.com/centerorbit/depcharge) | 17 | 3 | 2018/07/25 | 5 days ago | Helps orchestrating the execution of commands across the many dependencies in larger projects. |
| [httpref](https://github.com/dnnrly/httpref) | 17 | 3 | 2020/01/10 | 2 months ago | httpref is a handy CLI reference for HTTP methods, status codes, headers, and TCP and UDP ports. |
| [sg](https://github.com/ChristopherRabotin/sg) | 5 | 2 | 2015/08/19 | 5 years ago | Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response. |
| [aptly-fork](https://github.com/smira/aptly-fork) | 3 | 0 | 2019/07/04 | 2 years ago | aptly is a Debian repository management tool. |
**[⬆ back to top](#awesome-go-info)**

### Other Software
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [croc](https://github.com/schollz/croc) | 17974 | 228 | 2017/10/17 | 2 days ago | Easily and securely send files or folders from one computer to another. |
| [restic](https://github.com/restic/restic) | 15210 | 242 | 2014/04/27 | 11 hours ago | De-duplicating backup program. |
| [goreplay](https://github.com/buger/goreplay) | 15000 | 466 | 2013/05/30 | 8 hours ago | Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time. |
| [seaweedfs](https://github.com/chrislusf/seaweedfs) | 13509 | 526 | 2014/07/14 | 7 hours ago | Fast, Simple and Scalable Distributed File System with O(1) disk seek. |
| [comcast](https://github.com/tylertreat/comcast) | 7710 | 150 | 2014/11/12 | 22 hours ago | Simulate bad network connections. |
| [confd](https://github.com/kelseyhightower/confd) | 7680 | 252 | 2013/10/01 | 2 months ago | Manage local application configuration files using templates and data from etcd or consul. |
| [toxiproxy](https://github.com/Shopify/toxiproxy) | 7617 | 389 | 2014/09/04 | 1 day ago | Proxy to simulate network and system conditions for automated tests. |
| [liteide](https://github.com/visualfc/liteide) | 6666 | 368 | 2012/11/19 | 1 day ago | LiteIDE is a simple, open source, cross-platform Go IDE. |
| [drive](https://github.com/odeke-em/drive) | 6256 | 187 | 2014/11/03 | 10 months ago | Google Drive client for the commandline. |
| [nes](https://github.com/fogleman/nes) | 4962 | 145 | 2015/03/02 | 6 months ago | Nintendo Entertainment System (NES) emulator written in Go. |
| [duplicacy](https://github.com/gilbertchen/duplicacy) | 3988 | 95 | 2016/02/23 | 13 hours ago | A cross-platform network and cloud backup tool based on the idea of lock-free deduplication. |
| [scc](https://github.com/boyter/scc) | 2954 | 27 | 2018/03/01 | 1 week ago | Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates. |
| [mylg](https://github.com/mehrdadrad/mylg) | 2541 | 112 | 2016/06/21 | 1 year ago | Command Line Network Diagnostic tool written in Go. |
| [goboy](https://github.com/Humpheh/goboy) | 2404 | 44 | 2017/08/20 | 1 year ago | Nintendo Game Boy Color emulator written in Go. |
| [sup](https://github.com/pressly/sup) | 2311 | 70 | 2015/02/23 | 6 months ago | Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers. |
| [lgo](https://github.com/yunabe/lgo) | 2227 | 47 | 2017/10/05 | 1 year ago | Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility. |
| [circuit](https://github.com/gocircuit/circuit) | 1923 | 138 | 2014/04/10 | 1 year ago | Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications. |
| [snap](https://github.com/intelsdi-x/snap) | 1796 | 142 | 2014/08/13 | 3 years ago | Powerful telemetry framework. |
| [borg](https://github.com/ok-borg/borg) | 1529 | 41 | 2016/09/10 | 3 years ago | Terminal based search engine for bash snippets. |
| [community](https://github.com/documize/community) | 1452 | 54 | 2016/04/29 | 1 month ago | Modern wiki software that integrates data from SaaS tools. |
| [blocky](https://github.com/0xERR0R/blocky) | 1198 | 19 | 2019/11/06 | 1 day ago | Fast and lightweight DNS proxy as ad-blocker for local network with many features. |
| [Go-Package-Store](https://github.com/shurcooL/Go-Package-Store) | 886 | 22 | 2014/01/24 | 1 year ago | App that displays updates for the Go packages in your GOPATH. |
| [shell2http](https://github.com/msoap/shell2http) | 873 | 23 | 2015/03/11 | 1 month ago | Executing shell commands via http server (for prototyping or remote control). |
| [vflow](https://github.com/EdgeCast/vflow) | 859 | 85 | 2017/02/24 | 2 weeks ago | High-performance, scalable and reliable IPFIX, sFlow and Netflow collector. |
| [peg](https://github.com/pointlander/peg) | 830 | 27 | 2010/04/25 | 4 months ago | Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. |
| [leaps](https://github.com/Jeffail/leaps) | 709 | 29 | 2014/06/19 | 10 months ago | Pair programming service using Operational Transforms. |
| [gfile](https://github.com/Antonito/gfile) | 639 | 11 | 2019/03/08 | 10 months ago | Securely transfer files between two computers, without any third party, over WebRTC. |
| [guora](https://github.com/meloalright/guora) | 571 | 14 | 2020/08/13 | 1 year ago | A self-hosted Quora like web application written in Go. |
| [gebug](https://github.com/moshebe/gebug) | 558 | 5 | 2020/07/20 | 19 hours ago | A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly. |
| [gocc](https://github.com/goccmack/gocc) | 506 | 22 | 2015/06/05 | 2 weeks ago | Gocc is a compiler kit for Go written in Go. |
| [mockingjay-server](https://github.com/quii/mockingjay-server) | 502 | 9 | 2015/04/04 | 11 months ago | Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests. |
| [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) | 439 | 20 | 2015/10/08 | 4 months ago | Video streaming torrent client. |
| [ipe](https://github.com/dimiro1/ipe) | 342 | 18 | 2015/01/13 | 9 months ago | Open source Pusher server implementation compatible with Pusher client libraries written in GO. |
| [IDE](https://github.com/thestrukture/IDE) | 325 | 19 | 2017/09/09 | 5 months ago | Browser accessible IDE. Designed for Go with Go. |
| [tcpprobe](https://github.com/mehrdadrad/tcpprobe) | 315 | 9 | 2020/10/26 | 10 months ago | TCP tool for network performance and path monitoring, including socket statistics. |
| [wellington](https://github.com/wellington/wellington) | 301 | 13 | 2014/12/08 | 1 year ago | Sass project management tool, extends the language with sprite functions (like Compass). |
| [woke](https://github.com/get-woke/woke) | 294 | 7 | 2020/08/31 | 22 hours ago | Detect non-inclusive language in your source code. |
| [cherry](https://github.com/rafael-santiago/cherry) | 268 | 13 | 2015/10/24 | 4 years ago | Tiny webchat server in Go. |
| [joincap](https://github.com/assafmo/joincap) | 171 | 8 | 2018/05/31 | 9 months ago | Command-line utility for merging multiple pcap files together. |
| [tcpdog](https://github.com/mehrdadrad/tcpdog) | 169 | 10 | 2020/12/30 | 5 months ago | eBPF based TCP observability. |
| [Neo-cowsay](https://github.com/Code-Hex/Neo-cowsay) | 167 | 7 | 2016/11/05 | 2 weeks ago | 🐮 cowsay is reborn. for a New Era. |
| [orbit](https://github.com/gulien/orbit) | 162 | 8 | 2017/05/13 | 11 months ago | A simple tool for running commands and generating files from templates. |
| [vaku](https://github.com/lingrino/vaku) | 127 | 3 | 2018/04/24 | 1 week ago | CLI & API for folder-based functions in Vault like copy, move, and search. |
| [dp](https://github.com/scryinfo/dp) | 83 | 12 | 2018/12/12 | 1 month ago | Through SDK for data exchange with blockchain, developers can get easy access to DAPP development. |
| [boxed](https://github.com/tejo/boxed) | 75 | 3 | 2015/04/18 | 3 years ago | Dropbox based blog engine. |
| [crawley](https://github.com/s0rg/crawley) | 45 | 1 | 2021/10/27 | 1 week ago | Web scraper/crawler for cli. |
| [naclpipe](https://github.com/unix4fun/naclpipe) | 22 | 6 | 2015/05/05 | 3 years ago | Simple NaCL EC25519 based crypto pipe tool written in Go. |
| [term-quiz](https://github.com/crazcalm/term-quiz) | 19 | 1 | 2017/12/26 | 3 years ago | Quizzes for your terminal. |
| [snitch](https://github.com/lucasgomide/snitch) | 15 | 1 | 2017/04/06 | 3 years ago | Simple way to notify your team and many tools when someone has deployed any application via Tsuru. |
| [GoDocTooltip](https://github.com/diankong/GoDocTooltip) | 12 | 3 | 2016/01/21 | 1 week ago | Chrome extension for Go Doc sites, which shows function description as tooltip at function list. |
| [hoofli](https://github.com/dnnrly/hoofli) | 1 | 2 | 2021/04/23 | 2 months ago | Generate PlantUML diagrams from Chrome or Firefox network inspections. |
**[⬆ back to top](#awesome-go-info)**

# Resources
        
*Where to discover new Go libraries.*
**[⬆ back to top](#awesome-go-info)**

## Benchmarks
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) | 1607 | 85 | 2016/04/06 | 4 months ago | Go web framework benchmark. |
| [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) | 1542 | 60 | 2013/12/16 | 1 week ago | Go HTTP request router benchmark and comparison. |
| [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) | 1235 | 38 | 2013/01/18 | 2 months ago | Benchmarks of Go serialization methods. |
| [skynet](https://github.com/atemerev/skynet) | 1002 | 50 | 2016/02/14 | 7 months ago | Skynet 1M threads microbenchmark. |
| [speedtest-resize](https://github.com/fawick/speedtest-resize) | 215 | 7 | 2013/09/16 | 1 year ago | Compare various Image resize algorithms for the Go language. |
| [go-benchmarks](https://github.com/tylertreat/go-benchmarks) | 142 | 11 | 2016/02/25 | 5 years ago | Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches. |
| [gospeed](https://github.com/feyeleanor/gospeed) | 108 | 7 | 2011/05/23 | 10 months ago | Go micro-benchmarks for calculating the speed of language constructs. |
| [autobench](https://github.com/davecheney/autobench) | 92 | 9 | 2013/03/28 | 7 years ago | Framework to compare the performance between different Go versions. |
| [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) | 60 | 5 | 2014/09/24 | 3 years ago | Collection of benchmarks for popular Go database/SQL utilities. |
| [gocostmodel](https://github.com/mna/gocostmodel) | 57 | 6 | 2014/12/19 | 7 months ago | Benchmarks of common basic operations for the Go language. |
| [kvbench](https://github.com/jimrobinson/kvbench) | 24 | 1 | 2014/04/15 | 2 years ago | Key/Value database benchmark. |
| [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) | 22 | 2 | 2017/01/24 | 4 years ago | Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results. |
| [go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) | 19 | 1 | 2021/02/09 | 10 months ago | benchmarks for machine learning inference in Go. |
| [go-json-benchmark](https://github.com/zerosnake0/go-json-benchmark) | 6 | 2 | 2019/11/10 | 1 year ago | Go JSON benchmark. |
**[⬆ back to top](#awesome-go-info)**

## Conferences
        
**[⬆ back to top](#awesome-go-info)**

## E-Books
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [GoBooks](https://github.com/dariubs/GoBooks) | 10659 | 605 | 2015/05/05 | 22 hours ago | A curated list of Go books. |
| [The-Golang-Standard-Library-by-Example](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example) | 8304 | 588 | 2013/04/14 | 1 week ago | Golang标准库。对于程序员而言，标准库与语言本身同样重要，它好比一个百宝箱，能为各种常见的任务提供完美的解决方案。以示例驱动的方式讲解Golang的标准库。 |
| [gosuccinctly](https://github.com/thedevsir/gosuccinctly) | 21 | 4 | 2018/09/02 | 3 years ago | in Persian. |
**[⬆ back to top](#awesome-go-info)**

## Gophers
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gophers](https://github.com/egonelbre/gophers) | 2566 | 59 | 2015/06/03 | 1 year ago | Free gophers. |
| [gophers](https://github.com/ashleymcnamara/gophers) | 2539 | 97 | 2017/02/15 | 2 years ago | Gopher artworks by Ashley McNamara. |
| [free-gophers-pack](https://github.com/MariaLetta/free-gophers-pack) | 2365 | 57 | 2019/04/02 | 1 year ago | Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster. |
| [gophericons](https://github.com/shalakhin/gophericons) | 592 | 21 | 2015/08/22 | 3 years ago | 34 gopher images for Go developers community |
| [gopherize.me](https://github.com/matryer/gopherize.me) | 541 | 8 | 2017/01/25 | 4 months ago | Gopherize yourself. |
| [gopher-stickers](https://github.com/tenntenn/gopher-stickers) | 518 | 14 | 2014/11/09 | 2 years ago | gopher stickers |
| [gopher-vector](https://github.com/golang-samples/gopher-vector) | 401 | 12 | 2013/03/31 | 5 years ago | Vector data of gopher |
| [go-gopher](https://github.com/sillecelik/go-gopher) | 98 | 0 | 2018/03/28 | 4 months ago | Gopher amigurumi toy pattern. |
| [gopher-logos](https://github.com/GolangUA/gopher-logos) | 95 | 9 | 2017/07/27 | 6 months ago | adorable gopher logos. |
| [gophers](https://github.com/rogeralsing/gophers) | 54 | 2 | 2017/01/28 | 1 year ago | random gopher graphics. |
| [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) | 41 | 2 | 2014/09/03 | 3 years ago | Go gopher Vector Data [.ai, .svg]. |
| [gophers](https://github.com/scraly/gophers) | 12 | 2 | 2021/06/23 | 2 months ago | Gophers by Aurélie Vache. |
**[⬆ back to top](#awesome-go-info)**

## Meetups
        
*Add the group of your city/country here (send **PR**)*
**[⬆ back to top](#awesome-go-info)**

## Style Guides
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-styleguide](https://github.com/bahlo/go-styleguide) | 1197 | 31 | 2017/07/29 | 3 months ago | 🏆 Opinionated Styleguide for the Go language |
**[⬆ back to top](#awesome-go-info)**

## Twitter
        
**[⬆ back to top](#awesome-go-info)**

## Websites
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) | 28347 | 1713 | 2014/07/08 | 2 weeks ago | List of other amazingly awesome lists. |
| [awesome-remote-job](https://github.com/lukasz-madon/awesome-remote-job) | 21488 | 994 | 2015/01/02 | 18 hours ago | Curated list of awesome remote jobs. A lot of them are looking for Go hackers. |
| [awesome-golang-workshops](https://github.com/amit-davidson/awesome-golang-workshops) | 454 | 17 | 2021/06/27 | 5 months ago | A curated list of awesome golang workshops. |
| [golang-graphics](https://github.com/mholt/golang-graphics) | 139 | 8 | 2014/03/24 | 6 years ago | Collection of Go images, graphics, and art. |
| [gocryforhelp](https://github.com/ninedraft/gocryforhelp) | 40 | 11 | 2016/05/09 | 4 years ago | Collection of Go projects that needs help. Good place to start your open-source way in Go. |
| [awesome-go-extra](https://github.com/xwjdsh/awesome-go-extra) | 20 | 2 | 2021/06/01 | 4 days ago | Parse awesome-go README file and generate a new README file with repo info. |
**[⬆ back to top](#awesome-go-info)**

### Tutorials
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [build-web-application-with-golang](https://github.com/astaxie/build-web-application-with-golang) | 39342 | 2446 | 2012/08/02 | 1 month ago | Golang ebook intro how to build a web app with golang. |
| [go-patterns](https://github.com/tmrts/go-patterns) | 18031 | 614 | 2015/12/14 | 4 months ago | Curated list of Go design patterns, recipes and idioms. |
| [learn-go-with-tests](https://github.com/quii/learn-go-with-tests) | 16146 | 313 | 2018/03/02 | 6 hours ago | Learn Go with test-driven development. |
| [learngo](https://github.com/inancgumus/learngo) | 11896 | 282 | 2018/10/15 | 50 minutes ago | Learn Go with thousands of examples, exercises, and quizzes. |
| [golang-cheat-sheet](https://github.com/a8m/golang-cheat-sheet) | 6119 | 197 | 2014/02/13 | 2 weeks ago | Go's reference card. |
| [golang-for-nodejs-developers](https://github.com/miguelmota/golang-for-nodejs-developers) | 2708 | 40 | 2019/01/03 | 3 months ago | Examples of Golang compared to Node.js for learning. |
| [working-with-go](https://github.com/mkaz/working-with-go) | 1157 | 48 | 2014/05/04 | 1 year ago | Intro to go for experienced programmers. |
| [ethereum-development-with-go-book](https://github.com/miguelmota/ethereum-development-with-go-book) | 1118 | 52 | 2018/05/16 | 1 day ago | A little e-book on Ethereum Development with Go. |
| [go-clean-template](https://github.com/evrone/go-clean-template) | 487 | 20 | 2021/01/18 | 2 days ago | Clean Architecture template for Golang services. |
| [goapp](https://github.com/bnkamalesh/goapp) | 329 | 9 | 2020/07/04 | 1 month ago | An opinionated guideline to structure & develop a Go web application/service. |
| [design-patterns](https://github.com/shubhamzanwar/design-patterns) | 63 | 4 | 2020/09/24 | 1 year ago | Collection of programming design patterns implemented in Go. |
| [go-patterns](https://github.com/haveyoudebuggedit/go-patterns) | 1 | 1 | 2021/06/25 | 6 months ago | Advanced Go patterns with ready-to-run examples. |

> 该项目源码[Awesome Go Analysis](https://github.com/plholx/awesome-go-analysis)
> 更专业的go开源项目分析请移步 [Awesome Go](https://go.libhunt.com/)
