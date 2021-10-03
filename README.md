# Awesome Go Info

go语言开源项目列表，项目分类及GitHub上的开源项目数据完全来自于[awesome-go](https://github.com/avelino/awesome-go) 的[README.md](https://github.com/avelino/awesome-go/blob/master/README.md)文件，通过调用GitHub的API获取仓库信息，展示项目的star数、watch数等，方便查看go语言开源项目的一些相关信息。

_该文件仅包含[awesome-go](https://github.com/avelino/awesome-go) [README.md](https://github.com/avelino/awesome-go/blob/master/README.md)文件中列出的在GitHub上开源的优秀项目，不罗列其它golang相关的网站_
_该文件中的GitHub仓库信息数据会在每天凌晨1点左右更新,当前数据更新于2021-10-04 00:48:48_

- [Awesome Go](#awesome-go)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Bot Building](#bot-building)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
        - [Relational Databases](#relational-databases)
        - [NoSQL Databases](#nosql-databases)
    - [Date and Time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Dynamic DNS](#dynamic-dns)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Error Handling](#error-handling)
    - [Files](#files)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Functional](#functional)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Geographic](#geographic)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [IoT](#iot-internet-of-things)
    - [Job Scheduler](#job-scheduler)
    - [JSON](#json)
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
    - [OpenGL](#opengl)
    - [ORM](#orm)
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
        - [Testing Frameworks](#testing-frameworks)
        - [Mock](#mock)
        - [Fail injection](#fail-injection)
    - [Text Processing](#text-processing)
        - [Specific Formats](#specific-formats)
        - [Utility](#utility)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [UUID](#uuid)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        - [Routers](#routers)
    - [Windows](#windows)
    - [XML](#xml)
    - [WebAssembly](#webassembly)
    - [Files](#Files)
    - [File Handling](#file-handling)
    - [Build Automation](#build-automation)
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
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)
    - [Style Guides](#style-guides)




# Awesome Go
        

## Audio and Music
        
*Libraries for manipulating audio.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [oto](https://github.com/hajimehoshi/oto) | 864 | 10 | 2017/05/04 | 3 days ago | A low-level library to play sound on multiple platforms. |
| [portaudio](https://github.com/gordonklaus/portaudio) | 466 | 12 | 2015/09/16 | 1 year ago | Go bindings for the PortAudio audio I/O library. |
| [music-theory](https://github.com/go-music-theory/music-theory) | 361 | 20 | 2016/03/17 | 1 year ago | Music theory models in Go. |
| [waveform](https://github.com/mdlayher/waveform) | 343 | 11 | 2014/09/13 | 1 year ago | Go package capable of generating waveform images from audio streams. |
| [portmidi](https://github.com/rakyll/portmidi) | 262 | 11 | 2013/11/10 | 11 months ago | Go bindings for PortMidi. |
| [id3v2](https://github.com/bogem/id3v2) | 192 | 7 | 2016/05/15 | 5 months ago | ID3 decoding and encoding library for Go. |
| [flac](https://github.com/mewkiz/flac) | 164 | 11 | 2012/11/01 | 8 months ago | Native Go FLAC encoder/decoder with support for FLAC streams. |
| [malgo](https://github.com/gen2brain/malgo) | 153 | 5 | 2017/11/09 | 1 week ago | Mini audio library. |
| [GoAudio](https://github.com/DylanMeeus/GoAudio) | 150 | 6 | 2020/07/05 | 6 months ago | Native Go Audio Processing Library. |
| [mix](https://github.com/go-mix/mix) | 144 | 3 | 2016/01/03 | 1 year ago | Sequence-based Go-native audio mixer for music apps. |
| [go-sox](https://github.com/krig/go-sox) | 123 | 9 | 2013/10/08 | 3 years ago | libsox bindings for go. |
| [mp3](https://github.com/tcolgate/mp3) | 118 | 2 | 2015/02/26 | 4 years ago | Native Go MP3 decoder. |
| [gaad](https://github.com/Comcast/gaad) | 86 | 11 | 2016/07/11 | 1 day ago | Native Go AAC bitstream parser. |
| [go-taglib](https://github.com/wtolson/go-taglib) | 74 | 6 | 2012/11/20 | 3 years ago | Go bindings for taglib. |
| [minimp3](https://github.com/tosone/minimp3) | 63 | 3 | 2018/01/26 | 6 months ago | Lightweight MP3 decoder library. |
| [EasyMIDI](https://github.com/algoGuy/EasyMIDI) | 35 | 3 | 2018/02/19 | 3 years ago | EasyMidi is a simple and reliable library for working with standard midi file (SMF). |
| [go_mediainfo](https://github.com/zhulik/go_mediainfo) | 32 | 1 | 2015/12/13 | 5 years ago | libmediainfo bindings for go. |
| [vorbis](https://github.com/mccoyst/vorbis) | 28 | 3 | 2013/07/12 | 2 years ago | "Native" Go Vorbis decoder (uses CGO, but has no dependencies). |
| [gosamplerate](https://github.com/dh1tw/gosamplerate) | 12 | 1 | 2016/11/20 | 1 year ago | libsamplerate bindings for go. |

## Authentication and OAuth
        
*Libraries for implementing authentications schemes.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [casbin](https://github.com/casbin/casbin) | 10385 | 220 | 2017/04/08 | 2 days ago | Authorization library that supports access control models like ACL, RBAC, ABAC. |
| [jwt-go](https://github.com/dgrijalva/jwt-go) | 9947 | 150 | 2012/04/18 | 3 weeks ago | Golang implementation of JSON Web Tokens (JWT). |
| [oauth2](https://github.com/golang/oauth2) | 3854 | 103 | 2014/04/14 | 1 day ago | Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support. |
| [goth](https://github.com/markbates/goth) | 3357 | 61 | 2014/10/14 | 5 days ago | provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box. |
| [authboss](https://github.com/volatiletech/authboss) | 2849 | 56 | 2015/01/03 | 1 month ago | Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time. |
| [go-jose](https://github.com/square/go-jose) | 1822 | 60 | 2014/11/14 | 2 months ago | Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. |
| [loginsrv](https://github.com/tarent/loginsrv) | 1814 | 53 | 2016/11/11 | 7 months ago | JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam. |
| [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) | 1812 | 88 | 2015/11/01 | 9 months ago | Standalone, specification-compliant,  OAuth2 server written in Golang. |
| [osin](https://github.com/openshift/osin) | 1694 | 72 | 2013/09/10 | 2 weeks ago | Golang OAuth2 server library. |
| [gologin](https://github.com/dghubble/gologin) | 1437 | 28 | 2015/06/23 | 20 hours ago | chainable handlers for login with OAuth1 and OAuth2 authentication providers. |
| [gorbac](https://github.com/mikespook/gorbac) | 1214 | 61 | 2013/12/26 | 5 months ago | provides a lightweight role-based access control (RBAC) implementation in Golang. |
| [scs](https://github.com/alexedwards/scs) | 936 | 25 | 2016/08/08 | 3 weeks ago | Session Manager for HTTP servers. |
| [paseto](https://github.com/o1egl/paseto) | 542 | 23 | 2018/01/23 | 1 month ago | Golang implementation of Platform-Agnostic Security Tokens (PASETO). |
| [permissions2](https://github.com/xyproto/permissions2) | 435 | 14 | 2014/11/19 | 2 months ago | Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt. |
| [go-guardian](https://github.com/shaj13/go-guardian) | 305 | 5 | 2020/05/14 | 4 days ago | Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token and Certificate based authentication. |
| [jwt](https://github.com/cristalhq/jwt) | 290 | 12 | 2019/07/20 | 4 days ago | Safe, simple and fast JSON Web Tokens for Go. |
| [jwt](https://github.com/pascaldekloe/jwt) | 269 | 13 | 2018/03/21 | 7 months ago | Lightweight JSON Web Token (JWT) library. |
| [jeff](https://github.com/abraithwaite/jeff) | 231 | 4 | 2018/08/02 | 3 months ago | Simple, flexible, secure and idiomatic web session management with pluggable backends. |
| [httpauth](https://github.com/goji/httpauth) | 209 | 7 | 2014/05/26 | 5 days ago | HTTP Authentication middleware. |
| [jwt-auth](https://github.com/adam-hanna/jwt-auth) | 206 | 12 | 2016/07/05 | 2 months ago | JWT middleware for Golang http servers with many configuration options. |
| [branca](https://github.com/hako/branca) | 158 | 8 | 2018/01/09 | 1 year ago | Golang implementation of Branca Tokens. |
| [sessionup](https://github.com/swithek/sessionup) | 113 | 6 | 2019/07/23 | 1 month ago | Simple, yet effective HTTP session management and identification package. |
| [session](https://github.com/icza/session) | 106 | 7 | 2016/02/08 | 2 months ago | Go session management for web servers (including support for Google App Engine - GAE). |
| [sjwt](https://github.com/brianvoe/sjwt) | 94 | 1 | 2019/06/20 | 2 years ago | Simple jwt generator and parser. |
| [jwt](https://github.com/robbert229/jwt) | 93 | 9 | 2016/06/05 | 10 months ago | Clean and easy to use implementation of JSON Web Tokens (JWT). |
| [rbac](https://github.com/zpatrick/rbac) | 85 | 3 | 2018/08/02 | 3 years ago | Minimalistic RBAC package for Go applications. |
| [sessions](https://github.com/adam-hanna/sessions) | 60 | 3 | 2017/04/29 | 1 year ago | Dead simple, highly performant, highly customizable sessions service for go http servers. |
| [securecookie](https://github.com/chmike/securecookie) | 53 | 5 | 2017/09/03 | 1 week ago | Efficient secure cookie encoding/decoding. |
| [go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) | 29 | 1 | 2020/08/21 | 2 weeks ago | Golang library for providing a canonical representation of email address. |
| [otpgo](https://github.com/jltorresm/otpgo) | 23 | 3 | 2020/08/19 | 7 months ago | Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go. |
| [scope](https://github.com/SonicRoshan/scope) | 15 | 1 | 2019/09/23 | 4 months ago | Easily Manage OAuth2 Scopes In Go. |
| [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) | 9 | 2 | 2017/10/20 | 2 years ago | Go session management using the SessionGate Redis module. |
| [cookiestxt](https://github.com/mengzhuo/cookiestxt) | 8 | 1 | 2017/10/09 | 6 months ago | provides parser of cookies.txt file format. |
| [signedvalue](https://github.com/sashka/signedvalue) | 8 | 0 | 2018/01/06 | 2 years ago | Signed and timestamped strings compatible with [Tornado's](https://github.com/tornadoweb/tornado) `create_signed_value`, `decode_signed_value`, and therefore `set_secure_cookie` and `get_secure_cookie`. |
| [casbin](https://github.com/hsluoyz/casbin) | 3 | 0 | 2021/04/16 | 4 months ago | Authorization library that supports access control models like ACL, RBAC, ABAC. |

## Bot Building
        
*Libraries for building and working with bots.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [telegram-bot-api](https://github.com/go-telegram-bot-api/telegram-bot-api) | 3084 | 79 | 2015/06/25 | 1 month ago | Simple and clean Telegram bot client. |
| [olivia](https://github.com/olivia-ai/olivia) | 3050 | 83 | 2018/06/05 | 2 weeks ago | A chatbot built with an artificial neural network. |
| [telebot](https://github.com/tucnak/telebot) | 2130 | 49 | 2015/06/25 | 2 days ago | Telegram bot framework written in Go. |
| [kelp](https://github.com/stellar/kelp) | 754 | 50 | 2018/08/08 | 1 week ago | official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies. |
| [bot](https://github.com/go-chat-bot/bot) | 702 | 48 | 2015/09/22 | 1 year ago | IRC, Slack & Telegram bot written in Go. |
| [golang-crypto-trading-bot](https://github.com/saniales/golang-crypto-trading-bot) | 610 | 34 | 2017/05/14 | 4 months ago | A golang implementation of a console-based trading bot for cryptocurrency exchanges. |
| [slacker](https://github.com/shomali11/slacker) | 556 | 16 | 2017/05/20 | 1 week ago | Easy to use framework to create Slack bots. |
| [tbot](https://github.com/yanzay/tbot) | 318 | 10 | 2015/09/11 | 6 months ago | Telegram bot server with API similar to net/http. |
| [go-sarah](https://github.com/oklahomer/go-sarah) | 203 | 7 | 2016/11/06 | 2 months ago | Framework to build bot for desired chat services including LINE, Slack, Gitter and more. |
| [go-twitch-irc](https://github.com/gempir/go-twitch-irc) | 192 | 11 | 2017/03/23 | 5 days ago | Libary to write bots for twitch. |
| [tenyks](https://github.com/kyleterry/tenyks) | 171 | 14 | 2012/08/26 | 2 years ago | Service oriented IRC bot using Redis and JSON for messaging. |
| [hanu](https://github.com/sbstjn/hanu) | 135 | 6 | 2016/09/16 | 3 months ago | Framework for writing Slack bots. |
| [go-tgbot](https://github.com/olebedev/go-tgbot) | 107 | 9 | 2016/12/11 | 3 years ago | Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware. |
| [margelet](https://github.com/zhulik/margelet) | 63 | 4 | 2015/11/21 | 5 years ago | Framework for building Telegram bots. |
| [ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) | 50 | 5 | 2017/12/19 | 2 weeks ago | A Discord bot for managing ephemeral roles based upon voice channel member presence. |
| [slackscot](https://github.com/alexandre-normand/slackscot) | 46 | 1 | 2015/10/22 | 7 months ago | Another framework for building Slack bots. |
| [govkbot](https://github.com/nikepan/govkbot) | 36 | 3 | 2016/07/11 | 1 month ago | Simple Go [VK](https://vk.com) bot library. |
| [micha](https://github.com/onrik/micha) | 17 | 4 | 2016/04/14 | 4 months ago | Go Library for Telegram bot api. |

## Command Line
        
*Libraries for building Console Applications and Console User Interfaces.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [cobra](https://github.com/spf13/cobra) | 23359 | 345 | 2013/09/03 | 3 days ago | Commander for modern Go CLI interactions. |
| [cli](https://github.com/urfave/cli) | 16616 | 297 | 2013/07/13 | 2 weeks ago | Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli). |
| [termui](https://github.com/gizak/termui) | 11279 | 296 | 2015/02/03 | 2 months ago | Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib). |
| [gocui](https://github.com/jroimartin/gocui) | 7439 | 129 | 2014/01/04 | 1 week ago | Minimalist Go library aimed at creating Console User Interfaces. |
| [termbox-go](https://github.com/nsf/termbox-go) | 4154 | 97 | 2012/01/12 | 4 months ago | Termbox is a library for creating cross-platform text-based interfaces. |
| [go-prompt](https://github.com/c-bata/go-prompt) | 4142 | 56 | 2017/08/14 | 1 month ago | Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit). |
| [kingpin](https://github.com/alecthomas/kingpin) | 3131 | 54 | 2014/05/14 | 1 month ago | Command line and flag parser supporting sub commands. |
| [dnote](https://github.com/dnote/dnote) | 2154 | 31 | 2017/03/30 | 1 week ago | A simple command line notebook with multi-device sync. |
| [progressbar](https://github.com/schollz/progressbar) | 2091 | 23 | 2017/10/26 | 4 days ago | Basic thread-safe progress bar that works in every OS. |
| [go-flags](https://github.com/jessevdk/go-flags) | 2046 | 30 | 2012/08/31 | 3 weeks ago | go command line option parser. |
| [pterm](https://github.com/pterm/pterm) | 1874 | 17 | 2020/09/17 | 22 hours ago | A library to beautify console output on every platform with many combinable components. |
| [uiprogress](https://github.com/gosuri/uiprogress) | 1838 | 36 | 2015/11/17 | 1 month ago | Flexible library to render progress bars in terminal applications. |
| [termdash](https://github.com/mum4k/termdash) | 1814 | 27 | 2018/03/24 | 2 months ago | Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui). |
| [asciigraph](https://github.com/guptarohit/asciigraph) | 1756 | 29 | 2018/06/17 | 6 months ago | Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies. |
| [pflag](https://github.com/spf13/pflag) | 1569 | 31 | 2013/08/30 | 1 week ago | Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags. |
| [readline](https://github.com/chzyer/readline) | 1555 | 40 | 2015/09/20 | 1 year ago | Pure golang implementation that provides most features in GNU-Readline under MIT license. |
| [mpb](https://github.com/vbauerster/mpb) | 1449 | 20 | 2016/12/14 | 2 weeks ago | Multi progress bar for terminal applications. |
| [cli](https://github.com/mitchellh/cli) | 1391 | 25 | 2013/11/03 | 1 month ago | Go library for implementing command-line interfaces. |
| [uilive](https://github.com/gosuri/uilive) | 1346 | 19 | 2015/11/16 | 3 weeks ago | Library for updating terminal output in realtime. |
| [go-arg](https://github.com/alexflint/go-arg) | 1272 | 14 | 2015/11/01 | 1 day ago | Struct-based argument parsing in Go. |
| [docopt.go](https://github.com/docopt/docopt.go) | 1266 | 35 | 2013/08/25 | 11 months ago | Command-line arguments parser that will make you smile. |
| [aurora](https://github.com/logrusorgru/aurora) | 1129 | 9 | 2016/11/06 | 7 months ago | ANSI terminal colors that supports fmt.Printf/Sprintf. |
| [color](https://github.com/gookit/color) | 929 | 16 | 2018/07/01 | 1 month ago | Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows. |
| [gcli](https://github.com/tcnksm/gcli) | 907 | 26 | 2014/06/19 | 3 years ago | The easy way to start building Golang command line applications. |
| [liner](https://github.com/peterh/liner) | 817 | 22 | 2012/08/15 | 6 months ago | Go readline-like library for command-line interfaces. |
| [complete](https://github.com/posener/complete) | 792 | 15 | 2017/05/05 | 5 months ago | Write bash completions in Go + Go command bash completion. |
| [mow.cli](https://github.com/jawher/mow.cli) | 746 | 20 | 2014/12/18 | 2 months ago | Go library for building CLI applications with sophisticated flag and argument parsing and validation. |
| [flaggy](https://github.com/integrii/flaggy) | 734 | 18 | 2018/03/05 | 1 month ago | A robust and idiomatic flags package with excellent subcommand support. |
| [ops](https://github.com/nanovms/ops) | 717 | 28 | 2018/09/10 | 4 days ago | Unikernel Builder/Orchestrator. |
| [uitable](https://github.com/gosuri/uitable) | 619 | 15 | 2015/11/13 | 11 months ago | Library to improve readability in terminal apps using tabular data. |
| [cli](https://github.com/mkideal/cli) | 612 | 23 | 2016/02/26 | 2 weeks ago | Feature-rich and easy to use command-line package based on golang struct tags. |
| [go-colorable](https://github.com/mattn/go-colorable) | 555 | 19 | 2014/07/30 | 4 days ago | Colorable writer for windows. |
| [go-isatty](https://github.com/mattn/go-isatty) | 553 | 11 | 2014/04/01 | 3 days ago | isatty for golang. |
| [chalk](https://github.com/ttacon/chalk) | 381 | 8 | 2014/07/18 | 2 years ago | Intuitive package for prettifying terminal/console output. |
| [argparse](https://github.com/akamensky/argparse) | 364 | 15 | 2017/11/24 | 1 month ago | Command line argument parser inspired by Python's argparse module. |
| [simpletable](https://github.com/alexeyco/simpletable) | 328 | 4 | 2017/03/29 | 5 months ago | Simple tables in terminal with Go. |
| [tabby](https://github.com/cheynewallace/tabby) | 295 | 3 | 2018/12/17 | 9 months ago | A tiny library for super simple Golang tables. |
| [go-colortext](https://github.com/daviddengcn/go-colortext) | 207 | 9 | 2013/01/23 | 1 year ago | Go library for color output in terminals. |
| [yacspin](https://github.com/theckman/yacspin) | 199 | 5 | 2019/12/29 | 1 month ago | Yet Another CLi Spinner package, for working with terminal spinners. |
| [commandeer](https://github.com/jaffee/commandeer) | 148 | 6 | 2017/10/12 | 3 months ago | Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags. |
| [wmenu](https://github.com/dixonwille/wmenu) | 142 | 2 | 2016/04/20 | 1 month ago | Easy to use menu structure for cli applications that prompts users to make choices. |
| [sflags](https://github.com/octago/sflags) | 129 | 6 | 2016/12/04 | 2 months ago | Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries. |
| [flag](https://github.com/cosiner/flag) | 116 | 7 | 2016/10/05 | 9 months ago | Simple but powerful command line option parsing library for Go supporting subcommand. |
| [clif](https://github.com/ukautz/clif) | 111 | 3 | 2015/05/30 | 2 years ago | Small command line interface framework. |
| [job](https://github.com/liujianping/job) | 109 | 1 | 2019/04/09 | 1 year ago | JOB, make your short-term command as a long-term job. |
| [flag](https://github.com/zhuah/flag) | 102 | 5 | 2016/10/05 | 2 years ago | Simple but powerful command line option parsing library for Go supporting subcommand. |
| [cli](https://github.com/teris-io/cli) | 89 | 2 | 2017/05/24 | 4 months ago | Simple and complete API for building command line interfaces in Go. |
| [env](https://github.com/codingconcepts/env) | 81 | 1 | 2017/06/14 | 1 year ago | Tag-based environment configuration for structs. |
| [cfmt](https://github.com/mingrammer/cfmt) | 81 | 3 | 2018/03/15 | 2 years ago | Contextual fmt inspired by bootstrap color classes. |
| [cmdr](https://github.com/hedzr/cmdr) | 79 | 4 | 2019/05/15 | 1 week ago | A POSIX/GNU style, getopt-like command-line UI Go library. |
| [clir](https://github.com/leaanthony/clir) | 76 | 3 | 2019/11/18 | 4 months ago | A Simple and Clear CLI library. Dependency free. |
| [gocmd](https://github.com/devfacet/gocmd) | 55 | 3 | 2018/01/08 | 4 months ago | Go library for building command line applications. |
| [tabular](https://github.com/InVisionApp/tabular) | 55 | 102 | 2018/04/23 | 3 years ago | Print ASCII tables from command line utilities without the need to pass large sets of data to the API. |
| [wlog](https://github.com/dixonwille/wlog) | 51 | 1 | 2016/04/13 | 1 month ago | Simple logging interface that supports cross-platform color and concurrency. |
| [strumt](https://github.com/antham/strumt) | 44 | 2 | 2017/06/19 | 5 months ago | Library to create prompt chain. |
| [flagvar](https://github.com/sgreben/flagvar) | 37 | 2 | 2018/05/18 | 1 year ago | A collection of flag argument types for Go's standard `flag` package. |
| [go-getoptions](https://github.com/DavidGamba/go-getoptions) | 37 | 4 | 2015/12/18 | 2 months ago | Go option parser inspired on the flexibility of Perl’s GetOpt::Long. |
| [ctc](https://github.com/wzshiming/ctc) | 34 | 1 | 2018/04/27 | 1 year ago | The non-invasive cross-platform terminal color library does not need to modify the Print method. |
| [cmd](https://github.com/posener/cmd) | 33 | 2 | 2019/10/29 | 1 year ago | Extends the standard `flag` package to support sub commands and more in idomatic way. |
| [argv](https://github.com/cosiner/argv) | 30 | 1 | 2017/01/22 | 1 year ago | Go library to split command line string as arguments array using the bash syntax. |
| [cfmt](https://github.com/i582/cfmt) | 29 | 2 | 2020/11/13 | 3 months ago | Simple and convenient formatted stylized output fully compatible with fmt library. |
| [go-commander](https://github.com/yitsushi/go-commander) | 24 | 1 | 2016/10/10 | 1 year ago | Go library to simplify CLI workflow. |
| [colourize](https://github.com/TreyBastian/colourize) | 24 | 3 | 2015/05/11 | 5 years ago | Go library for ANSI colour text in terminals. |
| [argv](https://github.com/zhuah/argv) | 19 | 1 | 2017/01/22 | 2 years ago | Go library to split command line string as arguments array using the bash syntax. |
| [sand](https://github.com/Zaba505/sand) | 15 | 1 | 2018/11/18 | 2 years ago | Simple API for creating interpreters and so much more. |
| [ts](https://github.com/liujianping/ts) | 13 | 0 | 2019/06/25 | 2 years ago | Timestamp convert & compare tool. |
| [go-ataman](https://github.com/workanator/go-ataman) | 11 | 2 | 2017/05/17 | 9 months ago | Go library for rendering ANSI colored text templates in terminals. |
| [table](https://github.com/tomlazar/table) | 10 | 1 | 2020/09/22 | 7 months ago | Small library for terminal color based tables . |

## Configuration
        
*Libraries for configuration parsing.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [viper](https://github.com/spf13/viper) | 16925 | 240 | 2014/04/02 | 7 hours ago | Go configuration with fangs. |
| [godotenv](https://github.com/joho/godotenv) | 4189 | 42 | 2013/07/30 | 6 days ago | Go port of Ruby's dotenv library (Loads environment variables from `.env`). |
| [envconfig](https://github.com/kelseyhightower/envconfig) | 3798 | 41 | 2013/11/06 | 1 week ago | Go library for managing configuration data from environment variables. |
| [ini](https://github.com/go-ini/ini) | 2687 | 76 | 2014/12/18 | 2 weeks ago | Go package to read and write INI files. |
| [env](https://github.com/caarlos0/env) | 2055 | 22 | 2015/07/28 | 2 weeks ago | Parse environment variables to Go structs (with defaults). |
| [konfig](https://github.com/lalamove/konfig) | 614 | 14 | 2019/01/18 | 11 months ago | Composable, observable and performant config handling for Go for the distributed processing era. |
| [koanf](https://github.com/knadh/koanf) | 613 | 14 | 2019/06/18 | 9 hours ago | Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line. |
| [confita](https://github.com/heetch/confita) | 415 | 23 | 2017/12/21 | 2 months ago | Load configuration in cascade from multiple backends into a struct. |
| [cleanenv](https://github.com/ilyakaznacheev/cleanenv) | 376 | 6 | 2019/07/12 | 1 week ago | Minimalistic configuration reader (from files, ENV, and wherever you want). |
| [aconfig](https://github.com/cristalhq/aconfig) | 286 | 5 | 2020/06/26 | 1 week ago | Simple, useful and opinionated config loader. |
| [config](https://github.com/gookit/config) | 282 | 13 | 2018/07/07 | 5 days ago | application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge. |
| [config](https://github.com/JeremyLoy/config) | 268 | 1 | 2019/04/02 | 2 months ago | Cloud native application configuration. Bind ENV to structs in only two lines. |
| [store](https://github.com/tucnak/store) | 257 | 5 | 2015/10/03 | 4 years ago | Lightweight configuration manager for Go. |
| [hjson-go](https://github.com/hjson/hjson-go) | 242 | 9 | 2016/08/05 | 5 months ago | Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments. |
| [config](https://github.com/olebedev/config) | 240 | 8 | 2014/04/21 | 4 months ago | JSON or YAML configuration wrapper with environment variables and flags parsing. |
| [envconfig](https://github.com/vrischmann/envconfig) | 209 | 6 | 2015/04/21 | 9 months ago | Read your configuration from environment variables. |
| [config](https://github.com/joshbetz/config) | 206 | 2 | 2017/04/02 | 1 year ago | Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP. |
| [config](https://github.com/golobby/config) | 181 | 5 | 2019/10/15 | 8 hours ago | A lightweight yet powerful config package for Go projects. |
| [fig](https://github.com/kkyr/fig) | 168 | 5 | 2020/01/16 | 1 month ago | Tiny library for reading configuration from a file and from environment variables (with validation & defaults). |
| [gcfg](https://github.com/go-gcfg/gcfg) | 155 | 8 | 2015/08/17 | 3 months ago | read INI-style configuration files into Go structs; supports user-defined types and subsections. |
| [goconfig](https://github.com/gosidekick/goconfig) | 149 | 14 | 2016/12/18 | 1 year ago | Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file. |
| [xdg](https://github.com/adrg/xdg) | 135 | 4 | 2014/08/22 | 2 weeks ago | Go implementation of the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) and [XDG user directories](https://wiki.archlinux.org/index.php/XDG_user_directories). |
| [goconfig](https://github.com/crgimenes/goconfig) | 131 | 11 | 2016/12/18 | 1 year ago | Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file. |
| [envh](https://github.com/antham/envh) | 95 | 4 | 2017/01/12 | 5 months ago | Helpers to manage environment variables. |
| [envcfg](https://github.com/tomazk/envcfg) | 94 | 1 | 2014/11/29 | 4 years ago | Un-marshaling environment variables to Go structs. |
| [harvester](https://github.com/beatlabs/harvester) | 86 | 12 | 2019/04/09 | 3 weeks ago | Harvester, a easy to use static and dynamic configuration package supportig seeding, env vars and Consul integration. |
| [configuro](https://github.com/sherifabdlnaby/configuro) | 77 | 4 | 2020/04/09 | 6 months ago | opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications. |
| [xdg](https://github.com/OpenPeeDeeP/xdg) | 63 | 3 | 2017/07/20 | 11 months ago | Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html). |
| [gofigure](https://github.com/ian-kent/gofigure) | 60 | 5 | 2014/11/25 | 2 years ago | Go application configuration made easy. |
| [configure](https://github.com/paked/configure) | 54 | 4 | 2015/06/14 | 2 years ago | Provides configuration through multiple sources, including JSON, flags and environment variables. |
| [go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) | 41 | 25 | 2019/01/24 | 6 months ago | Go package that fetches parameters from AWS System Manager - Parameter Store. |
| [configuration](https://github.com/BoRuDar/configuration) | 40 | 2 | 2019/11/27 | 6 days ago | Library for initializing configuration structs from env variables, files, flags and 'default' tag. |
| [ingo](https://github.com/schachmat/ingo) | 35 | 1 | 2016/02/07 | 4 years ago | Flags persisted in an ini-like config file. |
| [go-up](https://github.com/ufoscout/go-up) | 32 | 1 | 2018/02/18 | 1 year ago | A simple configuration library with recursive placeholders resolution and no magic. |
| [hocon](https://github.com/gurkankaymak/hocon) | 29 | 1 | 2020/03/01 | 3 months ago | Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files. |
| [mini](https://github.com/sasbury/mini) | 28 | 1 | 2015/04/29 | 2 years ago | Golang package for parsing ini-style configuration files. |
| [genv](https://github.com/sakirsensoy/genv) | 25 | 2 | 2019/07/15 | 2 years ago | Read environment variables easily with dotenv support. |
| [conflate](https://github.com/the4thamigo-uk/conflate) | 20 | 0 | 2018/02/01 | 1 year ago | Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema. |
| [envconf](https://github.com/ian-kent/envconf) | 10 | 1 | 2014/10/26 | 7 years ago | Configuration from environment. |
| [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) | 10 | 1 | 2019/12/02 | 9 months ago | Go utility for loading configuration parameters from AWS SSM (Parameter Store). |
| [env](https://github.com/nasermirzaei89/env) | 7 | 0 | 2019/07/24 | 11 months ago | Simple useful package for read environment variables. |
| [go-ini](https://github.com/subpop/go-ini) | 5 | 1 | 2019/09/11 | 5 months ago | A Go package that marshals and unmarshals INI-files. |
| [sprbox](https://github.com/oblq/sprbox) | 4 | 2 | 2018/07/17 | 1 year ago | Build-environment aware toolbox factory and agnostic config parser (YAML, TOML, JSON and Environment vars). |
| [swap](https://github.com/oblq/swap) | 4 | 2 | 2020/04/12 | 2 hours ago | Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env). |
| [typenv](https://github.com/diegomarangoni/typenv) | 4 | 1 | 2020/06/30 | 1 year ago | Minimalistic, zero dependency, typed environment variables library. |

## Continuous Integration
        
*Tools for help with continuous integration.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [drone](https://github.com/drone/drone) | 23961 | 561 | 2014/02/07 | 1 day ago | Drone is a Continuous Integration platform built on Docker, written in Go. |
| [cds](https://github.com/ovh/cds) | 3591 | 87 | 2016/10/11 | 1 day ago | Enterprise-Grade CI/CD and DevOps Automation Open Source Platform. |
| [goveralls](https://github.com/mattn/goveralls) | 701 | 13 | 2013/04/17 | 1 week ago | Go integration for Coveralls.io continuous code coverage tracking system. |
| [overalls](https://github.com/go-playground/overalls) | 106 | 4 | 2015/07/30 | 1 year ago | Multi-Package go project coverprofile for tools like goveralls. |
| [duci](https://github.com/duck8823/duci) | 67 | 3 | 2018/04/01 | 3 weeks ago | A simple ci server no needs domain specific languages. |
| [gomason](https://github.com/nikogura/gomason) | 51 | 1 | 2017/11/18 | 2 months ago | Test, Build, Sign, and Publish your go binaries from a clean workspace. |
| [roveralls](https://github.com/lawrencewoodman/roveralls) | 14 | 1 | 2016/06/26 | 3 years ago | Recursive coverage testing tool. |

## CSS Preprocessors
        
*Libraries for preprocessing CSS files.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gcss](https://github.com/yosssi/gcss) | 446 | 16 | 2014/09/04 | 7 years ago | Pure Go CSS Preprocessor. |
| [go-libsass](https://github.com/wellington/go-libsass) | 179 | 8 | 2015/04/19 | 11 months ago | Go wrapper to the 100% Sass compatible libsass project. |

## Data Structures
        
*Generic datastructures and algorithms in Go.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gods](https://github.com/emirpasic/gods) | 10540 | 350 | 2015/03/04 | 3 days ago | Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc. |
| [go-datastructures](https://github.com/Workiva/go-datastructures) | 6186 | 328 | 2014/10/29 | 5 months ago | Collection of useful, performant, and thread-safe data structures. |
| [golang-set](https://github.com/deckarep/golang-set) | 2084 | 44 | 2013/07/03 | 6 months ago | Thread-Safe and Non-Thread-Safe high-performance sets for Go. |
| [gota](https://github.com/go-gota/gota) | 1778 | 78 | 2016/02/06 | 1 week ago | Implementation of dataframes, series, and data wrangling methods for Go. |
| [BoomFilters](https://github.com/tylertreat/BoomFilters) | 1378 | 39 | 2015/02/06 | 6 months ago | Probabilistic data structures for processing continuous, unbounded streams. |
| [roaring](https://github.com/RoaringBitmap/roaring) | 1329 | 40 | 2014/07/10 | 1 month ago | Go package implementing compressed bitsets. |
| [bloom](https://github.com/bits-and-blooms/bloom) | 1307 | 36 | 2011/05/21 | 3 days ago | Go package implementing Bloom filters. |
| [bloom](https://github.com/willf/bloom) | 1012 | 36 | 2011/05/21 | 5 months ago | Go package implementing Bloom filters. |
| [gocache](https://github.com/eko/gocache) | 959 | 20 | 2019/10/05 | 1 month ago | A complete Go cache library with mutiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more. |
| [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) | 828 | 19 | 2015/06/28 | 2 months ago | Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. |
| [hyperloglog](https://github.com/axiomhq/hyperloglog) | 751 | 17 | 2017/06/18 | 2 months ago | HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction. |
| [bitset](https://github.com/bits-and-blooms/bitset) | 735 | 30 | 2011/05/11 | 3 weeks ago | Go package implementing bitsets. |
| [bitset](https://github.com/willf/bitset) | 662 | 30 | 2011/05/11 | 5 months ago | Go package implementing bitsets. |
| [algorithms](https://github.com/shady831213/algorithms) | 564 | 20 | 2018/01/31 | 6 months ago | Algorithms and data structures.CLRS study. |
| [trie](https://github.com/derekparker/trie) | 551 | 22 | 2014/03/06 | 1 year ago | Trie implementation in Go. |
| [go-geoindex](https://github.com/hailocab/go-geoindex) | 333 | 66 | 2015/01/22 | 3 years ago | In-memory geo index. |
| [gostl](https://github.com/liyue201/gostl) | 312 | 10 | 2019/10/12 | 5 days ago | Data structure and algorithm library for go, designed to provide functions similar to C++ STL. |
| [go-edlib](https://github.com/hbollon/go-edlib) | 286 | 10 | 2020/08/18 | 3 weeks ago | Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode. |
| [mafsa](https://github.com/smartystreets-archives/mafsa) | 283 | 16 | 2014/11/07 | 2 years ago | MA-FSA implementation with Minimal Perfect Hashing. |
| [ttlcache](https://github.com/ReneKroon/ttlcache) | 278 | 12 | 2014/12/13 | 2 weeks ago | In-memory string-interface{} cache with various time-based expiration options and callbacks. |
| [merkletree](https://github.com/cbergoon/merkletree) | 271 | 8 | 2017/04/12 | 1 year ago | Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures. |
| [deque](https://github.com/gammazero/deque) | 247 | 7 | 2018/04/24 | 4 months ago | Fast ring-buffer deque (double-ended queue). |
| [hilbert](https://github.com/google/hilbert) | 236 | 22 | 2015/08/06 | 2 years ago | Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves. |
| [goskiplist](https://github.com/ryszard/goskiplist) | 230 | 16 | 2012/05/09 | 1 year ago | Skip list implementation in Go. |
| [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) | 210 | 8 | 2016/04/01 | 1 year ago | Go implementation of Adaptive Radix Tree. |
| [binpacker](https://github.com/zhuangsirui/binpacker) | 172 | 13 | 2016/02/02 | 2 months ago | Binary packer and unpacker helps user build custom binary stream. |
| [skiplist](https://github.com/MauriceGit/skiplist) | 168 | 6 | 2018/06/23 | 1 year ago | Very fast Go Skiplist implementation. |
| [levenshtein](https://github.com/agnivade/levenshtein) | 161 | 4 | 2014/07/30 | 4 months ago | Implementation to calculate levenshtein distance in Go. |
| [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) | 145 | 2 | 2019/01/10 | 1 year ago | Concurrent FIFO queue. |
| [bloom](https://github.com/zentures/bloom) | 144 | 9 | 2013/09/03 | 3 years ago | Bloom filters implemented in Go. |
| [iter](https://github.com/disksing/iter) | 137 | 5 | 2019/10/20 | 1 year ago | Go implementation of C++ STL iterators and algorithms. |
| [ring](https://github.com/tannerryan/ring) | 120 | 1 | 2019/01/27 | 1 year ago | Go implementation of a high performance, thread safe bloom filter. |
| [go-rquad](https://github.com/arl/go-rquad) | 117 | 4 | 2016/09/12 | 1 year ago | Region quadtrees with efficient point location and neighbour finding. |
| [ring](https://github.com/TheTannerRyan/ring) | 110 | 1 | 2019/01/27 | 2 years ago | Go implementation of a high performance, thread safe bloom filter. |
| [encoding](https://github.com/zentures/encoding) | 108 | 7 | 2013/09/20 | 3 years ago | Integer Compression Libraries for Go. |
| [bit](https://github.com/yourbasic/bit) | 107 | 8 | 2017/05/03 | 3 years ago | Golang set data structure with bonus bit-twiddling functions. |
| [remember-go](https://github.com/rocketlaunchr/remember-go) | 100 | 5 | 2019/04/04 | 5 months ago | A universal interface for caching slow database queries (backed by redis, memcached, ristretto, or in-memory). |
| [conjungo](https://github.com/InVisionApp/conjungo) | 95 | 111 | 2016/12/29 | 11 months ago | A small, powerful and flexible merge library. |
| [skiplist](https://github.com/gansidui/skiplist) | 75 | 8 | 2014/11/18 | 6 years ago | Skiplist implementation in Go. |
| [go-mcache](https://github.com/OrlovEvgeny/go-mcache) | 73 | 4 | 2018/04/14 | 1 year ago | Fast in-memory key:value store/cache library. Pointer caches. |
| [bloom](https://github.com/yourbasic/bloom) | 63 | 3 | 2017/05/06 | 4 years ago | Golang Bloom filter implementation. |
| [levenshtein](https://github.com/agext/levenshtein) | 59 | 2 | 2016/04/08 | 11 months ago | Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. |
| [count-min-log](https://github.com/seiflotfy/count-min-log) | 53 | 2 | 2015/08/16 | 4 years ago | Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory). |
| [crunch](https://github.com/superwhiskers/crunch) | 45 | 6 | 2019/02/27 | 1 month ago | Go package implementing buffers for handling various datatypes easily. |
| [goset](https://github.com/zoumo/goset) | 41 | 1 | 2017/08/25 | 9 months ago | A useful Set collection implementation for Go. |
| [nan](https://github.com/kak-tus/nan) | 41 | 3 | 2020/05/05 | 4 days ago | Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers. |
| [hide](https://github.com/emvi/hide) | 37 | 4 | 2019/01/16 | 8 months ago | ID type with marshalling to/from hash to prevent sending IDs to clients. |
| [concurrent-writer](https://github.com/free/concurrent-writer) | 36 | 5 | 2017/09/18 | 3 years ago | Highly concurrent drop-in replacement for `bufio.Writer`. |
| [pipeline](https://github.com/hyfather/pipeline) | 34 | 2 | 2018/04/25 | 3 years ago | An implementation of pipelines with fan-in and fan-out. |
| [timedmap](https://github.com/zekroTJA/timedmap) | 32 | 2 | 2019/01/30 | 3 months ago | Map with expiring key-value pairs. |
| [typ](https://github.com/gurukami/typ) | 29 | 2 | 2019/03/03 | 23 hours ago | Null Types, Safe primitive type conversion and fetching value from complex structures. |
| [deque](https://github.com/edwingeng/deque) | 28 | 4 | 2019/02/01 | 4 months ago | A highly optimized double-ended queue. |
| [dict](https://github.com/srfrog/dict) | 22 | 1 | 2019/04/23 | 11 months ago | Python-like dictionaries (dict) for Go. |
| [null](https://github.com/emvi/null) | 21 | 3 | 2018/07/04 | 8 months ago | Nullable Go types that can be marshalled/unmarshalled to/from JSON. |
| [go-ef](https://github.com/amallia/go-ef) | 18 | 2 | 2017/09/22 | 4 years ago | A Go implementation of the Elias-Fano encoding. |
| [cmap](https://github.com/lrita/cmap) | 18 | 2 | 2019/11/26 | 1 year ago | a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards. |
| [mspm](https://github.com/BlackRabbitt/mspm) | 16 | 3 | 2018/05/17 | 3 years ago | Multi-String Pattern Matching Algorithm for information retrieval. |
| [ptrie](https://github.com/viant/ptrie) | 16 | 8 | 2019/05/20 | 1 year ago | An implementation of prefix tree. |
| [set](https://github.com/StudioSol/set) | 16 | 21 | 2018/07/20 | 2 days ago | Simple set data structure implementation in Go using LinkedHashMap. |
| [treap](https://github.com/perdata/treap) | 12 | 3 | 2018/09/16 | 1 year ago | Persistent, fast ordered map using tree heaps. |
| [gofal](https://github.com/xxjwxc/gofal) | 9 | 2 | 2019/08/05 | 2 years ago | fractional api for Go. |
| [parsefields](https://github.com/MonaxGT/parsefields) | 6 | 1 | 2019/04/12 | 2 years ago | Tools for parse JSON-like logs for collecting unique fields and events. |
| [goterator](https://github.com/yaa110/goterator) | 5 | 1 | 2020/08/12 | 10 months ago | Iterator implementation to provide map and reduce functionalities. |
| [slices](https://github.com/srfrog/slices) | 3 | 2 | 2020/07/02 | 10 months ago | Functions that operate on slices; like `package strings` but adapted to work with slices. |

## Database
        
*SQL query builder, libraries for building and using SQL.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [prometheus](https://github.com/prometheus/prometheus) | 38968 | 1148 | 2012/11/24 | 3 hours ago | Monitoring system and time series database. |
| [tidb](https://github.com/pingcap/tidb) | 29156 | 1336 | 2015/09/06 | 53 minutes ago | TiDB is a distributed SQL database. Inspired by the design of Google F1. |
| [cockroach](https://github.com/cockroachdb/cockroach) | 22174 | 730 | 2014/02/06 | 11 hours ago | Scalable, Geo-Replicated, Transactional Datastore. |
| [influxdb](https://github.com/influxdata/influxdb) | 22165 | 755 | 2013/09/26 | 1 day ago | Scalable datastore for metrics, events, and real-time analytics. |
| [dgraph](https://github.com/dgraph-io/dgraph) | 16719 | 374 | 2015/08/25 | 20 hours ago | Scalable, Distributed, Low Latency, High Throughput Graph Database. |
| [vitess](https://github.com/vitessio/vitess) | 12583 | 514 | 2013/06/27 | 44 minutes ago | vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. |
| [groupcache](https://github.com/golang/groupcache) | 10683 | 500 | 2013/07/22 | 4 months ago | Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. |
| [bolt](https://github.com/boltdb/bolt) | 10426 | 343 | 2013/12/20 | 3 years ago | Low-level key/value database for Go. |
| [badger](https://github.com/dgraph-io/badger) | 9800 | 246 | 2017/01/26 | 4 days ago | Fast key-value store in Go. |
| [rqlite](https://github.com/rqlite/rqlite) | 8939 | 229 | 2014/08/23 | 1 week ago | The lightweight, distributed, relational database built on SQLite. |
| [migrate](https://github.com/golang-migrate/migrate) | 7253 | 76 | 2018/01/19 | 5 days ago | Database migrations. CLI and Golang library. |
| [pgweb](https://github.com/sosedoff/pgweb) | 7042 | 148 | 2014/10/09 | 1 week ago | Web-based PostgreSQL database browser. |
| [kingshard](https://github.com/flike/kingshard) | 5820 | 407 | 2015/07/04 | 3 months ago | kingshard is a high performance proxy for MySQL powered by Golang. |
| [go-cache](https://github.com/patrickmn/go-cache) | 5423 | 116 | 2012/01/02 | 3 months ago | In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications. |
| [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) | 5202 | 105 | 2018/09/30 | 2 days ago | fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL. |
| [bigcache](https://github.com/allegro/bigcache) | 5169 | 119 | 2016/03/23 | 6 days ago | Efficient key/value cache for gigabytes of data. |
| [bbolt](https://github.com/etcd-io/bbolt) | 4825 | 123 | 2017/06/17 | 18 hours ago | An embedded key/value database for Go. |
| [goleveldb](https://github.com/syndtr/goleveldb) | 4613 | 180 | 2013/01/23 | 1 week ago | Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go. |
| [orchestrator](https://github.com/openark/orchestrator) | 4252 | 264 | 2016/11/30 | 6 days ago | MySQL replication topology manager & visualizer. |
| [squirrel](https://github.com/Masterminds/squirrel) | 4227 | 49 | 2014/01/18 | 3 days ago | Go library that helps you build SQL queries. |
| [ledisdb](https://github.com/ledisdb/ledisdb) | 3738 | 186 | 2014/04/30 | 6 months ago | Ledisdb is a high performance NoSQL like Redis based on LevelDB. |
| [go-mysql-elasticsearch](https://github.com/go-mysql-org/go-mysql-elasticsearch) | 3609 | 181 | 2015/01/15 | 8 months ago | Sync your MySQL data into Elasticsearch automatically. |
| [buntdb](https://github.com/tidwall/buntdb) | 3469 | 100 | 2016/07/19 | 2 months ago | Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support. |
| [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) | 3419 | 178 | 2015/01/15 | 8 months ago | Sync your MySQL data into Elasticsearch automatically. |
| [orchestrator](https://github.com/github/orchestrator) | 3362 | 299 | 2016/11/30 | 1 year ago | MySQL replication topology manager & visualizer. |
| [ledisdb](https://github.com/siddontang/ledisdb) | 3265 | 188 | 2014/04/30 | 1 year ago | Ledisdb is a high performance NoSQL like Redis based on LevelDB. |
| [go-mysql](https://github.com/go-mysql-org/go-mysql) | 3246 | 162 | 2014/02/21 | 5 days ago | Go toolset to handle MySQL protocol and replication. |
| [immudb](https://github.com/codenotary/immudb) | 3134 | 52 | 2019/11/07 | 2 days ago | immudb is a lightweight, high-speed immutable database for systems and applications written in Go. |
| [go-mysql](https://github.com/siddontang/go-mysql) | 2922 | 161 | 2014/02/21 | 6 months ago | Go toolset to handle MySQL protocol and replication. |
| [xo](https://github.com/xo/xo) | 2913 | 71 | 2016/02/05 | 1 week ago | Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server. |
| [prest](https://github.com/prest/prest) | 2855 | 84 | 2016/11/22 | 1 week ago | Simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new. |
| [tiedot](https://github.com/HouzuoGuo/tiedot) | 2623 | 161 | 2013/05/26 | 3 weeks ago | Your NoSQL database powered by Golang. |
| [sql-migrate](https://github.com/rubenv/sql-migrate) | 2260 | 34 | 2014/09/09 | 1 week ago | Database migration tool. Allows embedding migrations into the application using go-bindata. |
| [goose](https://github.com/pressly/goose) | 1895 | 46 | 2016/02/25 | 4 weeks ago | Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. |
| [nutsdb](https://github.com/xujiajun/nutsdb) | 1743 | 51 | 2018/12/07 | 4 weeks ago | Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set. |
| [gcache](https://github.com/bluele/gcache) | 1712 | 44 | 2015/01/24 | 1 month ago | Cache library with support for expirable Cache, LFU, LRU and ARC. |
| [cache2go](https://github.com/muesli/cache2go) | 1606 | 69 | 2013/11/11 | 4 months ago | In-memory key:value cache which supports automatic invalidation based on timeouts. |
| [goqu](https://github.com/doug-martin/goqu) | 1278 | 38 | 2015/02/21 | 1 day ago | Idiomatic SQL builder and query library. |
| [gendry](https://github.com/didi/gendry) | 1266 | 62 | 2017/12/01 | 1 week ago | Non-invasive SQL builder and powerful data binder. |
| [fastcache](https://github.com/VictoriaMetrics/fastcache) | 1257 | 30 | 2018/11/22 | 2 weeks ago | fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead. |
| [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) | 1224 | 73 | 2018/04/11 | 1 month ago | CovenantSQL is a SQL database on blockchain. |
| [diskv](https://github.com/peterbourgon/diskv) | 1100 | 38 | 2012/03/21 | 1 month ago | Home-grown disk-backed key-value store. |
| [skeema](https://github.com/skeema/skeema) | 936 | 30 | 2016/10/31 | 2 days ago | Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools. |
| [databunker](https://github.com/securitybunker/databunker) | 896 | 27 | 2019/12/08 | 1 month ago | Personally identifiable information (PII) storage service built to comply with GDPR and CCPA. |
| [eliasdb](https://github.com/krotik/eliasdb) | 837 | 25 | 2016/08/13 | 4 months ago | Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language. |
| [moss](https://github.com/couchbase/moss) | 828 | 76 | 2016/02/06 | 2 months ago | Moss is a simple LSM key-value storage engine written in 100% Go. |
| [pogreb](https://github.com/akrylysov/pogreb) | 817 | 25 | 2018/01/06 | 1 month ago | Embedded key-value store for read-heavy workloads. |
| [chproxy](https://github.com/Vertamedia/chproxy) | 720 | 31 | 2017/09/18 | 6 days ago | HTTP proxy for ClickHouse database. |
| [gormigrate](https://github.com/go-gormigrate/gormigrate) | 679 | 7 | 2016/08/31 | 8 hours ago | Database schema migration helper for Gorm ORM. |
| [dotsql](https://github.com/qustavo/dotsql) | 600 | 25 | 2014/11/20 | 1 month ago | Go library that helps you keep sql files in one place and use them with ease. |
| [dotsql](https://github.com/gchaincl/dotsql) | 591 | 25 | 2014/11/20 | 7 months ago | Go library that helps you keep sql files in one place and use them with ease. |
| [pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) | 552 | 16 | 2018/12/19 | 1 week ago | Advanced scheduling for PostgreSQL. |
| [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) | 542 | 28 | 2015/12/10 | 8 months ago | Powerful data retrieval methods as well as DB-agnostic query building capabilities. |
| [jet](https://github.com/go-jet/jet) | 489 | 11 | 2019/03/02 | 1 week ago | Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure. |
| [levigo](https://github.com/jmhodges/levigo) | 401 | 23 | 2012/01/17 | 1 year ago | Levigo is a Go wrapper for LevelDB. |
| [dbq](https://github.com/rocketlaunchr/dbq) | 318 | 9 | 2019/07/11 | 7 months ago | Zero boilerplate database operations for Go. |
| [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) | 306 | 7 | 2017/04/29 | 5 months ago | Collects small insterts and sends big requests to ClickHouse servers. |
| [pudge](https://github.com/recoilme/pudge) | 296 | 11 | 2018/11/20 | 3 months ago | Fast and simple  key/value store written using Go's standard library. |
| [sqrl](https://github.com/elgris/sqrl) | 231 | 9 | 2014/06/25 | 2 days ago | SQL query builder, fork of Squirrel with improved performance. |
| [vasto](https://github.com/chrislusf/vasto) | 221 | 19 | 2018/01/16 | 2 years ago | A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption. |
| [kivik](https://github.com/go-kivik/kivik) | 215 | 5 | 2017/02/09 | 3 months ago | Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases. |
| [piladb](https://github.com/fern4lvarez/piladb) | 189 | 12 | 2015/09/08 | 11 months ago | Lightweight RESTful database engine based on stack data structures. |
| [myreplication](https://github.com/2tvenom/myreplication) | 175 | 21 | 2015/02/04 | 3 years ago | MySql binary log replication listener. Supports statement and row based replication. |
| [sqlingo](https://github.com/lqs/sqlingo) | 158 | 13 | 2018/11/18 | 1 week ago | A lightweight DSL to build SQL in Go. |
| [goose](https://github.com/steinbacher/goose) | 144 | 4 | 2016/03/04 | 5 years ago | Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. |
| [octillery](https://github.com/blastrain/octillery) | 144 | 19 | 2018/11/26 | 4 months ago | Go package for sharding databases ( Supports every ORM or raw SQL ). |
| [golang-scribble](https://github.com/nanobox-io/golang-scribble) | 135 | 5 | 2018/06/21 | 2 years ago | Tiny flat file JSON store. |
| [darwin](https://github.com/GuiaBolso/darwin) | 123 | 4 | 2016/04/05 | 6 months ago | Database schema evolution library for Go. |
| [go-structured-query](https://github.com/bokwoon95/go-structured-query) | 123 | 1 | 2020/05/30 | 1 month ago | Type-safe SQL builder and struct mapper for Go. |
| [migrator](https://github.com/lopezator/migrator) | 116 | 5 | 2019/02/04 | 1 year ago | Dead simple Go database migration library. |
| [slowpoke](https://github.com/recoilme/slowpoke) | 97 | 8 | 2018/02/19 | 2 years ago | Key-value store with persistence. |
| [cache](https://github.com/akyoto/cache) | 94 | 3 | 2019/05/11 | 1 year ago | In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage. |
| [databunker](https://github.com/paranoidguy/databunker) | 93 | 9 | 2019/12/08 | 10 months ago | Personally identifiable information (PII) storage service built to comply with GDPR and CCPA. |
| [octillery](https://github.com/knocknote/octillery) | 92 | 16 | 2018/11/26 | 1 year ago | Go package for sharding databases ( Supports every ORM or raw SQL ). |
| [igor](https://github.com/galeone/igor) | 84 | 7 | 2016/03/10 | 1 year ago | Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax. |
| [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) | 80 | 1 | 2018/08/11 | 1 month ago | A Go package to help write migrations with go-pg/pg. |
| [unitdb](https://github.com/unit-io/unitdb) | 74 | 8 | 2019/08/29 | 1 month ago | Fast timeseries database for IoT, realtime messaging  applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application. |
| [bcache](https://github.com/iwanbk/bcache) | 70 | 3 | 2018/12/26 | 2 years ago | Eventually consistent distributed in-memory  cache Go library. |
| [dbbench](https://github.com/sj14/dbbench) | 59 | 4 | 2018/11/24 | 4 days ago | Database benchmarking tool with support for several databases and scripts. |
| [couchcache](https://github.com/codingsince1985/couchcache) | 54 | 3 | 2015/04/05 | 1 day ago | RESTful caching micro-service backed by Couchbase server. |
| [godbal](https://github.com/xujiajun/godbal) | 52 | 4 | 2018/02/28 | 2 years ago | Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily. |
| [datagen](https://github.com/codingconcepts/datagen) | 40 | 1 | 2019/04/18 | 1 year ago | A fast data generator that's multi-table aware and supports multi-row DML. |
| [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) | 38 | 6 | 2017/12/18 | 3 years ago | BigCache with clustering support and individual item expiration. |
| [buildsqlx](https://github.com/arthurkushman/buildsqlx) | 38 | 1 | 2019/08/18 | 5 months ago | Go database query builder library for PostgreSQL. |
| [gondolier](https://github.com/emvi/gondolier) | 31 | 4 | 2017/10/18 | 2 years ago | Database migration library using struct decorators. |
| [prep](https://github.com/hexdigest/prep) | 28 | 3 | 2017/12/11 | 3 years ago | Use prepared SQL statements without changing your code. |
| [coffer](https://github.com/claygod/coffer) | 27 | 5 | 2019/05/13 | 4 days ago | Simple ACID key-value database that supports transactions. |
| [go-fixtures](https://github.com/RichardKnop/go-fixtures) | 26 | 1 | 2015/12/24 | 1 year ago | Django style fixtures for Golang's excellent built-in database/sql library. |
| [avro](https://github.com/khezen/avro) | 25 | 2 | 2019/04/07 | 1 year ago | Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes. |
| [pravasan](https://github.com/pravasan/pravasan) | 24 | 7 | 2015/01/03 | 2 years ago | Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc. |
| [sqlf](https://github.com/leporo/sqlf) | 24 | 4 | 2019/07/20 | 1 day ago | Fast SQL query builder. |
| [qry](https://github.com/HnH/qry) | 19 | 3 | 2019/08/20 | 3 days ago | Tool that generates constants from files with raw SQL queries. |
| [gosql](https://github.com/twharmon/gosql) | 16 | 1 | 2020/01/08 | 1 year ago | SQL Query builder with better null values support. |
| [tempdb](https://github.com/rafaeljesus/tempdb) | 15 | 3 | 2017/03/17 | 3 years ago | Key-value store for temporary items. |
| [gorocksdb](https://github.com/kapitan-k/gorocksdb) | 12 | 1 | 2017/12/28 | 3 years ago | Gorocksdb is a wrapper for [RocksDB](https://rocksdb.org) written in Go. |
| [rwdb](https://github.com/andizzle/rwdb) | 12 | 2 | 2017/10/04 | 3 years ago | rwdb provides read replica capability for multiple database servers setup. |
| [mpath-go](https://github.com/spacetab-io/mpath-go) | 9 | 4 | 2020/01/09 | 1 year ago | MPTT (Modified Preorder Tree Traversal) package for SQL records - materialized path realisation. |
| [schema](https://github.com/adlio/schema) | 7 | 3 | 2019/09/24 | 8 months ago | Library to embed schema migrations for database/sql-compatible databases inside your Go binaries. |
| [bucket](https://github.com/PumpkinSeed/bucket) | 6 | 3 | 2019/09/22 | 1 year ago | Optimized data structure framework for Couchbase specialized on one bucket usage. |
| [gostore](https://github.com/twharmon/gostore) | 5 | 2 | 2020/01/08 | 1 year ago | Gostore is a simple, durable, embedded key-value storage engine written in Go. |
| [go-pg-migrate](https://github.com/lawzava/go-pg-migrate) | 5 | 1 | 2021/01/16 | 3 months ago | CLI-friendly package for go-pg migrations management. |
| [tracedb](https://github.com/unit-io/tracedb) | 3 | 1 | 2019/08/29 | 1 year ago | Fast timeseries database for IoT, realtime messaging  applications. Access tracedb with pubsub over tcp or websocket using github.com/unit-io/trace application. |
| [ttlcache](https://github.com/cheshir/ttlcache) | 3 | 1 | 2021/01/06 | 6 months ago | In-memory key value storage with TTL for each record. |
| [bitcask](https://github.com/prologic/bitcask) | 1 | 1 | 2019/03/12 | 2 months ago | Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL). |
| [ormlite](https://github.com/pupizoid/ormlite) | 1 | 2 | 2018/06/28 | 8 months ago | Lightweight package containing some ORM-like features and helpers for sqlite databases. |

## Database Drivers
        
*Libraries for connecting and operating databases.*

### Relational Databases
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [mysql](https://github.com/go-sql-driver/mysql) | 11535 | 406 | 2012/12/09 | 2 weeks ago | MySQL driver for Go. |
| [pq](https://github.com/lib/pq) | 6800 | 151 | 2012/03/12 | 1 week ago | Pure Go Postgres driver for database/sql. |
| [go-sqlite3](https://github.com/mattn/go-sqlite3) | 5126 | 151 | 2011/11/11 | 1 month ago | SQLite3 driver for go that uses database/sql. |
| [pgx](https://github.com/jackc/pgx) | 4574 | 85 | 2013/03/30 | 1 day ago | PostgreSQL driver supporting features beyond those exposed by database/sql. |
| [go-mssqldb](https://github.com/denisenkom/go-mssqldb) | 1440 | 69 | 2013/12/16 | 1 day ago | Microsoft MSSQL driver for Go. |
| [go-oci8](https://github.com/mattn/go-oci8) | 563 | 40 | 2012/02/29 | 8 months ago | Oracle driver for go that uses database/sql. |
| [godror](https://github.com/godror/godror) | 294 | 20 | 2019/11/21 | 2 days ago | Oracle driver for Go, using the ODPI-C driver. |
| [goracle](https://github.com/go-goracle/goracle) | 283 | 28 | 2015/03/25 | 1 year ago | Oracle driver for Go, using the ODPI-C driver. |
| [firebirdsql](https://github.com/nakagami/firebirdsql) | 153 | 18 | 2013/08/27 | 15 hours ago | Firebird RDBMS SQL driver for Go. |
| [go-adodb](https://github.com/mattn/go-adodb) | 122 | 12 | 2011/11/14 | 1 year ago | Microsoft ActiveX Object DataBase driver for go that uses database/sql. |
| [gofreetds](https://github.com/minus5/gofreetds) | 106 | 23 | 2012/12/06 | 10 months ago | Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org). |
| [sqinn-go](https://github.com/cvilsmeier/sqinn-go) | 79 | 1 | 2020/06/06 | 4 months ago | SQLite with pure Go. |
| [calcite-avatica-go](https://github.com/apache/calcite-avatica-go) | 78 | 25 | 2017/08/08 | 1 year ago | Apache Avatica/Phoenix SQL driver for database/sql. |
| [bgc](https://github.com/viant/bgc) | 15 | 11 | 2016/06/13 | 1 year ago | Datastore Connectivity for BigQuery for go. |

### NoSQL Databases
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [cayley](https://github.com/cayleygraph/cayley) | 13953 | 607 | 2014/06/05 | 1 month ago | Graph database with support for multiple backends. |
| [redis](https://github.com/go-redis/redis) | 12572 | 247 | 2012/07/25 | 20 hours ago | Redis client for Golang. |
| [redigo](https://github.com/gomodule/redigo) | 8675 | 297 | 2012/04/14 | 3 days ago | Redigo is a Go client for the Redis database. |
| [bleve](https://github.com/blevesearch/bleve) | 7859 | 252 | 2014/04/17 | 1 week ago | Modern text indexing library for go. |
| [elastic](https://github.com/olivere/elastic) | 6247 | 174 | 2012/12/06 | 1 week ago | Elasticsearch client for Go. |
| [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) | 6112 | 135 | 2017/02/08 | 1 day ago | Official MongoDB driver for the Go language. |
| [riot](https://github.com/go-ego/riot) | 5980 | 201 | 2017/06/21 | 11 months ago | Go Open Source, Distributed, Simple and efficient Search Engine. |
| [go-elasticsearch](https://github.com/elastic/go-elasticsearch) | 3653 | 311 | 2017/03/27 | 2 days ago | Official Elasticsearch client for Go. |
| [mgo](https://github.com/globalsign/mgo) | 1913 | 62 | 2017/04/13 | 6 months ago | (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms. |
| [rethinkdb-go](https://github.com/rethinkdb/rethinkdb-go) | 1573 | 49 | 2013/09/12 | 6 days ago | Go language driver for RethinkDB. |
| [elastigo](https://github.com/mattbaird/elastigo) | 950 | 47 | 2012/10/12 | 2 years ago | Elasticsearch client library. |
| [elasticsql](https://github.com/cch123/elasticsql) | 789 | 33 | 2016/08/24 | 3 weeks ago | Convert sql to elasticsearch dsl in Go. |
| [qmgo](https://github.com/qiniu/qmgo) | 674 | 19 | 2020/08/04 | 2 weeks ago | The MongoDB driver for Go. It‘s based on official MongoDB driver but easier to use like Mgo. |
| [redeo](https://github.com/bsm/redeo) | 401 | 26 | 2014/03/06 | 9 months ago | Redis-protocol compatible TCP servers/services. |
| [neoism](https://github.com/jmcvetta/neoism) | 379 | 25 | 2012/07/12 | 1 year ago | Neo4j client for Golang. |
| [mgm](https://github.com/Kamva/mgm) | 372 | 16 | 2019/12/27 | 2 months ago | MongoDB model-based ODM for Go (based on official MongoDB driver). |
| [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) | 370 | 42 | 2014/07/26 | 1 week ago | Aerospike client in Go language. |
| [gokv](https://github.com/philippgille/gokv) | 362 | 10 | 2018/10/08 | 2 weeks ago | Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more). |
| [gocb](https://github.com/couchbase/gocb) | 329 | 67 | 2015/01/15 | 1 week ago | Official Couchbase Go SDK. |
| [go-couchbase](https://github.com/couchbase/go-couchbase) | 314 | 25 | 2012/01/19 | 1 month ago | Couchbase client in Go. |
| [go-rejson](https://github.com/nitishm/go-rejson) | 180 | 7 | 2018/04/23 | 6 months ago | Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease. |
| [cachego](https://github.com/faabiosr/cachego) | 158 | 7 | 2016/10/05 | 1 week ago | Golang Cache component for multiple drivers. |
| [godis](https://github.com/piaohao/godis) | 95 | 10 | 2019/06/14 | 1 year ago | redis client implement by golang, inspired by jedis. |
| [skizze](https://github.com/seiflotfy/skizze) | 79 | 6 | 2016/01/17 | 5 years ago | probabilistic data-structures service and storage. |
| [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) | 76 | 7 | 2011/06/04 | 3 years ago | Neo4j REST Client in golang. |
| [dynago](https://github.com/underarmour/dynago) | 71 | 124 | 2015/05/18 | 4 years ago | Dynago is a principle of least surprise client for DynamoDB. |
| [arangolite](https://github.com/solher/arangolite) | 69 | 6 | 2015/10/04 | 6 months ago | Lightweight golang driver for ArangoDB. |
| [go-pilosa](https://github.com/pilosa/go-pilosa) | 46 | 20 | 2016/09/30 | 1 year ago | Go client library for Pilosa. |
| [goforestdb](https://github.com/couchbase/goforestdb) | 30 | 39 | 2014/05/14 | 4 years ago | Go bindings for ForestDB. |
| [neo4j](https://github.com/cihangir/neo4j) | 26 | 4 | 2013/05/18 | 6 years ago | Neo4j Rest API Bindings for Golang. |
| [goriak](https://github.com/zegl/goriak) | 25 | 4 | 2016/10/05 | 2 weeks ago | Go language driver for Riak KV. |
| [goes](https://github.com/OwnLocal/goes) | 24 | 34 | 2015/12/28 | 11 months ago | Library to interact with Elasticsearch. |
| [dsc](https://github.com/viant/dsc) | 22 | 16 | 2016/06/13 | 1 year ago | Datastore connectivity for SQL, NoSQL, structured files. |
| [xredis](https://github.com/shomali11/xredis) | 15 | 2 | 2017/06/14 | 2 years ago | Typesafe, customizable, clean & easy to use Redis client. |
| [godscache](https://github.com/defcronyke/godscache) | 9 | 3 | 2018/05/08 | 2 years ago | A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached. |
| [asc](https://github.com/viant/asc) | 6 | 11 | 2016/06/13 | 2 years ago | Datastore Connectivity for Aerospike for go. |
| [gocosmos](https://github.com/btnguyen2k/gocosmos) | 4 | 2 | 2020/12/06 | 2 months ago | REST client and standard `database/sql` driver for Azure Cosmos DB. |

## Date and Time
        
*Libraries for working with dates and times.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [now](https://github.com/jinzhu/now) | 3285 | 64 | 2013/11/18 | 1 month ago | Now is a time toolkit for golang. |
| [dateparse](https://github.com/araddon/dateparse) | 1537 | 22 | 2014/04/21 | 1 month ago | Parse date's without knowing format in advance. |
| [carbon](https://github.com/uniplaces/carbon) | 621 | 43 | 2016/08/03 | 3 months ago | Simple Time extension with a lot of util methods, ported from PHP Carbon library. |
| [durafmt](https://github.com/hako/durafmt) | 403 | 6 | 2016/05/20 | 3 months ago | Time duration formatting library for Go. |
| [timeutil](https://github.com/leekchan/timeutil) | 185 | 8 | 2015/08/02 | 2 years ago | Useful extensions (Timedelta, Strftime, ...) to the golang's time package. |
| [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) | 104 | 4 | 2016/01/31 | 4 months ago | The implementation of the Persian (Solar Hijri) Calendar in Go (golang). |
| [iso8601](https://github.com/relvacode/iso8601) | 95 | 4 | 2017/04/25 | 3 months ago | Efficiently parse ISO8601 date-times without regex. |
| [date](https://github.com/rickb777/date) | 76 | 3 | 2015/11/23 | 3 weeks ago | Augments Time for working with dates, date ranges, time spans, periods, and time-of-day. |
| [timespan](https://github.com/SaidinWoT/timespan) | 75 | 6 | 2014/10/07 | 2 years ago | For interacting with intervals of time, defined as a start time and a duration. |
| [feiertage](https://github.com/wlbr/feiertage) | 40 | 3 | 2015/11/04 | 1 month ago | Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving... |
| [go-sunrise](https://github.com/nathan-osman/go-sunrise) | 37 | 5 | 2017/06/15 | 3 months ago | Calculate the sunrise and sunset times for a given location. |
| [go-str2duration](https://github.com/xhit/go-str2duration) | 31 | 3 | 2020/02/02 | 1 year ago | Convert string to duration. Support time.Duration returned string and more. |
| [kair](https://github.com/GuilhermeCaruso/kair) | 21 | 1 | 2018/10/03 | 1 year ago | Date and Time - Golang Formatting Library. |
| [cronrange](https://github.com/1set/cronrange) | 12 | 2 | 2019/11/10 | 1 month ago | Parses Cron-style time range expressions, checks if the given time is within any ranges. |
| [nulltime](https://github.com/kirillDanshin/nulltime) | 11 | 2 | 2016/03/06 | 4 years ago | Nullable `time.Time`. |
| [tuesday](https://github.com/osteele/tuesday) | 9 | 3 | 2017/08/10 | 3 months ago | Ruby-compatible Strftime function. |
| [strftime](https://github.com/awoodbeck/strftime) | 7 | 2 | 2018/02/10 | 3 years ago | C99-compatible strftime formatter. |
| [go-week](https://github.com/stoewer/go-week) | 6 | 5 | 2018/02/23 | 1 year ago | An efficient package to work with ISO8601 week dates. |

## Distributed Systems
        
*Packages that help with building Distributed Systems.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [kit](https://github.com/go-kit/kit) | 21360 | 695 | 2015/02/03 | 2 days ago | Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc. |
| [go-micro](https://github.com/asim/go-micro) | 16873 | 513 | 2015/01/13 | 1 day ago | A distributed systems development framework. |
| [nitro](https://github.com/gonitro/nitro) | 14946 | 498 | 2015/01/13 | 10 months ago | A distributed systems development framework. |
| [nitro](https://github.com/asim/nitro) | 14898 | 498 | 2015/01/13 | 10 months ago | A distributed systems development framework. |
| [grpc-go](https://github.com/grpc/grpc-go) | 14614 | 488 | 2014/12/08 | 1 day ago | The Go language implementation of gRPC. HTTP/2 based RPC. |
| [go-micro](https://github.com/micro/go-micro) | 14444 | 485 | 2015/01/13 | 11 months ago | A distributed systems development framework. |
| [micro](https://github.com/micro/micro) | 10415 | 336 | 2015/01/16 | 4 days ago | A distributed systems runtime for the cloud and beyond. |
| [nats-server](https://github.com/nats-io/nats-server) | 9926 | 378 | 2012/10/29 | 2 days ago | Lightweight, high performance messaging system for microservices, IoT, and cloud native systems. |
| [rpcx](https://github.com/smallnest/rpcx) | 6065 | 343 | 2016/05/18 | 2 weeks ago | Distributed pluggable RPC service framework like alibaba Dubbo. |
| [raft](https://github.com/hashicorp/raft) | 5098 | 349 | 2013/11/05 | 2 days ago | Golang implementation of the Raft consensus protocol, by HashiCorp. |
| [lura](https://github.com/luraproject/lura) | 4551 | 121 | 2016/11/04 | 3 weeks ago | Ultra performant API Gateway framework with middlewares. |
| [tendermint](https://github.com/tendermint/tendermint) | 4352 | 256 | 2014/05/14 | 1 day ago | High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols. |
| [torrent](https://github.com/anacrolix/torrent) | 4054 | 132 | 2015/01/08 | 16 hours ago | BitTorrent client package. |
| [krakend](https://github.com/devopsfaith/krakend) | 3891 | 112 | 2016/11/04 | 5 months ago | Ultra performant API Gateway framework with middlewares. |
| [dragonboat](https://github.com/lni/dragonboat) | 3853 | 144 | 2018/12/23 | 2 weeks ago | A feature complete and high performance multi-group Raft library in Go. |
| [emitter](https://github.com/emitter-io/emitter) | 3043 | 101 | 2016/10/29 | 3 months ago | High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love. |
| [glow](https://github.com/chrislusf/glow) | 2989 | 147 | 2015/06/14 | 2 years ago | Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go. |
| [gleam](https://github.com/chrislusf/gleam) | 2893 | 152 | 2016/08/26 | 4 months ago | Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed. |
| [liftbridge](https://github.com/liftbridge-io/liftbridge) | 2138 | 70 | 2017/10/13 | 4 days ago | Lightweight, fault-tolerant message streams for NATS. |
| [hprose-golang](https://github.com/hprose/hprose-golang) | 1180 | 92 | 2014/02/14 | 1 month ago | Very newbility RPC Library, support 25+ languages now. |
| [ringpop-go](https://github.com/uber/ringpop-go) | 699 | 2443 | 2015/06/05 | 7 months ago | Scalable, fault-tolerant application-layer sharding for Go applications. |
| [gorpc](https://github.com/valyala/gorpc) | 643 | 24 | 2014/11/20 | 2 years ago | Simple, fast and scalable RPC library for high load. |
| [rain](https://github.com/cenkalti/rain) | 633 | 17 | 2014/05/21 | 3 days ago | BitTorrent client and library. |
| [go-health](https://github.com/InVisionApp/go-health) | 602 | 120 | 2017/11/29 | 1 year ago | Library for enabling asynchronous dependency health checks in your service. |
| [redislock](https://github.com/bsm/redislock) | 505 | 8 | 2019/06/24 | 2 months ago | Simplified distributed locking implementation using Redis. |
| [go-sundheit](https://github.com/AppsFlyer/go-sundheit) | 432 | 9 | 2019/04/08 | 1 month ago | A library built to provide support for defining async service health checks for golang services. |
| [consistent](https://github.com/buraksezer/consistent) | 411 | 14 | 2018/03/25 | 3 months ago | Consistent hashing with bounded loads. |
| [digota](https://github.com/digota/digota) | 407 | 29 | 2017/08/14 | 7 months ago | grpc ecommerce microservice. |
| [arpc](https://github.com/lesismal/arpc) | 369 | 18 | 2020/05/19 | 3 days ago | More effective network communication, support two-way-calling, notify, broadcast. |
| [sleuth](https://github.com/ursiform/sleuth) | 339 | 10 | 2016/04/23 | 3 years ago | Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)). |
| [go-jump](https://github.com/dgryski/go-jump) | 334 | 16 | 2014/06/15 | 3 years ago | Port of Google's "Jump" Consistent Hash function. |
| [dht](https://github.com/anacrolix/dht) | 205 | 13 | 2016/12/14 | 6 days ago | BitTorrent Kademlia DHT implementation. |
| [jsonrpc](https://github.com/ybbus/jsonrpc) | 190 | 9 | 2016/11/10 | 3 weeks ago | JSON-RPC 2.0 HTTP client implementation. |
| [jsonrpc](https://github.com/osamingo/jsonrpc) | 154 | 5 | 2016/10/28 | 3 days ago | The jsonrpc package helps implement of JSON-RPC 2.0. |
| [celeriac.v1](https://github.com/svcavallar/celeriac.v1) | 67 | 4 | 2015/10/10 | 11 months ago | Library for adding support for interacting and monitoring Celery workers, tasks and events in Go. |
| [doublejump](https://github.com/edwingeng/doublejump) | 66 | 5 | 2018/06/26 | 2 months ago | A revamped Google's jump consistent hash. |
| [outboxer](https://github.com/italolelis/outboxer) | 56 | 0 | 2019/02/01 | 5 days ago | Outboxer is a go library that implements the outbox pattern. |
| [semaphore](https://github.com/jexia/semaphore) | 56 | 15 | 2020/02/05 | 4 months ago | A straightforward (micro) service orchestrator. |
| [flowgraph](https://github.com/vectaport/flowgraph) | 41 | 1 | 2018/08/29 | 5 months ago | flow-based programming package. |
| [drmaa](https://github.com/dgruber/drmaa) | 34 | 3 | 2013/03/17 | 1 year ago | Job submission library for cluster schedulers based on the DRMAA standard. |
| [maestro](https://github.com/jexia/maestro) | 34 | 16 | 2020/02/05 | 1 year ago | A straightforward (micro) service orchestrator. |
| [go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) | 31 | 1 | 2020/06/06 | 2 months ago | MySQL based distributed lock. |
| [go-pdu](https://github.com/pdupub/go-pdu) | 29 | 5 | 2018/10/08 | 1 month ago | A decentralized identity-based social network. |
| [dynatomic](https://github.com/tylfin/dynatomic) | 14 | 0 | 2019/02/08 | 11 months ago | A library for using DynamoDB as an atomic counter. |
| [micro](https://github.com/gmsec/micro) | 13 | 3 | 2020/05/03 | 1 month ago | A Go distributed systems development framework. |
| [consistenthash](https://github.com/mbrostami/consistenthash) | 9 | 1 | 2020/04/22 | 1 year ago | Consistent hashing with configurable replicas. |

## Dynamic DNS
        
*Tools for updating dynamic DNS records.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [godns](https://github.com/TimothyYe/godns) | 876 | 33 | 2014/05/11 | 1 week ago | A dynamic DNS client tool, supports DNSPod & HE.net, written in Go. |
| [ddns](https://github.com/skibish/ddns) | 193 | 8 | 2017/03/13 | 4 months ago | Personal DDNS client with Digital Ocean Networking DNS as backend. |

## Email
        
*Libraries and tools that implement email creation and sending.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [MailHog](https://github.com/mailhog/MailHog) | 9059 | 147 | 2014/04/16 | 3 days ago | Email and SMTP testing with web and API interface. |
| [hermes](https://github.com/matcornic/hermes) | 2343 | 29 | 2017/03/25 | 10 months ago | Golang package that generates clean, responsive HTML e-mails. |
| [email](https://github.com/jordan-wright/email) | 1832 | 50 | 2013/12/12 | 1 month ago | A robust and flexible email library for Go. |
| [go-imap](https://github.com/emersion/go-imap) | 1365 | 43 | 2016/04/26 | 3 weeks ago | IMAP library for clients and servers. |
| [sendgrid-go](https://github.com/sendgrid/sendgrid-go) | 762 | 194 | 2013/09/12 | 1 week ago | SendGrid's Go library for sending email. |
| [mailgun-go](https://github.com/mailgun/mailgun-go) | 540 | 72 | 2014/02/28 | 4 days ago | Go library for sending mail with the Mailgun API. |
| [email-verifier](https://github.com/AfterShip/email-verifier) | 313 | 22 | 2020/12/18 | 1 week ago | A Go library for email verification without sending any emails. |
| [go-message](https://github.com/emersion/go-message) | 213 | 13 | 2016/12/31 | 3 months ago | Streaming library for the Internet Message Format and mail messages. |
| [hectane](https://github.com/hectane/hectane) | 209 | 14 | 2015/08/28 | 10 months ago | Lightweight SMTP client providing an HTTP API. |
| [go-simple-mail](https://github.com/xhit/go-simple-mail) | 204 | 4 | 2019/09/15 | 7 hours ago | Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send. |
| [douceur](https://github.com/aymerick/douceur) | 198 | 3 | 2015/04/09 | 3 months ago | CSS inliner for your HTML emails. |
| [mailchain](https://github.com/mailchain/mailchain) | 86 | 6 | 2019/04/11 | 2 months ago | Send encrypted emails to blockchain addresses written in Go. |
| [go-premailer](https://github.com/vanng822/go-premailer) | 73 | 2 | 2015/02/16 | 7 months ago | Inline styling for HTML mail in Go. |
| [go-dkim](https://github.com/toorop/go-dkim) | 71 | 3 | 2015/04/29 | 11 months ago | DKIM library, to sign & verify email. |
| [smtp](https://github.com/mailhog/smtp) | 65 | 9 | 2014/12/24 | 6 months ago | SMTP server protocol state machine. |
| [go-email-validator](https://github.com/go-email-validator/go-email-validator) | 13 | 4 | 2020/12/10 | 4 days ago | Modular email validator for syntax, disposable, smtp, etc... checking. |

## Embeddable Scripting Languages
        
*Embedding other languages inside your go code.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [otto](https://github.com/robertkrimen/otto) | 5508 | 183 | 2012/10/06 | 1 year ago | JavaScript interpreter written in Go. |
| [gopher-lua](https://github.com/yuin/gopher-lua) | 4319 | 151 | 2015/02/15 | 1 week ago | Lua 5.1 VM and compiler written in Go. |
| [tengo](https://github.com/d5/tengo) | 2442 | 57 | 2019/01/09 | 1 week ago | Bytecode compiled script language for Go. |
| [goja](https://github.com/dop251/goja) | 2407 | 67 | 2016/11/04 | 4 days ago | ECMAScript 5.1(+) implementation in Go. |
| [go-lua](https://github.com/Shopify/go-lua) | 2163 | 330 | 2013/12/20 | 2 months ago | Port of the Lua 5.2 VM to pure Go. |
| [expr](https://github.com/antonmedv/expr) | 1969 | 42 | 2018/07/14 | 1 month ago | Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing. |
| [go-python](https://github.com/sbinet/go-python) | 1307 | 44 | 2012/07/09 | 5 months ago | naive go bindings to the CPython C-API. |
| [anko](https://github.com/mattn/anko) | 1181 | 47 | 2014/03/28 | 4 months ago | Scriptable interpreter written in Go. |
| [cel-go](https://github.com/google/cel-go) | 911 | 31 | 2018/03/09 | 2 days ago | Fast, portable, non-Turing complete expression evaluation with gradual typing. |
| [go-php](https://github.com/deuill/go-php) | 812 | 43 | 2015/09/17 | 3 years ago | PHP bindings for Go. |
| [go-duktape](https://github.com/olebedev/go-duktape) | 778 | 28 | 2015/01/08 | 6 months ago | Duktape JavaScript engine bindings for Go. |
| [golua](https://github.com/aarzilli/golua) | 557 | 34 | 2010/12/06 | 4 months ago | Go bindings for Lua C API. |
| [gisp](https://github.com/jcla1/gisp) | 467 | 22 | 2014/01/11 | 4 years ago | Simple LISP in Go. |
| [gval](https://github.com/PaesslerAG/gval) | 378 | 15 | 2017/09/27 | 4 months ago | A highly customizable expression language written in Go. |
| [gentee](https://github.com/gentee/gentee) | 81 | 3 | 2018/01/14 | 9 months ago | Embeddable scripting programming language. |
| [binder](https://github.com/alexeyco/binder) | 53 | 2 | 2017/04/02 | 3 years ago | Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua). |
| [purl](https://github.com/ian-kent/purl) | 33 | 3 | 2014/11/29 | 6 years ago | Perl 5.18.2 embedded in Go. |
| [ngaro](https://github.com/db47h/ngaro) | 20 | 2 | 2016/08/09 | 3 years ago | Embeddable Ngaro VM implementation enabling scripting in Retro. |
| [ecal](https://github.com/krotik/ecal) | 12 | 2 | 2020/11/30 | 4 months ago | A simple embeddable scripting language which supports concurrent event processing. |

## Error Handling
        
*Libraries for handling errors.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [errors](https://github.com/pkg/errors) | 7306 | 112 | 2015/12/27 | 1 month ago | Package that provides simple error handling primitives. |
| [go-multierror](https://github.com/hashicorp/go-multierror) | 1358 | 234 | 2014/12/15 | 2 months ago | Go (golang) package for representing a list of errors as a single error. |
| [eris](https://github.com/rotisserie/eris) | 837 | 11 | 2019/09/07 | 2 months ago | A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors. |
| [errorx](https://github.com/joomcode/errorx) | 769 | 75 | 2018/08/17 | 5 months ago | A feature rich error package with stack traces, composition of errors and more. |
| [tracerr](https://github.com/ztrue/tracerr) | 685 | 11 | 2019/02/06 | 2 years ago | Golang errors with stack trace and source fragments. |
| [errlog](https://github.com/snwfdhmp/errlog) | 397 | 6 | 2019/02/16 | 10 months ago | Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place. |
| [emperror](https://github.com/emperror/emperror) | 222 | 4 | 2017/06/13 | 1 year ago | Error handling tools and best practices for Go libraries and applications. |
| [errors](https://github.com/emperror/errors) | 99 | 4 | 2019/07/09 | 6 months ago | Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives. |
| [errors](https://github.com/bnkamalesh/errors) | 24 | 2 | 2020/07/17 | 4 months ago | Drop-in replacement for builting Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions. |
| [werr](https://github.com/txgruppi/werr) | 13 | 0 | 2015/08/04 | 5 years ago | Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called. |
| [falcon](https://github.com/SonicRoshan/falcon) | 7 | 2 | 2019/09/09 | 2 years ago | A Simple Yet Highly Powerful Package For Error Handling. |
| [errors](https://github.com/neuronlabs/errors) | 3 | 2 | 2019/07/26 | 2 years ago | Simple golang error handling with classification primitives. |
| [errors](https://github.com/PumpkinSeed/errors) | 3 | 1 | 2020/01/08 | 1 year ago | The most simple error wrapper with awesome performance and minimal memory overhead. |

## Files
        
*Libraries for handling files and file systems.*

## Financial
        
*Packages for accounting and finance.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [decimal](https://github.com/shopspring/decimal) | 3358 | 64 | 2015/02/25 | 3 weeks ago | Arbitrary-precision fixed-point decimal numbers. |
| [go-money](https://github.com/Rhymond/go-money) | 995 | 15 | 2017/03/20 | 3 days ago | Implementation of Fowler's Money pattern. |
| [accounting](https://github.com/leekchan/accounting) | 676 | 14 | 2015/08/10 | 8 months ago | money and currency formatting for golang. |
| [go-finance](https://github.com/FlashBoys/go-finance) | 534 | 27 | 2016/02/28 | 3 years ago | Comprehensive financial markets data in Go. |
| [techan](https://github.com/sdcoffey/techan) | 525 | 46 | 2017/03/08 | 2 weeks ago | Technical analysis library with advanced market analysis and trading strategies. |
| [currency](https://github.com/bojanz/currency) | 264 | 6 | 2020/04/16 | 4 months ago | Handles currency amounts, provides currency information and formatting. |
| [orderbook](https://github.com/i25959341/orderbook) | 218 | 19 | 2018/04/24 | 4 months ago | Matching Engine for Limit Order Book in Golang. |
| [go-finance](https://github.com/alpeb/go-finance) | 110 | 8 | 2017/06/01 | 5 months ago | Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations. |
| [transaction](https://github.com/claygod/transaction) | 95 | 9 | 2017/10/11 | 2 months ago | Embedded transactional database of accounts, running in multithreaded mode. |
| [ofxgo](https://github.com/aclindsa/ofxgo) | 93 | 10 | 2015/11/08 | 1 month ago | Query OFX servers and/or parse the responses (with example command-line client). |
| [vat](https://github.com/dannyvankooten/vat) | 84 | 3 | 2016/06/18 | 8 months ago | VAT number validation & EU VAT rates. |
| [sleet](https://github.com/BoltApp/sleet) | 68 | 43 | 2019/11/13 | 2 days ago | One unified interface for multiple Payment Service Providers (PsP) to process online payment. |
| [go-finnhub](https://github.com/m1/go-finnhub) | 61 | 6 | 2020/01/13 | 1 year ago | Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges. |
| [currency](https://github.com/bnkamalesh/currency) | 43 | 6 | 2017/05/09 | 1 year ago | High performant & accurate currency computation package. |
| [fastme](https://github.com/newity/fastme) | 24 | 4 | 2020/10/29 | 1 week ago | Fast extensible matching engine Go implementation. |
| [go-finance](https://github.com/pieterclaerhout/go-finance) | 5 | 1 | 2019/09/30 | 1 year ago | Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers. |

## Forms
        
*Libraries for working with forms.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [nosurf](https://github.com/justinas/nosurf) | 1217 | 34 | 2013/08/22 | 11 months ago | CSRF protection middleware for Go. |
| [binding](https://github.com/mholt/binding) | 785 | 32 | 2014/05/20 | 3 years ago | Binds form and JSON data from net/http Request to struct. |
| [csrf](https://github.com/gorilla/csrf) | 702 | 23 | 2015/08/03 | 2 months ago | CSRF protection for Go web applications & services. |
| [form](https://github.com/go-playground/form) | 494 | 13 | 2016/05/26 | 2 months ago | Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. |
| [conform](https://github.com/leebenson/conform) | 239 | 5 | 2016/01/05 | 3 days ago | Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags. |
| [formam](https://github.com/monoculum/formam) | 164 | 5 | 2014/10/25 | 16 hours ago | decode form's values into a struct. |
| [forms](https://github.com/albrow/forms) | 123 | 7 | 2014/08/07 | 4 years ago | Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. |
| [qs](https://github.com/sonh/qs) | 59 | 3 | 2020/10/02 | 3 months ago | Go module for encoding structs into URL query parameters. |
| [bind](https://github.com/robfig/bind) | 26 | 3 | 2014/08/06 | 7 years ago | Bind form data to any Go values. |
| [queryparam](https://github.com/TomWright/queryparam) | 10 | 2 | 2018/06/14 | 1 year ago | Decode `url.Values` into usable struct values of standard or custom types. |

## Functional
        
*Packages to support functional programming in Go.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-underscore](https://github.com/tobyhede/go-underscore) | 1213 | 30 | 2014/07/02 | 2 years ago | Useful collection of helpfully functional Go collection utilities. |
| [fpGo](https://github.com/TeaEntityLab/fpGo) | 196 | 6 | 2018/05/24 | 1 month ago | Monad, Functional Programming features for Golang. |
| [fuego](https://github.com/seborama/fuego) | 98 | 3 | 2018/11/05 | 10 months ago | Functional Experiment in Go. |

## Game Development
        
*Awesome game development libraries.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [ebiten](https://github.com/hajimehoshi/ebiten) | 5113 | 117 | 2013/06/16 | 1 day ago | dead simple 2D game library in Go. |
| [leaf](https://github.com/name5566/leaf) | 4152 | 320 | 2014/08/04 | 2 months ago | Lightweight game server framework. |
| [pixel](https://github.com/faiface/pixel) | 3655 | 99 | 2016/11/19 | 1 day ago | Hand-crafted 2D game library in Go. |
| [goworld](https://github.com/xiaonanln/goworld) | 1952 | 130 | 2017/06/03 | 3 months ago | Scalable game server engine, featuring space-entity framework and hot-swapping. |
| [nano](https://github.com/lonng/nano) | 1823 | 65 | 2017/08/02 | 3 months ago | Lightweight, facility, high performance golang based game server framework. |
| [engine](https://github.com/g3n/engine) | 1648 | 77 | 2017/03/07 | 6 days ago | Go 3D Game Engine. |
| [go-sdl2](https://github.com/veandco/go-sdl2) | 1630 | 45 | 2013/06/05 | 2 weeks ago | Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/). |
| [engo](https://github.com/EngoEngine/engo) | 1430 | 48 | 2014/11/12 | 4 days ago | Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm. |
| [termloop](https://github.com/JoelOtter/termloop) | 1239 | 30 | 2015/05/23 | 1 month ago | Terminal-based game engine for Go, built on top of Termbox. |
| [pitaya](https://github.com/topfreegames/pitaya) | 1182 | 69 | 2018/03/19 | 1 week ago | Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. |
| [gonet](https://github.com/xtaci/gonet) | 1150 | 136 | 2013/04/11 | 4 years ago | Game server skeleton implemented with golang. |
| [oak](https://github.com/oakmound/oak) | 941 | 43 | 2017/07/15 | 19 hours ago | Pure Go game engine. |
| [raylib-go](https://github.com/gen2brain/raylib-go) | 658 | 18 | 2017/01/27 | 3 weeks ago | Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming. |
| [engine](https://github.com/azul3d/engine) | 499 | 24 | 2016/02/29 | 1 year ago | 3D game engine written in Go. |
| [go-astar](https://github.com/beefsack/go-astar) | 450 | 10 | 2014/05/28 | 1 year ago | Go implementation of the A\* path finding algorithm. |
| [GarageEngine](https://github.com/vova616/GarageEngine) | 320 | 31 | 2012/08/07 | 2 years ago | 2d game engine written in Go working on OpenGL. |
| [go3d](https://github.com/ungerik/go3d) | 208 | 10 | 2011/06/27 | 5 days ago | Performance oriented 2D/3D math package for Go. |
| [glop](https://github.com/runningwild/glop) | 77 | 3 | 2011/04/20 | 6 years ago | Glop (Game Library Of Power) is a fairly simple cross-platform game library. |
| [prototype](https://github.com/gonutz/prototype) | 62 | 3 | 2015/03/04 | 1 month ago | Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API. |
| [tile](https://github.com/kelindar/tile) | 37 | 1 | 2020/08/19 | 2 months ago | Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export. |
| [go-collada](https://github.com/GlenKelley/go-collada) | 15 | 3 | 2013/09/19 | 8 years ago | Go package for working with the Collada file format. |

## Generation and Generics
        
*Tools to enhance the language with features like generics via code generation.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-linq](https://github.com/ahmetb/go-linq) | 2695 | 76 | 2013/12/19 | 5 months ago | .NET LINQ-like query methods for Go. |
| [jennifer](https://github.com/dave/jennifer) | 2178 | 31 | 2016/12/04 | 8 months ago | Generate arbitrary Go code without templates. |
| [gen](https://github.com/clipperhouse/gen) | 1318 | 33 | 2013/10/13 | 1 year ago | Code generation tool for ‘generics’-like functionality. |
| [goderive](https://github.com/awalterschulze/goderive) | 930 | 21 | 2017/02/10 | 2 months ago | Derives functions from input types. |
| [gowrap](https://github.com/hexdigest/gowrap) | 534 | 11 | 2018/09/15 | 2 months ago | Generate decorators for Go interfaces using simple templates. |
| [interfaces](https://github.com/rjeczalik/interfaces) | 307 | 7 | 2015/12/06 | 5 months ago | Command line tool for generating interface definitions. |
| [go-enum](https://github.com/abice/go-enum) | 239 | 3 | 2017/08/10 | 3 days ago | Code generation for enums from code comments. |
| [pkgreflect](https://github.com/ungerik/pkgreflect) | 99 | 6 | 2012/09/03 | 4 years ago | Go preprocessor for package scoped reflection. |
| [efaceconv](https://github.com/t0pep0/efaceconv) | 49 | 4 | 2016/11/18 | 4 years ago | Code generation tool for high performance conversion from interface{} to immutable type without allocations. |
| [gotype](https://github.com/wzshiming/gotype) | 36 | 4 | 2017/12/05 | 2 months ago | Golang source code parsing, usage like reflect package. |
| [GENERIS](https://github.com/senselogic/GENERIS) | 29 | 1 | 2019/03/10 | 1 month ago | Code generation tool providing generics, free-form macros, conditional compilation and HTML templating. |
| [go-xray](https://github.com/pieterclaerhout/go-xray) | 19 | 3 | 2019/10/01 | 1 year ago | Helpers for making the use of reflection easier. |
| [typeregistry](https://github.com/xiaoxin01/typeregistry) | 11 | 1 | 2020/01/14 | 1 year ago | A library to create type dynamically. |

## Geographic
        
*Geographic tools and servers*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [tile38](https://github.com/tidwall/tile38) | 7713 | 204 | 2016/03/04 | 1 day ago | Geolocation DB with spatial index and realtime geofencing. |
| [geo](https://github.com/golang/geo) | 1279 | 77 | 2014/12/03 | 1 week ago | S2 geometry library in Go. |
| [mbtileserver](https://github.com/consbio/mbtileserver) | 281 | 15 | 2014/11/01 | 1 month ago | A simple Go-based server for map tiles stored in mbtiles format. |
| [osm](https://github.com/paulmach/osm) | 176 | 12 | 2016/02/02 | 3 weeks ago | Library for reading, writing and working with OpenStreetMap data and APIs. |
| [geocache](https://github.com/melihmucuk/geocache) | 133 | 6 | 2016/06/21 | 5 years ago | In-memory cache that is suitable for geolocation based applications. |
| [wgs84](https://github.com/wroge/wgs84) | 65 | 1 | 2019/06/08 | 10 months ago | Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM). |
| [geoserver](https://github.com/hishamkaram/geoserver) | 58 | 2 | 2018/03/26 | 2 months ago | geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API. |
| [gismanager](https://github.com/hishamkaram/gismanager) | 38 | 0 | 2018/09/29 | 2 years ago | Publish Your GIS Data(Vector Data) to PostGIS and Geoserver. |
| [pbf](https://github.com/maguro/pbf) | 26 | 3 | 2017/09/18 | 5 months ago | OpenStreetMap PBF golang encoder/decoder. |
| [s2-geojson](https://github.com/pantrif/s2-geojson) | 13 | 1 | 2020/03/27 | 1 year ago | Convert geojson to s2 cells & demonstrating some S2 geometry features on map. |

## Go Compilers
        
*Tools for compiling Go to other languages.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gopherjs](https://github.com/gopherjs/gopherjs) | 10538 | 258 | 2013/08/27 | 1 day ago | Compiler from Go to JavaScript. |
| [llgo](https://github.com/go-llvm/llgo) | 1095 | 63 | 2011/11/05 | 6 years ago | LLVM-based compiler for Go. |
| [tardisgo](https://github.com/tardisgo/tardisgo) | 411 | 30 | 2014/01/08 | 4 years ago | Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler. |
| [c4go](https://github.com/Konstantin8105/c4go) | 281 | 18 | 2018/03/28 | 5 months ago | Transpile C code to Go code. |
| [f4go](https://github.com/Konstantin8105/f4go) | 26 | 4 | 2018/07/08 | 8 months ago | Transpile FORTRAN 77 code to Go code. |

## Goroutines
        
*Tools for managing and working with Goroutines.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [ants](https://github.com/panjf2000/ants) | 6549 | 153 | 2018/05/19 | 6 days ago | A high-performance and low-cost goroutine pool in Go. |
| [tunny](https://github.com/Jeffail/tunny) | 2625 | 74 | 2014/04/02 | 2 months ago | Goroutine pool for golang. |
| [goworker](https://github.com/benmanns/goworker) | 2608 | 74 | 2013/07/22 | 3 months ago | goworker is a Go-based background worker. |
| [grpool](https://github.com/ivpusic/grpool) | 656 | 29 | 2015/07/22 | 2 years ago | Lightweight Goroutine pool. |
| [pool](https://github.com/go-playground/pool) | 639 | 14 | 2015/10/28 | 3 months ago | Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation. |
| [workerpool](https://github.com/gammazero/workerpool) | 639 | 16 | 2016/05/17 | 3 days ago | Goroutine pool that limits the concurrency of task execution, not the number of tasks queued. |
| [gowp](https://github.com/xxjwxc/gowp) | 327 | 17 | 2019/09/14 | 4 months ago | gowp is concurrency limiting goroutine pool. |
| [pond](https://github.com/alitto/pond) | 294 | 8 | 2020/03/21 | 2 months ago | Minimalistic and High-performance goroutine worker pool written in Go. |
| [go-floc](https://github.com/workanator/go-floc) | 209 | 7 | 2017/07/03 | 1 month ago | Orchestrate goroutines with ease. |
| [go-flow](https://github.com/kamildrazkiewicz/go-flow) | 174 | 10 | 2016/09/25 | 2 years ago | Control goroutines execution order. |
| [semaphore](https://github.com/marusama/semaphore) | 124 | 2 | 2017/11/22 | 6 months ago | Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations). |
| [go-workers](https://github.com/catmullet/go-workers) | 123 | 4 | 2020/10/06 | 1 week ago | Easily and safely run workers for large data processing pipelines. |
| [artifex](https://github.com/mborders/artifex) | 116 | 7 | 2018/10/31 | 1 year ago | Simple in-memory job queue for Golang using worker-based dispatching. |
| [GoSlaves](https://github.com/dgrr/GoSlaves) | 95 | 4 | 2017/09/17 | 2 years ago | Simple and Asynchronous Goroutine pool library. |
| [errgroup](https://github.com/neilotoole/errgroup) | 94 | 2 | 2020/06/26 | 2 weeks ago | Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines. |
| [async](https://github.com/StudioSol/async) | 92 | 13 | 2017/06/30 | 10 months ago | A safe way to execute functions asynchronously, recovering them in case of panic. |
| [semaphore](https://github.com/kamilsk/semaphore) | 88 | 1 | 2016/10/08 | 1 year ago | Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context. |
| [gpool](https://github.com/sherifabdlnaby/gpool) | 81 | 1 | 2018/12/03 | 1 year ago | manages a resizeable pool of context-aware goroutines to bound concurrency. |
| [worker-pool](https://github.com/vardius/worker-pool) | 81 | 5 | 2017/10/04 | 8 months ago | goworker is a Go simple async worker pool. |
| [cyclicbarrier](https://github.com/marusama/cyclicbarrier) | 77 | 2 | 2018/01/11 | 1 year ago | CyclicBarrier for golang. |
| [gollback](https://github.com/vardius/gollback) | 65 | 1 | 2019/05/11 | 1 year ago | asynchronous simple function utilities, for managing execution of closures and callbacks. |
| [threadpool](https://github.com/shettyh/threadpool) | 61 | 2 | 2017/09/06 | 1 year ago | Golang threadpool implementation. |
| [Hunch](https://github.com/AaronJan/Hunch) | 58 | 1 | 2019/06/05 | 11 months ago | Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive. |
| [routine](https://github.com/x-mod/routine) | 44 | 3 | 2019/03/04 | 1 year ago | go routine control with context, support: Main, Go, Pool and some useful Executors. |
| [nursery](https://github.com/arunsworld/nursery) | 35 | 4 | 2019/11/23 | 2 months ago | Structured concurrency in Go. |
| [kyoo](https://github.com/dirkaholic/kyoo) | 34 | 2 | 2020/01/06 | 1 year ago | Provides an unlimited job queue and concurrent worker pools. |
| [parallel-fn](https://github.com/rafaeljesus/parallel-fn) | 31 | 3 | 2017/06/18 | 3 years ago | Run functions in parallel. |
| [goccm](https://github.com/zenthangplus/goccm) | 25 | 1 | 2019/08/16 | 2 months ago | Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently. |
| [async](https://github.com/reugn/async) | 24 | 2 | 2019/12/28 | 1 year ago | An alternative sync library for Go (Future, Promise, Locks). |
| [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) | 22 | 1 | 2018/08/08 | 1 year ago | Like `sync.WaitGroup` with error handling and concurrency control. |
| [go-trylock](https://github.com/subchen/go-trylock) | 21 | 1 | 2018/04/26 | 4 months ago | TryLock support on read-write lock for Golang. |
| [stl](https://github.com/ssgreg/stl) | 19 | 1 | 2018/06/19 | 1 year ago | Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism. |
| [channelify](https://github.com/ddelizia/channelify) | 14 | 1 | 2020/10/05 | 7 months ago | Transform your function to return channels for easy and powerful parallel processing. |
| [gohive](https://github.com/loveleshsharma/gohive) | 13 | 3 | 2019/05/31 | 2 years ago | A highly performant and easy to use Goroutine pool for Go. |
| [conexec](https://github.com/ITcathyh/conexec) | 11 | 2 | 2019/12/24 | 1 year ago | A concurrent toolkit to help execute funcs concurrently in an efficient and safe way. It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency. |
| [queue](https://github.com/AnikHasibul/queue) | 9 | 0 | 2018/12/21 | 2 years ago | Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more. |
| [hands](https://github.com/duanckham/hands) | 7 | 1 | 2020/04/04 | 1 year ago | A process controller used to control the execution and return strategies of multiple goroutines. |
| [go-tools](https://github.com/nikhilsaraf/go-tools) | 5 | 2 | 2018/11/14 | 2 years ago | Manage a pool of goroutines using this lightweight library with a simple API. |
| [concurrency-limiter](https://github.com/vivek-ng/concurrency-limiter) | 4 | 1 | 2020/11/22 | 10 months ago | Concurrency limiter with support for timeouts , dynamic priority and context cancellation of goroutines. |
| [breaker](https://github.com/kamilsk/breaker) | 0 | 0 | 2019/02/15 | 2 months ago | Flexible mechanism to make execution flow interruptible. |

## GUI
        
*Interaction*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fyne](https://github.com/fyne-io/fyne) | 14242 | 229 | 2018/02/04 | 1 day ago | Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android. |
| [webview](https://github.com/webview/webview) | 8928 | 225 | 2017/08/19 | 5 days ago | Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). |
| [qt](https://github.com/therecipe/qt) | 8794 | 318 | 2014/11/19 | 8 months ago | Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi). |
| [ui](https://github.com/andlabs/ui) | 7984 | 372 | 2014/02/17 | 2 months ago | Platform-native GUI library for Go. Cross platform. |
| [robotgo](https://github.com/go-vgo/robotgo) | 6920 | 232 | 2016/09/26 | 5 days ago | Go Native cross-platform GUI system automation. Control the mouse, keyboard and other. |
| [webview](https://github.com/zserge/webview) | 6166 | 211 | 2017/08/19 | 1 year ago | Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). |
| [walk](https://github.com/lxn/walk) | 5677 | 265 | 2010/09/16 | 2 months ago | Windows application library kit for Go. |
| [go-app](https://github.com/maxence-charriere/go-app) | 5358 | 146 | 2016/10/12 | 1 hour ago | Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. |
| [go-astilectron](https://github.com/asticode/go-astilectron) | 4034 | 137 | 2017/04/22 | 3 weeks ago | Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron). |
| [app](https://github.com/maxence-charriere/app) | 3314 | 111 | 2016/10/12 | 1 year ago | Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. |
| [go-sciter](https://github.com/sciter-sdk/go-sciter) | 2221 | 127 | 2015/10/15 | 5 months ago | Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform. |
| [systray](https://github.com/getlantern/systray) | 1964 | 62 | 2014/11/12 | 5 months ago | Cross platform Go library to place an icon and menu in the notification area. |
| [gotk3](https://github.com/gotk3/gotk3) | 1591 | 63 | 2015/08/13 | 3 weeks ago | Go bindings for GTK3. |
| [gosx-notifier](https://github.com/deckarep/gosx-notifier) | 546 | 16 | 2013/11/25 | 1 year ago | OSX Desktop Notifications library for Go. |
| [gowd](https://github.com/dtylman/gowd) | 325 | 27 | 2017/03/29 | 2 years ago | Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform. |
| [trayhost](https://github.com/shurcooL/trayhost) | 218 | 7 | 2014/04/25 | 1 year ago | Cross-platform Go library to place an icon in the host operating system's taskbar. |
| [go-appindicator](https://github.com/dawidd6/go-appindicator) | 17 | 5 | 2019/05/04 | 9 months ago | Go bindings for libappindicator3 C library. |
| [activity-tracker](https://github.com/prashantgupta24/activity-tracker) | 12 | 2 | 2019/03/12 | 2 years ago | OSX library to notify about any (pluggable) activity on your machine. |
| [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) | 10 | 3 | 2019/03/30 | 2 years ago | OSX Sleep/Wake notifications in golang. |

## Hardware
        
*Libraries, tools, and tutorials for interacting with hardware.*

## Images
        
*Libraries for manipulating images.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gocv](https://github.com/hybridgroup/gocv) | 4369 | 140 | 2017/09/18 | 1 week ago | Go package for computer vision using OpenCV 3.3+. |
| [imaging](https://github.com/disintegration/imaging) | 3937 | 77 | 2012/12/06 | 9 months ago | Simple Go image processing package. |
| [imaginary](https://github.com/h2non/imaginary) | 3854 | 77 | 2015/03/04 | 4 weeks ago | Fast and simple HTTP microservice for image resizing. |
| [bild](https://github.com/anthonynsimon/bild) | 3365 | 71 | 2016/08/01 | 7 months ago | Collection of image processing algorithms in pure Go. |
| [gg](https://github.com/fogleman/gg) | 3031 | 90 | 2016/02/18 | 5 days ago | 2D rendering in pure Go. |
| [ln](https://github.com/fogleman/ln) | 2965 | 92 | 2016/01/10 | 2 years ago | 3D line art rendering in Go. |
| [resize](https://github.com/nfnt/resize) | 2731 | 81 | 2012/08/02 | 10 months ago | Image resizing for Go with common interpolation methods. |
| [pt](https://github.com/fogleman/pt) | 1965 | 59 | 2015/01/23 | 2 years ago | Path tracing engine written in Go. |
| [svgo](https://github.com/ajstarks/svgo) | 1732 | 50 | 2010/03/05 | 6 days ago | Go Language Library for SVG generation. |
| [bimg](https://github.com/h2non/bimg) | 1640 | 37 | 2015/03/17 | 1 month ago | Small package for fast and efficient image processing using libvips. |
| [smartcrop](https://github.com/muesli/smartcrop) | 1546 | 33 | 2014/04/07 | 4 months ago | Finds good crops for arbitrary images and crop sizes. |
| [picfit](https://github.com/thoas/picfit) | 1545 | 54 | 2014/12/06 | 2 weeks ago | An image resizing server written in Go. |
| [gift](https://github.com/disintegration/gift) | 1466 | 51 | 2014/07/12 | 10 months ago | Package of image processing filters. |
| [imagick](https://github.com/gographics/imagick) | 1361 | 54 | 2013/04/30 | 3 weeks ago | Go binding to ImageMagick's MagickWand C API. |
| [go-opencv](https://github.com/go-opencv/go-opencv) | 1251 | 63 | 2013/12/09 | 2 years ago | Go bindings for OpenCV. |
| [geopattern](https://github.com/pravj/geopattern) | 1136 | 22 | 2014/10/22 | 2 years ago | Create beautiful generative image patterns from a string. |
| [stegify](https://github.com/DimitarPetrov/stegify) | 949 | 21 | 2018/11/29 | 1 year ago | Go tool for LSB steganography, capable of hiding any file within an image. |
| [canvas](https://github.com/tdewolff/canvas) | 810 | 18 | 2017/05/20 | 5 days ago | Vector graphics to PDF, SVG or rasterized image. |
| [image2ascii](https://github.com/qeesung/image2ascii) | 578 | 8 | 2018/10/20 | 2 months ago | Convert image to ASCII. |
| [govips](https://github.com/davidbyttow/govips) | 517 | 13 | 2016/12/25 | 4 weeks ago | A lightning fast image processing and resizing library for Go. |
| [draft](https://github.com/lucasepe/draft) | 510 | 12 | 2020/06/05 | 3 weeks ago | Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax. |
| [govatar](https://github.com/o1egl/govatar) | 458 | 10 | 2016/01/18 | 6 months ago | Library and CMD tool for generating funny avatars. |
| [mort](https://github.com/aldor007/mort) | 436 | 18 | 2017/11/19 | 1 month ago | Storage and image processing server written in Go. |
| [goimagehash](https://github.com/corona10/goimagehash) | 432 | 11 | 2017/07/28 | 7 months ago | Go Perceptual image hashing package. |
| [go-nude](https://github.com/koyachi/go-nude) | 335 | 16 | 2014/05/02 | 2 years ago | Nudity detection with Go. |
| [rez](https://github.com/bamiaux/rez) | 202 | 9 | 2014/01/16 | 4 years ago | Image resizing in pure Go and SIMD. |
| [darkroom](https://github.com/gojek/darkroom) | 170 | 9 | 2019/07/01 | 3 months ago | An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency. |
| [mergi](https://github.com/noelyahan/mergi) | 153 | 7 | 2018/09/24 | 1 year ago | Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate). |
| [img](https://github.com/hawx/img) | 137 | 5 | 2012/07/28 | 6 years ago | Selection of image manipulation tools. |
| [gltf](https://github.com/qmuntal/gltf) | 120 | 4 | 2019/01/15 | 5 months ago | Efficient and robust glTF 2.0 reader, writer and validator. |
| [go-cairo](https://github.com/ungerik/go-cairo) | 115 | 5 | 2012/08/22 | 6 months ago | Go binding for the cairo graphics library. |
| [steganography](https://github.com/auyer/steganography) | 114 | 6 | 2018/05/21 | 2 months ago | Pure Go Library for LSB steganography. |
| [cameron](https://github.com/aofei/cameron) | 70 | 4 | 2018/05/05 | 7 months ago | An avatar generator for Go. |
| [go-gd](https://github.com/bolknote/go-gd) | 53 | 4 | 2011/05/12 | 3 years ago | Go binding for GD library. |
| [gridder](https://github.com/shomali11/gridder) | 46 | 4 | 2020/04/10 | 2 days ago | A Grid based 2D Graphics library. |
| [goimghdr](https://github.com/corona10/goimghdr) | 36 | 1 | 2018/02/25 | 2 years ago | The imghdr module determines the type of image contained in a file for Go. |
| [tga](https://github.com/ftrvxmtrx/tga) | 28 | 3 | 2012/10/08 | 6 years ago | Package tga is a TARGA image format decoder/encoder. |
| [webp-server](https://github.com/mehdipourfar/webp-server) | 27 | 1 | 2020/11/22 | 8 months ago | Simple and minimal image server capable of storing, resizing, converting and caching images. |
| [go-webcolors](https://github.com/jyotiska/go-webcolors) | 25 | 2 | 2014/04/24 | 6 years ago | Port of webcolors library from Python to Go. |
| [mpo](https://github.com/donatj/mpo) | 7 | 2 | 2015/04/14 | 1 year ago | Decoder and conversion tool for MPO 3D Photos. |

## IoT
        
*Libraries for programming devices of the IoT.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [flogo](https://github.com/TIBCOSoftware/flogo) | 1848 | 156 | 2016/07/10 | 10 months ago | Project Flogo is an Open Source Framework for IoT Edge Apps & Integration. |
| [mainflux](https://github.com/mainflux/mainflux) | 1558 | 103 | 2015/07/06 | 49 minutes ago | Industrial IoT Messaging and Device Management Server. |
| [gatt](https://github.com/paypal/gatt) | 988 | 55 | 2014/04/23 | 1 year ago | Gatt is a Go package for building Bluetooth Low Energy peripherals. |
| [heedy](https://github.com/heedy/heedy) | 288 | 24 | 2015/01/16 | 6 days ago | Open-Source Platform for Quantified Self & IoT. |
| [devices](https://github.com/goiot/devices) | 244 | 15 | 2016/05/30 | 5 years ago | Suite of libraries for IoT devices, experimental for x/exp/io. |
| [sensorbee](https://github.com/sensorbee/sensorbee) | 207 | 19 | 2016/02/19 | 1 year ago | Lightweight stream processing engine for IoT. |
| [huego](https://github.com/amimof/huego) | 188 | 4 | 2017/05/16 | 1 month ago | An extensive Philips Hue client library for Go. |
| [eywa](https://github.com/xcodersun/eywa) | 50 | 8 | 2016/02/20 | 4 years ago | Project Eywa is essentially a connection manager that keeps track of connected devices. |

## Job Scheduler
        
*Libraries for scheduling jobs.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gocron](https://github.com/go-co-op/gocron) | 1200 | 16 | 2020/03/20 | 2 weeks ago | Easy and fluent Go job scheduling. This is an actively maintained fork of [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron). |
| [jobrunner](https://github.com/bamzi/jobrunner) | 882 | 27 | 2015/10/21 | 10 months ago | Smart and featureful cron job scheduler with job queuing and live monitoring built in. |
| [gron](https://github.com/roylee0704/gron) | 877 | 16 | 2016/06/04 | 8 months ago | Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly. |
| [go-quartz](https://github.com/reugn/go-quartz) | 514 | 13 | 2019/04/14 | 3 days ago | Simple, zero-dependency scheduling library for Go. |
| [jobs](https://github.com/albrow/jobs) | 483 | 19 | 2015/02/09 | 3 years ago | Persistent and flexible background jobs library. |
| [scheduler](https://github.com/carlescere/scheduler) | 372 | 15 | 2015/02/03 | 9 months ago | Cronjobs scheduling made easy. |
| [go-cron](https://github.com/rk/go-cron) | 207 | 9 | 2011/04/15 | 1 year ago | Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. |
| [leprechaun](https://github.com/kilgaloon/leprechaun) | 84 | 8 | 2018/04/08 | 9 months ago | Job scheduler that supports webhooks, crons and classic scheduling. |
| [clockwork](https://github.com/whiteShtef/clockwork) | 29 | 1 | 2018/04/23 | 1 year ago | Simple and intuitive job scheduling library in Go. |
| [cronticker](https://github.com/krayzpipes/cronticker) | 1 | 1 | 2020/11/28 | 9 months ago | A ticker implementation to support cron schedules. |

## JSON
        
*Libraries for working with JSON.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gjson](https://github.com/tidwall/gjson) | 9062 | 153 | 2016/08/11 | 1 week ago | Get a JSON value with one line of code. |
| [gojson](https://github.com/ChimeraCoder/gojson) | 2418 | 46 | 2012/12/27 | 2 months ago | Automatically generate Go (golang) struct definitions from example JSON. |
| [fastjson](https://github.com/valyala/fastjson) | 1326 | 26 | 2018/05/28 | 2 months ago | Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection. |
| [kazaam](https://github.com/qntfy/kazaam) | 207 | 22 | 2016/07/19 | 2 months ago | API for arbitrary transformation of JSON documents. |
| [gojq](https://github.com/elgs/gojq) | 177 | 5 | 2015/12/30 | 10 months ago | JSON query in Golang. |
| [jsondiff](https://github.com/wI2L/jsondiff) | 128 | 2 | 2020/11/28 | 1 month ago | JSON diff library for Go based on RFC6902 (JSON Patch). |
| [jettison](https://github.com/wI2L/jettison) | 112 | 6 | 2019/08/30 | 1 month ago | Fast and flexible JSON encoder for Go. |
| [gjo](https://github.com/skanehira/gjo) | 99 | 8 | 2019/02/23 | 5 months ago | Small utility to create JSON objects. |
| [jsongo](https://github.com/ricardolonga/jsongo) | 97 | 1 | 2015/08/07 | 4 years ago | Fluent API to make it easier to create Json objects. |
| [json2go](https://github.com/m-zajac/json2go) | 92 | 3 | 2017/06/10 | 5 months ago | Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all. |
| [jaydiff](https://github.com/yazgazan/jaydiff) | 84 | 2 | 2017/04/24 | 8 months ago | JSON diff utility written in Go. |
| [ajson](https://github.com/spyzhov/ajson) | 75 | 2 | 2019/03/07 | 1 year ago | Abstract JSON for golang with JSONPath support. |
| [jsonf](https://github.com/miolini/jsonf) | 62 | 3 | 2015/05/25 | 9 months ago | Console tool for highlighted formatting and struct query fetching JSON. |
| [mp](https://github.com/sanbornm/mp) | 44 | 2 | 2014/06/15 | 5 years ago | Simple cli email parser. It currently takes stdin and outputs JSON. |
| [go-respond](https://github.com/nicklaw5/go-respond) | 41 | 1 | 2017/03/12 | 1 week ago | Go package for handling common HTTP JSON responses. |
| [go-jsonerror](https://github.com/ddymko/go-jsonerror) | 10 | 2 | 2018/10/18 | 2 years ago | Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec. |
| [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) | 10 | 2 | 2016/07/08 | 4 years ago | Go bindings based on the JSON API errors reference. |
| [jsonhal](https://github.com/RichardKnop/jsonhal) | 9 | 2 | 2016/01/15 | 1 year ago | Simple Go package to make custom structs marshal into HAL compatible JSON responses. |
| [mapslice-json](https://github.com/ake-persson/mapslice-json) | 8 | 1 | 2020/02/19 | 2 months ago | Go MapSlice for ordered marshal/ unmarshal of maps in JSON. |
| [ej](https://github.com/lucassscaravelli/ej) | 7 | 2 | 2020/01/04 | 1 year ago | Write and read JSON from different sources succinctly. |
| [dynjson](https://github.com/cocoonspace/dynjson) | 7 | 2 | 2020/05/06 | 6 months ago | Client-customizable JSON formats for dynamic APIs. |
| [epoch](https://github.com/vtopc/epoch) | 6 | 1 | 2019/12/15 | 6 months ago | Contains primitives for marshaling/unmarshaling Unix timestamp/epoch to/from build-in time.Time type in JSON. |
| [mapslice-json](https://github.com/mickep76/mapslice-json) | 5 | 1 | 2020/02/19 | 1 year ago | Go MapSlice for ordered marshal/ unmarshal of maps in JSON. |
| [jzon](https://github.com/zerosnake0/jzon) | 5 | 1 | 2019/11/12 | 6 months ago | JSON library with standard compatible API/behavior. |
| [jsonic](https://github.com/sinhashubham95/jsonic) | 4 | 1 | 2021/01/09 | 8 months ago | Utilities to handle and query JSON without defining structs in a type safe manner. |

## Logging
        
*Libraries for generating and working with log files.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [logrus](https://github.com/sirupsen/logrus) | 18818 | 310 | 2013/10/16 | 2 weeks ago | Structured logger for Go. |
| [zap](https://github.com/uber-go/zap) | 13751 | 250 | 2016/02/18 | 11 hours ago | Fast, structured, leveled logging in Go. |
| [zerolog](https://github.com/rs/zerolog) | 5330 | 55 | 2017/05/12 | 2 days ago | Zero-allocation JSON logger. |
| [go-spew](https://github.com/davecgh/go-spew) | 4605 | 62 | 2013/01/09 | 10 months ago | Implements a deep pretty printer for Go data structures to aid in debugging. |
| [glog](https://github.com/golang/glog) | 3024 | 88 | 2013/07/16 | 1 month ago | Leveled execution logs for Go. |
| [lumberjack](https://github.com/natefinch/lumberjack) | 2808 | 55 | 2014/06/14 | 1 month ago | Simple rolling logger, implements io.WriteCloser. |
| [tail](https://github.com/hpcloud/tail) | 2185 | 100 | 2013/02/05 | 2 months ago | Go package striving to emulate the features of the BSD tail program. |
| [seelog](https://github.com/cihub/seelog) | 1561 | 91 | 2011/11/17 | 2 years ago | Logging functionality with flexible dispatching, filtering, and formatting. |
| [log](https://github.com/apex/log) | 1174 | 35 | 2015/12/21 | 1 month ago | Structured logging package for Go. |
| [log15](https://github.com/inconshreveable/log15) | 1019 | 26 | 2014/05/20 | 1 week ago | Simple, powerful logging for Go. |
| [onelog](https://github.com/francoispqt/onelog) | 398 | 10 | 2018/05/06 | 2 years ago | Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation. |
| [log](https://github.com/phuslu/log) | 397 | 16 | 2019/07/07 | 5 days ago | Structured Logging Made Easy. |
| [logxi](https://github.com/mgutz/logxi) | 346 | 10 | 2015/03/01 | 1 year ago | 12-factor app logger that is fast and makes you happy. |
| [logutils](https://github.com/hashicorp/logutils) | 295 | 247 | 2013/10/09 | 1 year ago | Utilities for slightly better logging in Go (Golang) extending the standard logger. |
| [log](https://github.com/go-playground/log) | 275 | 11 | 2016/02/07 | 1 year ago | Simple, configurable and scalable Structured Logging for Go. |
| [go-logger](https://github.com/apsdehal/go-logger) | 269 | 7 | 2014/09/26 | 2 years ago | Simple logger of Go Programs, with level handlers. |
| [httpretty](https://github.com/henvic/httpretty) | 239 | 5 | 2020/01/24 | 9 months ago | Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest). |
| [sqldb-logger](https://github.com/simukti/sqldb-logger) | 193 | 2 | 2019/11/02 | 4 months ago | A logger for Go SQL database driver without modify existing *sql.DB stdlib usage. |
| [rollingwriter](https://github.com/arthurkiller/rollingwriter) | 179 | 8 | 2017/02/12 | 1 month ago | RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation. |
| [logger](https://github.com/azer/logger) | 147 | 6 | 2014/09/30 | 10 months ago | Minimalistic logging library for Go. |
| [logur](https://github.com/logur/logur) | 139 | 6 | 2018/12/09 | 1 year ago | An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries ([logrus](https://github.com/sirupsen/logrus), [go-kit log](https://github.com/go-kit/kit/tree/master/log), [zap](https://github.com/uber-go/zap), [zerolog](https://github.com/rs/zerolog), etc). |
| [xlog](https://github.com/rs/xlog) | 136 | 8 | 2015/10/22 | 7 months ago | Structured logger for `net/context` aware HTTP handlers with flexible dispatching. |
| [glg](https://github.com/kpango/glg) | 126 | 5 | 2017/06/21 | 2 months ago | glg is simple and fast leveled logging library for Go. |
| [ozzo-log](https://github.com/go-ozzo/ozzo-log) | 113 | 12 | 2015/10/22 | 8 months ago | High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail). |
| [logvoyage](https://github.com/firstrow/logvoyage) | 89 | 5 | 2015/03/29 | 4 years ago | Full-featured logging saas written in golang. |
| [go-cronowriter](https://github.com/utahta/go-cronowriter) | 45 | 1 | 2017/02/04 | 6 months ago | Simple writer that rotate log files automatically based on current date and time, like cronolog. |
| [log](https://github.com/alexcesaro/log) | 45 | 6 | 2014/04/19 | 6 years ago | Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. |
| [gologger](https://github.com/sadlil/gologger) | 39 | 6 | 2015/09/02 | 3 years ago | Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch. |
| [logex](https://github.com/chzyer/logex) | 38 | 9 | 2014/10/10 | 4 years ago | Golang log lib, supports tracking and level, wrap by standard log lib. |
| [go-log](https://github.com/ian-kent/go-log) | 37 | 2 | 2014/05/02 | 3 years ago | Log4j implementation in Go. |
| [go-log](https://github.com/siddontang/go-log) | 28 | 6 | 2014/05/18 | 2 years ago | Log lib supports level and multi handlers. |
| [journald](https://github.com/ssgreg/journald) | 27 | 2 | 2017/08/23 | 7 months ago | Go implementation of systemd Journal's native API for logging. |
| [logrusly](https://github.com/sebest/logrusly) | 27 | 4 | 2014/09/11 | 2 months ago | [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). |
| [distillog](https://github.com/amoghe/distillog) | 26 | 2 | 2015/10/12 | 3 years ago | distilled levelled logging (think of it as stdlib + log levels). |
| [log](https://github.com/teris-io/log) | 24 | 2 | 2017/10/28 | 3 years ago | Structured log interface for Go cleanly separates logging facade from its implementation. |
| [mlog](https://github.com/jbrodriguez/mlog) | 23 | 1 | 2014/10/20 | 3 years ago | Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. |
| [gomol](https://github.com/aphistic/gomol) | 17 | 2 | 2015/08/30 | 2 years ago | Multiple-output, structured logging for Go with extensible logging outputs. |
| [glo](https://github.com/lajosbencz/glo) | 14 | 1 | 2019/01/19 | 2 years ago | PHP Monolog inspired logging facility with identical severity levels. |
| [zkits-logger](https://github.com/edoger/zkits-logger) | 14 | 1 | 2020/03/31 | 2 months ago | A powerful zero-dependency JSON logger. |
| [logrusiowriter](https://github.com/cabify/logrusiowriter) | 12 | 92 | 2019/08/09 | 1 year ago | `io.Writer` implementation using [logrus](https://github.com/sirupsen/logrus) logger. |
| [go-log](https://github.com/subchen/go-log) | 11 | 2 | 2017/05/07 | 3 years ago | Simple and configurable Logging in Go, with level, formatters and writers. |
| [logmatic](https://github.com/mborders/logmatic) | 10 | 2 | 2018/11/07 | 8 months ago | Colorized logger for Golang with dynamic log level configuration. |
| [log](https://github.com/aerogo/log) | 9 | 2 | 2017/06/10 | 1 year ago | An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection). |
| [logdump](https://github.com/ewwwwwqm/logdump) | 9 | 2 | 2017/01/13 | 3 years ago | Package for multi-level logging. |
| [logmatic](https://github.com/borderstech/logmatic) | 9 | 2 | 2018/11/07 | 2 years ago | Colorized logger for Golang with dynamic log level configuration. |
| [logo](https://github.com/mbndr/logo) | 9 | 2 | 2017/02/07 | 9 months ago | Golang logger to different configurable writers. |
| [go-log](https://github.com/pieterclaerhout/go-log) | 8 | 2 | 2019/10/01 | 1 year ago | A logging library with strack traces, object dumping and optional timestamps. |
| [xlog](https://github.com/xfxdev/xlog) | 6 | 1 | 2016/05/05 | 2 years ago | Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format. |
| [kemba](https://github.com/clok/kemba) | 4 | 1 | 2020/07/13 | 2 months ago | A tiny debug logging tool inspired by [debug](https://github.com/visionmedia/debug), great for CLI tools and applications. |

## Machine Learning
        
*Libraries for Machine Learning.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [golearn](https://github.com/sjwhitworth/golearn) | 8033 | 431 | 2013/12/26 | 3 weeks ago | General Machine Learning library for Go. |
| [gorse](https://github.com/zhenghaoz/gorse) | 4556 | 44 | 2018/08/14 | 2 days ago | An offline recommender system backend based on collaborative filtering written in Go. |
| [gorgonia](https://github.com/gorgonia/gorgonia) | 4205 | 192 | 2016/09/14 | 4 days ago | graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms. |
| [tfgo](https://github.com/galeone/tfgo) | 1794 | 60 | 2017/05/23 | 2 weeks ago | Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python. |
| [gosseract](https://github.com/otiai10/gosseract) | 1575 | 47 | 2013/10/11 | 1 month ago | Go package for OCR (Optical Character Recognition), by using Tesseract C++ library. |
| [goml](https://github.com/cdipaolo/goml) | 1248 | 73 | 2015/06/27 | 2 months ago | On-line Machine Learning in Go. |
| [eaopt](https://github.com/MaxHalford/eaopt) | 747 | 28 | 2016/01/31 | 6 months ago | An evolutionary optimization library. |
| [bayesian](https://github.com/jbrukh/bayesian) | 714 | 35 | 2011/11/23 | 1 year ago | Naive Bayesian Classification for Golang. |
| [CloudForest](https://github.com/ryanbressler/CloudForest) | 691 | 43 | 2012/10/22 | 9 months ago | Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. |
| [gobrain](https://github.com/goml/gobrain) | 491 | 27 | 2014/04/29 | 9 months ago | Neural Networks written in go. |
| [ocrserver](https://github.com/otiai10/ocrserver) | 425 | 15 | 2015/11/15 | 1 month ago | A simple OCR API server, seriously easy to be deployed by Docker and Heroku. |
| [onnx-go](https://github.com/owulveryck/onnx-go) | 346 | 12 | 2018/08/28 | 4 months ago | Go Interface to Open Neural Network Exchange (ONNX). |
| [go-deep](https://github.com/patrikeh/go-deep) | 328 | 16 | 2017/12/09 | 6 months ago | A feature-rich neural network library in Go. |
| [regommend](https://github.com/muesli/regommend) | 294 | 16 | 2014/02/05 | 2 years ago | Recommendation & collaborative filtering engine. |
| [goptuna](https://github.com/c-bata/goptuna) | 188 | 9 | 2019/07/24 | 3 months ago | Bayesian optimization framework for black-box functions written in Go. Everything will be optimized. |
| [go-galib](https://github.com/thoj/go-galib) | 187 | 15 | 2009/11/30 | 5 years ago | Genetic Algorithms library written in Go / golang. |
| [goRecommend](https://github.com/timkaye11/goRecommend) | 177 | 10 | 2014/07/16 | 7 years ago | Recommendation Algorithms library written in Go. |
| [shield](https://github.com/eaigner/shield) | 143 | 11 | 2013/04/10 | 1 year ago | Bayesian text classifier with flexible tokenizers and storage backends for Go. |
| [goga](https://github.com/tomcraven/goga) | 111 | 9 | 2015/10/20 | 4 years ago | Genetic algorithm library for Go. |
| [go-fann](https://github.com/vksnk/go-fann) | 103 | 9 | 2011/03/10 | 6 years ago | Go bindings for Fast Artificial Neural Networks(FANN) library. |
| [goscore](https://github.com/asafschers/goscore) | 69 | 7 | 2017/08/19 | 2 years ago | Go Scoring API for PMML. |
| [gonet](https://github.com/dathoangnd/gonet) | 69 | 5 | 2020/01/11 | 1 year ago | Neural Network for Go. |
| [libsvm](https://github.com/datastream/libsvm) | 67 | 11 | 2012/07/31 | 5 years ago | libsvm golang version derived work based on LIBSVM 3.14. |
| [neural-go](https://github.com/schuyler/neural-go) | 61 | 3 | 2011/10/17 | 1 year ago | Multilayer perceptron network implemented in Go, with training via backpropagation. |
| [go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) | 60 | 1 | 2020/12/18 | 3 months ago | Fast and convenient feature processing for low latency machine leraning in Go. |
| [go-pr](https://github.com/daviddengcn/go-pr) | 59 | 7 | 2013/06/07 | 8 years ago | Pattern recognition package in Go lang. |
| [neat](https://github.com/jinyeom/neat) | 59 | 13 | 2016/11/17 | 3 years ago | Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT). |
| [fonet](https://github.com/Fontinalis/fonet) | 48 | 5 | 2017/10/03 | 4 months ago | A Deep Neural Network library written in Go. |
| [golinear](https://github.com/danieldk/golinear) | 42 | 6 | 2013/04/05 | 3 years ago | liblinear bindings for Go. |
| [Varis](https://github.com/Xamber/Varis) | 38 | 8 | 2017/10/10 | 3 years ago | Golang Neural Network. |
| [godist](https://github.com/e-dard/godist) | 30 | 4 | 2014/09/05 | 6 years ago | Various probability distributions, and associated methods. |
| [go-cluster](https://github.com/e-XpertSolutions/go-cluster) | 29 | 8 | 2017/10/04 | 3 years ago | Go implementation of the k-modes and k-prototypes clustering algorithms. |
| [evoli](https://github.com/khezen/evoli) | 16 | 5 | 2015/06/12 | 6 months ago | Genetic Algorithm and Particle Swarm Optimization library. |
| [probab](https://github.com/ThePaw/probab) | 16 | 2 | 2015/09/14 | 6 years ago | Probability distribution functions. Bayesian inference. Written in pure Go. |
| [gomind](https://github.com/surenderthakran/gomind) | 15 | 3 | 2017/10/19 | 3 years ago | A simplistic Neural Network Library in Go. |
| [randomForest](https://github.com/malaschitz/randomForest) | 15 | 4 | 2018/10/25 | 1 month ago | Easy to use Random Forest library for Go. |

## Messaging
        
*Libraries that implement messaging systems.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [sarama](https://github.com/Shopify/sarama) | 7691 | 472 | 2013/07/05 | 2 days ago | Go library for Apache Kafka. |
| [gorush](https://github.com/appleboy/gorush) | 5759 | 185 | 2016/03/22 | 1 week ago | Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm). |
| [machinery](https://github.com/RichardKnop/machinery) | 5624 | 153 | 2015/04/05 | 4 days ago | Asynchronous task queue/job queue based on distributed message passing. |
| [centrifugo](https://github.com/centrifugal/centrifugo) | 5427 | 198 | 2015/03/31 | 22 hours ago | Real-time messaging (Websockets or SockJS) server in Go. |
| [go-socket.io](https://github.com/googollee/go-socket.io) | 4280 | 132 | 2013/07/13 | 1 month ago | socket.io library for golang, a realtime application framework. |
| [nats.go](https://github.com/nats-io/nats.go) | 3575 | 162 | 2012/08/15 | 2 days ago | Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library. |
| [benthos](https://github.com/Jeffail/benthos) | 3423 | 88 | 2016/03/22 | 2 days ago | A message streaming bridge between a range of protocols. |
| [confluent-kafka-go](https://github.com/confluentinc/confluent-kafka-go) | 2918 | 269 | 2016/07/12 | 1 week ago | confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform. |
| [apns2](https://github.com/sideshow/apns2) | 2557 | 77 | 2016/01/05 | 1 week ago | HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps. |
| [mercure](https://github.com/dunglas/mercure) | 2551 | 56 | 2018/07/14 | 1 week ago | Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events). |
| [melody](https://github.com/olahol/melody) | 2237 | 60 | 2015/05/13 | 4 months ago | Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling. |
| [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) | 2006 | 232 | 2013/12/27 | 4 years ago | gopush-cluster is a go push server cluster. |
| [go-nsq](https://github.com/nsqio/go-nsq) | 1982 | 64 | 2013/08/29 | 4 days ago | the official Go package for NSQ. |
| [asynq](https://github.com/hibiken/asynq) | 1599 | 34 | 2019/11/15 | 3 hours ago | A simple, reliable, and efficient distributed task queue for Go built on top of Redis. |
| [mangos-v1](https://github.com/nanomsg/mangos-v1) | 1532 | 83 | 2014/10/25 | 1 year ago | Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability. |
| [uniqush-push](https://github.com/uniqush/uniqush-push) | 1281 | 79 | 2011/08/29 | 1 year ago | Redis backed unified push service for server-side notifications to mobile devices. |
| [Beaver](https://github.com/Clivern/Beaver) | 1167 | 26 | 2018/10/20 | 1 week ago | A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps. |
| [EventBus](https://github.com/asaskevich/EventBus) | 994 | 28 | 2014/12/19 | 3 months ago | The lightweight event bus with async compatibility. |
| [zmq4](https://github.com/pebbe/zmq4) | 929 | 43 | 2013/10/18 | 1 week ago | Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). |
| [gollum](https://github.com/trivago/gollum) | 904 | 38 | 2015/06/20 | 3 months ago | A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations. |
| [dbus](https://github.com/godbus/dbus) | 620 | 19 | 2014/03/27 | 3 weeks ago | Native Go bindings for D-Bus. |
| [golongpoll](https://github.com/jcuga/golongpoll) | 576 | 22 | 2015/11/02 | 5 months ago | HTTP longpoll server library that makes web pub-sub simple. |
| [mangos](https://github.com/nanomsg/mangos) | 444 | 22 | 2018/10/12 | 1 week ago | Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability. |
| [emitter](https://github.com/olebedev/emitter) | 408 | 10 | 2015/11/10 | 1 year ago | Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins. |
| [glue](https://github.com/desertbit/glue) | 385 | 17 | 2015/06/07 | 1 year ago | Robust Go and Javascript Socket Library (Alternative to Socket.io). |
| [pubsub](https://github.com/cskr/pubsub) | 356 | 9 | 2012/04/01 | 1 year ago | Simple pubsub package for go. |
| [bus](https://github.com/mustafaturan/bus) | 224 | 4 | 2019/04/27 | 4 months ago | Minimalist message bus implementation for internal communication. |
| [message-bus](https://github.com/vardius/message-bus) | 193 | 8 | 2017/10/04 | 8 months ago | messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD. |
| [rabtap](https://github.com/jandelgado/rabtap) | 188 | 10 | 2017/11/11 | 1 week ago | RabbitMQ swiss army knife cli app. |
| [guble](https://github.com/smancke/guble) | 148 | 13 | 2015/11/15 | 3 years ago | Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence. |
| [hub](https://github.com/leandro-lugaresi/hub) | 111 | 2 | 2018/04/13 | 11 months ago | A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges. |
| [oplog](https://github.com/dailymotion/oplog) | 108 | 93 | 2014/11/06 | 5 years ago | Generic oplog/replication system for REST APIs. |
| [rabbus](https://github.com/rafaeljesus/rabbus) | 91 | 8 | 2017/05/07 | 2 years ago | A tiny wrapper over amqp exchanges and queues. |
| [drone-line](https://github.com/appleboy/drone-line) | 76 | 5 | 2016/09/13 | 3 months ago | Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI. |
| [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) | 69 | 9 | 2017/01/15 | 3 years ago | A tiny wrapper around NSQ topic and channel. |
| [go-mq](https://github.com/cheshir/go-mq) | 68 | 6 | 2017/06/19 | 4 months ago | RabbitMQ client with declarative configuration. |
| [redisqueue](https://github.com/robinjoseph08/redisqueue) | 64 | 3 | 2019/07/07 | 2 months ago | redisqueue provides a producer and consumer of a queue that uses Redis streams. |
| [RapidMQ](https://github.com/sybrexsys/RapidMQ) | 62 | 5 | 2016/10/04 | 3 years ago | RapidMQ is a lightweight and reliable library for managing of the local messages queue. |
| [go-notify](https://github.com/TheCreeper/go-notify) | 55 | 2 | 2015/03/01 | 9 months ago | Native implementation of the freedesktop notification spec. |
| [commander](https://github.com/jeroenrinzema/commander) | 55 | 1 | 2018/04/20 | 5 months ago | A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka. |
| [go-res](https://github.com/jirenius/go-res) | 49 | 2 | 2018/07/15 | 2 weeks ago | Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate. |
| [event](https://github.com/agoalofalife/event) | 41 | 4 | 2017/07/02 | 3 years ago | Implementation of the pattern observer. |
| [commander](https://github.com/CloudProud/commander) | 38 | 1 | 2018/04/20 | 1 year ago | A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka. |
| [hare](https://github.com/leozz37/hare) | 30 | 1 | 2020/12/01 | 1 month ago | A user friendly library for sending messages and listening to TCP sockets. |
| [ami](https://github.com/kak-tus/ami) | 21 | 1 | 2018/10/27 | 1 year ago | Go client to reliable queues based on Redis Cluster Streams. |
| [gosd](https://github.com/alexsniffin/gosd) | 18 | 1 | 2020/05/17 | 10 months ago | A library for scheduling when to dispatch a message to a channel. |
| [go-vitotrol](https://github.com/maxatome/go-vitotrol) | 16 | 7 | 2016/11/03 | 7 months ago | Client library to Viessmann Vitotrol web service. |
| [rmqconn](https://github.com/sbabiv/rmqconn) | 15 | 1 | 2019/01/14 | 1 year ago | RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed. |
| [jazz](https://github.com/socifi/jazz) | 13 | 4 | 2018/10/22 | 2 years ago | A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages. |
| [gaurun-client](https://github.com/osamingo/gaurun-client) | 9 | 1 | 2017/06/29 | 2 months ago | Gaurun Client written in Go. |

## Microsoft Office
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [unioffice](https://github.com/unidoc/unioffice) | 2996 | 73 | 2017/08/29 | 1 week ago | Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents. |

### Microsoft Excel
        
*Libraries for working with Microsoft Excel.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [excelize](https://github.com/qax-os/excelize) | 9746 | 201 | 2016/08/29 | 2 days ago | Golang library for reading and writing Microsoft Excel™ (XLSX) files. |
| [excelize](https://github.com/360EntSecGroup-Skylar/excelize) | 9117 | 200 | 2016/08/29 | 2 months ago | Golang library for reading and writing Microsoft Excel™ (XLSX) files. |
| [xlsx](https://github.com/tealeg/xlsx) | 5120 | 173 | 2011/06/28 | 2 days ago | Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs. |
| [xlsx](https://github.com/plandem/xlsx) | 143 | 13 | 2017/08/26 | 11 months ago | Fast and safe way to read/update your existing Microsoft Excel files in Go programs. |
| [go-excel](https://github.com/szyhf/go-excel) | 130 | 3 | 2017/09/03 | 4 months ago | A simple and light reader to read a relate-db-like excel as a table. |
| [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) | 16 | 2 | 2017/03/13 | 3 years ago | Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files. |

## Miscellaneous
        

### Dependency Injection
        
*Libraries for working with dependency injection.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fx](https://github.com/uber-go/fx) | 2251 | 62 | 2016/10/27 | 2 weeks ago | A dependency injection based application framework for Go (built on top of dig). |
| [dig](https://github.com/uber-go/dig) | 2123 | 50 | 2017/03/21 | 1 week ago | A reflection based dependency injection toolkit for Go. |
| [container](https://github.com/golobby/container) | 247 | 5 | 2019/09/23 | 1 month ago | A powerful IoC Container with fluent and easy-to-use interface. |
| [dingo](https://github.com/i-love-flamingo/dingo) | 109 | 24 | 2018/10/29 | 5 months ago | A dependency injection toolkit for Go, based on Guice. |
| [di](https://github.com/goava/di) | 104 | 8 | 2020/02/03 | 2 months ago | A dependency injection container for go programming language. |
| [di](https://github.com/goioc/di) | 101 | 5 | 2020/06/11 | 2 months ago | Spring-inspired Dependency Injection Container. |
| [inject](https://github.com/defval/inject) | 53 | 1 | 2019/02/03 | 1 year ago | A reflection based dependency injection container with simple interface. |
| [alice](https://github.com/magic003/alice) | 43 | 2 | 2017/04/08 | 4 years ago | Additive dependency injection container for Golang. |
| [wire](https://github.com/Fs02/wire) | 34 | 2 | 2018/07/05 | 1 month ago | Strict Runtime Dependency Injection for Golang. |
| [linker](https://github.com/logrange/linker) | 32 | 4 | 2018/12/04 | 1 year ago | A reflection based dependency injection and inversion of control library with components lifecycle support. |
| [gocontainer](https://github.com/vardius/gocontainer) | 14 | 0 | 2019/06/06 | 1 year ago | Simple Dependency Injection Container. |

### Project Layout
        
*Unofficial set of patterns for structuring projects.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [project-layout](https://github.com/golang-standards/project-layout) | 26722 | 548 | 2017/09/09 | 4 days ago | Set of common historical and emerging project layout patterns in the Go ecosystem. |
| [modern-go-application](https://github.com/sagikazarmark/modern-go-application) | 1051 | 25 | 2018/09/14 | 2 months ago | Go application boilerplate and example applying modern practices. |
| [go-restful-api](https://github.com/qiangxue/go-restful-api) | 1038 | 52 | 2016/08/15 | 1 year ago | An idiomatic Go RESTful API starter kit following SOLID principles and Clean Architecture with a common project layout. |
| [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) | 476 | 9 | 2016/12/18 | 7 months ago | A Go application boilerplate template for quick starting projects following production best practices. |
| [seed](https://github.com/golang-templates/seed) | 212 | 5 | 2020/04/30 | 1 week ago | Go application GitHub repository template. |
| [scaffold](https://github.com/catchplay/scaffold) | 100 | 5 | 2018/12/11 | 2 years ago | Scaffold generates a starter Go project layout. Lets you focus on business logic implemented. |
| [go-todo-backend](https://github.com/Fs02/go-todo-backend) | 100 | 4 | 2020/06/25 | 1 week ago | Go Todo Backend example using modular project layout for product microservice. |
| [go-sample](https://github.com/zitryss/go-sample) | 93 | 1 | 2019/01/24 | 2 years ago | A sample layout for Go application projects with the real code. |
| [gobase](https://github.com/wajox/gobase) | 11 | 3 | 2020/12/15 | 1 week ago | A simple skeleton for golang application with basic setup for real golang application. |

### Strings
        
*Libraries for working with strings.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [xstrings](https://github.com/huandu/xstrings) | 937 | 25 | 2015/01/06 | 9 months ago | Collection of useful string functions ported from other languages. |
| [strutil](https://github.com/ozgio/strutil) | 128 | 3 | 2018/08/16 | 3 months ago | String utilities. |
| [stringy](https://github.com/gobeam/stringy) | 76 | 3 | 2020/04/03 | 4 months ago | String manipulation library to convert string to camel case, snake case, kebab case / slugify etc. |
| [Stringy](https://github.com/gobeam/Stringy) | 30 | 1 | 2020/04/03 | 1 year ago | String manipulation library to convert string to camel case, snake case, kebab case / slugify etc. |

### Uncategorized
        
*These libraries were placed here because none of the other categories seemed to fit.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gopsutil](https://github.com/shirou/gopsutil) | 6805 | 210 | 2014/04/18 | 2 hours ago | Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). |
| [archiver](https://github.com/mholt/archiver) | 3311 | 53 | 2016/04/08 | 1 day ago | Library and command for making and extracting .zip and .tar.gz archives. |
| [gofakeit](https://github.com/brianvoe/gofakeit) | 2064 | 17 | 2015/04/24 | 4 days ago | Random data generator written in go. |
| [gatus](https://github.com/TwinProduction/gatus) | 1858 | 22 | 2019/09/04 | 2 days ago | Automated service health dashboard. |
| [gosms](https://github.com/haxpax/gosms) | 1353 | 57 | 2015/01/23 | 7 months ago | Your own local SMS gateway in Go that can be used to send SMS. |
| [go-resiliency](https://github.com/eapache/go-resiliency) | 1266 | 26 | 2014/11/29 | 2 weeks ago | Resiliency patterns for golang. |
| [base64Captcha](https://github.com/mojocn/base64Captcha) | 1220 | 47 | 2017/12/12 | 2 months ago | Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha. |
| [go-commons-pool](https://github.com/jolestar/go-commons-pool) | 982 | 50 | 2015/12/28 | 5 months ago | Generic object pool for Golang. |
| [llvm](https://github.com/llir/llvm) | 806 | 34 | 2014/09/19 | 2 weeks ago | Library for interacting with LLVM IR in pure Go. |
| [shortid](https://github.com/teris-io/shortid) | 700 | 10 | 2016/01/04 | 10 months ago | Distributed generation of super short, unique, non-sequential, URL friendly IDs. |
| [ghorg](https://github.com/gabrie30/ghorg) | 505 | 13 | 2018/03/29 | 3 days ago | Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, and Bitbucket. |
| [health](https://github.com/dimiro1/health) | 425 | 6 | 2016/03/08 | 1 year ago | Easy to use, extensible health check library. |
| [go-conv](https://github.com/cstockton/go-conv) | 372 | 9 | 2016/10/11 | 1 month ago | Package conv provides fast and intuitive conversions across Go types. |
| [banner](https://github.com/dimiro1/banner) | 357 | 6 | 2016/03/25 | 9 months ago | Add beautiful banners into your Go applications. |
| [gountries](https://github.com/pariz/gountries) | 323 | 11 | 2016/01/13 | 5 months ago | Package that exposes country and subdivision data. |
| [stateless](https://github.com/qmuntal/stateless) | 320 | 7 | 2019/09/11 | 1 week ago | A fluent library for creating state machines. |
| [shoutrrr](https://github.com/containrrr/shoutrrr) | 238 | 9 | 2019/04/11 | 4 weeks ago | Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others. |
| [ffmt](https://github.com/go-ffmt/ffmt) | 237 | 7 | 2015/02/14 | 6 months ago | Beautify data display for Humans. |
| [lk](https://github.com/hyperboloide/lk) | 220 | 7 | 2016/07/14 | 1 year ago | A simple licensing library for golang. |
| [antch](https://github.com/antchfx/antch) | 216 | 16 | 2017/09/28 | 1 year ago | A fast, powerful and extensible web crawling & scraping framework. |
| [healthcheck](https://github.com/etherlabsio/healthcheck) | 200 | 9 | 2017/08/18 | 3 months ago | An opinionated and concurrent health-check HTTP handler for RESTful services. |
| [battery](https://github.com/distatus/battery) | 191 | 5 | 2016/03/12 | 1 week ago | Cross-platform, normalized battery information library. |
| [bitio](https://github.com/icza/bitio) | 168 | 8 | 2016/05/31 | 2 months ago | Highly optimized bit-level Reader and Writer for Go. |
| [stats](https://github.com/go-playground/stats) | 157 | 3 | 2015/09/14 | 5 years ago | Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... |
| [go-unarr](https://github.com/gen2brain/go-unarr) | 149 | 6 | 2015/11/01 | 11 months ago | Decompression library for RAR, TAR, ZIP and 7z archives. |
| [turtle](https://github.com/hackebrot/turtle) | 124 | 2 | 2017/09/08 | 3 months ago | Emojis for Go. |
| [gommit](https://github.com/antham/gommit) | 95 | 4 | 2016/08/30 | 1 week ago | Analyze git commit messages to ensure they follow defined patterns. |
| [gotoprom](https://github.com/cabify/gotoprom) | 91 | 95 | 2018/10/10 | 1 year ago | Type-safe metrics builder wrapper library for the official Prometheus client. |
| [indigo](https://github.com/osamingo/indigo) | 89 | 1 | 2016/08/31 | 8 months ago | Distributed unique ID generator of using Sonyflake and encoded by Base58. |
| [captcha](https://github.com/steambap/captcha) | 85 | 5 | 2017/09/12 | 5 days ago | Package captcha provides an easy to use, unopinionated API for captcha generation. |
| [morse](https://github.com/alwindoss/morse) | 70 | 2 | 2018/08/15 | 1 month ago | Library to convert to and from morse code. |
| [persian](https://github.com/mavihq/persian) | 59 | 5 | 2017/10/16 | 3 months ago | Some utilities for Persian language in go. |
| [pdfgen](https://github.com/hyperboloide/pdfgen) | 53 | 4 | 2015/11/30 | 3 years ago | HTTP service to generate PDF from Json requests. |
| [xkg](https://github.com/go-xkg/xkg) | 51 | 2 | 2015/01/05 | 6 years ago | X Keyboard Grabber. |
| [faker](https://github.com/pioz/faker) | 43 | 3 | 2020/07/22 | 1 month ago | Random fake data and struct generator for Go. |
| [browscap_go](https://github.com/digitalcrab/browscap_go) | 38 | 5 | 2014/09/18 | 2 weeks ago | GoLang Library for [Browser Capabilities Project](http://browscap.org/). |
| [datacounter](https://github.com/miolini/datacounter) | 36 | 1 | 2015/10/14 | 1 year ago | Go counters for readers/writer/http.ResponseWriter. |
| [autoflags](https://github.com/artyom/autoflags) | 34 | 5 | 2014/05/15 | 5 months ago | Go package to automatically define command line flags from struct fields. |
| [sandid](https://github.com/aofei/sandid) | 31 | 1 | 2018/06/12 | 7 months ago | Every grain of sand on earth has its own ID. |
| [url-shortener](https://github.com/pantrif/url-shortener) | 31 | 1 | 2018/06/04 | 3 years ago | A modern, powerful, and robust URL shortener microservice with mysql support. |
| [xdg](https://github.com/rkoesters/xdg) | 27 | 3 | 2013/12/15 | 2 months ago | FreeDesktop.org (xdg) Specs implemented in Go. |
| [gosh](https://github.com/osamingo/gosh) | 26 | 0 | 2018/05/25 | 8 months ago | Provide Go Statistics Handler, Struct, Measure Method. |
| [metrics](https://github.com/pascaldekloe/metrics) | 20 | 1 | 2019/01/29 | 6 months ago | Library for metrics instrumentation and Prometheus exposition. |
| [shellwords](https://github.com/Wing924/shellwords) | 15 | 1 | 2017/09/28 | 4 years ago | A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell. |
| [anagent](https://github.com/mudler/anagent) | 13 | 2 | 2017/12/29 | 3 years ago | Minimalistic, pluggable Golang evloop/timer handler with dependency-injection. |
| [avgRating](https://github.com/kirillDanshin/avgRating) | 10 | 2 | 2017/08/05 | 4 years ago | Calculate average score and rating based on Wilson Score Equation. |
| [hostutils](https://github.com/Wing924/hostutils) | 9 | 1 | 2017/09/26 | 2 years ago | A golang library for packing and unpacking FQDNs list. |
| [numa](https://github.com/lrita/numa) | 6 | 4 | 2018/12/10 | 9 months ago | NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code. |

## Natural Language Processing
        
*Libraries for working with human languages.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [prose](https://github.com/jdkato/prose) | 2799 | 59 | 2017/02/17 | 1 week ago | Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only. |
| [gse](https://github.com/go-ego/gse) | 1644 | 57 | 2017/06/23 | 21 hours ago | Go efficient text segmentation; support english, chinese, japanese and other. |
| [gojieba](https://github.com/yanyiwu/gojieba) | 1611 | 68 | 2015/09/12 | 4 months ago | This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm. |
| [when](https://github.com/olebedev/when) | 1128 | 25 | 2016/12/27 | 7 months ago | Natural EN and RU language date/time parser with pluggable rules. |
| [go-pinyin](https://github.com/mozillazg/go-pinyin) | 1017 | 38 | 2014/11/09 | 4 months ago | CN Hanzi to Hanyu Pinyin converter. |
| [spago](https://github.com/nlpodyssey/spago) | 963 | 28 | 2020/01/05 | 3 months ago | Self-contained Machine Learning and Natural Language Processing library in Go. |
| [kagome](https://github.com/ikawaha/kagome) | 582 | 22 | 2014/06/26 | 2 weeks ago | JP morphological analyzer written in pure Go. |
| [whatlanggo](https://github.com/abadojack/whatlanggo) | 509 | 15 | 2017/02/20 | 8 months ago | Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc). |
| [nlp](https://github.com/shixzie/nlp) | 371 | 23 | 2017/01/25 | 4 years ago | Extract values from strings and fill your structs with nlp. |
| [nlp](https://github.com/james-bowman/nlp) | 340 | 25 | 2017/03/15 | 4 months ago | Go Natural Language Processing library supporting LSA (Latent Semantic Analysis). |
| [sentences](https://github.com/neurosnap/sentences) | 310 | 14 | 2015/08/07 | 3 months ago | Sentence tokenizer:  converts text into a list of sentences. |
| [getlang](https://github.com/rylans/getlang) | 122 | 4 | 2018/03/01 | 9 months ago | Fast natural language detection package. |
| [go-unidecode](https://github.com/mozillazg/go-unidecode) | 90 | 2 | 2016/07/08 | 5 months ago | ASCII transliterations of Unicode text. |
| [go-nlp](https://github.com/nuance/go-nlp) | 89 | 6 | 2011/05/02 | 10 years ago | Utilities for working with discrete probability distributions and other tools useful for doing NLP work. |
| [RAKE.Go](https://github.com/afjoseph/RAKE.Go) | 82 | 7 | 2016/12/17 | 1 year ago | Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE). |
| [gounidecode](https://github.com/fiam/gounidecode) | 73 | 5 | 2012/05/01 | 6 years ago | Unicode transliterator (also known as unidecode) for Go. |
| [go-stem](https://github.com/agonopol/go-stem) | 65 | 4 | 2011/09/23 | 3 years ago | Implementation of the porter stemming algorithm. |
| [textcat](https://github.com/pebbe/textcat) | 65 | 7 | 2012/09/21 | 7 months ago | Go package for n-gram based text categorization, with support for utf-8 and raw text. |
| [MMSEGO](https://github.com/awsong/MMSEGO) | 59 | 5 | 2012/04/18 | 9 years ago | This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. |
| [stemmer](https://github.com/dchest/stemmer) | 49 | 4 | 2011/03/21 | 4 years ago | Stemmer packages for Go programming language. Includes English and German stemmers. |
| [go2vec](https://github.com/danieldk/go2vec) | 41 | 7 | 2015/01/27 | 3 years ago | Reader and utility functions for word2vec embeddings. |
| [porter2](https://github.com/zentures/porter2) | 40 | 3 | 2015/01/21 | 1 year ago | Really fast Porter 2 stemmer. |
| [petrovich](https://github.com/striker2000/petrovich) | 36 | 2 | 2016/12/26 | 7 months ago | Petrovich is the library which inflects Russian names to given grammatical case. |
| [address](https://github.com/bojanz/address) | 33 | 3 | 2020/10/07 | 1 week ago | Handles address representation, validation and formatting. |
| [mystem](https://github.com/dveselov/mystem) | 28 | 3 | 2016/08/30 | 5 years ago | CGo bindings to Yandex.Mystem - russian morphology analyzer. |
| [snowball](https://github.com/goodsign/snowball) | 28 | 1 | 2012/12/11 | 4 years ago | Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). |
| [go-localize](https://github.com/m1/go-localize) | 26 | 2 | 2019/12/23 | 2 days ago | Simple and easy to use i18n (Internationalization and localization) engine - used for translating locale strings. |
| [paicehusk](https://github.com/rookii/paicehusk) | 26 | 3 | 2012/09/29 | 7 years ago | Golang implementation of the Paice/Husk Stemming Algorithm. |
| [iuliia-go](https://github.com/mehanizm/iuliia-go) | 25 | 2 | 2020/04/27 | 3 months ago | Transliterate Cyrillic → Latin in every possible way. |
| [golibstemmer](https://github.com/rjohnsondev/golibstemmer) | 19 | 2 | 2012/08/06 | 7 years ago | Go bindings for the snowball libstemmer library including porter 2. |
| [icu](https://github.com/goodsign/icu) | 19 | 0 | 2012/12/11 | 4 years ago | Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1. |
| [govader](https://github.com/jonreiter/govader) | 16 | 1 | 2020/01/19 | 7 months ago | Go implementation of [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment). |
| [transliterator](https://github.com/alexsergivan/transliterator) | 13 | 1 | 2020/04/17 | 1 year ago | Provides one-way string transliteration with supporting of language-specific transliteration rules. |
| [gotokenizer](https://github.com/xujiajun/gotokenizer) | 12 | 1 | 2018/10/11 | 2 years ago | A tokenizer based on the dictionary and Bigram language models for Go. (Now only support chinese segmentation) |
| [shamoji](https://github.com/osamingo/shamoji) | 12 | 2 | 2017/07/23 | 8 months ago | The shamoji is word filtering package written in Go. |
| [detectlanguage-go](https://github.com/detectlanguage/detectlanguage-go) | 10 | 2 | 2019/12/14 | 11 months ago | Language Detection API Go Client. Supports batch requests, short phrase or single word language detection. |
| [libtextcat](https://github.com/goodsign/libtextcat) | 10 | 2 | 2012/12/10 | 8 years ago | Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. |
| [porter](https://github.com/a2800276/porter) | 8 | 1 | 2013/09/17 | 8 years ago | This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm. |
| [gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) | 7 | 1 | 2020/04/21 | 6 months ago | Sentiment analyzer using sentiwordnet lexicon in Go. |

## Networking
        
*Libraries for working with various layers of the network.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fasthttp](https://github.com/valyala/fasthttp) | 16139 | 401 | 2015/10/18 | 8 hours ago | Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http. |
| [kcptun](https://github.com/xtaci/kcptun) | 12588 | 595 | 2016/02/26 | 1 week ago | Extremely simple & fast udp tunnel based on KCP protocol. |
| [webrtc](https://github.com/pion/webrtc) | 8007 | 245 | 2018/05/18 | 1 day ago | A pure Go implementation of the WebRTC API. |
| [quic-go](https://github.com/lucas-clemente/quic-go) | 5830 | 201 | 2016/04/06 | 1 week ago | An implementation of the QUIC protocol in pure Go. |
| [dns](https://github.com/miekg/dns) | 5779 | 176 | 2010/08/03 | 5 days ago | Go library for working with DNS. |
| [gnet](https://github.com/panjf2000/gnet) | 5220 | 143 | 2019/02/24 | 5 days ago | `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go. |
| [gopacket](https://github.com/google/gopacket) | 4406 | 142 | 2015/03/16 | 1 week ago | Go library for packet processing with libpcap bindings. |
| [httplab](https://github.com/qustavo/httplab) | 3727 | 63 | 2017/02/08 | 2 years ago | HTTPLabs let you inspect HTTP requests and forge responses. |
| [httplab](https://github.com/gchaincl/httplab) | 3710 | 64 | 2017/02/08 | 2 years ago | HTTPLabs let you inspect HTTP requests and forge responses. |
| [kcp-go](https://github.com/xtaci/kcp-go) | 3091 | 153 | 2015/06/16 | 3 weeks ago | KCP - Fast and Reliable ARQ Protocol. |
| [gobgp](https://github.com/osrg/gobgp) | 2282 | 118 | 2014/09/14 | 2 days ago | BGP implemented in the Go Programming Language. |
| [ssh](https://github.com/gliderlabs/ssh) | 2157 | 55 | 2016/10/03 | 1 month ago | Higher-level API for building SSH servers (wraps crypto/ssh). |
| [fortio](https://github.com/fortio/fortio) | 2083 | 46 | 2017/10/10 | 1 month ago | Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC. |
| [water](https://github.com/songgao/water) | 1299 | 46 | 2013/03/25 | 5 months ago | Simple TUN/TAP library. |
| [gev](https://github.com/Allenxuxu/gev) | 1252 | 40 | 2019/09/01 | 10 hours ago | gev is a lightweight, fast non-blocking TCP network library based on Reactor mode. |
| [go-getter](https://github.com/hashicorp/go-getter) | 1229 | 240 | 2015/10/12 | 1 week ago | Go library for downloading files or directories from various sources using a URL. |
| [nff-go](https://github.com/intel-go/nff-go) | 1107 | 78 | 2017/03/29 | 3 weeks ago | Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF). |
| [sftp](https://github.com/pkg/sftp) | 1050 | 55 | 2013/11/05 | 6 days ago | Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt. |
| [grab](https://github.com/cavaliergopher/grab) | 920 | 17 | 2016/01/05 | 3 weeks ago | Go package for managing file downloads. |
| [grab](https://github.com/cavaliercoder/grab) | 918 | 17 | 2016/01/05 | 3 weeks ago | Go package for managing file downloads. |
| [ftp](https://github.com/jlaffaye/ftp) | 839 | 25 | 2011/05/06 | 1 hour ago | Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959). |
| [mdns](https://github.com/hashicorp/mdns) | 803 | 240 | 2014/01/29 | 5 months ago | Simple mDNS (Multicast DNS) client/server library in Golang. |
| [gosnmp](https://github.com/gosnmp/gosnmp) | 758 | 48 | 2012/08/27 | 2 hours ago | Native Go library for performing SNMP actions. |
| [vssh](https://github.com/yahoo/vssh) | 743 | 20 | 2020/06/09 | 10 months ago | Go library for building network and server automation over SSH protocol. |
| [cidranger](https://github.com/yl2chen/cidranger) | 634 | 17 | 2017/08/21 | 5 days ago | Fast IP to CIDR lookup for Go. |
| [lhttp](https://github.com/fanux/lhttp) | 630 | 59 | 2015/12/29 | 3 years ago | Powerful websocket framework, build your IM server more easily. |
| [gosnmp](https://github.com/soniah/gosnmp) | 563 | 46 | 2012/08/27 | 1 year ago | Native Go library for performing SNMP actions. |
| [peerdiscovery](https://github.com/schollz/peerdiscovery) | 503 | 18 | 2018/04/22 | 22 hours ago | Pure Go library for cross-platform local peer discovery using UDP multicast. |
| [gotcp](https://github.com/gansidui/gotcp) | 487 | 39 | 2014/04/13 | 4 years ago | Go package for quickly writing tcp applications. |
| [stun](https://github.com/gortc/stun) | 473 | 21 | 2016/04/24 | 4 months ago | Go implementation of RFC 5389 STUN protocol. |
| [gmqtt](https://github.com/DrmagicE/gmqtt) | 471 | 26 | 2018/09/16 | 1 week ago | Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1. |
| [go-stun](https://github.com/ccding/go-stun) | 455 | 15 | 2013/08/17 | 5 months ago | Go implementation of the STUN client (RFC 3489 and RFC 5389). |
| [gopcap](https://github.com/akrennmair/gopcap) | 433 | 23 | 2009/11/19 | 4 months ago | Go wrapper for libpcap. |
| [raw](https://github.com/mdlayher/raw) | 402 | 13 | 2015/07/06 | 1 week ago | Package raw enables reading and writing data at the device driver level for a network interface. |
| [tcp_server](https://github.com/firstrow/tcp_server) | 393 | 19 | 2014/10/13 | 6 months ago | Go library for building tcp servers faster. |
| [gaio](https://github.com/xtaci/gaio) | 385 | 17 | 2019/12/20 | 2 weeks ago | High performance async-io networking for Golang in proactor mode. |
| [winrm](https://github.com/masterzen/winrm) | 327 | 19 | 2013/12/30 | 2 months ago | Go WinRM client to remotely execute commands on Windows machines. |
| [arp](https://github.com/mdlayher/arp) | 261 | 10 | 2015/07/06 | 1 year ago | Package arp implements the ARP protocol, as described in RFC 826. |
| [buffstreams](https://github.com/StabbyCutyou/buffstreams) | 246 | 14 | 2015/06/29 | 1 year ago | Streaming protocolbuffer data over TCP made easy. |
| [ethernet](https://github.com/mdlayher/ethernet) | 230 | 13 | 2015/07/03 | 2 years ago | Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. |
| [gnxi](https://github.com/google/gnxi) | 191 | 32 | 2017/09/26 | 1 week ago | A collection of tools for Network Management that use the gNMI and gNOI protocols. |
| [jazigo](https://github.com/udhos/jazigo) | 171 | 14 | 2016/06/07 | 2 years ago | Jazigo is a tool written in Go for retrieving configuration for multiple network devices. |
| [utp](https://github.com/anacrolix/utp) | 161 | 18 | 2015/03/20 | 8 months ago | Go uTP micro transport protocol implementation. |
| [canopus](https://github.com/zubairhamed/canopus) | 146 | 14 | 2015/02/24 | 3 years ago | CoAP Client/Server implementation (RFC 7252). |
| [sslb](https://github.com/eduardonunesp/sslb) | 131 | 9 | 2015/10/18 | 2 years ago | It's a Super Simples Load Balancer, just a little project to achieve some kind of performance. |
| [xtcp](https://github.com/xfxdev/xtcp) | 127 | 15 | 2016/03/31 | 1 year ago | TCP Server Framework with simultaneous full duplex communication, graceful shutdown, and custom protocol. |
| [dhcp6](https://github.com/mdlayher/dhcp6) | 70 | 4 | 2015/05/22 | 2 years ago | Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. |
| [ether](https://github.com/songgao/ether) | 70 | 4 | 2014/05/21 | 5 years ago | Cross-platform Go package for sending and receiving ethernet frames. |
| [packet](https://github.com/aerogo/packet) | 57 | 5 | 2017/10/29 | 1 year ago | Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed. |
| [linkio](https://github.com/ian-kent/linkio) | 49 | 2 | 2014/12/24 | 4 years ago | Network link speed simulation for Reader/Writer interfaces. |
| [portproxy](https://github.com/aybabtme/portproxy) | 45 | 0 | 2014/12/13 | 6 years ago | Simple TCP proxy which adds CORS support to API's which don't support it. |
| [go-powerdns](https://github.com/joeig/go-powerdns) | 40 | 5 | 2018/06/21 | 1 month ago | PowerDNS API bindings for Golang. |
| [graval](https://github.com/koofr/graval) | 27 | 8 | 2014/04/22 | 1 year ago | Experimental FTP server framework. |
| [panoptes-stream](https://github.com/yahoo/panoptes-stream) | 27 | 8 | 2020/10/09 | 7 months ago | A cloud native distributed streaming network telemetry (gNMI, Juniper JTI and Cisco MDT). |
| [publicip](https://github.com/polera/publicip) | 24 | 2 | 2016/12/28 | 4 years ago | Package publicip returns your public facing IPv4 address (internet egress). |
| [golibwireshark](https://github.com/sunwxg/golibwireshark) | 21 | 2 | 2015/11/16 | 4 years ago | Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data. |
| [gohooks](https://github.com/averageflow/gohooks) | 14 | 1 | 2020/10/30 | 2 months ago | GoHooks make it easy to send and consume secured web-hooks from a Go application. Inspired by Spatie's Laravel Webhook Client and Server. |
| [goshark](https://github.com/sunwxg/goshark) | 13 | 1 | 2015/11/01 | 4 years ago | Package goshark use tshark to decode IP packet and create data struct to analyse packet. |
| [llb](https://github.com/kirillDanshin/llb) | 11 | 1 | 2016/02/21 | 5 years ago | It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response. |
| [tspool](https://github.com/two/tspool) | 10 | 1 | 2018/10/27 | 2 years ago | A TCP Library use worker pool to improve performance and protect your server. |
| [httpproxy](https://github.com/wzshiming/httpproxy) | 9 | 2 | 2018/07/18 | 2 days ago | HTTP proxy handler and dialer. |
| [gosocsvr](https://github.com/Rakeki/gosocsvr) | 5 | 2 | 2019/11/12 | 1 year ago | Socket server made simple. |

### HTTP Clients
        
*Libraries for making HTTP requests.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [resty](https://github.com/go-resty/resty) | 4961 | 90 | 2015/08/28 | 2 weeks ago | Simple HTTP and REST client for Go inspired by Ruby rest-client. |
| [heimdall](https://github.com/gojek/heimdall) | 2062 | 52 | 2018/01/19 | 1 month ago | An enchanced http client with retry and hystrix capabilities. |
| [grequests](https://github.com/levigross/grequests) | 1824 | 35 | 2015/06/11 | 10 months ago | A Go "clone" of the great and famous Requests library. |
| [sling](https://github.com/dghubble/sling) | 1362 | 29 | 2015/04/02 | 22 hours ago | Sling is a Go HTTP client library for creating and sending API requests. |
| [gentleman](https://github.com/h2non/gentleman) | 920 | 20 | 2016/02/21 | 7 months ago | Full-featured plugin-driven HTTP client library. |
| [pester](https://github.com/sethgrid/pester) | 563 | 6 | 2015/05/20 | 1 year ago | Go HTTP client calls with retries, backoff, and concurrency. |
| [request](https://github.com/monaco-io/request) | 138 | 10 | 2020/03/25 | 14 hours ago | HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency. |
| [sreq](https://github.com/winterssy/sreq) | 50 | 0 | 2019/12/04 | 1 year ago | A simple, user-friendly and concurrent safe HTTP request library for Go. |
| [rq](https://github.com/ddo/rq) | 39 | 3 | 2017/12/26 | 2 years ago | A nicer interface for golang stdlib HTTP client. |
| [go-http-client](https://github.com/bozd4g/go-http-client) | 26 | 2 | 2019/12/14 | 5 months ago | Make http calls simply and easily. |
| [httpretry](https://github.com/ybbus/httpretry) | 14 | 2 | 2020/02/05 | 1 year ago | Enriches the default go HTTP client with retry functionality. |

## OpenGL
        
*Libraries for using OpenGL in Go.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [glfw](https://github.com/go-gl/glfw) | 1150 | 39 | 2013/05/19 | 2 months ago | Go bindings for GLFW 3. |
| [gl](https://github.com/go-gl/gl) | 837 | 39 | 2015/02/22 | 3 weeks ago | Go bindings for OpenGL (generated via glow). |
| [mathgl](https://github.com/go-gl/mathgl) | 392 | 28 | 2013/02/13 | 1 year ago | Pure Go math package specialized for 3D math, with inspiration from GLM. |
| [gl](https://github.com/goxjs/gl) | 152 | 15 | 2015/05/18 | 9 months ago | Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). |
| [glfw](https://github.com/goxjs/glfw) | 71 | 7 | 2014/12/27 | 1 year ago | Go cross-platform glfw library for creating an OpenGL context and receiving events. |
| [go-glmatrix](https://github.com/technohippy/go-glmatrix) | 2 | 1 | 2020/07/02 | 8 months ago | Go port of [glMatrix](http://glmatrix.net/) library. |

## ORM
        
*Libraries that implement Object-Relational Mapping or datamapping techniques.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gorm](https://github.com/go-gorm/gorm) | 25379 | 491 | 2013/10/25 | 3 days ago | The fantastic ORM library for Golang, aims to be developer friendly. |
| [ent](https://github.com/ent/ent) | 8724 | 136 | 2019/06/12 | 3 hours ago | An entity framework for Go. Simple, yet powerful ORM for modeling and querying data. |
| [ent](https://github.com/facebook/ent) | 6615 | 123 | 2019/06/12 | 7 months ago | An entity framework for Go. Simple, yet powerful ORM for modeling and querying data. |
| [xorm](https://github.com/go-xorm/xorm) | 6186 | 262 | 2013/05/09 | 1 year ago | Simple and powerful ORM for Go. |
| [pg](https://github.com/go-pg/pg) | 4831 | 88 | 2013/04/24 | 1 week ago | PostgreSQL ORM with focus on PostgreSQL specific features and performance. |
| [sqlboiler](https://github.com/volatiletech/sqlboiler) | 4280 | 80 | 2016/02/21 | 2 days ago | ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema. |
| [gorp](https://github.com/go-gorp/gorp) | 3518 | 111 | 2012/01/04 | 7 months ago | Go Relational Persistence, ORM-ish library for Go. |
| [ent](https://github.com/facebookincubator/ent) | 3067 | 65 | 2019/06/12 | 1 year ago | An entity framework for Go. Simple, yet powerful ORM for modeling and querying data. |
| [db](https://github.com/upper/db) | 2753 | 63 | 2013/10/23 | 1 month ago | Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. |
| [gormt](https://github.com/xxjwxc/gormt) | 1450 | 20 | 2019/05/05 | 4 days ago | Mysql database to golang gorm struct. |
| [reform](https://github.com/go-reform/reform) | 1186 | 24 | 2016/02/25 | 6 days ago | Better ORM for Go, based on non-empty interfaces and code generation. |
| [pop](https://github.com/gobuffalo/pop) | 1121 | 25 | 2018/02/07 | 9 hours ago | Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. |
| [go-queryset](https://github.com/jirfag/go-queryset) | 636 | 24 | 2017/09/03 | 2 months ago | 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM. |
| [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) | 636 | 14 | 2017/12/27 | 3 weeks ago | A flexible and powerful SQL string builder library plus a zero-config ORM. |
| [qbs](https://github.com/coocood/qbs) | 548 | 44 | 2013/02/02 | 4 years ago | Stands for Query By Struct. A Go ORM. |
| [rel](https://github.com/go-rel/rel) | 430 | 8 | 2019/10/06 | 6 days ago | Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API. |
| [zoom](https://github.com/albrow/zoom) | 278 | 20 | 2013/07/17 | 1 year ago | Blazing-fast datastore and querying engine built on Redis. |
| [grimoire](https://github.com/Fs02/grimoire) | 152 | 6 | 2018/03/05 | 1 week ago | Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3). |
| [gosql](https://github.com/rushteam/gosql) | 147 | 7 | 2020/04/27 | 3 months ago | A easy ORM for mysql. |
| [gorm](https://github.com/jinzhu/gorm) | 137 | 10 | 2013/10/25 | 1 year ago | The fantastic ORM library for Golang, aims to be developer friendly. |
| [go-store](https://github.com/gosuri/go-store) | 103 | 9 | 2015/03/22 | 4 years ago | Simple and fast Redis backed key-value store library for Go. |
| [marlow](https://github.com/dadleyy/marlow) | 83 | 5 | 2017/09/15 | 1 year ago | Generated ORM from project structs for compile time safety assurances. |
| [go-firestorm](https://github.com/jschoedt/go-firestorm) | 24 | 1 | 2018/12/04 | 5 months ago | A simple ORM for Google/Firebase Cloud Firestore. |
| [lore](https://github.com/abrahambotros/lore) | 9 | 1 | 2017/04/29 | 4 years ago | Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go. |
| [marlow](https://github.com/marlow/marlow) | 7 | 3 | 2020/08/11 | 1 year ago | Generated ORM from project structs for compile time safety assurances. |
| [rel](https://github.com/Fs02/rel) | 1 | 0 | 2019/10/06 | 1 year ago | Golang SQL Repository Layer for Clean (Onion) Architecture. |

## Package Management
        
*Unofficial libraries for package and dependency management.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [dep](https://github.com/golang/dep) | 13131 | 267 | 2016/10/07 | 1 year ago | Go dependency tool. |
| [glide](https://github.com/Masterminds/glide) | 8130 | 189 | 2014/07/09 | 7 months ago | Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip. |
| [godep](https://github.com/tools/godep) | 5610 | 149 | 2013/05/01 | 3 years ago | dependency tool for go, godep helps build packages reproducibly by fixing their dependencies. |
| [govendor](https://github.com/kardianos/govendor) | 5009 | 97 | 2015/04/12 | 1 year ago | Go Package Manager. Go vendor tool that works with the standard vendor file. |
| [gopm](https://github.com/gpmgo/gopm) | 2499 | 85 | 2013/05/15 | 2 years ago | Go Package Manager. |
| [gom](https://github.com/mattn/gom) | 1396 | 36 | 2013/09/11 | 2 years ago | Go Manager - bundle for go. |
| [gpm](https://github.com/pote/gpm) | 1197 | 32 | 2013/09/05 | 4 years ago | Barebones dependency manager for Go. |
| [goop](https://github.com/petejkim/goop) | 778 | 36 | 2014/06/18 | 5 years ago | Simple dependency manager for Go (golang), inspired by Bundler. |
| [modgv](https://github.com/lucasepe/modgv) | 394 | 7 | 2020/09/12 | 1 year ago | Converts 'go mod graph' output into Graphviz's DOT language. |
| [nut](https://github.com/jingweno/nut) | 242 | 6 | 2015/01/23 | 6 years ago | Vendor Go dependencies. |
| [nut](https://github.com/owenthereal/nut) | 239 | 6 | 2015/01/23 | 6 years ago | Vendor Go dependencies. |
| [johnny-deps](https://github.com/VividCortex/johnny-deps) | 214 | 21 | 2013/07/19 | 9 months ago | Minimal dependency version using Git. |
| [gigo](https://github.com/LyricalSecurity/gigo) | 199 | 5 | 2015/05/01 | 2 years ago | PIP-like dependency tool for golang, with support for private repositories and hashes. |
| [mvn-golang](https://github.com/raydac/mvn-golang) | 131 | 11 | 2016/03/24 | 3 weeks ago | plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure. |
| [VenGO](https://github.com/DamnWidget/VenGO) | 120 | 9 | 2014/10/17 | 5 years ago | create and manage exportable isolated go virtual environments. |
| [gop](https://github.com/lunny/gop) | 49 | 8 | 2017/02/18 | 2 years ago | Build and manage your Go applications out of GOPATH. |

## Performance
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [jaeger](https://github.com/jaegertracing/jaeger) | 14355 | 345 | 2016/04/15 | 1 day ago | A distributed tracing system. |
| [pixie](https://github.com/pixie-io/pixie) | 1869 | 58 | 2020/02/27 | 1 day ago | No instrumentation tracing for Golang applications via eBPF. |
| [pixie](https://github.com/pixie-labs/pixie) | 1796 | 55 | 2020/02/27 | 1 month ago | No instrumentation tracing for Golang applications via eBPF. |
| [statsviz](https://github.com/arl/statsviz) | 1707 | 21 | 2020/08/14 | 1 week ago | Live visualization of your Go application runtime statistics. |
| [profile](https://github.com/pkg/profile) | 1582 | 39 | 2014/10/22 | 3 weeks ago | Simple profiling support package for Go. |
| [tracer](https://github.com/kamilsk/tracer) | 54 | 4 | 2019/06/22 | 7 months ago | Simple, lightweight tracing. |

## Query Language
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [graphql](https://github.com/graphql-go/graphql) | 8005 | 151 | 2015/07/19 | 1 month ago | Implementation of GraphQL for Go. |
| [graphql-go](https://github.com/graph-gophers/graphql-go) | 3937 | 91 | 2016/10/18 | 8 hours ago | GraphQL server with a focus on ease of use. |
| [gojsonq](https://github.com/thedevsaddam/gojsonq) | 1743 | 33 | 2018/05/19 | 1 month ago | A simple Go package to Query over JSON Data. |
| [dasel](https://github.com/TomWright/dasel) | 1626 | 10 | 2020/09/22 | 3 days ago | Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies. |
| [jsonql](https://github.com/elgs/jsonql) | 245 | 11 | 2015/12/29 | 10 months ago | JSON query expression library in Golang. |
| [rql](https://github.com/a8m/rql) | 231 | 10 | 2018/06/05 | 3 months ago | Resource Query Language for REST API. |
| [jsonslice](https://github.com/bhmj/jsonslice) | 54 | 0 | 2018/05/02 | 1 year ago | Jsonpath queries with advanced filters. |
| [graphql](https://github.com/tmc/graphql) | 53 | 11 | 2015/04/18 | 4 years ago | graphql parser + utilities. |
| [api-fu](https://github.com/ccbrown/api-fu) | 38 | 2 | 2019/07/30 | 3 days ago | Comprehensive GraphQL implementation. |
| [straf](https://github.com/SonicRoshan/straf) | 31 | 1 | 2019/08/16 | 1 year ago | Easily Convert Golang structs to GraphQL objects. |
| [rest-query-parser](https://github.com/timsolov/rest-query-parser) | 27 | 2 | 2020/02/10 | 3 months ago | Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query. |
| [jsonpath](https://github.com/AsaiYusuke/jsonpath) | 5 | 1 | 2020/11/29 | 7 months ago | A query library for retrieving part of JSON based on JSONPath syntax. |
| [gws](https://github.com/Zaba505/gws) | 4 | 1 | 2020/06/08 | 1 year ago | Apollos' "GraphQL over Websocket" client and server implementation. |

## Resource Embedding
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [packr](https://github.com/gobuffalo/packr) | 3292 | 48 | 2017/03/15 | 1 month ago | The simple and easy way to embed static files into Go binaries. |
| [statik](https://github.com/rakyll/statik) | 3287 | 50 | 2014/02/04 | 10 months ago | Embeds static files into a Go executable. |
| [go.rice](https://github.com/GeertJohan/go.rice) | 2251 | 57 | 2013/10/23 | 7 months ago | go.rice is a Go package that makes working with resources such as HTML, JS, CSS, images, and templates very easy. |
| [vfsgen](https://github.com/shurcooL/vfsgen) | 933 | 20 | 2015/05/18 | 1 year ago | Generates a vfsdata.go file that statically implements the given virtual filesystem. |
| [esc](https://github.com/mjibson/esc) | 602 | 15 | 2014/01/26 | 1 year ago | Embeds files into Go programs and provides http.FileSystem interfaces to them. |
| [fileb0x](https://github.com/UnnoTed/fileb0x) | 592 | 18 | 2016/01/23 | 7 months ago | Simple tool to embed files in go with focus on "customization" and ease to use. |
| [go-resources](https://github.com/omeid/go-resources) | 173 | 9 | 2015/02/21 | 4 months ago | Unfancy resources embedding with Go. |
| [statics](https://github.com/go-playground/statics) | 63 | 3 | 2015/10/07 | 5 years ago | Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks. |
| [go-embed](https://github.com/pyros2097/go-embed) | 28 | 3 | 2015/12/06 | 8 months ago | Generates go code to embed resource files into your library or executable. |
| [templify](https://github.com/wlbr/templify) | 26 | 3 | 2016/05/22 | 1 month ago | Embed external template files into Go code to create single file binaries. |
| [mule](https://github.com/wlbr/mule) | 9 | 2 | 2020/01/17 | 1 month ago | Embed external resources like images, movies ... into Go source code to create single file binaries using `go generate`. Focussed on simplicity. |

## Science and Data Analysis
        
*Libraries for scientific computing and data analyzing.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gonum](https://github.com/gonum/gonum) | 5209 | 114 | 2017/03/25 | 1 day ago | Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more. |
| [stats](https://github.com/montanaflynn/stats) | 2049 | 52 | 2014/12/16 | 5 months ago | Statistics package with common functions missing from the Golang standard library. |
| [plot](https://github.com/gonum/plot) | 1998 | 58 | 2013/07/23 | 5 days ago | gonum/plot provides an API for building and drawing plots in Go. |
| [gosl](https://github.com/cpmech/gosl) | 1606 | 72 | 2015/02/09 | 3 weeks ago | Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more. |
| [streamtools](https://github.com/nytlabs/streamtools) | 1314 | 71 | 2013/07/05 | 6 years ago | general purpose, graphical tool for dealing with streams of data. |
| [go-dsp](https://github.com/mjibson/go-dsp) | 748 | 29 | 2011/11/02 | 3 years ago | Digital Signal Processing for Go. |
| [chart](https://github.com/vdobler/chart) | 689 | 45 | 2011/06/27 | 4 months ago | Simple Chart Plotting library for Go. Supports many graphs types. |
| [goraph](https://github.com/gyuho/goraph) | 648 | 40 | 2014/02/27 | 4 years ago | Pure Go graph theory library(data structure, algorith visualization). |
| [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) | 617 | 27 | 2018/10/01 | 5 months ago | Dataframes for machine-learning and statistics (similar to pandas). |
| [graph](https://github.com/yourbasic/graph) | 481 | 22 | 2017/04/27 | 1 week ago | Library of basic graph algorithms. |
| [orb](https://github.com/paulmach/orb) | 418 | 22 | 2016/03/28 | 4 days ago | 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support. |
| [ewma](https://github.com/VividCortex/ewma) | 339 | 24 | 2013/07/05 | 1 month ago | Exponentially-weighted moving averages. |
| [calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) | 327 | 10 | 2020/07/01 | 2 days ago | Calendar heatmap in plain Go inspired by Github contribution activity. |
| [gohistogram](https://github.com/VividCortex/gohistogram) | 158 | 17 | 2013/07/02 | 9 months ago | Approximate histograms for data streams. |
| [TextRank](https://github.com/DavidBelicza/TextRank) | 144 | 8 | 2018/01/09 | 2 months ago | TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support. |
| [sparse](https://github.com/james-bowman/sparse) | 121 | 8 | 2017/05/16 | 2 months ago | Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries. |
| [pagerank](https://github.com/alixaxel/pagerank) | 72 | 8 | 2015/08/06 | 3 months ago | Weighted PageRank algorithm implemented in Go. |
| [geom](https://github.com/skelterjohn/geom) | 48 | 5 | 2011/06/07 | 3 years ago | 2D geometry for golang. |
| [evaler](https://github.com/soniah/evaler) | 45 | 5 | 2012/09/04 | 3 years ago | Simple floating point arithmetic expression evaluator. |
| [goent](https://github.com/kzahedi/goent) | 25 | 1 | 2017/08/08 | 2 years ago | GO Implementation of Entropy Measures. |
| [triangolatte](https://github.com/tchayen/triangolatte) | 24 | 2 | 2018/07/18 | 2 months ago | 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs. |
| [decimal](https://github.com/db47h/decimal) | 23 | 4 | 2020/05/27 | 1 year ago | Package decimal implements arbitrary-precision decimal floating-point arithmetic. |
| [piecewiselinear](https://github.com/sgreben/piecewiselinear) | 20 | 4 | 2018/10/21 | 10 months ago | Tiny linear interpolation library. |
| [GoStats](https://github.com/OGFris/GoStats) | 16 | 3 | 2018/07/22 | 2 years ago | GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions. |
| [PiHex](https://github.com/claygod/PiHex) | 14 | 3 | 2016/07/22 | 1 year ago | Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi. |
| [ode](https://github.com/ChristopherRabotin/ode) | 13 | 4 | 2016/11/11 | 4 years ago | Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions. |
| [assocentity](https://github.com/ndabAP/assocentity) | 5 | 2 | 2018/12/21 | 11 months ago | Package assocentity returns the average distance from words to a given entity. |
| [go-gt](https://github.com/ThePaw/go-gt) | 5 | 0 | 2015/09/14 | 6 years ago | Graph theory algorithms written in "Go" language. |
| [rootfinding](https://github.com/khezen/rootfinding) | 5 | 3 | 2018/10/30 | 1 year ago | root-finding algorithms library for finding roots of quadratic functions. |
| [bradleyterry](https://github.com/seanhagen/bradleyterry) | 4 | 2 | 2019/04/30 | 2 years ago | Provides a Bradley-Terry Model for pairwise comparisons. |

## Security
        
*Libraries that are used to help make your application more secure.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [lego](https://github.com/go-acme/lego) | 4842 | 96 | 2015/06/08 | 3 hours ago | Pure Go ACME client library and CLI tool (for use with Let's Encrypt). |
| [cameradar](https://github.com/Ullaakut/cameradar) | 2705 | 130 | 2016/05/20 | 1 week ago | Tool and library to remotely hack RTSP streams from surveillance cameras. |
| [memguard](https://github.com/awnumar/memguard) | 1994 | 47 | 2017/04/22 | 6 months ago | A pure Go library for handling sensitive values in memory. |
| [acmetool](https://github.com/hlandau/acmetool) | 1875 | 63 | 2015/11/15 | 6 months ago | ACME (Let's Encrypt) client tool with automatic renewal. |
| [secure](https://github.com/unrolled/secure) | 1821 | 37 | 2014/05/20 | 2 months ago | HTTP middleware for Go that facilitates some quick security wins. |
| [themis](https://github.com/cossacklabs/themis) | 1358 | 42 | 2015/05/06 | 2 weeks ago | high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps. |
| [acra](https://github.com/cossacklabs/acra) | 802 | 39 | 2016/11/14 | 4 months ago | Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system. |
| [nacl](https://github.com/kevinburke/nacl) | 510 | 12 | 2017/07/20 | 6 months ago | Go implementation of the NaCL set of API's. |
| [ssh-vault](https://github.com/ssh-vault/ssh-vault) | 316 | 10 | 2016/09/29 | 2 months ago | encrypt/decrypt using ssh keys. |
| [firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) | 310 | 9 | 2020/06/12 | 1 year ago | A rest application to dynamically update firewalld rules on a linux server. |
| [badactor](https://github.com/jaredfolkins/badactor) | 303 | 8 | 2014/12/12 | 1 year ago | In-memory, application-driven jailer built in the spirit of fail2ban. |
| [go-password-validator](https://github.com/wagslane/go-password-validator) | 296 | 9 | 2020/10/14 | 5 months ago | Password validator based on raw cryptographic entropy values. |
| [optimus-go](https://github.com/pjebs/optimus-go) | 286 | 5 | 2015/05/05 | 1 year ago | ID hashing and Obfuscation using Knuth's Algorithm. |
| [go-password-validator](https://github.com/lane-c-wagner/go-password-validator) | 259 | 8 | 2020/10/14 | 9 months ago | Password validator based on raw cryptographic entropy values. |
| [passlib](https://github.com/hlandau/passlib) | 253 | 11 | 2014/12/21 | 6 months ago | Futureproof password hashing library. |
| [go-yara](https://github.com/hillu/go-yara) | 225 | 20 | 2015/01/25 | 4 months ago | Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)". |
| [simple-scrypt](https://github.com/elithrar/simple-scrypt) | 172 | 7 | 2015/04/14 | 5 months ago | Scrypt package with a simple, obvious API and automatic cost calibration built-in. |
| [argon2pw](https://github.com/raja/argon2pw) | 87 | 4 | 2018/03/13 | 3 weeks ago | Argon2 password hash generation with constant-time password comparison. |
| [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) | 43 | 2 | 2017/10/19 | 9 months ago | A probably paranoid package for securely hashing and encrypting passwords. |
| [go-generate-password](https://github.com/m1/go-generate-password) | 27 | 2 | 2019/11/14 | 1 month ago | Password generator that can be used on the cli or as a library. |
| [certificates](https://github.com/mvmaasakkers/certificates) | 21 | 0 | 2019/03/04 | 9 months ago | An opinionated tool for generating tls certificates. |
| [secureio](https://github.com/xaionaro-go/secureio) | 21 | 3 | 2018/12/25 | 1 year ago | An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519. |
| [argon2-hashing](https://github.com/andskur/argon2-hashing) | 14 | 2 | 2019/01/02 | 1 year ago | light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package. |
| [goArgonPass](https://github.com/dwin/goArgonPass) | 13 | 2 | 2018/05/30 | 9 months ago | Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations. |
| [sslmgr](https://github.com/adrianosela/sslmgr) | 11 | 2 | 2019/04/02 | 2 years ago | SSL certificates made easy with a high level wrapper around acme/autocert. |

## Serialization
        
*Libraries and tools for binary serialization.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go](https://github.com/json-iterator/go) | 9870 | 231 | 2016/11/30 | 1 week ago | High-performance 100% compatible drop-in replacement of "encoding/json". |
| [protobuf](https://github.com/golang/protobuf) | 7954 | 209 | 2014/11/23 | 2 weeks ago | Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers. |
| [mapstructure](https://github.com/mitchellh/mapstructure) | 4917 | 68 | 2013/05/20 | 2 weeks ago | Go library for decoding generic map values into native Go structures. |
| [protobuf](https://github.com/gogo/protobuf) | 4841 | 103 | 2014/12/03 | 1 month ago | Protocol Buffers for Go with Gadgets. |
| [go](https://github.com/ugorji/go) | 1585 | 52 | 2013/05/30 | 4 months ago | High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support. |
| [colfer](https://github.com/pascaldekloe/colfer) | 626 | 33 | 2015/09/05 | 3 weeks ago | Code generation for the Colfer binary format. |
| [csvutil](https://github.com/jszwec/csvutil) | 604 | 8 | 2017/10/30 | 1 month ago | High Performance, idiomatic CSV record encoding and decoding to native Go structures. |
| [cbor](https://github.com/fxamacker/cbor) | 329 | 6 | 2019/05/15 | 3 days ago | Small, safe, and easy CBOR encoding and decoding library. |
| [go-capnproto](https://github.com/glycerine/go-capnproto) | 279 | 11 | 2013/11/07 | 1 year ago | Cap'n Proto library and parser for go. |
| [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) | 151 | 9 | 2012/12/23 | 2 years ago | GoLang library for working with PHP session format and PHP Serialize/Unserialize functions. |
| [structomap](https://github.com/danhper/structomap) | 130 | 7 | 2015/05/13 | 2 years ago | Library to easily and dynamically generate maps from static structures. |
| [bambam](https://github.com/glycerine/bambam) | 62 | 4 | 2014/09/17 | 5 years ago | generator for Cap'n Proto schemas from go. |
| [asn1](https://github.com/Logicalis/asn1) | 48 | 9 | 2016/02/29 | 2 years ago | Asn.1 BER and DER encoding library for golang. |
| [binstruct](https://github.com/ghostiam/binstruct) | 35 | 2 | 2018/10/23 | 2 weeks ago | Golang binary decoder for mapping data into the structure. |
| [pletter](https://github.com/vimeda/pletter) | 15 | 7 | 2019/07/09 | 4 days ago | A standard way to wrap a proto message for message brokers. |
| [elastic](https://github.com/epiclabs-io/elastic) | 15 | 1 | 2020/02/25 | 4 months ago | Convert slices, maps or any other unknown value across different types at run-time, no matter what. |
| [fwencoder](https://github.com/o1egl/fwencoder) | 14 | 2 | 2017/12/25 | 1 year ago | Fixed width file parser (encoding and decoding library) for Go. |
| [bel](https://github.com/csweichel/bel) | 13 | 2 | 2019/02/20 | 1 year ago | Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC. |
| [bel](https://github.com/32leaves/bel) | 8 | 1 | 2019/02/20 | 2 years ago | Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC. |
| [fixedwidth](https://github.com/huydang284/fixedwidth) | 5 | 1 | 2019/08/11 | 1 year ago | Fixed-width text formatting (UTF-8 supported). |
| [unitpacking](https://github.com/recolude/unitpacking) | 3 | 2 | 2021/01/17 | 5 months ago | Library to pack unit vectors into as fewest bytes as possible. |
| [go-lctree](https://github.com/sbourlon/go-lctree) | 2 | 1 | 2020/05/04 | 1 year ago | Provides a CLI and primitives to serialize and deserialize [LeetCode binary trees](https://support.leetcode.com/hc/en-us/articles/360011883654-What-does-1-null-2-3-mean-in-binary-tree-representation). |

## Server Applications
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [etcd](https://github.com/etcd-io/etcd) | 37406 | 1356 | 2013/07/06 | 1 hour ago | Highly-available key value store for shared configuration and service discovery. |
| [caddy](https://github.com/caddyserver/caddy) | 34787 | 763 | 2015/01/13 | 1 day ago | Caddy is an alternative, HTTP/2 web server that's easy to configure and use. |
| [minio](https://github.com/minio/minio) | 29491 | 582 | 2015/01/14 | 8 hours ago | Minio is a distributed object storage server. |
| [roadrunner](https://github.com/spiral/roadrunner) | 5894 | 151 | 2017/12/26 | 2 hours ago | High-performance PHP application server, load-balancer and process manager. |
| [devd](https://github.com/cortesi/devd) | 3172 | 68 | 2015/09/27 | 1 month ago | Local webserver for developers. |
| [sftpgo](https://github.com/drakkan/sftpgo) | 2999 | 65 | 2019/07/20 | 3 hours ago | Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage. |
| [algernon](https://github.com/xyproto/algernon) | 1859 | 51 | 2015/03/10 | 3 days ago | HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. |
| [fider](https://github.com/getfider/fider) | 1713 | 34 | 2017/01/17 | 20 minutes ago | Fider is an open platform to collect and organize customer feedback. |
| [flagr](https://github.com/checkr/flagr) | 1685 | 75 | 2017/10/03 | 1 week ago | Flagr is an open-source feature flagging and A/B testing service. |
| [flipt](https://github.com/markphelps/flipt) | 1556 | 15 | 2016/11/05 | 4 days ago | A self contained feature flag solution written in Go and Vue. |
| [trickster](https://github.com/trickstercache/trickster) | 1532 | 43 | 2018/03/29 | 3 weeks ago | HTTP reverse proxy cache and time series accelerator. |
| [discovery](https://github.com/bilibili/discovery) | 1509 | 60 | 2018/04/20 | 2 months ago | A registry for resilient mid-tier load balancing and failover. |
| [trickster](https://github.com/tricksterproxy/trickster) | 1403 | 41 | 2018/03/29 | 4 months ago | HTTP reverse proxy cache and time series accelerator. |
| [jackal](https://github.com/ortuman/jackal) | 1144 | 40 | 2017/11/13 | 4 hours ago | An XMPP server written in Go. |
| [trickster](https://github.com/Comcast/trickster) | 1053 | 35 | 2018/03/29 | 1 year ago | HTTP reverse proxy cache and time series accelerator. |
| [go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) | 362 | 2 | 2020/12/11 | 2 days ago | A feature flag solution, with only a YAML file in the backend (S3, GitHub, HTTP, local file ...), no server to install, just add a file in a central system and refer to it. |
| [dudeldu](https://github.com/krotik/dudeldu) | 129 | 3 | 2016/09/07 | 2 years ago | A simple SHOUTcast server. |
| [lets-proxy2](https://github.com/rekby/lets-proxy2) | 58 | 5 | 2019/04/12 | 4 weeks ago | Reverse proxy for handle https with issue certificates in fly from lets-encrypt. |
| [psql-streamer](https://github.com/blind-oracle/psql-streamer) | 32 | 4 | 2019/04/28 | 1 year ago | Stream database events from PostgreSQL to Kafka. |
| [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) | 26 | 1 | 2018/10/23 | 1 year ago | Nginx log parser and exporter to Prometheus. |
| [simple-jwt-provider](https://github.com/leberKleber/simple-jwt-provider) | 20 | 2 | 2019/12/18 | 2 months ago | Simple and lightweight provider which exhibits JWTs, supports login, password-reset (via mail) and user management. |
| [go-proxy-cache](https://github.com/fabiocicerchia/go-proxy-cache) | 18 | 1 | 2020/11/12 | 6 days ago | Simple Reverse Proxy with Caching, written in Go, using Redis. |
| [protoxy](https://github.com/camgraff/protoxy) | 17 | 2 | 2020/09/03 | 10 months ago | A proxy server that converts JSON request bodies to Protocol Buffers. |
| [riemann-relay](https://github.com/blind-oracle/riemann-relay) | 0 | 1 | 2019/04/23 | 1 year ago | Relay to load-balance Riemann events and/or convert them to Carbon. |

## Stream Processing
        
*Libraries and tools for stream processing and reactive programming.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-streams](https://github.com/reugn/go-streams) | 723 | 21 | 2019/04/30 | 1 month ago | Go stream processing library. |
| [machine](https://github.com/whitaker-io/machine) | 97 | 6 | 2020/10/13 | 1 day ago | Go library for writing and generating stream workers with built in metrics and traceability. |
| [stream](https://github.com/youthlin/stream) | 42 | 2 | 2020/11/12 | 9 months ago | Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce... |

## Template Engines
        
*Libraries and tools for templating and lexing.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gofpdf](https://github.com/jung-kurt/gofpdf) | 3868 | 104 | 2015/03/13 | 2 weeks ago | PDF document generator with high level support for text, drawing and images. |
| [sprig](https://github.com/Masterminds/sprig) | 2572 | 32 | 2013/11/22 | 1 month ago | Useful template functions for Go templates. |
| [quicktemplate](https://github.com/valyala/quicktemplate) | 2229 | 58 | 2016/03/06 | 2 weeks ago | Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it. |
| [pongo2](https://github.com/flosch/pongo2) | 2058 | 62 | 2013/08/23 | 1 month ago | Django-like template-engine for Go. |
| [hero](https://github.com/shiyanhui/hero) | 1478 | 43 | 2017/01/15 | 1 year ago | Hero is a handy, fast and powerful go template engine. |
| [mustache](https://github.com/hoisie/mustache) | 1022 | 36 | 2009/12/30 | 1 week ago | Go implementation of the Mustache template language. |
| [amber](https://github.com/eknkc/amber) | 880 | 19 | 2012/10/31 | 11 months ago | Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade. |
| [jet](https://github.com/CloudyKit/jet) | 837 | 22 | 2016/03/31 | 7 months ago | Jet template engine. |
| [ace](https://github.com/yosssi/ace) | 805 | 23 | 2014/07/13 | 3 years ago | Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold. |
| [gorazor](https://github.com/sipin/gorazor) | 789 | 58 | 2014/05/01 | 10 months ago | Razor view engine for Golang. |
| [fasttemplate](https://github.com/valyala/fasttemplate) | 536 | 19 | 2015/08/19 | 8 months ago | Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/). |
| [ego](https://github.com/benbjohnson/ego) | 504 | 16 | 2014/02/23 | 2 months ago | Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled. |
| [maroto](https://github.com/johnfercher/maroto) | 451 | 10 | 2019/05/20 | 1 month ago | A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple. |
| [raymond](https://github.com/aymerick/raymond) | 443 | 11 | 2015/04/22 | 6 days ago | Complete handlebars implementation in Go. |
| [goview](https://github.com/foolin/goview) | 252 | 6 | 2019/04/14 | 9 months ago | Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application. |
| [soy](https://github.com/robfig/soy) | 156 | 12 | 2013/12/15 | 4 days ago | Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/). |
| [liquid](https://github.com/osteele/liquid) | 137 | 6 | 2017/06/26 | 2 months ago | Go implementation of Shopify Liquid templates. |
| [velvet](https://github.com/gobuffalo/velvet) | 73 | 6 | 2016/12/29 | 4 years ago | Complete handlebars implementation in Go. |
| [kasia.go](https://github.com/ziutek/kasia.go) | 72 | 2 | 2010/12/07 | 6 years ago | Templating system for HTML and other text documents - go implementation. |
| [extemplate](https://github.com/dannyvankooten/extemplate) | 40 | 4 | 2018/08/10 | 3 months ago | Tiny wrapper around html/template to allow for easy file-based template inheritance. |
| [gospin](https://github.com/m1/gospin) | 28 | 3 | 2019/02/22 | 4 months ago | Article spinning and spintax/spinning syntax engine, useful for A/B, testing pieces of text/articles and creating more natural conversations. |
| [damsel](https://github.com/dskinner/damsel) | 24 | 4 | 2012/05/02 | 5 years ago | Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others. |

## Testing
        
*Libraries for testing codebases and generating test data.*

### Testing Frameworks
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [testify](https://github.com/stretchr/testify) | 14431 | 176 | 2012/10/16 | 3 weeks ago | Sacred extension to the standard go testing package. |
| [go-cmp](https://github.com/google/go-cmp) | 2510 | 26 | 2017/07/07 | 2 weeks ago | Package for comparing Go values in tests. |
| [httpexpect](https://github.com/gavv/httpexpect) | 1787 | 35 | 2016/04/29 | 1 month ago | Concise, declarative, and easy to use end-to-end HTTP and REST API testing. |
| [godog](https://github.com/cucumber/godog) | 1472 | 96 | 2015/06/10 | 4 days ago | Cucumber or Behat like BDD framework for Go. |
| [godog](https://github.com/DATA-DOG/godog) | 895 | 30 | 2015/06/10 | 1 year ago | Cucumber or Behat like BDD framework for Go. |
| [goblin](https://github.com/franela/goblin) | 815 | 16 | 2013/09/19 | 2 hours ago | Mocha like testing framework fo Go. |
| [go-vcr](https://github.com/dnaeon/go-vcr) | 776 | 14 | 2015/12/14 | 3 months ago | Record and replay your HTTP interactions for fast, deterministic and accurate tests. |
| [baloo](https://github.com/h2non/baloo) | 718 | 11 | 2016/05/29 | 2 years ago | Expressive and versatile end-to-end HTTP API testing made easy. |
| [testfixtures](https://github.com/go-testfixtures/testfixtures) | 704 | 6 | 2016/04/05 | 6 days ago | A helper for Rails' like test fixtures to test database applications. |
| [gnomock](https://github.com/orlangure/gnomock) | 532 | 10 | 2020/01/31 | 6 hours ago | integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks. |
| [go-mutesting](https://github.com/zimmski/go-mutesting) | 471 | 8 | 2014/12/26 | 2 days ago | Mutation testing for Go source code. |
| [goc](https://github.com/qiniu/goc) | 433 | 20 | 2020/05/07 | 1 week ago | Goc is a comprehensive coverage testing system for The Go Programming Language. |
| [gofight](https://github.com/appleboy/gofight) | 392 | 13 | 2016/03/29 | 3 months ago | API Handler Testing for Golang Router framework. |
| [embedded-postgres](https://github.com/fergusstrange/embedded-postgres) | 287 | 3 | 2019/11/16 | 5 hours ago | Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test. |
| [frisby](https://github.com/hofstadter-io/frisby) | 268 | 10 | 2015/09/15 | 1 year ago | REST API testing framework. |
| [frisby](https://github.com/verdverm/frisby) | 257 | 8 | 2015/09/15 | 1 year ago | REST API testing framework. |
| [gotest.tools](https://github.com/gotestyourself/gotest.tools) | 254 | 8 | 2017/08/08 | 2 weeks ago | A collection of packages to augment the go testing package and support common patterns. |
| [go-testdeep](https://github.com/maxatome/go-testdeep) | 219 | 2 | 2018/05/26 | 5 days ago | Extremely flexible golang deep comparison, extends the go testing package. |
| [go-carpet](https://github.com/msoap/go-carpet) | 215 | 4 | 2016/02/28 | 4 weeks ago | Tool for viewing test coverage in terminal. |
| [charlatan](https://github.com/percolate/charlatan) | 194 | 51 | 2017/10/06 | 2 years ago | Tool to generate fake interface implementations for tests. |
| [endly](https://github.com/viant/endly) | 194 | 16 | 2017/08/28 | 2 months ago | Declarative end to end functional testing. |
| [commander](https://github.com/commander-cli/commander) | 189 | 7 | 2019/02/22 | 1 month ago | Tool for testing cli applications on windows, linux and osx. |
| [cupaloy](https://github.com/bradleyjkemp/cupaloy) | 178 | 2 | 2017/08/07 | 1 week ago | Simple snapshot testing addon for your test framework. |
| [commander](https://github.com/SimonBaeumer/commander) | 154 | 9 | 2019/02/22 | 1 year ago | Tool for testing cli applications on windows, linux and osx. |
| [dbcleaner](https://github.com/khaiql/dbcleaner) | 132 | 2 | 2017/01/17 | 1 year ago | Clean database for testing purpose, inspired by `database_cleaner` in Ruby. |
| [gospec](https://github.com/luontola/gospec) | 114 | 4 | 2009/11/24 | 7 years ago | BDD-style testing framework for the Go programming language. |
| [wstest](https://github.com/posener/wstest) | 86 | 2 | 2017/03/31 | 9 months ago | Websocket client for unit-testing a websocket http.Handler. |
| [gocrest](https://github.com/corbym/gocrest) | 82 | 4 | 2017/12/23 | 9 months ago | Composable hamcrest-like matchers for Go assertions. |
| [testcase](https://github.com/adamluzsi/testcase) | 80 | 3 | 2019/04/22 | 2 weeks ago | Idiomatic testing framework for Behavior Driven Development. |
| [jsonassert](https://github.com/kinbiko/jsonassert) | 70 | 1 | 2018/10/26 | 1 month ago | Package for verifying that your JSON payloads are serialized correctly. |
| [restit](https://github.com/go-restit/restit) | 54 | 7 | 2014/06/25 | 1 year ago | Go micro framework to help writing RESTful API integration test. |
| [gospecify](https://github.com/stesla/gospecify) | 53 | 6 | 2009/11/20 | 10 years ago | This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec. |
| [go-hit](https://github.com/Eun/go-hit) | 49 | 1 | 2019/06/04 | 3 days ago | Hit is an http integration test framework written in golang. |
| [covergates](https://github.com/covergates/covergates) | 45 | 5 | 2020/05/29 | 9 months ago | Self-hosted code coverage report review and management service. |
| [gomatch](https://github.com/jfilipczyk/gomatch) | 41 | 2 | 2019/01/27 | 8 months ago | library created for testing JSON against patterns. |
| [dsunit](https://github.com/viant/dsunit) | 38 | 10 | 2016/06/13 | 1 year ago | Datastore testing for SQL, NoSQL, structured files. |
| [assert](https://github.com/go-playground/assert) | 35 | 2 | 2015/07/20 | 11 months ago | Basic Assertion Library used along side native go testing, with building blocks for custom assertions. |
| [hamcrest](https://github.com/rdrdr/hamcrest) | 26 | 3 | 2010/12/22 | 8 months ago | fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results. |
| [flute](https://github.com/suzuki-shunsuke/flute) | 16 | 0 | 2019/07/06 | 1 week ago | HTTP client testing framework. |
| [schema](https://github.com/jgroeneveld/schema) | 15 | 1 | 2015/08/13 | 2 years ago | Quick and easy expression matching for JSON schemas used in requests and responses. |
| [badio](https://github.com/cavaliercoder/badio) | 10 | 0 | 2016/02/11 | 5 years ago | Extensions to Go's `testing/iotest` package. |
| [biff](https://github.com/fulldump/biff) | 10 | 1 | 2018/03/28 | 2 months ago | Bifurcation testing framework, BDD compatible. |
| [gogiven](https://github.com/corbym/gogiven) | 10 | 5 | 2017/12/31 | 2 months ago | YATSPEC-like BDD testing framework for Go. |
| [gosuite](https://github.com/pavlo/gosuite) | 10 | 2 | 2016/10/15 | 5 years ago | Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests. |
| [testsql](https://github.com/zhulongcheng/testsql) | 10 | 2 | 2018/09/22 | 2 years ago | Generate test data from SQL files before testing and clear it after finished. |
| [badio](https://github.com/cavaliergopher/badio) | 10 | 0 | 2016/02/11 | 5 years ago | Extensions to Go's `testing/iotest` package. |
| [stop-and-go](https://github.com/elgohr/stop-and-go) | 6 | 1 | 2020/11/06 | 1 month ago | Testing helper for concurrency. |
| [trial](https://github.com/jgroeneveld/trial) | 5 | 0 | 2015/06/18 | 2 years ago | Quick and easy extendable assertions without introducing much boilerplate. |
| [tt](https://github.com/vcaesar/tt) | 5 | 1 | 2018/04/03 | 1 week ago | Simple and colorful test tools. |

### Mock
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [chromedp](https://github.com/chromedp/chromedp) | 6794 | 153 | 2017/01/24 | 1 month ago | a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol. |
| [mock](https://github.com/golang/mock) | 6229 | 84 | 2015/06/12 | 1 day ago | Mocking framework for the Go programming language. |
| [go-fuzz](https://github.com/dvyukov/go-fuzz) | 4138 | 87 | 2015/04/15 | 2 weeks ago | Randomized testing system. |
| [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) | 3822 | 37 | 2014/02/07 | 1 month ago | Mock SQL driver for testing database interactions. |
| [selenoid](https://github.com/aerokube/selenoid) | 2005 | 102 | 2016/08/22 | 3 weeks ago | alternative Selenium hub server that launches browsers within containers. |
| [rod](https://github.com/go-rod/rod) | 1846 | 29 | 2020/01/21 | 6 days ago | A Devtools driver to make web automation and scraping easy. |
| [hoverfly](https://github.com/SpectoLabs/hoverfly) | 1782 | 62 | 2015/11/30 | 1 week ago | HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI. |
| [gock](https://github.com/h2non/gock) | 1496 | 19 | 2016/03/02 | 2 months ago | Versatile HTTP mocking made easy. |
| [httpmock](https://github.com/jarcoal/httpmock) | 1196 | 9 | 2014/02/24 | 7 months ago | Easy mocking of HTTP responses from external resources. |
| [gofuzz](https://github.com/google/gofuzz) | 1155 | 26 | 2014/07/31 | 4 weeks ago | Library for populating go objects with random values. |
| [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) | 576 | 9 | 2014/05/21 | 3 days ago | Tool for generating self-contained mock objects. |
| [cdp](https://github.com/mafredri/cdp) | 573 | 18 | 2017/03/12 | 2 months ago | Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it. |
| [playwright-go](https://github.com/mxschmitt/playwright-go) | 499 | 16 | 2020/08/16 | 7 hours ago | browser automation library to control Chromium, Firefox and WebKit with a single API. |
| [minimock](https://github.com/gojuno/minimock) | 423 | 10 | 2016/08/03 | 1 week ago | Mock generator for Go interfaces. |
| [go-txdb](https://github.com/DATA-DOG/go-txdb) | 386 | 7 | 2015/07/08 | 5 months ago | Single transaction based database driver mainly for testing purposes. |
| [ggr](https://github.com/aerokube/ggr) | 274 | 26 | 2016/06/16 | 3 weeks ago | a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs. |
| [rod](https://github.com/ysmood/rod) | 273 | 8 | 2020/01/21 | 1 year ago | A chrome devtools controller that is easy and safe to use. |
| [tavor](https://github.com/zimmski/tavor) | 233 | 12 | 2014/05/18 | 2 years ago | Generic fuzzing and delta-debugging framework. |
| [govcr](https://github.com/seborama/govcr) | 98 | 2 | 2016/07/10 | 2 years ago | HTTP mock for Golang: record and replay HTTP interactions for offline testing. |
| [timex](https://github.com/cabify/timex) | 57 | 79 | 2020/01/02 | 1 year ago | A test-friendly replacement for the native `time` package. |
| [mockhttp](https://github.com/tv42/mockhttp) | 22 | 2 | 2011/06/11 | 7 years ago | Mock object for Go http.ResponseWriter. |
| [go-localstack](https://github.com/elgohr/go-localstack) | 18 | 1 | 2020/03/18 | 2 days ago | Tool for using localstack in AWS testing. |
| [mockit](https://github.com/pasdam/mockit) | 9 | 1 | 2020/01/01 | 1 week ago | Allows functions and method easy mocking, without defining new types; it's similar to Mockito for Java. |

### Fail injection
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [failpoint](https://github.com/pingcap/failpoint) | 627 | 100 | 2019/04/02 | 1 week ago | An implementation of [failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail) for Golang. |

## Text Processing
        
*Libraries for parsing and manipulating texts.*

### Specific Formats
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [colly](https://github.com/gocolly/colly) | 14935 | 322 | 2017/09/29 | 3 days ago | Fast and Elegant Scraping Framework for Gophers. |
| [goquery](https://github.com/PuerkitoBio/goquery) | 10642 | 264 | 2012/08/29 | 1 week ago | GoQuery brings a syntax and a set of features similar to jQuery to the Go language. |
| [blackfriday](https://github.com/russross/blackfriday) | 4799 | 91 | 2011/05/27 | 3 days ago | Markdown processor in Go. |
| [sh](https://github.com/mvdan/sh) | 4072 | 52 | 2016/01/16 | 1 day ago | Shell parser and formatter. |
| [toml](https://github.com/BurntSushi/toml) | 3626 | 85 | 2013/02/26 | 1 week ago | TOML configuration format (encoder/decoder with reflection). |
| [go-humanize](https://github.com/dustin/go-humanize) | 2823 | 34 | 2012/01/13 | 1 month ago | Formatters for time, numbers, and memory size to human readable format. |
| [bluemonday](https://github.com/microcosm-cc/bluemonday) | 2074 | 29 | 2013/11/20 | 1 month ago | HTML Sanitizer. |
| [gofeed](https://github.com/mmcdole/gofeed) | 1726 | 43 | 2016/01/23 | 1 month ago | Parse RSS and Atom feeds in Go. |
| [inject](https://github.com/facebookarchive/inject) | 1349 | 45 | 2013/10/21 | 2 years ago | Package inject provides a reflect based injector. |
| [go-toml](https://github.com/pelletier/go-toml) | 1112 | 32 | 2013/02/24 | 2 days ago | Go library for the TOML format with query support and handy cli tools. |
| [commonregex](https://github.com/mingrammer/commonregex) | 782 | 21 | 2017/03/23 | 1 year ago | A collection of common regular expressions for Go. |
| [slug](https://github.com/gosimple/slug) | 678 | 14 | 2014/03/31 | 4 hours ago | URL-friendly slugify with multiple languages support. |
| [mxj](https://github.com/clbanning/mxj) | 485 | 26 | 2014/02/03 | 6 months ago | Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. |
| [dataflowkit](https://github.com/slotix/dataflowkit) | 482 | 22 | 2017/02/09 | 1 year ago | Web scraping Framework to turn websites into structured data. |
| [gographviz](https://github.com/awalterschulze/gographviz) | 448 | 12 | 2015/03/14 | 1 month ago | Parses the Graphviz DOT language. |
| [htmlquery](https://github.com/antchfx/htmlquery) | 405 | 12 | 2017/12/05 | 1 week ago | An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression. |
| [go-runewidth](https://github.com/mattn/go-runewidth) | 390 | 12 | 2013/06/21 | 1 week ago | Functions to get fixed width of the character or string. |
| [omniparser](https://github.com/jf-tech/omniparser) | 383 | 9 | 2020/08/16 | 3 weeks ago | A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema. |
| [gotext](https://github.com/leonelquinteros/gotext) | 307 | 6 | 2016/06/19 | 1 week ago | GNU gettext utilities for Go. |
| [html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) | 257 | 7 | 2018/05/15 | 3 weeks ago | Convert HTML to Markdown. Even works with entire websites and can be extended through rules. |
| [goq](https://github.com/andrewstuart/goq) | 200 | 7 | 2017/02/20 | 1 month ago | Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery). |
| [goribot](https://github.com/zhshch2002/goribot) | 199 | 11 | 2019/09/08 | 1 year ago | A simple golang spider/scraping framework,build a spider in 3 lines. |
| [go-nmea](https://github.com/adrianmo/go-nmea) | 154 | 7 | 2015/07/22 | 3 weeks ago | NMEA parser library for the Go language. |
| [sdp](https://github.com/gortc/sdp) | 112 | 8 | 2016/05/13 | 1 year ago | SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)]. |
| [go-zero-width](https://github.com/trubitsyn/go-zero-width) | 96 | 1 | 2018/06/18 | 1 year ago | Zero-width character detection and removal for Go. |
| [podcast](https://github.com/eduncan911/podcast) | 95 | 5 | 2017/02/02 | 11 months ago | iTunes Compliant and RSS 2. |
| [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) | 88 | 10 | 2016/07/05 | 6 days ago | Editorconfig file parser and manipulator for Go. |
| [align](https://github.com/Guitarbum722/align) | 70 | 5 | 2017/04/29 | 3 weeks ago | A general purpose application that aligns text. |
| [go-slugify](https://github.com/mozillazg/go-slugify) | 68 | 2 | 2016/07/16 | 1 year ago | Make pretty slug with multiple languages support. |
| [genex](https://github.com/alixaxel/genex) | 61 | 3 | 2015/03/09 | 1 year ago | Count and expand Regular Expressions into all matching Strings. |
| [go-vcard](https://github.com/emersion/go-vcard) | 61 | 4 | 2017/03/21 | 4 months ago | Parse and format vCard. |
| [goregen](https://github.com/zach-klippenstein/goregen) | 59 | 2 | 2014/12/27 | 2 months ago | Library for generating random strings from regular expressions. |
| [did](https://github.com/ockam-network/did) | 55 | 15 | 2018/11/02 | 9 months ago | DID (Decentralized Identifiers) Parser and Stringer in Go. |
| [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) | 54 | 3 | 2017/11/15 | 3 months ago | Fixed-width text formatting (encoder/decoder with reflection). |
| [guesslanguage](https://github.com/endeveit/guesslanguage) | 53 | 1 | 2014/12/16 | 3 years ago | Functions to determine the natural language of a unicode text. |
| [allot](https://github.com/sbstjn/allot) | 49 | 1 | 2016/10/16 | 5 months ago | Placeholder and wildcard text parsing for CLI tools and bots. |
| [pagser](https://github.com/foolin/pagser) | 40 | 2 | 2020/04/19 | 1 year ago | Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler. |
| [gonameparts](https://github.com/polera/gonameparts) | 33 | 0 | 2015/05/17 | 2 years ago | Parses human names into individual name parts. |
| [slugify](https://github.com/avelino/slugify) | 27 | 2 | 2015/04/13 | 3 years ago | Go slugify application that handles string. |
| [codetree](https://github.com/aerogo/codetree) | 17 | 3 | 2016/11/26 | 1 year ago | Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure. |
| [enca](https://github.com/endeveit/enca) | 11 | 1 | 2014/12/17 | 5 years ago | Minimal cgo bindings for [libenca](http://cihar.com/software/enca/). |
| [syndfeed](https://github.com/zhengchun/syndfeed) | 7 | 1 | 2017/04/07 | 3 years ago | A syndication feed for Atom 1.0 and RSS 2.0. |
| [bbConvert](https://github.com/CalebQ42/bbConvert) | 6 | 1 | 2016/04/15 | 5 years ago | Converts bbCode to HTML that allows you to add support for custom bbCode tags. |
| [doi](https://github.com/hscells/doi) | 6 | 1 | 2017/08/02 | 4 years ago | Document object identifier (doi) parser in Go. |
| [ltsv](https://github.com/Wing924/ltsv) | 5 | 1 | 2019/05/12 | 2 years ago | High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go. |
| [encoding](https://github.com/mickep76/encoding) | 4 | 1 | 2018/04/06 | 1 year ago | Package provides a generic interface to encoders and decodersa. |
| [encoding](https://github.com/ake-persson/encoding) | 4 | 1 | 2018/04/06 | 1 year ago | Package provides a generic interface to encoders and decodersa. |

### Utility
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [xurls](https://github.com/mvdan/xurls) | 828 | 18 | 2015/01/12 | 2 days ago | Extract urls from text. |
| [gotabulate](https://github.com/bndr/gotabulate) | 270 | 9 | 2014/08/21 | 7 months ago | Easily pretty-print your tabular data with Go. |
| [radix](https://github.com/yourbasic/radix) | 172 | 7 | 2017/06/09 | 3 years ago | fast string sorting algorithm. |
| [regroup](https://github.com/oriser/regroup) | 93 | 1 | 2020/09/08 | 2 months ago | Match regex expression named groups into go struct using struct tags and automatic parsing. |
| [parth](https://github.com/codemodus/parth) | 40 | 4 | 2015/04/06 | 2 years ago | URL path segmentation parsing. |
| [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) | 39 | 2 | 2018/09/09 | 3 months ago | A sanitization-based swear filter for Go. |
| [xj2go](https://github.com/wk30/xj2go) | 21 | 2 | 2017/09/19 | 1 year ago | Convert xml or json to go struct. |
| [xj2go](https://github.com/stackerzzq/xj2go) | 19 | 2 | 2017/09/19 | 1 year ago | Convert xml or json to go struct. |
| [tagify](https://github.com/zoomio/tagify) | 18 | 2 | 2018/03/20 | 1 month ago | Produces a set of tags from given source. |
| [kace](https://github.com/codemodus/kace) | 17 | 2 | 2015/06/04 | 3 years ago | Common case conversions covering common initialisms. |
| [TySug](https://github.com/Dynom/TySug) | 10 | 1 | 2018/06/05 | 1 year ago | Alternative suggestions with respect to keyboard layouts. |
| [parseargs-go](https://github.com/txgruppi/parseargs-go) | 8 | 0 | 2016/02/24 | 4 years ago | string argument parser that understands quotes and backslashes. |
| [textwrap](https://github.com/isbm/textwrap) | 2 | 2 | 2019/07/26 | 2 years ago | Implementation of `textwrap` module from Python. |

## Third-party APIs
        
*Libraries for accessing third party APIs.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-github](https://github.com/google/go-github) | 7809 | 212 | 2013/05/24 | 3 days ago | Go library for accessing the GitHub REST API v3. |
| [aws-sdk-go](https://github.com/aws/aws-sdk-go) | 7147 | 260 | 2014/12/05 | 1 day ago | The official AWS SDK for the Go programming language. |
| [google-api-go-client](https://github.com/googleapis/google-api-go-client) | 2782 | 163 | 2014/11/24 | 21 hours ago | Auto-generated Google APIs for Go. |
| [google-cloud-go](https://github.com/googleapis/google-cloud-go) | 2662 | 241 | 2014/05/09 | 19 hours ago | Google Cloud APIs Go Client Library. |
| [discordgo](https://github.com/bwmarrin/discordgo) | 2380 | 55 | 2015/11/01 | 4 hours ago | Go bindings for the Discord Chat API. |
| [stripe-go](https://github.com/stripe/stripe-go) | 1435 | 41 | 2014/06/05 | 4 days ago | Go client for the Stripe API. |
| [minio-go](https://github.com/minio/minio-go) | 1418 | 47 | 2015/05/02 | 29 minutes ago | Minio Go Library for Amazon S3 compatible cloud storage. |
| [go-twitter](https://github.com/dghubble/go-twitter) | 1314 | 28 | 2015/04/11 | 19 hours ago | Go client library for the Twitter v1.1 APIs. |
| [anaconda](https://github.com/ChimeraCoder/anaconda) | 1103 | 22 | 2013/03/04 | 2 months ago | Go client library for the Twitter 1.1 API. |
| [facebook](https://github.com/huandu/facebook) | 1003 | 118 | 2012/07/28 | 5 months ago | Go Library that supports the Facebook Graph API. |
| [githubv4](https://github.com/shurcooL/githubv4) | 813 | 21 | 2017/05/27 | 2 days ago | Go library for accessing the GitHub GraphQL API v4. |
| [webhooks](https://github.com/go-playground/webhooks) | 659 | 15 | 2015/10/25 | 1 month ago | Webhook receiver for GitHub and Bitbucket. |
| [paypal](https://github.com/plutov/paypal) | 444 | 24 | 2015/10/14 | 5 days ago | Wrapper for PayPal payment API. |
| [geo-golang](https://github.com/codingsince1985/geo-golang) | 413 | 13 | 2014/12/04 | 1 month ago | Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs. |
| [ethrpc](https://github.com/onrik/ethrpc) | 214 | 14 | 2017/01/24 | 1 year ago | Go bindings for Ethereum JSON RPC API. |
| [go-marathon](https://github.com/gambol99/go-marathon) | 196 | 14 | 2015/02/11 | 1 year ago | Go library for interacting with Mesosphere's Marathon PAAS. |
| [trello](https://github.com/adlio/trello) | 183 | 6 | 2016/09/24 | 3 months ago | Go wrapper for the Trello API. |
| [twitter-scraper](https://github.com/n0madic/twitter-scraper) | 143 | 4 | 2018/11/29 | 3 days ago | Scrape the Twitter Frontend API without authentication and limits. |
| [medium-sdk-go](https://github.com/Medium/medium-sdk-go) | 131 | 133 | 2015/09/26 | 2 years ago | Golang SDK for Medium's OAuth2 API. |
| [gostorm](https://github.com/jsgilmore/gostorm) | 127 | 11 | 2013/07/22 | 4 years ago | GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. |
| [go-trending](https://github.com/andygrunwald/go-trending) | 116 | 7 | 2015/07/04 | 2 months ago | Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github. |
| [wit-go](https://github.com/wit-ai/wit-go) | 112 | 19 | 2018/08/20 | 1 month ago | Go client for wit.ai HTTP API. |
| [hipchat](https://github.com/daneharrigan/hipchat) | 111 | 7 | 2013/04/28 | 4 years ago | A golang package to communicate with HipChat over XMPP. |
| [hipchat](https://github.com/andybons/hipchat) | 105 | 6 | 2012/10/20 | 5 years ago | This project implements a golang client library for the Hipchat API. |
| [pushover](https://github.com/gregdel/pushover) | 103 | 4 | 2015/02/19 | 4 months ago | Go wrapper for the Pushover API. |
| [cachet](https://github.com/andygrunwald/cachet) | 88 | 7 | 2015/10/31 | 3 months ago | Go client library for [Cachet (open source status page system)](https://cachethq.io/). |
| [igdb](https://github.com/Henry-Sarabia/igdb) | 69 | 2 | 2017/08/24 | 6 months ago | Go client for the [Internet Game Database API](https://api.igdb.com/). |
| [gosip](https://github.com/koltyakov/gosip) | 64 | 4 | 2019/01/26 | 2 weeks ago | Go client library SharePoint API. |
| [go-circleci](https://github.com/jszwedko/go-circleci) | 60 | 3 | 2015/08/14 | 1 year ago | Go client library for interacting with CircleCI's API. |
| [simples3](https://github.com/rhnvrm/simples3) | 60 | 2 | 2018/12/06 | 2 months ago | Simple no frills AWS S3 Library using REST with V4 Signing written in Go. |
| [gogtrends](https://github.com/groovili/gogtrends) | 58 | 1 | 2018/12/27 | 3 weeks ago | Google Trends Unofficial API. |
| [go-unsplash](https://github.com/hbagdi/go-unsplash) | 56 | 2 | 2017/01/19 | 6 months ago | Go client library for the [Unsplash.com](https://unsplash.com) API. |
| [clarifai-go](https://github.com/Clarifai/clarifai-go) | 55 | 38 | 2015/09/28 | 4 years ago | Go client library for interfacing with the Clarifai API. |
| [megos](https://github.com/andygrunwald/megos) | 54 | 5 | 2015/10/02 | 3 months ago | Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster. |
| [go-amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) | 49 | 1 | 2016/11/15 | 3 years ago | Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html). |
| [gads](https://github.com/emiddleton/gads) | 49 | 7 | 2014/01/20 | 2 years ago | Google Adwords Unofficial API. |
| [ynab.go](https://github.com/brunomvsouza/ynab.go) | 48 | 2 | 2018/07/13 | 2 weeks ago | Go wrapper for the YNAB API. |
| [uptimerobot](https://github.com/bitfield/uptimerobot) | 46 | 4 | 2018/05/29 | 9 months ago | Go wrapper and command-line client for the Uptime Robot v2 API. |
| [go-xkcd](https://github.com/nishanths/go-xkcd) | 45 | 3 | 2016/02/26 | 7 months ago | Go client for the xkcd API. |
| [gomusicbrainz](https://github.com/michiwend/gomusicbrainz) | 44 | 6 | 2014/09/10 | 7 months ago | Go MusicBrainz WS2 client library. |
| [golang-tmdb](https://github.com/cyruzin/golang-tmdb) | 43 | 1 | 2019/01/11 | 23 hours ago | Golang wrapper for The Movie Database API v3. |
| [mixpanel](https://github.com/dukex/mixpanel) | 42 | 4 | 2014/05/20 | 1 month ago | Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications. |
| [fcm](https://github.com/maddevsio/fcm) | 41 | 5 | 2017/01/06 | 1 year ago | Go library for Firebase Cloud Messaging. |
| [go-spotify](https://github.com/rapito/go-spotify) | 38 | 2 | 2014/10/30 | 10 months ago | Go Library to access Spotify WEB API. |
| [golyrics](https://github.com/mamal72/golyrics) | 36 | 4 | 2016/11/18 | 3 years ago | Golyrics is a Go library to fetch music lyrics data from the Wikia website. |
| [translate](https://github.com/nuveo/translate) | 31 | 32 | 2015/07/13 | 5 years ago | Go online translation package. |
| [go-postman-collection](https://github.com/rbretecher/go-postman-collection) | 31 | 2 | 2019/11/16 | 1 month ago | Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia). |
| [gami](https://github.com/bit4bit/gami) | 30 | 4 | 2014/05/14 | 3 years ago | Go library for Asterisk Manager Interface. |
| [gcm](https://github.com/TheOrioli/gcm) | 29 | 3 | 2015/11/09 | 5 years ago | Go library for Google Cloud Messaging. |
| [airtable](https://github.com/mehanizm/airtable) | 28 | 1 | 2020/04/12 | 1 day ago | Go client library for the [Airtable API](https://airtable.com/api). |
| [patreon-go](https://github.com/mxpv/patreon-go) | 26 | 4 | 2017/08/06 | 2 years ago | Go library for Patreon API. |
| [go-myanimelist](https://github.com/nstratos/go-myanimelist) | 23 | 1 | 2015/05/03 | 3 weeks ago | Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api). |
| [go-steam](https://github.com/sostronk/go-steam) | 23 | 11 | 2014/11/23 | 3 weeks ago | Go Library to interact with Steam game servers. |
| [lastpass-go](https://github.com/ansd/lastpass-go) | 22 | 3 | 2019/07/11 | 2 weeks ago | Go client library for the [LastPass](https://www.lastpass.com/) API. |
| [go-twitch](https://github.com/knspriggs/go-twitch) | 21 | 5 | 2016/06/28 | 4 years ago | Go client for interacting with the Twitch v3 API. |
| [go-shopify](https://github.com/rapito/go-shopify) | 21 | 1 | 2014/10/28 | 10 months ago | Go Library to make CRUD request to the Shopify API. |
| [textbelt](https://github.com/farmergreg/textbelt) | 18 | 2 | 2015/09/01 | 6 years ago | Go client for the textbelt.com txt messaging API. |
| [google-play-scraper](https://github.com/n0madic/google-play-scraper) | 18 | 1 | 2019/09/20 | 1 week ago | Get data from Google Play Store. |
| [brewerydb](https://github.com/naegelejd/brewerydb) | 17 | 3 | 2015/04/15 | 6 years ago | Go library for accessing the BreweryDB API. |
| [codeship-go](https://github.com/codeship/codeship-go) | 17 | 20 | 2017/09/08 | 11 months ago | Go client library for interacting with Codeship's API v2. |
| [coinpaprika-api-go-client](https://github.com/coinpaprika/coinpaprika-api-go-client) | 13 | 8 | 2018/09/25 | 1 year ago | Go client library for interacting with Coinpaprika's API. |
| [go-hacknews](https://github.com/PaulRosset/go-hacknews) | 13 | 2 | 2017/08/10 | 4 years ago | Tiny Go client for HackerNews API. |
| [go-google-analytics](https://github.com/chonthu/go-google-analytics) | 12 | 2 | 2015/06/01 | 6 years ago | Simple wrapper for easy google analytics reporting. |
| [go-aws-news](https://github.com/circa10a/go-aws-news) | 12 | 3 | 2020/01/08 | 1 month ago | Go application and library to fetch what's new from AWS. |
| [go-here](https://github.com/abdullahselek/go-here) | 10 | 0 | 2019/07/07 | 1 year ago | Go client library around the HERE location based APIs. |
| [smitego](https://github.com/sergiotapia/smitego) | 10 | 0 | 2013/12/11 | 7 years ago | Go package to wraps access to the Smite game API. |
| [gopaapi5](https://github.com/utekaravinash/gopaapi5) | 10 | 3 | 2020/02/15 | 1 year ago | Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/). |
| [device-check-go](https://github.com/rinchsan/device-check-go) | 10 | 1 | 2019/04/11 | 1 week ago | Go client library for interacting with [iOS DeviceCheck API](https://developer.apple.com/documentation/devicecheck) v1. |
| [go-sophos](https://github.com/esurdam/go-sophos) | 8 | 2 | 2018/09/05 | 1 year ago | Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies. |
| [rrdaclient](https://github.com/Omie/rrdaclient) | 8 | 2 | 2014/09/15 | 7 years ago | Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP. |
| [slack](https://github.com/nlopes/slack) | 8 | 0 | 2015/01/24 | 4 months ago | Slack API in Go. |
| [go-google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) | 7 | 0 | 2016/10/24 | 5 years ago | Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/). |
| [go-sptrans](https://github.com/sergioaugrod/go-sptrans) | 6 | 3 | 2017/09/11 | 1 year ago | Go client library for the SPTrans Olho Vivo API. |
| [gumblr](https://github.com/mattcunningham/gumblr) | 6 | 1 | 2015/07/09 | 4 years ago | Go wrapper for the Tumblr v2 API. |
| [go-zooz](https://github.com/gojuno/go-zooz) | 6 | 14 | 2017/07/04 | 3 months ago | Go client for the Zooz API. |
| [go-chronos](https://github.com/axelspringer/go-chronos) | 4 | 9 | 2017/10/23 | 3 years ago | Go library for interacting with the [Chronos](https://mesos.github. |
| [libgoffi](https://github.com/clevabit/libgoffi) | 3 | 12 | 2019/08/03 | 1 year ago | Library adapter toolbox for native [libffi](http://sourceware. |
| [kanka](https://github.com/Henry-Sarabia/kanka) | 3 | 3 | 2019/12/26 | 1 year ago | Go client for the [Kanka API](https://kanka.io/en-US/docs/1.0). |
| [rawg-sdk-go](https://github.com/dimuska139/rawg-sdk-go) | 3 | 1 | 2020/10/16 | 2 months ago | Go library for the [RAWG Video Games Database](https://rawg. |
| [playlyfe-go-sdk](https://github.com/playlyfe/playlyfe-go-sdk) | 1 | 5 | 2015/05/25 | 5 years ago | The Playlyfe Rest API Go SDK. |
| [tripadvisor-golang](https://github.com/mrbenosborne/tripadvisor-golang) | 1 | 2 | 2019/04/15 | 1 year ago | Go wrapper for the TripAdvisor API. |
| [vl-go](https://github.com/verifid/vl-go) | 1 | 2 | 2019/02/09 | 4 months ago | Go client library around the VerifID identity verification layer API. |

## Utilities
        
*General utilities and tools to make your life easier.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fzf](https://github.com/junegunn/fzf) | 39470 | 394 | 2013/10/23 | 21 hours ago | Command-line fuzzy finder written in Go. |
| [hub](https://github.com/github/hub) | 21259 | 501 | 2009/12/05 | 2 days ago | wrap git commands with additional functionality to interact with github from the terminal. |
| [delve](https://github.com/go-delve/delve) | 13355 | 387 | 2014/05/20 | 1 year ago | Go debugger. |
| [ctop](https://github.com/bcicen/ctop) | 11978 | 165 | 2016/12/27 | 2 months ago | [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics. |
| [sqlx](https://github.com/jmoiron/sqlx) | 10867 | 192 | 2013/01/28 | 10 hours ago | provides a set of extensions on top of the excellent built-in database/sql package. |
| [wuzz](https://github.com/asciimoo/wuzz) | 9777 | 168 | 2017/01/30 | 1 month ago | Interactive cli tool for HTTP inspection. |
| [goreleaser](https://github.com/goreleaser/goreleaser) | 8769 | 110 | 2016/12/21 | 24 minutes ago | Deliver Go binaries as fast and easily as possible. |
| [usql](https://github.com/xo/usql) | 6782 | 115 | 2017/03/02 | 5 days ago | usql is a universal command-line interface for SQL databases. |
| [peco](https://github.com/peco/peco) | 6531 | 137 | 2014/06/06 | 2 months ago | Simplistic interactive filtering tool. |
| [godropbox](https://github.com/dropbox/godropbox) | 3975 | 246 | 2014/06/22 | 1 year ago | Common libraries for writing Go services/applications from Dropbox. |
| [hystrix-go](https://github.com/afex/hystrix-go) | 3391 | 91 | 2013/12/15 | 2 weeks ago | Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker. |
| [go-funk](https://github.com/thoas/go-funk) | 2916 | 37 | 2016/12/30 | 1 week ago | Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...). |
| [goreporter](https://github.com/qax-os/goreporter) | 2916 | 101 | 2017/03/27 | 2 years ago | Golang tool that does static analysis, unit testing, code review and generate code quality report. |
| [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) | 2890 | 101 | 2017/03/27 | 2 years ago | Golang tool that does static analysis, unit testing, code review and generate code quality report. |
| [minify](https://github.com/tdewolff/minify) | 2769 | 57 | 2014/05/21 | 1 day ago | Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats. |
| [panicparse](https://github.com/maruel/panicparse) | 2731 | 37 | 2015/02/02 | 2 weeks ago | Groups similar goroutines and colorizes stack dump. |
| [mc](https://github.com/minio/mc) | 1914 | 53 | 2015/01/16 | 1 day ago | Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems. |
| [storm](https://github.com/asdine/storm) | 1787 | 42 | 2016/01/10 | 4 months ago | Simple and powerful toolkit for BoltDB. |
| [mergo](https://github.com/imdario/mergo) | 1721 | 25 | 2013/03/11 | 1 week ago | Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements. |
| [spinner](https://github.com/briandowns/spinner) | 1584 | 16 | 2014/12/13 | 3 months ago | Go package to easily provide a terminal spinner with options. |
| [mole](https://github.com/davrodpin/mole) | 1503 | 29 | 2018/10/04 | 19 hours ago | cli app to easily create ssh tunnels. |
| [filetype](https://github.com/h2non/filetype) | 1412 | 30 | 2015/09/24 | 2 weeks ago | Small package to infer the file type checking the magic numbers signature. |
| [boilr](https://github.com/tmrts/boilr) | 1391 | 30 | 2015/12/19 | 2 months ago | Blazingly fast CLI tool for creating projects from boilerplate templates. |
| [jump](https://github.com/gsamokovarov/jump) | 1246 | 19 | 2015/08/16 | 3 months ago | Jump helps you navigate faster by learning your habits. |
| [circuitbreaker](https://github.com/rubyist/circuitbreaker) | 961 | 21 | 2014/07/17 | 1 year ago | Circuit Breakers in Go. |
| [gtm](https://github.com/git-time-metric/gtm) | 881 | 30 | 2016/06/19 | 1 year ago | Simple, seamless, lightweight time tracking for Git. |
| [cli](https://github.com/create-go-app/cli) | 866 | 14 | 2019/12/30 | 1 week ago | A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command. |
| [immortal](https://github.com/immortal/immortal) | 718 | 19 | 2016/06/30 | 1 year ago | \*nix cross-platform (OS agnostic) supervisor. |
| [hostctl](https://github.com/guumaster/hostctl) | 679 | 9 | 2020/03/14 | 2 months ago | A CLI tool to manage /etc/hosts with easy commands. |
| [circuit](https://github.com/cep21/circuit) | 599 | 14 | 2017/12/23 | 1 month ago | An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern. |
| [mimetype](https://github.com/gabriel-vasile/mimetype) | 588 | 9 | 2018/07/02 | 1 week ago | Package for MIME type detection based on magic numbers. |
| [htcat](https://github.com/htcat/htcat) | 535 | 19 | 2013/08/05 | 2 years ago | Parallel and Pipelined HTTP GET Utility. |
| [ergo](https://github.com/cristianoliveira/ergo) | 480 | 6 | 2017/08/19 | 2 months ago | The management of multiple local services running over different ports made easy. |
| [godaemon](https://github.com/VividCortex/godaemon) | 480 | 29 | 2013/08/01 | 3 months ago | Utility to write daemons. |
| [koazee](https://github.com/wesovilabs/koazee) | 473 | 11 | 2018/11/09 | 10 months ago | Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays. |
| [go-dry](https://github.com/ungerik/go-dry) | 468 | 15 | 2014/02/28 | 7 months ago | DRY (don't repeat yourself) package for Go. |
| [gopencils](https://github.com/bndr/gopencils) | 436 | 14 | 2014/06/23 | 2 years ago | Small and simple package to easily consume REST APIs. |
| [request](https://github.com/mozillazg/request) | 400 | 15 | 2014/12/21 | 1 year ago | Go HTTP Requests for Humans™. |
| [scany](https://github.com/georgysavva/scany) | 400 | 6 | 2020/07/02 | 1 month ago | Library for scanning data from a database into Go structs and more. |
| [delve](https://github.com/derekparker/delve) | 391 | 10 | 2020/02/18 | 1 week ago | Go debugger. |
| [gubrak](https://github.com/novalagung/gubrak) | 369 | 7 | 2018/03/09 | 1 year ago | Golang utility library with syntactic sugar. It's like lodash, but for golang. |
| [deepcopier](https://github.com/ulule/deepcopier) | 361 | 22 | 2015/07/24 | 1 year ago | Simple struct copying for Go. |
| [clockwork](https://github.com/jonboulle/clockwork) | 352 | 6 | 2014/09/09 | 1 year ago | A simple fake clock for golang. |
| [go-rate](https://github.com/beefsack/go-rate) | 340 | 11 | 2014/08/25 | 1 year ago | Timed rate limiter for Go. |
| [retry](https://github.com/kamilsk/retry) | 309 | 6 | 2016/11/02 | 7 months ago | The most advanced functional mechanism to perform actions repetitively until successful. |
| [gohper](https://github.com/cosiner/gohper) | 255 | 20 | 2015/03/23 | 4 years ago | Various tools/modules help for development. |
| [gohper](https://github.com/zhuah/gohper) | 252 | 20 | 2015/03/23 | 4 years ago | Various tools/modules help for development. |
| [serve](https://github.com/syntaqx/serve) | 249 | 7 | 2019/01/10 | 2 months ago | A static http server anywhere you need. |
| [scan](https://github.com/blockloop/scan) | 229 | 5 | 2017/11/27 | 3 months ago | Scan golang `sql.Rows` directly to structs, slices, or primitive types. |
| [go-trigger](https://github.com/sadlil/go-trigger) | 224 | 13 | 2015/10/19 | 4 years ago | Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project. |
| [util](https://github.com/shomali11/util) | 217 | 12 | 2017/05/24 | 1 year ago | Collection of useful utility functions. (strings, concurrency, manipulations, ...). |
| [gotenv](https://github.com/subosito/gotenv) | 205 | 3 | 2013/08/27 | 1 week ago | Load environment variables from `.env` or any `io.Reader` in Go. |
| [death](https://github.com/vrecan/death) | 174 | 3 | 2015/03/09 | 5 months ago | Managing go application shutdown with signals. |
| [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) | 171 | 5 | 2016/11/08 | 2 years ago | go:generate tool for wrapping symbols exported by golang plugins (1.8 only). |
| [toolbox](https://github.com/viant/toolbox) | 166 | 16 | 2016/06/13 | 1 month ago | Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer. |
| [rerun](https://github.com/ivpusic/rerun) | 162 | 7 | 2014/12/10 | 3 years ago | Recompiling and rerunning go apps when source changes. |
| [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) | 161 | 6 | 2015/10/12 | 1 month ago | XML Sitemap generator written in Go. |
| [moldova](https://github.com/StabbyCutyou/moldova) | 161 | 5 | 2016/01/30 | 4 years ago | Utility for generating random data based on an input template. |
| [apm](https://github.com/topfreegames/apm) | 155 | 19 | 2015/11/18 | 4 years ago | Process manager for Golang applications with an HTTP API. |
| [robustly](https://github.com/VividCortex/robustly) | 150 | 16 | 2013/07/08 | 5 months ago | Runs functions resiliently, catching and restarting panics. |
| [chyle](https://github.com/antham/chyle) | 139 | 7 | 2016/11/17 | 1 week ago | Changelog generator using a git repository with multiple configuration possibilities. |
| [changie](https://github.com/miniscruff/changie) | 126 | 3 | 2020/12/05 | 6 days ago | Automated changelog tool for preparing releases with lots of customization options. |
| [onecache](https://github.com/adelowo/onecache) | 124 | 7 | 2017/04/14 | 1 year ago | Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc). |
| [go-bsdiff](https://github.com/gabstv/go-bsdiff) | 123 | 3 | 2019/02/23 | 2 years ago | Pure Go bsdiff and bspatch libraries and CLI tools. |
| [countries](https://github.com/biter777/countries) | 123 | 6 | 2019/04/22 | 2 months ago | Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standarts. |
| [lrserver](https://github.com/jaschaephraim/lrserver) | 119 | 5 | 2014/07/15 | 3 years ago | LiveReload server for Go. |
| [go-pattern-match](https://github.com/alexpantyukhin/go-pattern-match) | 92 | 2 | 2018/12/11 | 1 year ago | Pattern matching libray. |
| [mssqlx](https://github.com/linxGnu/mssqlx) | 89 | 9 | 2016/12/26 | 2 weeks ago | Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind. |
| [nostromo](https://github.com/pokanop/nostromo) | 89 | 5 | 2019/07/13 | 9 months ago | CLI for building powerful aliases. |
| [goseaweedfs](https://github.com/linxGnu/goseaweedfs) | 88 | 8 | 2017/07/20 | 2 months ago | SeaweedFS client library with almost full features. |
| [xferspdy](https://github.com/monmohan/xferspdy) | 88 | 4 | 2015/05/22 | 6 months ago | Xferspdy provides binary diff and patch library in golang. |
| [sorty](https://github.com/jfcg/sorty) | 84 | 4 | 2019/02/18 | 6 days ago | Fast Concurrent / Parallel Sorting. |
| [go-health](https://github.com/Talento90/go-health) | 83 | 3 | 2018/02/13 | 3 years ago | Health package simplifies the way you add health check to your services. |
| [pm](https://github.com/VividCortex/pm) | 78 | 18 | 2013/11/17 | 9 months ago | Process (i.e. goroutine) manager with an HTTP API. |
| [repeat](https://github.com/ssgreg/repeat) | 77 | 5 | 2017/11/22 | 1 year ago | Go implementation of different backoff strategies useful for retrying operations and heartbeating. |
| [mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) | 74 | 3 | 2020/02/04 | 1 month ago | Mongodb Pagination for official mongodb/mongo-go-driver package which supports  both normal queries and Aggregation pipelines. |
| [netbug](https://github.com/e-dard/netbug) | 69 | 2 | 2015/03/05 | 6 years ago | Easy remote profiling of your services. |
| [mimemagic](https://github.com/zRedShift/mimemagic) | 67 | 2 | 2018/10/11 | 6 months ago | Pure Go ultra performant MIME sniffing library/utility. |
| [unis](https://github.com/esemplastic/unis) | 67 | 4 | 2017/05/06 | 4 years ago | Common Architecture™ for String Utilities in Go. |
| [handy](https://github.com/miguelpragier/handy) | 66 | 8 | 2018/06/13 | 1 year ago | Many utilities and helpers like string handlers/formatters and validators. |
| [multitick](https://github.com/VividCortex/multitick) | 66 | 16 | 2013/12/10 | 5 months ago | Multiplexor for aligned tickers. |
| [cmd](https://github.com/commander-cli/cmd) | 65 | 6 | 2019/09/27 | 1 year ago | Library for executing shell commands on osx, windows and linux. |
| [goreadability](https://github.com/philipjkim/goreadability) | 60 | 6 | 2016/04/20 | 2 years ago | Webpage summary extractor using Facebook Open Graph and arc90's readability. |
| [go-astitodo](https://github.com/asticode/go-astitodo) | 59 | 2 | 2016/10/17 | 1 year ago | Parse TODOs in your GO code. |
| [minquery](https://github.com/icza/minquery) | 59 | 2 | 2016/11/16 | 2 months ago | MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off). |
| [golog](https://github.com/mlimaloureiro/golog) | 55 | 3 | 2016/01/09 | 2 years ago | Easy and lightweight CLI tool to time track your tasks. |
| [pgo](https://github.com/arthurkushman/pgo) | 55 | 6 | 2018/12/26 | 1 week ago | Convenient functions for PHP community. |
| [copy-pasta](https://github.com/jutkko/copy-pasta) | 49 | 5 | 2017/01/28 | 1 year ago | Universal multi-workstation clipboard that uses S3 like backend for the storage. |
| [retry](https://github.com/thedevsaddam/retry) | 49 | 1 | 2018/02/25 | 8 months ago | Simple and easy retry mechanism package for Go. |
| [go-lock](https://github.com/viney-shih/go-lock) | 49 | 1 | 2020/04/30 | 2 months ago | go-lock is a lock library implementing read-write mutex and read-write trylock without starvation. |
| [beyond](https://github.com/wesovilabs/beyond) | 47 | 1 | 2019/10/18 | 5 days ago | The Go tool that will drive you to the AOP world! |
| [filter](https://github.com/gookit/filter) | 47 | 6 | 2018/09/26 | 2 months ago | provide filtering, sanitizing, and conversion of Go data. |
| [golarm](https://github.com/msempere/golarm) | 45 | 2 | 2015/08/14 | 6 years ago | Fire alarms with system events. |
| [limiters](https://github.com/mennanov/limiters) | 45 | 3 | 2019/08/28 | 1 month ago | Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks. |
| [dbt](https://github.com/nikogura/dbt) | 44 | 1 | 2017/11/30 | 7 months ago | A framework for running self-updating signed binaries from a central, trusted repository. |
| [goback](https://github.com/carlescere/goback) | 44 | 1 | 2015/03/13 | 6 months ago | Go simple exponential backoff package. |
| [slice](https://github.com/psampaz/slice) | 44 | 2 | 2019/11/26 | 1 year ago | Type-safe functions for common Go slice operations. |
| [intrinsic](https://github.com/mengzhuo/intrinsic) | 42 | 4 | 2017/06/13 | 4 years ago | Use x86 SIMD without writing any assembly code. |
| [retry-go](https://github.com/rafaeljesus/retry-go) | 42 | 2 | 2017/06/09 | 2 years ago | Retrying made simple and easy for golang. |
| [gpath](https://github.com/tenntenn/gpath) | 40 | 3 | 2017/05/24 | 4 years ago | Library to simplify access struct fields with Go's expression in reflection. |
| [go-httpheader](https://github.com/mozillazg/go-httpheader) | 36 | 3 | 2017/06/24 | 8 months ago | Go library for encoding structs into Header fields. |
| [myhttp](https://github.com/inancgumus/myhttp) | 35 | 0 | 2017/09/13 | 3 years ago | Simple API to make HTTP GET requests with timeout support. |
| [evaluator](https://github.com/nullne/evaluator) | 33 | 2 | 2017/04/27 | 2 months ago | Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend. |
| [equalizer](https://github.com/reugn/equalizer) | 33 | 2 | 2019/06/14 | 7 months ago | Quota manager and rate limiter collection for Go. |
| [gostrutils](https://github.com/ik5/gostrutils) | 32 | 3 | 2018/09/19 | 3 weeks ago | Collections of string manipulation and conversion functions. |
| [rclient](https://github.com/zpatrick/rclient) | 32 | 3 | 2017/02/28 | 1 year ago | Readable, flexible, simple-to-use client for REST APIs. |
| [backscanner](https://github.com/icza/backscanner) | 30 | 4 | 2017/10/18 | 2 months ago | A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. |
| [slicer](https://github.com/leaanthony/slicer) | 28 | 2 | 2019/01/10 | 1 month ago | Makes working with slices easier. |
| [tome](https://github.com/cyruzin/tome) | 28 | 1 | 2019/04/12 | 1 year ago | Tome was designed to paginate simple RESTful APIs. |
| [cmd](https://github.com/SimonBaeumer/cmd) | 25 | 2 | 2019/09/27 | 1 year ago | Library for executing shell commands on osx, windows and linux. |
| [ugo](https://github.com/alxrm/ugo) | 25 | 2 | 2016/02/17 | 5 years ago | ugo is slice toolbox with concise syntax for Go. |
| [generate](https://github.com/go-playground/generate) | 24 | 3 | 2015/11/15 | 4 years ago | runs go generate recursively on a specified path or environment variable and can filter by regex. |
| [goplaceholder](https://github.com/michiwend/goplaceholder) | 22 | 2 | 2014/10/12 | 5 years ago | a small golang lib to generate placeholder images. |
| [shutdown](https://github.com/ztrue/shutdown) | 22 | 1 | 2018/11/17 | 2 years ago | App shutdown hooks for `os.Signal` handling. |
| [rerate](https://github.com/abo/rerate) | 21 | 4 | 2016/05/24 | 4 years ago | Redis-based rate counter and rate limiter for Go. |
| [ghokin](https://github.com/antham/ghokin) | 20 | 3 | 2018/08/03 | 1 week ago | Parallelized formatter with no external dependencies for gherkin (cucumber, behat...). |
| [ctxutil](https://github.com/posener/ctxutil) | 18 | 1 | 2018/07/30 | 1 year ago | A collection of utility functions for contexts. |
| [structs](https://github.com/PumpkinSeed/structs) | 18 | 3 | 2017/08/26 | 4 years ago | Implement simple functions to manipulate structs. |
| [r](https://github.com/is5/r) | 18 | 3 | 2020/02/20 | 1 year ago | Python-like `range()` experience for Go. |
| [mimesniffer](https://github.com/aofei/mimesniffer) | 17 | 1 | 2018/12/20 | 7 months ago | A MIME type sniffer for Go. |
| [dlog](https://github.com/kirillDanshin/dlog) | 16 | 2 | 2016/07/04 | 4 years ago | Compile-time controlled logger to make your release smaller without removing debug calls. |
| [filler](https://github.com/yaronsumel/filler) | 16 | 1 | 2017/04/05 | 4 years ago | small utility to fill structs using "fill" tag. |
| [okrun](https://github.com/xta/okrun) | 15 | 3 | 2014/10/01 | 7 years ago | go run error steamroller. |
| [command](https://github.com/txgruppi/command) | 14 | 1 | 2015/08/24 | 5 years ago | Command pattern for Go with thread safe serial and parallel dispatcher. |
| [rest-go](https://github.com/edermanoel94/rest-go) | 14 | 3 | 2019/07/29 | 1 year ago | A package that provide many helpful methods for working with rest api. |
| [jsend](https://github.com/clevergo/jsend) | 14 | 4 | 2020/01/14 | 3 months ago | JSend's implementation writen in Go. |
| [go-convert](https://github.com/Eun/go-convert) | 12 | 1 | 2019/06/07 | 4 months ago | Package go-convert enbles you to convert a value into another type. |
| [ptr](https://github.com/gotidy/ptr) | 11 | 2 | 2019/12/25 | 11 months ago | Package that provide functions for simplified creation of pointers from constants of basic types. |
| [retry](https://github.com/shafreeck/retry) | 11 | 0 | 2018/07/18 | 1 year ago | A pretty simple library to ensure your work to be done. |
| [copy](https://github.com/gotidy/copy) | 11 | 3 | 2020/10/09 | 9 months ago | Package for fast copying structs of different types. |
| [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) | 10 | 1 | 2019/05/16 | 1 year ago | Go package for working with Problem Details. |
| [silk](https://github.com/chrispassas/silk) | 10 | 1 | 2018/12/18 | 10 months ago | Read silk netflow files. |
| [go-countries](https://github.com/mikekonan/go-countries) | 9 | 3 | 2020/10/27 | 9 months ago | Lightweight lookup over ISO-3166 codes. |
| [statiks](https://github.com/janiltonmaciel/statiks) | 8 | 0 | 2018/06/26 | 1 year ago | Fast, zero-configuration, static HTTP filer server. |
| [retry](https://github.com/percolate/retry) | 7 | 40 | 2018/06/15 | 2 years ago | A simple but highly configurable retry package for Go. |
| [sliceconv](https://github.com/Henry-Sarabia/sliceconv) | 7 | 1 | 2019/02/15 | 1 year ago | Slice conversion between primitive types. |
| [nfdump](https://github.com/chrispassas/nfdump) | 7 | 1 | 2020/04/08 | 1 month ago | Read nfdump netflow files. |
| [blank](https://github.com/Henry-Sarabia/blank) | 6 | 2 | 2019/02/13 | 2 years ago | Verify or remove blanks and whitespace from strings. |
| [go-safe](https://github.com/kenkyu392/go-safe) | 4 | 0 | 2019/10/29 | 4 months ago | Panic-safe sandbox. |
| [lets-go](https://github.com/aplescia-chwy/lets-go) | 3 | 1 | 2020/02/19 | 1 year ago | Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities. |
| [tik](https://github.com/andy2046/tik) | 3 | 1 | 2020/07/04 | 11 months ago | Simple and easy timing wheel package for Go. |
| [lets-go](https://github.com/aplescia/lets-go) | 3 | 1 | 2020/02/19 | 5 months ago | Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities. |
| [olaf](https://github.com/btnguyen2k/olaf) | 2 | 1 | 2019/01/03 | 2 years ago | Twitter Snowflake implemented in Go. |
| [goctx](https://github.com/zerosnake0/goctx) | 2 | 1 | 2020/11/14 | 10 months ago | Get your context value with high performance. |
| [bleep](https://github.com/sinhashubham95/bleep) | 2 | 1 | 2021/01/02 | 9 months ago | Perform any number of actions on any set of OS signals in Go. |
| [compare](https://github.com/posener/compare) | 1 | 1 | 2020/03/13 | 1 year ago | Enables more readable and easier comparison tasks. |

## UUID
        
*Libraries for working with UUIDs.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [uuid](https://github.com/google/uuid) | 3070 | 45 | 2016/02/12 | 1 month ago | Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services. |
| [ulid](https://github.com/oklog/ulid) | 2403 | 44 | 2016/12/06 | 2 months ago | Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier). |
| [uuid](https://github.com/gofrs/uuid) | 976 | 18 | 2018/07/13 | 3 weeks ago | Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid. |
| [wuid](https://github.com/edwingeng/wuid) | 428 | 16 | 2018/01/27 | 1 month ago | An extremely fast unique number generator, 10-135 times faster than UUID. |
| [sno](https://github.com/muyo/sno) | 53 | 3 | 2019/05/26 | 5 months ago | Compact, sortable and fast unique IDs with embedded metadata. |
| [nanoid](https://github.com/aidarkhanov/nanoid) | 34 | 1 | 2019/07/02 | 2 weeks ago | A tiny and efficient Go unique string ID generator. |
| [Goid](https://github.com/JakeHL/Goid) | 30 | 5 | 2017/05/19 | 2 years ago | Generate and Parse RFC4122 compliant V4 UUIDs. |
| [uuid](https://github.com/agext/uuid) | 14 | 3 | 2016/02/03 | 1 year ago | Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier. |
| [gouid](https://github.com/twharmon/gouid) | 10 | 1 | 2020/10/08 | 4 months ago | Generate cryptographically secure random string IDs with just one allocation. |

## Validation
        
*Libraries for validation.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [validator](https://github.com/go-playground/validator) | 8756 | 101 | 2015/02/12 | 1 week ago | Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving. |
| [govalidator](https://github.com/asaskevich/govalidator) | 4944 | 100 | 2014/06/20 | 1 week ago | Validators and sanitizers for strings, numerics, slices and structs. |
| [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) | 2340 | 31 | 2016/06/22 | 3 days ago | Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags. |
| [govalidator](https://github.com/thedevsaddam/govalidator) | 1017 | 21 | 2017/09/13 | 8 months ago | Validate Golang request data with simple rules. Highly inspired by Laravel's request validation. |
| [validate](https://github.com/gookit/validate) | 473 | 16 | 2018/07/16 | 2 months ago | Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features. |
| [checkdigit](https://github.com/osamingo/checkdigit) | 81 | 0 | 2019/04/05 | 9 months ago | Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.). |
| [terraform-validator](https://github.com/thazelart/terraform-validator) | 71 | 3 | 2019/05/29 | 1 year ago | A norms and conventions validator for Terraform. |
| [jio](https://github.com/faceair/jio) | 61 | 2 | 2018/10/28 | 1 year ago | jio is a json schema validator similar to [joi](https://github.com/hapijs/joi). |
| [validate](https://github.com/gobuffalo/validate) | 59 | 8 | 2018/02/10 | 10 months ago | This package provides a framework for writing validations for Go applications. |
| [gody](https://github.com/guiferpa/gody) | 51 | 0 | 2018/11/01 | 8 months ago | :balloon: A lightweight struct validator for Go. |
| [govalid](https://github.com/twharmon/govalid) | 22 | 1 | 2019/02/17 | 1 month ago | Fast, tag-based validation for structs. |

## Version Control
        
*Libraries for version control.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-git](https://github.com/src-d/go-git) | 5013 | 100 | 2015/10/22 | 1 year ago | highly extensible Git implementation in pure Go. |
| [go-git](https://github.com/go-git/go-git) | 2673 | 37 | 2019/12/19 | 2 days ago | highly extensible Git implementation in pure Go. |
| [git2go](https://github.com/libgit2/git2go) | 1657 | 54 | 2013/03/05 | 3 days ago | Go bindings for libgit2. |
| [hercules](https://github.com/src-d/hercules) | 1440 | 19 | 2016/12/12 | 4 months ago | gaining advanced insights from Git repository history. |
| [gh](https://github.com/rjeczalik/gh) | 76 | 6 | 2015/03/08 | 2 years ago | Scriptable server and net/http middleware for GitHub Webhooks. |
| [go-vcs](https://github.com/sourcegraph/go-vcs) | 75 | 70 | 2013/06/02 | 6 months ago | manipulate and inspect VCS repositories in Go. |
| [hgo](https://github.com/beyang/hgo) | 13 | 4 | 2014/06/18 | 6 years ago | Hgo is a collection of Go packages providing read-access to local Mercurial repositories. |

## Video
        
*Libraries for manipulating video.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [goav](https://github.com/giorgisio/goav) | 1725 | 50 | 2015/05/21 | 3 months ago | Comprehensive Go bindings for FFmpeg. |
| [m3u8](https://github.com/grafov/m3u8) | 857 | 40 | 2013/02/05 | 2 days ago | Parser and generator library of M3U8 playlists for Apple HLS. |
| [gmf](https://github.com/3d0c/gmf) | 705 | 31 | 2013/04/03 | 2 days ago | Go bindings for FFmpeg av\* libraries. |
| [go-astits](https://github.com/asticode/go-astits) | 375 | 15 | 2017/07/04 | 2 days ago | Parse and demux MPEG Transport Streams (.ts) natively in GO. |
| [go-astisub](https://github.com/asticode/go-astisub) | 334 | 8 | 2016/12/16 | 1 month ago | Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.). |
| [libvlc-go](https://github.com/adrg/libvlc-go) | 243 | 10 | 2015/01/06 | 1 week ago | Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player). |
| [gst](https://github.com/ziutek/gst) | 160 | 10 | 2011/07/26 | 8 months ago | Go bindings for GStreamer. |
| [go-m3u8](https://github.com/quangngotan95/go-m3u8) | 79 | 2 | 2018/11/06 | 1 year ago | Parser and generator library for Apple m3u8 playlists. |
| [v4l](https://github.com/korandiz/v4l) | 60 | 6 | 2016/10/25 | 1 week ago | Video capture library for Linux, written in Go. |
| [libgosubs](https://github.com/wargarblgarbl/libgosubs) | 14 | 2 | 2017/05/03 | 1 year ago | Subtitle format support for go. Supports .srt, .ttml, and .ass. |
| [go-mpd](https://github.com/unki2aut/go-mpd) | 10 | 1 | 2018/11/02 | 1 year ago | Parser and generator library for MPEG-DASH manifest files. |

## Web Frameworks
        
*Full stack web frameworks.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gin](https://github.com/gin-gonic/gin) | 51914 | 1355 | 2014/06/16 | 5 hours ago | Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity. |
| [echo](https://github.com/labstack/echo) | 20805 | 538 | 2015/03/01 | 1 day ago | High performance, minimalist Go web framework. |
| [fiber](https://github.com/gofiber/fiber) | 15603 | 230 | 2020/01/16 | 20 hours ago | An Express.js inspired web framework build on Fasthttp. |
| [revel](https://github.com/revel/revel) | 12400 | 543 | 2011/12/09 | 7 months ago | High-productivity web framework for the Go language. |
| [goa](https://github.com/goadesign/goa) | 4392 | 166 | 2014/12/05 | 5 days ago | Goa provides a holistic approach for developing remote APIs and microservices in Go. |
| [gizmo](https://github.com/nytimes/gizmo) | 3531 | 120 | 2015/12/15 | 2 months ago | Microservice toolkit used by the New York Times. |
| [go-json-rest](https://github.com/ant0ine/go-json-rest) | 3484 | 160 | 2013/02/19 | 8 months ago | Quick and easy way to setup a RESTful JSON API. |
| [macaron](https://github.com/go-macaron/macaron) | 3212 | 147 | 2014/07/10 | 10 months ago | Macaron is a high productive and modular design web framework in Go. |
| [utron](https://github.com/gernest/utron) | 2204 | 70 | 2015/09/16 | 2 years ago | Lightweight MVC framework for Go(Golang). |
| [go-tigertonic](https://github.com/rcrowley/go-tigertonic) | 996 | 46 | 2013/02/09 | 3 years ago | Go framework for building JSON web services inspired by Dropwizard. |
| [goyave](https://github.com/go-goyave/goyave) | 896 | 27 | 2019/10/21 | 5 days ago | Feature-complete web framework aimed at clean code and fast development, with powerful built-in functionalities. |
| [tango](https://github.com/lunny/tango) | 835 | 76 | 2014/12/17 | 2 years ago | Micro & pluggable web framework for Go. |
| [goyave](https://github.com/System-Glitch/goyave) | 807 | 24 | 2019/10/21 | 7 months ago | Feature-complete web framework aimed at clean code and fast development, with powerful built-in functionalities. |
| [gearbox](https://github.com/gogearbox/gearbox) | 563 | 16 | 2020/04/25 | 1 week ago | A web framework written in Go with a focus on high performance and memory optimization. |
| [gongular](https://github.com/mustafaakin/gongular) | 442 | 21 | 2016/06/22 | 1 year ago | Fast Go web framework with input mapping/validation and (DI) Dependency Injection. |
| [neo](https://github.com/ivpusic/neo) | 412 | 34 | 2015/02/04 | 3 years ago | Neo is minimal and fast Go Web Framework with extremely simple API. |
| [air](https://github.com/aofei/air) | 406 | 19 | 2016/07/20 | 5 months ago | An ideally refined web framework for Go. |
| [aero](https://github.com/aerogo/aero) | 404 | 19 | 2016/11/09 | 1 year ago | High-performance web framework for Go, reaches top scores in Lighthouse. |
| [mango](https://github.com/paulbellamy/mango) | 359 | 22 | 2011/05/25 | 4 years ago | Mango is a modular web-application framework for Go, inspired by Rack, and PEP333. |
| [gondola](https://github.com/rainycape/gondola) | 308 | 15 | 2014/07/25 | 2 years ago | The web framework for writing faster sites, faster. |
| [beego](https://github.com/astaxie/beego) | 260 | 9 | 2012/02/29 | 1 month ago | beego is an open-source, high-performance web framework for the Go programming language. |
| [golf](https://github.com/dinever/golf) | 251 | 17 | 2015/11/18 | 1 month ago | Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library. |
| [flamingo](https://github.com/i-love-flamingo/flamingo) | 232 | 24 | 2019/04/02 | 1 month ago | Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc. |
| [flamingo-commerce](https://github.com/i-love-flamingo/flamingo-commerce) | 212 | 22 | 2019/04/02 | 2 days ago | Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications. |
| [ginrpc](https://github.com/xxjwxc/ginrpc) | 190 | 7 | 2019/06/22 | 4 days ago | Gin parameter automatic binding tool,gin rpc tools. |
| [webgo](https://github.com/bnkamalesh/webgo) | 187 | 9 | 2015/12/16 | 3 weeks ago | A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc). |
| [gearbox](https://github.com/abahmed/gearbox) | 176 | 4 | 2020/04/25 | 1 year ago | A web framework written in Go with a focus on high performance and memory optimization. |
| [hiboot](https://github.com/hidevopsio/hiboot) | 162 | 14 | 2018/03/16 | 3 months ago | hiboot is a high performance web application framework with auto configuration and dependency injection support. |
| [uadmin](https://github.com/uadmin/uadmin) | 153 | 12 | 2018/10/05 | 1 month ago | Fully featured web framework for Golang, inspired by Django. |
| [go-rest](https://github.com/ungerik/go-rest) | 125 | 10 | 2012/07/13 | 4 years ago | Small and evil REST framework for Go. |
| [appy](https://github.com/appist/appy) | 109 | 4 | 2019/05/27 | 2 months ago | An opinionated productive web framework that helps scaling business easier. |
| [patron](https://github.com/beatlabs/patron) | 82 | 15 | 2019/01/30 | 4 days ago | Patron is a microservice framework following best cloud practices with a focus on productivity. |
| [vox](https://github.com/aisk/vox) | 75 | 2 | 2014/12/24 | 4 months ago | A golang web framework for humans, inspired by Koa heavily. |
| [microservice](https://github.com/claygod/microservice) | 74 | 9 | 2016/12/15 | 2 years ago | The framework for the creation of microservices, written in Golang. |
| [golax](https://github.com/fulldump/golax) | 73 | 7 | 2016/01/30 | 3 years ago | A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more. |
| [rux](https://github.com/gookit/rux) | 68 | 4 | 2018/08/05 | 1 month ago | Simple and fast web framework for build golang HTTP applications. |
| [yarf](https://github.com/yarf-framework/yarf) | 62 | 4 | 2015/09/02 | 2 years ago | Fast micro-framework designed to build REST APIs and web services in a fast and simple way. |
| [fireball](https://github.com/zpatrick/fireball) | 56 | 4 | 2016/07/20 | 3 years ago | More "natural" feeling web framework. |
| [goa](https://github.com/goa-go/goa) | 47 | 4 | 2019/07/26 | 1 year ago | goa is just like koajs for golang, it is a flexible, light, high-performance and extensible web framework based on middleware. |
| [api](https://github.com/resoursea/api) | 31 | 6 | 2015/01/24 | 6 years ago | REST framework for quickly writing resource based services. |
| [rex](https://github.com/goanywhere/rex) | 31 | 2 | 2014/10/16 | 3 years ago | Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`. |
| [goweb](https://github.com/twharmon/goweb) | 24 | 1 | 2019/05/07 | 7 months ago | Web framework with routing, websockets, logging, middleware, static file server (optional gzip), and automatic TLS. |
| [banjo](https://github.com/n4Zz2/banjo) | 18 | 1 | 2017/12/09 | 3 years ago | Very simple and fast web framework for Go. |
| [banjo](https://github.com/nsheremet/banjo) | 17 | 1 | 2017/12/09 | 3 years ago | Very simple and fast web framework for Go. |

### Middlewares
        

#### Actual middlewares
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [tollbooth](https://github.com/didip/tollbooth) | 2022 | 49 | 2015/05/17 | 2 weeks ago | Rate limit HTTP request handler. |
| [cors](https://github.com/rs/cors) | 1930 | 33 | 2014/10/25 | 1 week ago | Easily add CORS capabilities to your API. |
| [limiter](https://github.com/ulule/limiter) | 1343 | 29 | 2015/10/02 | 3 weeks ago | Dead simple rate limit middleware for Go. |
| [go-server-timing](https://github.com/mitchellh/go-server-timing) | 822 | 18 | 2018/02/12 | 10 months ago | Add/parse Server-Timing header. |
| [go-fault](https://github.com/github/go-fault) | 417 | 121 | 2020/05/14 | 2 weeks ago | Fault injection middleware for Go. |
| [ln-paywall](https://github.com/philippgille/ln-paywall) | 114 | 5 | 2018/06/29 | 2 years ago | Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin). |
| [xff](https://github.com/sebest/xff) | 85 | 2 | 2014/12/22 | 8 months ago | Handle `X-Forwarded-For` header and friends. |
| [formjson](https://github.com/rs/formjson) | 36 | 2 | 2015/03/19 | 5 years ago | Transparently handle JSON input as a standard form POST. |
| [client-timing](https://github.com/posener/client-timing) | 19 | 1 | 2018/02/23 | 1 year ago | An HTTP client for Server-Timing header. |

#### Libraries for creating HTTP middlewares
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [negroni](https://github.com/urfave/negroni) | 7079 | 238 | 2014/05/18 | 1 week ago | Idiomatic HTTP middleware for Golang. |
| [alice](https://github.com/justinas/alice) | 2368 | 48 | 2014/05/25 | 8 months ago | Painless middleware chaining for Go. |
| [render](https://github.com/unrolled/render) | 1539 | 35 | 2014/06/10 | 4 months ago | Go package for easily rendering JSON, XML, and HTML template responses. |
| [stats](https://github.com/thoas/stats) | 582 | 16 | 2015/03/05 | 2 years ago | Go middleware that stores various information about your web application. |
| [interpose](https://github.com/carbocation/interpose) | 291 | 12 | 2014/07/20 | 4 years ago | Minimalist net/http middleware for golang. |
| [renderer](https://github.com/thedevsaddam/renderer) | 226 | 7 | 2017/11/07 | 8 months ago | Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go. |
| [muxchain](https://github.com/stephens2424/muxchain) | 209 | 5 | 2014/05/03 | 2 years ago | Lightweight middleware for net/http. |
| [rye](https://github.com/InVisionApp/rye) | 97 | 203 | 2016/10/06 | 3 years ago | Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context. |
| [gores](https://github.com/alioygur/gores) | 96 | 5 | 2015/12/25 | 9 months ago | Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs. |
| [mediary](https://github.com/HereMobilityDevelopers/mediary) | 77 | 5 | 2020/03/23 | 1 year ago | add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses. |
| [chain](https://github.com/codemodus/chain) | 63 | 7 | 2015/05/14 | 3 years ago | Handler wrapper chaining with scoped data (net/context-based "middleware"). |
| [wrap](https://github.com/go-on/wrap) | 59 | 3 | 2014/02/16 | 3 years ago | Small middlewares package for net/http. |
| [catena](https://github.com/codemodus/catena) | 7 | 2 | 2015/07/30 | 3 years ago | http.Handler wrapper catenation (same API as "chain"). |

### Routers
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [mux](https://github.com/gorilla/mux) | 15206 | 311 | 2012/10/02 | 2 weeks ago | Powerful URL router and dispatcher for golang. |
| [httprouter](https://github.com/julienschmidt/httprouter) | 13206 | 323 | 2013/12/05 | 1 day ago | High performance router. Use this and the standard http handlers to form a very high performance web framework. |
| [chi](https://github.com/go-chi/chi) | 10179 | 180 | 2015/10/15 | 2 weeks ago | Small, fast and expressive HTTP router built on net/context. |
| [web](https://github.com/gocraft/web) | 1447 | 60 | 2013/11/16 | 1 year ago | Mux and middleware package in Go. |
| [bone](https://github.com/go-zoo/bone) | 1278 | 36 | 2014/11/19 | 2 years ago | Lightning Fast HTTP Multiplexer. |
| [goji](https://github.com/goji/goji) | 876 | 42 | 2015/11/16 | 2 years ago | Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`. |
| [fasthttprouter](https://github.com/buaazp/fasthttprouter) | 872 | 34 | 2015/12/13 | 2 years ago | High performance router forked from `httprouter`. The first router fit for `fasthttp`. |
| [gorouter](https://github.com/xujiajun/gorouter) | 504 | 16 | 2018/01/29 | 2 years ago | A simple and fast HTTP router for Go. |
| [httptreemux](https://github.com/dimfeld/httptreemux) | 500 | 24 | 2014/05/14 | 4 days ago | High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter. |
| [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) | 415 | 29 | 2015/10/27 | 3 weeks ago | An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs. |
| [lars](https://github.com/go-playground/lars) | 383 | 16 | 2015/12/24 | 2 years ago | Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks. |
| [siesta](https://github.com/VividCortex/siesta) | 349 | 28 | 2014/09/23 | 5 months ago | Composable framework to write middleware and handlers. |
| [vestigo](https://github.com/husobee/vestigo) | 263 | 15 | 2015/09/22 | 1 year ago | Performant, stand-alone, HTTP compliant URL Router for go web applications. |
| [router](https://github.com/gowww/router) | 160 | 7 | 2017/05/25 | 1 year ago | Lightning fast HTTP router fully compatible with the net/http.Handler interface. |
| [alien](https://github.com/gernest/alien) | 120 | 4 | 2016/01/30 | 2 years ago | Lightweight and fast http router from outer space. |
| [pure](https://github.com/go-playground/pure) | 116 | 6 | 2016/09/23 | 10 months ago | Is a lightweight HTTP router that sticks to the std "net/http" implementation. |
| [violetear](https://github.com/nbari/violetear) | 103 | 4 | 2015/06/19 | 4 months ago | Go HTTP router. |
| [Bxog](https://github.com/claygod/Bxog) | 102 | 8 | 2016/05/19 | 1 year ago | Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters. |
| [gorouter](https://github.com/vardius/gorouter) | 100 | 6 | 2016/07/14 | 1 week ago | GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`. |
| [xmux](https://github.com/rs/xmux) | 91 | 6 | 2015/12/14 | 4 years ago | High performance muxer based on `httprouter` with `net/context` support. |
| [bellt](https://github.com/GuilhermeCaruso/bellt) | 52 | 6 | 2019/02/21 | 1 year ago | A simple Go HTTP router. |
| [fastrouter](https://github.com/razonyang/fastrouter) | 19 | 2 | 2017/11/01 | 3 years ago | a fast, flexible HTTP router written in Go. |
| [route](https://github.com/goroute/route) | 7 | 4 | 2019/07/06 | 1 year ago | Simple yet powerful HTTP request multiplexer. |

## Windows
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-ole](https://github.com/go-ole/go-ole) | 789 | 41 | 2011/01/21 | 2 weeks ago | Win32 OLE implementation for golang. |
| [d3d9](https://github.com/gonutz/d3d9) | 128 | 8 | 2015/12/12 | 2 months ago | Go bindings for Direct3D9. |
| [gosddl](https://github.com/MonaxGT/gosddl) | 7 | 2 | 2018/12/04 | 2 years ago | Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL. |

## XML
        
*Libraries and tools for manipulating XML.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [zek](https://github.com/miku/zek) | 501 | 20 | 2017/11/23 | 1 week ago | Generate a Go struct from XML. |
| [xpath](https://github.com/antchfx/xpath) | 418 | 11 | 2016/10/09 | 1 week ago | XPath package for Go. |
| [xquery](https://github.com/antchfx/xquery) | 153 | 11 | 2016/10/09 | 3 years ago | XQuery lets you extract data from HTML/XML documents using XPath expression. |
| [xml2map](https://github.com/sbabiv/xml2map) | 34 | 1 | 2018/08/06 | 7 months ago | XML to MAP converter written Golang. |
| [xmlwriter](https://github.com/shabbyrobe/xmlwriter) | 20 | 2 | 2017/04/11 | 6 months ago | Procedural XML generation API based on libxml2's xmlwriter module. |
| [XML-Comp](https://github.com/XML-Comp/XML-Comp) | 15 | 2 | 2016/10/25 | 3 years ago | Simple command line XML comparer that generates diffs of folders, files and tags. |

## WebAssembly
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [tinygo](https://github.com/tinygo-org/tinygo) | 8699 | 163 | 2018/06/07 | 2 hours ago | Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM. |
| [dom](https://github.com/dennwc/dom) | 438 | 19 | 2018/06/30 | 2 years ago | DOM library. |
| [go-canvas](https://github.com/markfarnan/go-canvas) | 142 | 6 | 2019/05/05 | 9 months ago | Library to use HTML5 Canvas, with all drawing within go code. |
| [wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) | 97 | 3 | 2018/07/14 | 17 hours ago | Run Go WASM tests in your browser. |
| [webapi](https://github.com/gowebapi/webapi) | 90 | 8 | 2019/02/08 | 8 months ago | Bindings for DOM and HTML generated from WebIDL. |
| [vert](https://github.com/norunners/vert) | 55 | 5 | 2018/03/25 | 6 months ago | Interop between Go and JS values. |

## Files
        

## File Handling
        
*Libraries for handling files and file systems.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [afero](https://github.com/spf13/afero) | 3994 | 89 | 2014/10/28 | 3 weeks ago | FileSystem Abstraction System for Go. |
| [pdfcpu](https://github.com/pdfcpu/pdfcpu) | 2608 | 62 | 2017/06/18 | 1 month ago | PDF processor. |
| [notify](https://github.com/rjeczalik/notify) | 682 | 30 | 2014/09/08 | 1 month ago | File system event notification library with simple API, similar to os/signal. |
| [copy](https://github.com/otiai10/copy) | 341 | 7 | 2017/09/01 | 1 month ago | Copy directory recursively. |
| [bigfile](https://github.com/bigfile/bigfile) | 206 | 16 | 2019/07/15 | 1 year ago | A file transfer system, support to manage files with http api, rpc call and ftp client. |
| [afs](https://github.com/viant/afs) | 155 | 12 | 2019/08/19 | 1 month ago | Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go. |
| [vfs](https://github.com/C2FO/vfs) | 127 | 21 | 2017/08/01 | 4 days ago | A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS. |
| [go-csv-tag](https://github.com/artonge/go-csv-tag) | 90 | 0 | 2017/06/18 | 1 year ago | Load csv file using tag. |
| [go-exiftool](https://github.com/barasher/go-exiftool) | 81 | 4 | 2019/05/12 | 1 month ago | Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...). |
| [opc](https://github.com/qmuntal/opc) | 67 | 3 | 2018/11/06 | 7 months ago | Load Open Packaging Conventions (OPC) files for Go. |
| [skywalker](https://github.com/dixonwille/skywalker) | 65 | 4 | 2017/08/01 | 1 month ago | Package to allow one to concurrently go through a filesystem with ease. |
| [tarfs](https://github.com/posener/tarfs) | 47 | 2 | 2017/03/10 | 1 year ago | Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files. |
| [checksum](https://github.com/codingsince1985/checksum) | 42 | 2 | 2014/11/05 | 1 week ago | Compute message digest, like MD5 and SHA256, for large files. |
| [parquet](https://github.com/parsyl/parquet) | 34 | 6 | 2019/01/29 | 3 weeks ago | Read and write [parquet](https://parquet.apache.org) files. |
| [baraka](https://github.com/xis/baraka) | 33 | 2 | 2020/07/12 | 1 month ago | A library to process http file uploads easily. |
| [go-gtfs](https://github.com/artonge/go-gtfs) | 28 | 2 | 2017/07/09 | 1 year ago | Load gtfs files in go. |
| [flop](https://github.com/homedepot/flop) | 26 | 18 | 2019/03/01 | 8 months ago | File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html). |
| [gut](https://github.com/1set/gut) | 18 | 3 | 2019/10/05 | 10 months ago | Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links. |
| [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) | 14 | 3 | 2018/10/16 | 1 year ago | Copy files for humans. |
| [todotxt](https://github.com/1set/todotxt) | 9 | 2 | 2020/11/06 | 10 months ago | Go library for Gina Trapani's [*todo.txt*](http://todotxt.org/) files, supports parsing and manipulating of task lists in the [*todo.txt* format](https://github.com/todotxt/todo.txt). |

## Build Automation
        
*Libraries and tools helping with build automation.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [realize](https://github.com/oxequa/realize) | 4118 | 73 | 2016/07/12 | 4 months ago | Go build system with file watchers and live reload. Run, build and watch file changes with custom paths. |
| [task](https://github.com/go-task/task) | 3903 | 59 | 2017/02/27 | 18 hours ago | simple "Make" alternative. |
| [mmake](https://github.com/tj/mmake) | 1586 | 28 | 2017/02/15 | 1 year ago | Modern Make. |
| [goyek](https://github.com/goyek/goyek) | 257 | 4 | 2020/10/11 | 1 week ago | Create build pipelines in Go. |
| [taskctl](https://github.com/taskctl/taskctl) | 133 | 6 | 2019/11/12 | 4 months ago | Concurrent task runner. |
| [1build](https://github.com/gopinath-langote/1build) | 99 | 7 | 2019/04/23 | 1 week ago | Command line tool to frictionlessly manage project-specific commands. |
| [taskflow](https://github.com/pellared/taskflow) | 63 | 2 | 2020/10/11 | 5 months ago | Create build pipelines in Go. |
| [gaper](https://github.com/maxcnunes/gaper) | 48 | 0 | 2018/06/16 | 1 year ago | Builds and restarts a Go project when it crashes or some watched file changes. |

# Tools
        
*Go software and plugins.*

## Code Analysis
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [lint](https://github.com/golang/lint) | 3921 | 102 | 2013/06/02 | 4 months ago | Golint is a linter for Go source code. |
| [errcheck](https://github.com/kisielk/errcheck) | 1741 | 25 | 2013/02/24 | 3 months ago | Errcheck is a program for checking for unchecked errors in Go programs. |
| [gcvis](https://github.com/davecheney/gcvis) | 1032 | 36 | 2014/07/10 | 2 years ago | Visualise Go program GC trace data in real time. |
| [go-critic](https://github.com/go-critic/go-critic) | 995 | 20 | 2018/05/05 | 2 hours ago | source code linter that brings checks that are currently not implemented in other linters. |
| [php-parser](https://github.com/z7zmey/php-parser) | 826 | 29 | 2017/11/07 | 5 months ago | A Parser for PHP written in Go. |
| [goast-viewer](https://github.com/yuroyoro/goast-viewer) | 542 | 17 | 2014/06/30 | 2 years ago | Web based Golang AST visualizer. |
| [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) | 538 | 6 | 2019/04/19 | 4 weeks ago | An easy way to find outdated dependencies of your Go projects. |
| [goplantuml](https://github.com/jfeliu007/goplantuml) | 538 | 11 | 2019/05/26 | 4 months ago | Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them. |
| [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) | 513 | 11 | 2017/04/12 | 7 months ago | go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects. |
| [unconvert](https://github.com/mdempsky/unconvert) | 311 | 8 | 2016/02/19 | 1 year ago | Remove unnecessary type conversions from Go source. |
| [tickgit](https://github.com/augmentable-dev/tickgit) | 265 | 8 | 2019/10/12 | 1 year ago | CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author. |
| [dupl](https://github.com/mibk/dupl) | 255 | 8 | 2015/05/20 | 9 months ago | Tool for code clone detection. |
| [gostatus](https://github.com/shurcooL/gostatus) | 246 | 7 | 2013/11/27 | 2 years ago | Command line tool, shows the status of repositories that contain Go packages. |
| [golines](https://github.com/segmentio/golines) | 239 | 13 | 2019/10/01 | 2 months ago | Formatter that automatically shortens long lines in Go code. |
| [apicompat](https://github.com/bradleyfalzon/apicompat) | 174 | 7 | 2016/07/10 | 4 years ago | Checks recent changes to a Go project for backwards incompatible changes. |
| [checkstyle](https://github.com/qiniu/checkstyle) | 116 | 12 | 2014/01/01 | 6 months ago | checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments. |
| [lint](https://github.com/surullabs/lint) | 66 | 5 | 2016/07/09 | 2 years ago | Run linters as part of go test. |
| [validate](https://github.com/mccoyst/validate) | 60 | 6 | 2013/11/22 | 5 years ago | Automatically validates struct fields with tags. |
| [go-outdated](https://github.com/firstrow/go-outdated) | 45 | 1 | 2015/06/29 | 2 years ago | Console application that displays outdated packages. |
| [blanket](https://github.com/verygoodsoftwarenotvirus/blanket) | 14 | 2 | 2017/09/04 | 3 years ago | tarp finds functions and methods without direct unit tests in Go source code. |

## Editor Plugins
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [vim-go](https://github.com/fatih/vim-go) | 13818 | 279 | 2014/03/24 | 1 hour ago | Go development plugin for Vim. |
| [vscode-go](https://github.com/microsoft/vscode-go) | 5978 | 226 | 2015/10/14 | 1 year ago | Extension for Visual Studio Code (VS Code) which provides support for the Go language. |
| [gocode](https://github.com/nsf/gocode) | 4931 | 192 | 2010/07/05 | 7 months ago | Autocompletion daemon for the Go programming language. |
| [GoSublime](https://github.com/DisposaBoy/GoSublime) | 3416 | 116 | 2011/08/27 | 1 year ago | Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features. |
| [vscode-go](https://github.com/golang/vscode-go) | 2084 | 58 | 2020/03/06 | 3 days ago | Extension for Visual Studio Code (VS Code) which provides support for the Go language. |
| [go-plus](https://github.com/joefitzgerald/go-plus) | 1523 | 44 | 2014/03/13 | 5 months ago | Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting. |
| [go-mode.el](https://github.com/dominikh/go-mode.el) | 1185 | 55 | 2013/01/30 | 1 week ago | Go mode for GNU/Emacs. |
| [Watch](https://github.com/eaburns/Watch) | 188 | 14 | 2013/08/08 | 3 years ago | Runs a command in an acme win on file changes. |
| [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) | 88 | 5 | 2012/11/25 | 5 years ago | Vim plugin to highlight syntax errors on save. |
| [goimports-reviser](https://github.com/incu6us/goimports-reviser) | 70 | 3 | 2020/04/08 | 2 weeks ago | Formatting tool for imports. |
| [go-language-server](https://github.com/theia-ide/go-language-server) | 32 | 5 | 2017/11/21 | 2 years ago | A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol. |
| [gounit-vim](https://github.com/hexdigest/gounit-vim) | 22 | 2 | 2018/02/21 | 2 years ago | Vim plugin for generating Go tests based on the function's or method's signature. |
| [theia-go-extension](https://github.com/theia-ide/theia-go-extension) | 15 | 5 | 2017/11/30 | 2 years ago | Go language support for the Theia IDE. |

## Go Generate Tools
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gotests](https://github.com/cweill/gotests) | 3458 | 74 | 2016/01/19 | 4 months ago | Generate Go tests from your source code. |
| [genny](https://github.com/cheekybits/genny) | 1587 | 26 | 2014/10/27 | 1 month ago | Elegant generics for Go. |
| [re2dfa](https://github.com/opennota/re2dfa) | 187 | 9 | 2015/06/20 | 3 years ago | Transform regular expressions into finite state machines and output Go source code. |
| [xgen](https://github.com/xuri/xgen) | 112 | 10 | 2019/06/22 | 7 months ago | XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator. |
| [hasgo](https://github.com/DylanMeeus/hasgo) | 102 | 6 | 2019/05/16 | 5 months ago | Generate Haskell inspired functions for your slices. |
| [gocontracts](https://github.com/Parquery/gocontracts) | 76 | 8 | 2018/08/13 | 2 years ago | brings design-by-contract to Go by synchronizing the code with the documentation. |
| [gounit](https://github.com/hexdigest/gounit) | 57 | 5 | 2018/02/05 | 3 years ago | Generate Go tests using your own templates. |
| [generic](https://github.com/usk81/generic) | 41 | 3 | 2016/06/15 | 8 months ago | flexible data type for Go. |

## Go Tools
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-swagger](https://github.com/go-swagger/go-swagger) | 6836 | 123 | 2014/11/16 | 18 hours ago | Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API. |
| [OctoLinker](https://github.com/OctoLinker/OctoLinker) | 4816 | 89 | 2013/12/27 | 4 hours ago | Navigate through go files efficiently with the OctoLinker browser extension for GitHub. |
| [go-callvis](https://github.com/ofabry/go-callvis) | 3552 | 73 | 2016/09/03 | 1 month ago | Visualize call graph of your Go program using dot format. |
| [go-callvis](https://github.com/TrueFurby/go-callvis) | 2408 | 70 | 2016/09/03 | 1 year ago | Visualize call graph of your Go program using dot format. |
| [depth](https://github.com/KyleBanks/depth) | 645 | 13 | 2017/03/04 | 1 year ago | Visualize dependency trees of any package by analyzing imports. |
| [richgo](https://github.com/kyoh86/richgo) | 604 | 4 | 2017/01/04 | 2 months ago | Enrich `go test` outputs with text decorations. |
| [rts](https://github.com/galeone/rts) | 223 | 3 | 2016/04/04 | 1 week ago | RTS: response to struct. Generates Go structs from server responses. |
| [godbg](https://github.com/tylerwince/godbg) | 180 | 4 | 2019/01/23 | 2 years ago | Implementation of Rusts `dbg!` macro for quick and easy debugging during development. |
| [typex](https://github.com/dtgorski/typex) | 134 | 3 | 2020/03/24 | 8 months ago | Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration. |
| [colorgo](https://github.com/songgao/colorgo) | 108 | 4 | 2013/02/14 | 1 year ago | Wrapper around `go` command for colorized `go build` output. |
| [gothanks](https://github.com/psampaz/gothanks) | 105 | 3 | 2019/11/10 | 7 months ago | GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers. |
| [igo](https://github.com/rocketlaunchr/igo) | 47 | 3 | 2018/11/17 | 1 year ago | Improved Go Syntax (transpiler) |
| [go-james](https://github.com/pieterclaerhout/go-james) | 45 | 2 | 2019/10/14 | 7 months ago | Go project skeleton creator, builds and tests your projects without the manual setup. |
| [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) | 38 | 2 | 2015/05/22 | 3 years ago | Bash completion for go and wgo. |
| [generator-go-lang](https://github.com/axelspringer/generator-go-lang) | 23 | 13 | 2017/09/13 | 1 year ago | A [Yeoman](http://yeoman.io) generator to get new Go projects started. |

## Software Packages
        
*Software written in Go.*

### DevOps Tools
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [kubernetes](https://github.com/kubernetes/kubernetes) | 81468 | 3289 | 2014/06/06 | 12 minutes ago | Container Cluster Manager from Google. |
| [moby](https://github.com/moby/moby) | 61274 | 3058 | 2013/01/18 | 1 day ago | Collaborative project for the container ecosystem to assemble container-based systems. |
| [traefik](https://github.com/traefik/traefik) | 35226 | 702 | 2015/09/13 | 11 hours ago | Reverse proxy and load balancer with support for multiple backends. |
| [traefik](https://github.com/containous/traefik) | 30724 | 719 | 2015/09/13 | 1 year ago | Reverse proxy and load balancer with support for multiple backends. |
| [gitea](https://github.com/go-gitea/gitea) | 26512 | 485 | 2016/11/01 | 17 minutes ago | Fork of Gogs, entirely community driven. |
| [vegeta](https://github.com/tsenart/vegeta) | 18346 | 323 | 2013/08/13 | 1 week ago | HTTP load testing tool and library. It's over 9000! |
| [packer](https://github.com/hashicorp/packer) | 13187 | 483 | 2013/03/23 | 18 hours ago | Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. |
| [hey](https://github.com/rakyll/hey) | 12075 | 178 | 2016/09/02 | 6 days ago | Hey is a tiny program that sends some load to a web application. |
| [webhook](https://github.com/adnanh/webhook) | 6962 | 146 | 2015/01/12 | 6 days ago | Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server. |
| [gvm](https://github.com/moovweb/gvm) | 6638 | 154 | 2011/12/03 | 2 months ago | GVM provides an interface to manage Go versions. |
| [gaia](https://github.com/gaia-pipeline/gaia) | 4477 | 104 | 2017/12/28 | 2 weeks ago | Build powerful pipelines in any programming language. |
| [gox](https://github.com/mitchellh/gox) | 4102 | 76 | 2013/11/17 | 6 months ago | Dead simple, no frills Go cross compile tool. |
| [bosun](https://github.com/bosun-monitor/bosun) | 3203 | 148 | 2013/11/15 | 1 week ago | Time Series Alerting Framework. |
| [bombardier](https://github.com/codesenberg/bombardier) | 2793 | 65 | 2016/05/29 | 2 months ago | Fast cross-platform HTTP benchmarking tool. |
| [pomerium](https://github.com/pomerium/pomerium) | 2739 | 33 | 2019/01/01 | 2 days ago | Pomerium is an identity-aware access proxy. |
| [script](https://github.com/bitfield/script) | 1889 | 34 | 2019/04/20 | 1 week ago | Making it easy to write shell-like scripts in Go for DevOps and system administration tasks. |
| [fac](https://github.com/mkchoi212/fac) | 1730 | 32 | 2017/12/29 | 2 years ago | Command-line user interface to fix git merge conflicts. |
| [kala](https://github.com/ajvb/kala) | 1714 | 65 | 2015/03/19 | 4 months ago | Simplistic, modern, and performant job scheduler. |
| [goxc](https://github.com/laher/goxc) | 1668 | 51 | 2013/02/11 | 2 years ago | build tool for Go, with a focus on cross-compiling and packaging. |
| [statusok](https://github.com/sanathp/statusok) | 1518 | 51 | 2015/08/26 | 1 month ago | Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected. |
| [s3gof3r](https://github.com/rlmcpherson/s3gof3r) | 1106 | 33 | 2013/08/02 | 1 month ago | Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3. |
| [go-selfupdate](https://github.com/sanbornm/go-selfupdate) | 872 | 29 | 2013/11/13 | 1 week ago | Enable your Go applications to self update. |
| [s5cmd](https://github.com/peak/s5cmd) | 794 | 22 | 2016/11/16 | 2 days ago | Blazing fast S3 and local filesystem execution tool. |
| [skm](https://github.com/TimothyYe/skm) | 709 | 20 | 2017/10/11 | 1 week ago | SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily! |
| [scaleway-cli](https://github.com/scaleway/scaleway-cli) | 687 | 34 | 2015/03/20 | 1 day ago | Manage BareMetal Servers from Command Line (as easily as with Docker). |
| [aurora](https://github.com/xuri/aurora) | 536 | 31 | 2016/10/09 | 1 month ago | Cross-platform web-based Beanstalkd queue server console. |
| [cassowary](https://github.com/rogerwelin/cassowary) | 533 | 5 | 2019/08/25 | 6 months ago | Modern cross-platform HTTP load-testing tool written in Go. |
| [utask](https://github.com/ovh/utask) | 521 | 28 | 2019/11/05 | 4 days ago | Automation engine that models and executes business processes declared in yaml. |
| [govvv](https://github.com/ahmetb/govvv) | 499 | 10 | 2016/08/02 | 1 year ago | “go build” wrapper to easily add version information into Go binaries. |
| [gonative](https://github.com/inconshreveable/gonative) | 326 | 8 | 2014/05/01 | 5 years ago | Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages. |
| [trubka](https://github.com/xitonix/trubka) | 301 | 14 | 2019/07/05 | 9 months ago | A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka. |
| [pewpew](https://github.com/bengadbois/pewpew) | 296 | 10 | 2016/10/12 | 2 months ago | Flexible HTTP command line stress tester. |
| [mora](https://github.com/emicklei/mora) | 293 | 25 | 2013/07/12 | 5 months ago | REST server for accessing MongoDB documents and meta data. |
| [jenkins-cli](https://github.com/jenkins-zh/jenkins-cli) | 283 | 13 | 2019/06/21 | 3 days ago | Jenkins CLI allows you manage your Jenkins as an easy way. |
| [lstags](https://github.com/ivanilves/lstags) | 282 | 11 | 2017/08/15 | 2 months ago | Tool and API to sync Docker images across different registries. |
| [dogo](https://github.com/liudng/dogo) | 240 | 18 | 2014/11/19 | 2 years ago | Monitoring changes in the source file and automatically compile and run (restart). |
| [manssh](https://github.com/xwjdsh/manssh) | 231 | 4 | 2017/10/08 | 3 years ago | manssh is a command line tool for managing your ssh alias config easily. |
| [godbg](https://github.com/sirnewton01/godbg) | 225 | 18 | 2013/08/09 | 3 years ago | Web-based gdb front-end application. |
| [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) | 203 | 9 | 2017/03/03 | 3 months ago | Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`. |
| [blast](https://github.com/dave/blast) | 200 | 5 | 2017/10/21 | 3 years ago | A simple tool for API load testing and batch jobs. |
| [gobrew](https://github.com/cryptojuice/gobrew) | 183 | 5 | 2013/11/13 | 1 year ago | gobrew lets you easily switch between multiple versions of go. |
| [ostent](https://github.com/ostrost/ostent) | 172 | 7 | 2014/03/31 | 3 years ago | collects and displays system metrics and optionally relays to Graphite and/or InfluxDB. |
| [abbreviate](https://github.com/dnnrly/abbreviate) | 170 | 5 | 2018/11/23 | 3 days ago | abbreviate is a tool turning long strings in to shorter ones with configurable seperaters, for example to embed branch names in to deployment stack IDs. |
| [terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) | 163 | 11 | 2017/10/17 | 4 days ago | Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed. |
| [kcli](https://github.com/cswank/kcli) | 158 | 6 | 2017/03/25 | 1 year ago | Command line tool for inspecting kafka topics/partitions/messages. |
| [grapes](https://github.com/yaronsumel/grapes) | 154 | 6 | 2016/09/01 | 9 months ago | Lightweight tool designed to distribute commands over ssh with ease. |
| [winrm-cli](https://github.com/masterzen/winrm-cli) | 122 | 5 | 2016/05/23 | 1 year ago | Cli tool to remotely execute commands on Windows machines. |
| [dockerfile-generator](https://github.com/ozankasikci/dockerfile-generator) | 117 | 5 | 2019/08/14 | 1 year ago | A go library and an executable that produces valid Dockerfiles using various input channels. |
| [drone-scp](https://github.com/appleboy/drone-scp) | 87 | 3 | 2016/10/16 | 3 months ago | Copy files and artifacts via SSH using a binary, docker or Drone CI. |
| [go-furnace](https://github.com/go-furnace/go-furnace) | 84 | 2 | 2016/10/09 | 2 years ago | Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean. |
| [s3-proxy](https://github.com/oxyno-zeta/s3-proxy) | 59 | 2 | 2019/09/22 | 1 day ago | S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth). |
| [dropship](https://github.com/ChrisMcKenzie/dropship) | 55 | 3 | 2015/09/03 | 3 years ago | Tool for deploying code via cdn. |
| [drone-jenkins](https://github.com/appleboy/drone-jenkins) | 32 | 3 | 2016/10/15 | 1 hour ago | Trigger downstream Jenkins jobs using a binary, docker or Drone CI. |
| [rodent](https://github.com/alouche/rodent) | 31 | 2 | 2014/06/01 | 4 years ago | Rodent helps you manage Go versions, projects and track dependencies. |
| [awsenv](https://github.com/soniah/awsenv) | 27 | 2 | 2015/08/05 | 3 years ago | Small binary that loads Amazon (AWS) environment variables for a profile. |
| [lwc](https://github.com/timdp/lwc) | 25 | 4 | 2018/04/22 | 1 year ago | A live-updating version of the UNIX wc command. |
| [depcharge](https://github.com/centerorbit/depcharge) | 18 | 3 | 2018/07/25 | 1 year ago | Helps orchestrating the execution of commands across the many dependencies in larger projects. |
| [httpref](https://github.com/dnnrly/httpref) | 16 | 3 | 2020/01/10 | 3 days ago | httpref is a handy CLI reference for HTTP methods, status codes, headers, and TCP and UDP ports. |
| [sg](https://github.com/ChristopherRabotin/sg) | 6 | 1 | 2015/08/19 | 5 years ago | Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response. |
| [aptly-fork](https://github.com/smira/aptly-fork) | 4 | 0 | 2019/07/04 | 2 years ago | aptly is a Debian repository management tool. |

### Other Software
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [croc](https://github.com/schollz/croc) | 15078 | 224 | 2017/10/17 | 21 hours ago | Easily and securely send files or folders from one computer to another. |
| [goreplay](https://github.com/buger/goreplay) | 14747 | 468 | 2013/05/30 | 2 days ago | Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time. |
| [restic](https://github.com/restic/restic) | 13882 | 234 | 2014/04/27 | 9 hours ago | De-duplicating backup program. |
| [seaweedfs](https://github.com/chrislusf/seaweedfs) | 12902 | 523 | 2014/07/14 | 2 minutes ago | Fast, Simple and Scalable Distributed File System with O(1) disk seek. |
| [confd](https://github.com/kelseyhightower/confd) | 7607 | 254 | 2013/10/01 | 2 months ago | Manage local application configuration files using templates and data from etcd or consul. |
| [comcast](https://github.com/tylertreat/comcast) | 7579 | 150 | 2014/11/12 | 4 months ago | Simulate bad network connections. |
| [liteide](https://github.com/visualfc/liteide) | 6587 | 367 | 2012/11/19 | 3 months ago | LiteIDE is a simple, open source, cross-platform Go IDE. |
| [drive](https://github.com/odeke-em/drive) | 6159 | 192 | 2014/11/03 | 7 months ago | Google Drive client for the commandline. |
| [toxiproxy](https://github.com/Shopify/toxiproxy) | 5795 | 344 | 2014/09/04 | 1 week ago | Proxy to simulate network and system conditions for automated tests. |
| [nes](https://github.com/fogleman/nes) | 4887 | 146 | 2015/03/02 | 3 months ago | Nintendo Entertainment System (NES) emulator written in Go. |
| [duplicacy](https://github.com/gilbertchen/duplicacy) | 3815 | 97 | 2016/02/23 | 1 month ago | A cross-platform network and cloud backup tool based on the idea of lock-free deduplication. |
| [scc](https://github.com/boyter/scc) | 2777 | 27 | 2018/03/01 | 2 days ago | Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates. |
| [mylg](https://github.com/mehrdadrad/mylg) | 2508 | 113 | 2016/06/21 | 1 year ago | Command Line Network Diagnostic tool written in Go. |
| [goboy](https://github.com/Humpheh/goboy) | 2385 | 44 | 2017/08/20 | 1 year ago | Nintendo Game Boy Color emulator written in Go. |
| [sup](https://github.com/pressly/sup) | 2283 | 72 | 2015/02/23 | 3 months ago | Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers. |
| [lgo](https://github.com/yunabe/lgo) | 2212 | 50 | 2017/10/05 | 10 months ago | Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility. |
| [circuit](https://github.com/gocircuit/circuit) | 1916 | 139 | 2014/04/10 | 1 year ago | Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications. |
| [snap](https://github.com/intelsdi-x/snap) | 1795 | 144 | 2014/08/13 | 2 years ago | Powerful telemetry framework. |
| [borg](https://github.com/ok-borg/borg) | 1523 | 41 | 2016/09/10 | 3 years ago | Terminal based search engine for bash snippets. |
| [community](https://github.com/documize/community) | 1401 | 53 | 2016/04/29 | 1 week ago | Modern wiki software that integrates data from SaaS tools. |
| [Go-Package-Store](https://github.com/shurcooL/Go-Package-Store) | 888 | 22 | 2014/01/24 | 1 year ago | App that displays updates for the Go packages in your GOPATH. |
| [shell2http](https://github.com/msoap/shell2http) | 836 | 25 | 2015/03/11 | 1 month ago | Executing shell commands via http server (for prototyping or remote control). |
| [vflow](https://github.com/EdgeCast/vflow) | 833 | 84 | 2017/02/24 | 2 months ago | High-performance, scalable and reliable IPFIX, sFlow and Netflow collector. |
| [peg](https://github.com/pointlander/peg) | 816 | 28 | 2010/04/25 | 1 month ago | Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. |
| [vflow](https://github.com/VerizonDigital/vflow) | 813 | 84 | 2017/02/24 | 6 months ago | High-performance, scalable and reliable IPFIX, sFlow and Netflow collector. |
| [leaps](https://github.com/Jeffail/leaps) | 707 | 28 | 2014/06/19 | 7 months ago | Pair programming service using Operational Transforms. |
| [gfile](https://github.com/Antonito/gfile) | 631 | 12 | 2019/03/08 | 7 months ago | Securely transfer files between two computers, without any third party, over WebRTC. |
| [guora](https://github.com/meloalright/guora) | 557 | 14 | 2020/08/13 | 10 months ago | A self-hosted Quora like web application written in Go. |
| [gebug](https://github.com/moshebe/gebug) | 551 | 5 | 2020/07/20 | 1 day ago | A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly. |
| [gocc](https://github.com/goccmack/gocc) | 498 | 21 | 2015/06/05 | 5 months ago | Gocc is a compiler kit for Go written in Go. |
| [mockingjay-server](https://github.com/quii/mockingjay-server) | 497 | 9 | 2015/04/04 | 8 months ago | Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests. |
| [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) | 436 | 20 | 2015/10/08 | 2 months ago | Video streaming torrent client. |
| [ipe](https://github.com/dimiro1/ipe) | 330 | 18 | 2015/01/13 | 6 months ago | Open source Pusher server implementation compatible with Pusher client libraries written in GO. |
| [IDE](https://github.com/thestrukture/IDE) | 322 | 19 | 2017/09/09 | 2 months ago | Browser accessible IDE. Designed for Go with Go. |
| [tcpprobe](https://github.com/mehrdadrad/tcpprobe) | 306 | 9 | 2020/10/26 | 7 months ago | TCP tool for network performance and path monitoring, including socket statistics. |
| [wellington](https://github.com/wellington/wellington) | 300 | 13 | 2014/12/08 | 11 months ago | Sass project management tool, extends the language with sprite functions (like Compass). |
| [woke](https://github.com/get-woke/woke) | 276 | 7 | 2020/08/31 | 1 day ago | Detect non-inclusive language in your source code. |
| [cherry](https://github.com/rafael-santiago/cherry) | 253 | 12 | 2015/10/24 | 4 years ago | Tiny webchat server in Go. |
| [orange-cat](https://github.com/utatti/orange-cat) | 182 | 5 | 2014/11/01 | 2 years ago | Markdown previewer written in Go. |
| [orange-cat](https://github.com/hatashiro/orange-cat) | 182 | 5 | 2014/11/01 | 2 years ago | Markdown previewer written in Go. |
| [joincap](https://github.com/assafmo/joincap) | 169 | 8 | 2018/05/31 | 6 months ago | Command-line utility for merging multiple pcap files together. |
| [orbit](https://github.com/gulien/orbit) | 153 | 9 | 2017/05/13 | 8 months ago | A simple tool for running commands and generating files from templates. |
| [vaku](https://github.com/lingrino/vaku) | 122 | 3 | 2018/04/24 | 3 days ago | CLI & API for folder-based functions in Vault like copy, move, and search. |
| [dp](https://github.com/scryinfo/dp) | 83 | 11 | 2018/12/12 | 2 months ago | Through SDK for data exchange with blockchain, developers can get easy access to DAPP development. |
| [boxed](https://github.com/tejo/boxed) | 76 | 3 | 2015/04/18 | 3 years ago | Dropbox based blog engine. |
| [naclpipe](https://github.com/unix4fun/naclpipe) | 22 | 6 | 2015/05/05 | 2 years ago | Simple NaCL EC25519 based crypto pipe tool written in Go. |
| [term-quiz](https://github.com/crazcalm/term-quiz) | 18 | 1 | 2017/12/26 | 2 years ago | Quizzes for your terminal. |
| [snitch](https://github.com/lucasgomide/snitch) | 15 | 1 | 2017/04/06 | 3 years ago | Simple way to notify your team and many tools when someone has deployed any application via Tsuru. |
| [GoDocTooltip](https://github.com/diankong/GoDocTooltip) | 14 | 3 | 2016/01/21 | 8 months ago | Chrome extension for Go Doc sites, which shows function description as tooltip at function list. |

# Resources
        
*Where to discover new Go libraries.*

## Benchmarks
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) | 1561 | 84 | 2016/04/06 | 1 month ago | Go web framework benchmark. |
| [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) | 1525 | 60 | 2013/12/16 | 2 months ago | Go HTTP request router benchmark and comparison. |
| [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) | 1210 | 38 | 2013/01/18 | 2 days ago | Benchmarks of Go serialization methods. |
| [skynet](https://github.com/atemerev/skynet) | 994 | 50 | 2016/02/14 | 4 months ago | Skynet 1M threads microbenchmark. |
| [speedtest-resize](https://github.com/fawick/speedtest-resize) | 213 | 7 | 2013/09/16 | 11 months ago | Compare various Image resize algorithms for the Go language. |
| [go-benchmarks](https://github.com/tylertreat/go-benchmarks) | 139 | 11 | 2016/02/25 | 5 years ago | Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches. |
| [gospeed](https://github.com/feyeleanor/gospeed) | 108 | 7 | 2011/05/23 | 7 months ago | Go micro-benchmarks for calculating the speed of language constructs. |
| [autobench](https://github.com/davecheney/autobench) | 91 | 9 | 2013/03/28 | 7 years ago | Framework to compare the performance between different Go versions. |
| [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) | 60 | 5 | 2014/09/24 | 3 years ago | Collection of benchmarks for popular Go database/SQL utilities. |
| [gocostmodel](https://github.com/mna/gocostmodel) | 57 | 6 | 2014/12/19 | 4 months ago | Benchmarks of common basic operations for the Go language. |
| [kvbench](https://github.com/jimrobinson/kvbench) | 22 | 1 | 2014/04/15 | 2 years ago | Key/Value database benchmark. |
| [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) | 21 | 2 | 2017/01/24 | 4 years ago | Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results. |
| [go-json-benchmark](https://github.com/zerosnake0/go-json-benchmark) | 5 | 2 | 2019/11/10 | 1 year ago | Go JSON benchmark. |

## Conferences
        

## E-Books
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [GoBooks](https://github.com/dariubs/GoBooks) | 10158 | 588 | 2015/05/05 | 3 days ago | A curated list of Go books. |
| [The-Golang-Standard-Library-by-Example](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example) | 8093 | 590 | 2013/04/14 | 2 months ago | Golang标准库。对于程序员而言，标准库与语言本身同样重要，它好比一个百宝箱，能为各种常见的任务提供完美的解决方案。以示例驱动的方式讲解Golang的标准库。 |
| [gosuccinctly](https://github.com/thedevsir/gosuccinctly) | 18 | 4 | 2018/09/02 | 3 years ago | in Persian. |

## Gophers
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gophers](https://github.com/ashleymcnamara/gophers) | 2511 | 98 | 2017/02/15 | 2 years ago | Gopher artworks by Ashley McNamara. |
| [gophers](https://github.com/egonelbre/gophers) | 2475 | 58 | 2015/06/03 | 1 year ago | Free gophers. |
| [free-gophers-pack](https://github.com/MariaLetta/free-gophers-pack) | 2303 | 60 | 2019/04/02 | 1 year ago | Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster. |
| [gophericons](https://github.com/shalakhin/gophericons) | 589 | 20 | 2015/08/22 | 3 years ago | 34 gopher images for Go developers community |
| [gopherize.me](https://github.com/matryer/gopherize.me) | 519 | 8 | 2017/01/25 | 1 month ago | Gopherize yourself. |
| [gopher-stickers](https://github.com/tenntenn/gopher-stickers) | 511 | 14 | 2014/11/09 | 1 year ago | gopher stickers |
| [gopher-vector](https://github.com/golang-samples/gopher-vector) | 392 | 12 | 2013/03/31 | 5 years ago | Vector data of gopher |
| [go-gopher](https://github.com/sillecelik/go-gopher) | 100 | 0 | 2018/03/28 | 1 month ago | Gopher amigurumi toy pattern. |
| [gopher-logos](https://github.com/GolangUA/gopher-logos) | 95 | 9 | 2017/07/27 | 3 months ago | adorable gopher logos. |
| [gophers](https://github.com/rogeralsing/gophers) | 54 | 2 | 2017/01/28 | 1 year ago | random gopher graphics. |
| [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) | 41 | 2 | 2014/09/03 | 3 years ago | Go gopher Vector Data [.ai, .svg]. |

## Meetups
        
*Add the group of your city/country here (send **PR**)*

## Twitter
        

## Websites
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) | 28040 | 1725 | 2014/07/08 | 3 months ago | List of other amazingly awesome lists. |
| [awesome-remote-job](https://github.com/lukasz-madon/awesome-remote-job) | 21004 | 1001 | 2015/01/02 | 1 week ago | Curated list of awesome remote jobs. A lot of them are looking for Go hackers. |
| [golang-graphics](https://github.com/mholt/golang-graphics) | 140 | 8 | 2014/03/24 | 6 years ago | Collection of Go images, graphics, and art. |
| [gocryforhelp](https://github.com/ninedraft/gocryforhelp) | 39 | 11 | 2016/05/09 | 4 years ago | Collection of Go projects that needs help. Good place to start your open-source way in Go. |

### Tutorials
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [build-web-application-with-golang](https://github.com/astaxie/build-web-application-with-golang) | 38751 | 2458 | 2012/08/02 | 1 day ago | Golang ebook intro how to build a web app with golang. |
| [go-patterns](https://github.com/tmrts/go-patterns) | 17333 | 614 | 2015/12/14 | 1 month ago | Curated list of Go design patterns, recipes and idioms. |
| [learn-go-with-tests](https://github.com/quii/learn-go-with-tests) | 15466 | 316 | 2018/03/02 | 4 days ago | Learn Go with test-driven development. |
| [golang-cheat-sheet](https://github.com/a8m/golang-cheat-sheet) | 5842 | 194 | 2014/02/13 | 5 months ago | Go's reference card. |
| [golang-for-nodejs-developers](https://github.com/miguelmota/golang-for-nodejs-developers) | 2612 | 41 | 2019/01/03 | 3 weeks ago | Examples of Golang compared to Node.js for learning. |
| [working-with-go](https://github.com/mkaz/working-with-go) | 1161 | 49 | 2014/05/04 | 1 year ago | Intro to go for experienced programmers. |
| [ethereum-development-with-go-book](https://github.com/miguelmota/ethereum-development-with-go-book) | 945 | 46 | 2018/05/16 | 3 months ago | A little e-book on Ethereum Development with Go. |
| [goapp](https://github.com/bnkamalesh/goapp) | 283 | 9 | 2020/07/04 | 8 months ago | An opinionated guideline to structure & develop a Go web application/service. |
| [design-patterns](https://github.com/shubhamzanwar/design-patterns) | 59 | 4 | 2020/09/24 | 10 months ago | Collection of programming design patterns implemented in Go. |

## Style Guides
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-styleguide](https://github.com/bahlo/go-styleguide) | 1136 | 31 | 2017/07/29 | 4 days ago | 🏆 Opinionated Styleguide for the Go language |

> 该项目源码[Awesome Go Analysis](https://github.com/plholx/awesome-go-analysis)
> 更专业的go开源项目分析请移步 [Awesome Go](https://go.libhunt.com/)
