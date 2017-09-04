this is a processed copy of https://raw.githubusercontent.com/avelino/awesome-go/master/README.md

# Awesome Go [![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Join the chat at https://gitter.im/avelino/awesome-go](https://badges.gitter.im/avelino/awesome-go.svg)](https://gitter.im/avelino/awesome-go?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A curated list of awesome Go frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

### Contents

- [Awesome Go](#awesome-go)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [Date and Time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Files](#files)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [IoT](#iot-internet-of-things)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Query Language](#query-language)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
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

- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)

- [Server Applications](#server-applications)

- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)

## Audio and Music

*Libraries for manipulating audio.*

* [flac](https://github.com/eaburns/flac) - Native Go FLAC decoder. -> _stars: *71*, forks: 7, open issues:2_
* [flac](https://github.com/mewkiz/flac) - Native Go FLAC decoder. -> _stars: *51*, forks: 12, open issues:2_
* [gaad](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser. -> _stars: *30*, forks: 2, open issues:1_
* [go-sox](https://github.com/krig/go-sox) - libsox bindings for go. -> _stars: *50*, forks: 8, open issues:5_
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) - libmediainfo bindings for go. -> _stars: *16*, forks: 4, open issues:0_
* [gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go. -> _stars: *3*, forks: 0, open issues:0_
* [id3v2](https://github.com/bogem/id3v2) - Fast and stable ID3 parsing and writing library for Go. -> _stars: *48*, forks: 7, open issues:2_
* [mix](https://github.com/go-mix/mix) - Sequence-based Go-native audio mixer for music apps. -> _stars: *63*, forks: 11, open issues:11_
* [mp3](https://github.com/tcolgate/mp3) - Native Go MP3 decoder. -> _stars: *59*, forks: 7, open issues:0_
* [music-theory](https://github.com/go-music-theory/music-theory) - Music theory models in Go. -> _stars: *168*, forks: 16, open issues:6_
* [PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library. -> _stars: *149*, forks: 31, open issues:2_
* [portmidi](https://github.com/rakyll/portmidi) - Go bindings for PortMidi. -> _stars: *137*, forks: 38, open issues:10_
* [taglib](https://github.com/wtolson/go-taglib) - Go bindings for taglib. -> _stars: *52*, forks: 16, open issues:3_
* [vorbis](https://github.com/mccoyst/vorbis) - "Native" Go Vorbis decoder (uses CGO, but has no dependencies). -> _stars: *16*, forks: 5, open issues:2_
* [waveform](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams. -> _stars: *189*, forks: 10, open issues:2_

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* [authboss](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time. -> _stars: *1182*, forks: 83, open issues:35_
* [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC. -> _stars: *1135*, forks: 123, open issues:4_
* [Go-AWS-Auth](https://github.com/smartystreets/go-aws-auth) - AWS (Amazon Web Services) request signing library. -> _stars: *174*, forks: 38, open issues:17_
* [go-jose](https://github.com/square/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. -> _stars: *726*, forks: 93, open issues:16_
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - Standalone, specification-compliant,  OAuth2 server written in Golang. -> _stars: *616*, forks: 71, open issues:5_
* [go.auth](https://github.com/bradrydzewski/go.auth) - Authentication API for Go web applications. -> _stars: *347*, forks: 30, open issues:9_
* [gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers. -> _stars: *769*, forks: 37, open issues:2_
* [gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang. -> _stars: *596*, forks: 100, open issues:1_
* [goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple provides out of the box. -> _stars: *1305*, forks: 153, open issues:20_
* [httpauth](https://github.com/goji/httpauth) - HTTP Authentication middleware. -> _stars: *120*, forks: 16, open issues:1_
* [jwt](https://github.com/robbert229/jwt) - Clean and easy to use implementation of JSON Web Tokens (JWT). -> _stars: *20*, forks: 6, open issues:7_
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT middleware for goLang http servers with many configuration options. -> _stars: *75*, forks: 6, open issues:0_
* [jwt-go](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT). -> _stars: *2491*, forks: 274, open issues:37_
* [loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam. -> _stars: *442*, forks: 25, open issues:11_
* [oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support. -> _stars: *1242*, forks: 318, open issues:40_
* [osin](https://github.com/RangelReale/osin) - Golang OAuth2 server library. -> _stars: *1219*, forks: 248, open issues:31_
* [permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt. -> _stars: *237*, forks: 13, open issues:2_
* [session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE). -> _stars: *37*, forks: 3, open issues:3_
* [sessions](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers. -> _stars: *23*, forks: 0, open issues:1_
* [traefik](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends. -> _stars: *9546*, forks: 890, open issues:303_
* [yubigo](https://github.com/GeertJohan/yubigo) - Yubikey client package that provides a simple API to integrate the Yubico Yubikey into a go application. -> _stars: *75*, forks: 10, open issues:3_

## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [argv](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax. -> _stars: *2*, forks: 0, open issues:0_
* [cli](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang tag. -> _stars: *299*, forks: 24, open issues:10_
* [cli-init](https://github.com/tcnksm/gcli) - The easy way to start building Golang command line application. -> _stars: *735*, forks: 63, open issues:18_
* [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
* [cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions. -> _stars: *5062*, forks: 419, open issues:77_
* [complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion. -> _stars: *197*, forks: 8, open issues:3_
* [docopt.go](https://github.com/docopt/docopt.go) - Command-line arguments parser that will make you smile. -> _stars: *852*, forks: 69, open issues:23_
* [drive](https://github.com/odeke-em/drive) - Google Drive client for the commandline. -> _stars: *3460*, forks: 275, open issues:167_
* [env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs. -> _stars: *5*, forks: 0, open issues:0_
* [flag](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go support subcommand. -> _stars: *70*, forks: 2, open issues:3_
* [go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go. -> _stars: *425*, forks: 19, open issues:1_
* [go-flags](https://github.com/jessevdk/go-flags) - go command line option parser. -> _stars: *873*, forks: 117, open issues:14_
* [kingpin](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands. -> _stars: *1431*, forks: 97, open issues:11_
* [liner](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces. -> _stars: *390*, forks: 63, open issues:2_
* [mitchellh/cli](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces. -> _stars: *663*, forks: 53, open issues:8_
* [mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation. -> _stars: *423*, forks: 27, open issues:5_
* [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags. -> _stars: *238*, forks: 85, open issues:11_
* [readline](https://github.com/chzyer/readline) - Pure golang implementation that provide most of features in GNU-Readline under MIT license. -> _stars: *859*, forks: 75, open issues:38_
* [sflags](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries. -> _stars: *44*, forks: 3, open issues:3_
* [ukautz/clif](https://github.com/ukautz/clif) - Small command line interface framework. -> _stars: *77*, forks: 8, open issues:5_
* [urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli). -> _stars: *6414*, forks: 593, open issues:77_
* [wlog](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency. -> _stars: *19*, forks: 2, open issues:0_
* [wmenu](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompts users to make choices. -> _stars: *34*, forks: 4, open issues:1_

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [aurora](https://github.com/logrusorgru/aurora) - ANSI terminal colors that supports fmt.Printf/Sprintf. -> _stars: *243*, forks: 7, open issues:0_
* [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output. -> _stars: *208*, forks: 13, open issues:2_
* [color](https://github.com/fatih/color) - Versatile package for colored terminal output. -> _stars: *1792*, forks: 139, open issues:4_
* [colourize](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals. -> _stars: *11*, forks: 2, open issues:0_
* [go-ataman](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals. -> _stars: *1*, forks: 0, open issues:0_
* [go-colorable](https://github.com/mattn/go-colorable) - Colorable writer for windows. -> _stars: *200*, forks: 32, open issues:3_
* [go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals. -> _stars: *160*, forks: 10, open issues:2_
* [go-isatty](https://github.com/mattn/go-isatty) - isatty for golang. -> _stars: *171*, forks: 20, open issues:0_
* [gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces. -> _stars: *1880*, forks: 120, open issues:7_
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text. -> _stars: None, forks: None, open issues:None_
* [mpb](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications. -> _stars: *94*, forks: 9, open issues:1_
* [termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces. -> _stars: *2340*, forks: 206, open issues:38_
* [termtables](https://github.com/apcera/termtables) - Go port of the Ruby library [terminal-tables](https://github.com/tj/terminal-table) for simple ASCII table generation as well as providing markdown and HTML output. -> _stars: *100*, forks: 14, open issues:6_
* [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib). -> _stars: *6397*, forks: 353, open issues:69_
* [uilive](https://github.com/gosuri/uilive) - Library for updating terminal output in realtime. -> _stars: *565*, forks: 23, open issues:10_
* [uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications. -> _stars: *983*, forks: 47, open issues:10_
* [uitable](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data. -> _stars: *387*, forks: 13, open issues:2_

## Configuration

*Libraries for configuration parsing.*

* [config](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing. -> _stars: *123*, forks: 23, open issues:2_
* [configure](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables. -> _stars: *28*, forks: 3, open issues:0_
* [env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults). -> _stars: *303*, forks: 28, open issues:1_
* [envcfg](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs. -> _stars: *81*, forks: 5, open issues:0_
* [envconf](https://github.com/ian-kent/envconf) - Configuration from environment. -> _stars: *5*, forks: 2, open issues:0_
* [envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables. -> _stars: *108*, forks: 9, open issues:1_
* [gcfg](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections. -> _stars: *66*, forks: 17, open issues:3_
* [goConfig](https://github.com/crgimenes/goConfig) - Parse a struct as input and populates the fields of this struct with parameters fom command line, environment variables and configuration file. -> _stars: *43*, forks: 9, open issues:3_
* [godotenv](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`). -> _stars: *661*, forks: 45, open issues:10_
* [gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy. -> _stars: *43*, forks: 6, open issues:0_
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep you config structs along the code they configure and delegate parsing to submodules without sacrificing full config serialization. -> _stars: None, forks: None, open issues:None_
* [hjson](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments. -> _stars: *93*, forks: 9, open issues:0_
* [ingo](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file. -> _stars: *13*, forks: 1, open issues:0_
* [ini](https://github.com/go-ini/ini) - Go package for read and write INI files. -> _stars: *653*, forks: 123, open issues:9_
* [joshbetz/config](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP. -> _stars: *142*, forks: 7, open issues:1_
* [mini](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files. -> _stars: *12*, forks: 4, open issues:0_
* [store](https://github.com/tucnak/store) - Lightweight configuration manager for Go. -> _stars: *207*, forks: 8, open issues:0_
* [viper](https://github.com/spf13/viper) - Go configuration with fangs. -> _stars: *3586*, forks: 372, open issues:143_
* [xdg](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html). -> _stars: *0*, forks: 0, open issues:0_

## Continuous Integration

*Tools for help with continuous integration.*

* [drone](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go. -> _stars: *10905*, forks: 1232, open issues:109_
* [goveralls](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system. -> _stars: *410*, forks: 65, open issues:9_
* [overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls. -> _stars: *65*, forks: 16, open issues:1_
* [roveralls](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool. -> _stars: *1*, forks: 0, open issues:0_

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* [c6](https://github.com/c9s/c6) - High performance SASS compatible-implementation compiler written in Go. -> _stars: *379*, forks: 24, open issues:47_
* [gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor. -> _stars: *384*, forks: 24, open issues:7_
* [go-libsass](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project. -> _stars: *60*, forks: 8, open issues:9_

## Data Structures

*Generic datastructures and algorithms in Go.*

* [binpacker](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream. -> _stars: *50*, forks: 11, open issues:0_
* [bit](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions. -> _stars: *4*, forks: 1, open issues:0_
* [bitset](https://github.com/willf/bitset) - Go package implementing bitsets. -> _stars: *303*, forks: 62, open issues:0_
* [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go. -> _stars: *103*, forks: 10, open issues:0_
* [bloom](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation. -> _stars: *2*, forks: 0, open issues:0_
* [boomfilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams. -> _stars: *845*, forks: 50, open issues:5_
* [count-min-log](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory). -> _stars: *32*, forks: 4, open issues:0_
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. -> _stars: *235*, forks: 17, open issues:2_
* [encoding](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go. -> _stars: *74*, forks: 9, open issues:1_
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree. -> _stars: *21*, forks: 4, open issues:0_
* [go-datastructures](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures. -> _stars: *3389*, forks: 333, open issues:8_
* [go-geoindex](https://github.com/hailocab/go-geoindex) - In-memory geo index. -> _stars: *258*, forks: 32, open issues:2_
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding. -> _stars: *71*, forks: 2, open issues:1_
* [gods](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc. -> _stars: *3107*, forks: 270, open issues:9_
* [golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go. -> _stars: *592*, forks: 74, open issues:4_
* [goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go. -> _stars: *4*, forks: 1, open issues:0_
* [goskiplist](https://github.com/ryszard/goskiplist) - Skip list implementation in Go. -> _stars: *136*, forks: 30, open issues:1_
* [gota](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go. -> _stars: *311*, forks: 36, open issues:10_
* [hilbert](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves. -> _stars: *94*, forks: 11, open issues:2_
* [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction. -> _stars: *545*, forks: 17, open issues:0_
* [levenshtein](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. -> _stars: *6*, forks: 0, open issues:0_
* [levenshtein](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go. -> _stars: *9*, forks: 1, open issues:0_
* [mafsa](https://github.com/smartystreets/mafsa) - MA-FSA implementation with Minimal Perfect Hashing. -> _stars: *254*, forks: 17, open issues:8_
* [merkletree](https://github.com/cbergoon/merkletree) - Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures. -> _stars: *7*, forks: 0, open issues:0_
* [roaring](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets. -> _stars: *274*, forks: 33, open issues:21_
* [skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go. -> _stars: *40*, forks: 8, open issues:1_
* [trie](https://github.com/derekparker/trie) - Trie implementation in Go. -> _stars: *198*, forks: 21, open issues:5_
* [ttlcache](https://github.com/diegobernardes/ttlcache) - In-memory LRU string-interface{} map with expiration for golang. -> _stars: *45*, forks: 5, open issues:1_
* [willf/bloom](https://github.com/willf/bloom) - Go package implementing Bloom filters. -> _stars: *351*, forks: 64, open issues:2_

## Database

*Databases implemented in Go.*

* [BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data. -> _stars: *1048*, forks: 73, open issues:3_
* [bolt](https://github.com/boltdb/bolt) - Low-level key/value database for Go. -> _stars: *6804*, forks: 553, open issues:107_
* [buntdb](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support. -> _stars: *1563*, forks: 97, open issues:2_
* [cache2go](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts. -> _stars: *312*, forks: 129, open issues:0_
* [cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore. -> _stars: *10972*, forks: 1098, open issues:1052_
* [couchcache](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server. -> _stars: *25*, forks: 2, open issues:0_
* [dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database. -> _stars: *3692*, forks: 189, open issues:64_
* [diskv](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store. -> _stars: *475*, forks: 46, open issues:2_
* [eliasdb](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language. -> _stars: *431*, forks: 15, open issues:2_
* [forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB. -> _stars: *27*, forks: 3, open issues:7_
* [GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC. -> _stars: *233*, forks: 31, open issues:8_
* [geocache](https://github.com/melihmucuk/geocache) - In-memory cache that is suitable for geolocation based applications. -> _stars: *68*, forks: 2, open issues:0_
* [go-cache](https://github.com/pmylund/go-cache) - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications. -> _stars: *1061*, forks: 195, open issues:27_
* [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in the Go. -> _stars: *1740*, forks: 224, open issues:24_
* [groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. -> _stars: *5713*, forks: 663, open issues:10_
* [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics. -> _stars: *11395*, forks: 1625, open issues:555_
* [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB. -> _stars: *2222*, forks: 262, open issues:83_
* [levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB. -> _stars: *306*, forks: 63, open issues:3_
* [moss](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go. -> _stars: *346*, forks: 23, open issues:36_
* [piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures. -> _stars: *139*, forks: 14, open issues:11_
* [prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database. -> _stars: *11390*, forks: 1285, open issues:227_
* [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite. -> _stars: *3140*, forks: 154, open issues:30_
* [Scribble](https://github.com/nanobox-io/golang-scribble) - Tiny flat file JSON store. -> _stars: *70*, forks: 19, open issues:5_
* [tempdb](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items. -> _stars: *6*, forks: 1, open issues:0_
* [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1. -> _stars: *9368*, forks: 1287, open issues:335_
* [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang. -> _stars: *1896*, forks: 169, open issues:14_
* [Tile38](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing. -> _stars: *3337*, forks: 156, open issues:44_

*Database schema migration.*

* [darwin](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go. -> _stars: *42*, forks: 4, open issues:0_
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library. -> _stars: *2*, forks: 3, open issues:0_
* [goose](https://github.com/steinbacher/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. -> _stars: *48*, forks: 7, open issues:5_
* [gormigrate](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM. -> _stars: *60*, forks: 6, open issues:0_
* [migrate](https://github.com/mattes/migrate) - Database migrations. CLI and Golang library. -> _stars: *1526*, forks: 252, open issues:42_
* [pravasan](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to support soon for Postgres, SQLite, MongoDB, etc. -> _stars: *18*, forks: 3, open issues:30_
* [soda](https://github.com/markbates/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. -> _stars: None, forks: None, open issues:None_
* [sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata. -> _stars: *743*, forks: 78, open issues:31_

*Database tools.*

* [go-mysql](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication. -> _stars: *632*, forks: 166, open issues:20_
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically. -> _stars: *855*, forks: 202, open issues:52_
* [kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang. -> _stars: *2884*, forks: 589, open issues:43_
* [myreplication](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Support statement and row based replication. -> _stars: *82*, forks: 28, open issues:3_
* [orchestrator](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer. -> _stars: *839*, forks: 112, open issues:61_
* [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser. -> _stars: *4466*, forks: 286, open issues:21_
* [pREST](https://github.com/nuveo/prest) - Serve a RESTful API from any PostgreSQL database. -> _stars: *1408*, forks: 45, open issues:22_
* [vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. -> _stars: *4929*, forks: 645, open issues:111_

*SQL query builder, libraries for building and using SQL.*

* [dat](https://github.com/mgutz/dat) - Go Postgres Data Access Toolkit. -> _stars: *456*, forks: 38, open issues:25_
* [Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use it with ease. -> _stars: *306*, forks: 19, open issues:2_
* [goqu](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library. -> _stars: *334*, forks: 33, open issues:9_
* [igor](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax. -> _stars: *61*, forks: 2, open issues:0_
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities. -> _stars: *174*, forks: 24, open issues:5_
* [scaneo](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs. -> _stars: *109*, forks: 8, open issues:3_
* [sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance. -> _stars: *79*, forks: 6, open issues:1_
* [Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries. -> _stars: *1195*, forks: 98, open issues:32_
* [xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server. -> _stars: *1243*, forks: 102, open issues:41_

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [avatica](https://github.com/Boostport/avatica) - Apache Phoenix/Avatica SQL driver for database/sql. -> _stars: *32*, forks: 7, open issues:0_
    * [bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go. -> _stars: *5*, forks: 2, open issues:0_
    * [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go. -> _stars: *64*, forks: 15, open issues:9_
    * [go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that using database/sql. -> _stars: *59*, forks: 25, open issues:10_
    * [go-bqstreamer](https://github.com/rounds/go-bqstreamer) - BigQuery fast and concurrent stream insert. -> _stars: *130*, forks: 14, open issues:5_
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go. -> _stars: *588*, forks: 121, open issues:50_
    * [go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that using database/sql. -> _stars: *228*, forks: 131, open issues:52_
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go. -> _stars: *4076*, forks: 882, open issues:61_
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that using database/sql. -> _stars: *1964*, forks: 448, open issues:68_
    * [gofreetds](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org). -> _stars: *50*, forks: 25, open issues:10_
    * [pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql. -> _stars: *1093*, forks: 124, open issues:35_
    * [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql. -> _stars: *3132*, forks: 427, open issues:122_

* NoSQL Databases
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language. -> _stars: *230*, forks: 93, open issues:10_
    * [arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB. -> _stars: *50*, forks: 14, open issues:3_
    * [asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go. -> _stars: *2*, forks: 1, open issues:0_
    * [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends. -> _stars: *10421*, forks: 899, open issues:65_
    * [dsc](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files. -> _stars: *4*, forks: 2, open issues:0_
    * [dynago](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB. -> _stars: None, forks: None, open issues:None_
    * [go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go. -> _stars: *246*, forks: 78, open issues:31_
    * [go-couchdb](https://github.com/fjl/go-couchdb) - Yet another CouchDB HTTP API wrapper for Go. -> _stars: *45*, forks: 22, open issues:16_
    * [gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK. -> _stars: *223*, forks: 58, open issues:0_
    * [gocql](http://gocql.github.io) - Go language driver for Apache Cassandra.
    * [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language. -> _stars: None, forks: None, open issues:None_
    * [gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB. -> _stars: *1217*, forks: 133, open issues:9_
    * [goriak](https://github.com/zegl/goriak) - Go language driver for Riak KV. -> _stars: None, forks: None, open issues:None_
    * [mgo](https://godoc.org/labix.org/v2/mgo) - MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
    * [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang. -> _stars: *22*, forks: 3, open issues:8_
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang. -> _stars: *65*, forks: 14, open issues:1_
    * [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang. -> _stars: None, forks: None, open issues:None_
    * [redigo](https://github.com/garyburd/redigo) - Redigo is a Go client for the Redis database. -> _stars: None, forks: None, open issues:None_
    * [redis](https://github.com/go-redis/redis) - Redis client for Golang. -> _stars: None, forks: None, open issues:None_
    * [redis](https://github.com/hoisie/redis) - Simple, powerful Redis client for Go. -> _stars: None, forks: None, open issues:None_
    * [redis](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services. -> _stars: None, forks: None, open issues:None_
    * [xredis](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client. -> _stars: None, forks: None, open issues:None_

* Search and Analytic Databases.
    * [bleve](https://github.com/blevesearch/bleve) - Modern text indexing library for go. -> _stars: None, forks: None, open issues:None_
    * [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go. -> _stars: *1633*, forks: 378, open issues:25_
    * [elasticsql](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go. -> _stars: *95*, forks: 14, open issues:4_
    * [elastigo](https://github.com/mattbaird/elastigo) - Elasticsearch client library. -> _stars: None, forks: None, open issues:None_
    * [goes](https://github.com/belogik/goes) - Library to interact with Elasticsearch. -> _stars: None, forks: None, open issues:None_
    * [skizze](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage. -> _stars: None, forks: None, open issues:None_

## Date and Time

*Libraries for working with dates and times.*

* [carbon](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library. -> _stars: *124*, forks: 12, open issues:5_
* [dateparse](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance. -> _stars: *38*, forks: 7, open issues:2_
* [durafmt](https://github.com/hako/durafmt) - Uime duration formatting library for Go. -> _stars: None, forks: None, open issues:None_
* [feiertage](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecoast, Thanksgiving... -> _stars: None, forks: None, open issues:None_
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang). -> _stars: *26*, forks: 2, open issues:0_
* [goweek](https://github.com/grsmv/goweek) - Library for working with week entity in golang. -> _stars: *12*, forks: 3, open issues:0_
* [now](https://github.com/jinzhu/now) - Now is a time toolkit for golang. -> _stars: *951*, forks: 53, open issues:5_
* [NullTime](https://github.com/kirillDanshin/nulltime) - Nullable `time.Time`. -> _stars: *3*, forks: 1, open issues:0_
* [timeutil](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package. -> _stars: *139*, forks: 4, open issues:0_
* [tuesday](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function. -> _stars: *1*, forks: 0, open issues:1_

## Distributed Systems

*Packages that help with building Distributed Systems.*

* [celeriac](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go. -> _stars: *26*, forks: 3, open issues:0_
* [digota](https://github.com/digota/digota) - grpc ecommerce microservice. -> _stars: *131*, forks: 8, open issues:9_
* [drmaa](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard. -> _stars: *18*, forks: 10, open issues:0_
* [flowgraph](https://github.com/vectaport/flowgraph) - MPI-style ready-send coordination layer. -> _stars: None, forks: None, open issues:None_
* [gleam](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed. -> _stars: *849*, forks: 87, open issues:5_
* [glow](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go. -> _stars: None, forks: None, open issues:None_
* [go-jump](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function. -> _stars: *127*, forks: 11, open issues:0_
* [go-kit](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc. -> _stars: *7596*, forks: 752, open issues:33_
* [gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load. -> _stars: None, forks: None, open issues:None_
* [grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC. -> _stars: None, forks: None, open issues:None_
* [hprose](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now. -> _stars: None, forks: None, open issues:None_
* [jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0. -> _stars: None, forks: None, open issues:None_
* [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation. -> _stars: *9*, forks: 2, open issues:0_
* [KrakenD](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway framework with middlewares. -> _stars: None, forks: None, open issues:None_
* [micro](https://github.com/micro/micro) - Pluggable microservice toolkit and distributed systems platform. -> _stars: *3500*, forks: 256, open issues:1_
* [NATS](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems. -> _stars: None, forks: None, open issues:None_
* [raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp. -> _stars: *1313*, forks: 167, open issues:56_
* [raft](https://github.com/coreos/etcd/tree/master/raft) - Go implementation of the Raft consensus protocol, by CoreOS. -> _stars: None, forks: None, open issues:None_
* [ringpop-go](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications. -> _stars: None, forks: None, open issues:None_
* [rpcx](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo. -> _stars: *1385*, forks: 245, open issues:11_
* [sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)). -> _stars: None, forks: None, open issues:None_
* [tendermint](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols. -> _stars: *624*, forks: 128, open issues:108_
* [torrent](https://github.com/anacrolix/torrent) - BitTorrent client package. -> _stars: None, forks: None, open issues:None_
    * [dht](https://godoc.org/github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation.
    * [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client. -> _stars: None, forks: None, open issues:None_

## Email

*Libraries that implement email creation and sending.*

* [douceur](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails. -> _stars: None, forks: None, open issues:None_
* [email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go. -> _stars: *791*, forks: 90, open issues:24_
* [go-dkim](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email. -> _stars: None, forks: None, open issues:None_
* [go-imap](https://github.com/emersion/go-imap) - IMAP library for clients and servers. -> _stars: None, forks: None, open issues:None_
* [go-message](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages. -> _stars: None, forks: None, open issues:None_
* [Gomail](https://github.com/go-gomail/gomail/) - Gomail is a very simple and powerful package to send emails. -> _stars: None, forks: None, open issues:None_
* [Hectane](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API. -> _stars: None, forks: None, open issues:None_
* [hermes](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails. -> _stars: None, forks: None, open issues:None_
* [MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface. -> _stars: None, forks: None, open issues:None_
* [SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email. -> _stars: None, forks: None, open issues:None_
* [smtp](https://github.com/mailhog/smtp) - SMTP server protocol state machine. -> _stars: None, forks: None, open issues:None_

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* [agora](https://github.com/PuerkitoBio/agora) - Dynamically typed, embeddable programming language in Go. -> _stars: None, forks: None, open issues:None_
* [anko](https://github.com/mattn/anko) - Scriptable interpreter written in Go. -> _stars: None, forks: None, open issues:None_
* [binder](https://github.com/alexeyco/binder) - Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua). -> _stars: None, forks: None, open issues:None_
* [gisp](https://github.com/jcla1/gisp) - Simple LISP in Go. -> _stars: None, forks: None, open issues:None_
* [go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go. -> _stars: None, forks: None, open issues:None_
* [go-lua](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go. -> _stars: None, forks: None, open issues:None_
* [go-php](https://github.com/deuill/go-php) - PHP bindings for Go. -> _stars: None, forks: None, open issues:None_
* [go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API. -> _stars: None, forks: None, open issues:None_
* [golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API. -> _stars: None, forks: None, open issues:None_
* [gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go. -> _stars: None, forks: None, open issues:None_
* [ngaro](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro. -> _stars: None, forks: None, open issues:None_
* [otto](https://github.com/robertkrimen/otto) - JavaScript interpreter written in Go. -> _stars: None, forks: None, open issues:None_
* [purl](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go. -> _stars: None, forks: None, open issues:None_

## Files

*Libraries for  handling files and file systems.*

* [afero](https://github.com/spf13/afero) - FileSystem Abstraction System for Go. -> _stars: None, forks: None, open issues:None_
* [go-csv-tag](https://github.com/artonge/go-csv-tag) - Load csv file using tag. -> _stars: None, forks: None, open issues:None_
* [go-gtfs](https://github.com/artonge/go-gtfs) - Load gtfs files in go. -> _stars: *3*, forks: 0, open issues:0_
* [notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal. -> _stars: None, forks: None, open issues:None_
* [skywalker](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease. -> _stars: *10*, forks: 1, open issues:0_
* [tarfs](https://github.com/posener/tarfs) - Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files. -> _stars: *11*, forks: 0, open issues:0_

## Financial

*Packages for accounting and finance.*

* [accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang. -> _stars: None, forks: None, open issues:None_
* [decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers. -> _stars: None, forks: None, open issues:None_
* [go-finance](https://github.com/FlashBoys/go-finance) - Comprehensive financial markets data in Go. -> _stars: None, forks: None, open issues:None_
* [go-money](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern. -> _stars: None, forks: None, open issues:None_
* [ofxgo](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client). -> _stars: None, forks: None, open issues:None_
* [vat](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates. -> _stars: None, forks: None, open issues:None_

## Forms

*Libraries for working with forms.*

* [bind](https://github.com/robfig/bind) - Bind form data to any Go values. -> _stars: None, forks: None, open issues:None_
* [binding](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct. -> _stars: None, forks: None, open issues:None_
* [conform](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags. -> _stars: None, forks: None, open issues:None_
* [form](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. -> _stars: None, forks: None, open issues:None_
* [formam](https://github.com/monoculum/formam) - decode form's values into a struct. -> _stars: None, forks: None, open issues:None_
* [forms](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. -> _stars: None, forks: None, open issues:None_
* [gorilla/csrf](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services. -> _stars: None, forks: None, open issues:None_
* [nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go. -> _stars: None, forks: None, open issues:None_

## Game Development

*Awesome game development libraries.*

* [Azul3D](https://github.com/azul3d/engine) - 3D game engine written in Go. -> _stars: None, forks: None, open issues:None_
* [Ebiten](https://github.com/hajimehoshi/ebiten) - simple 2D game library in Go. -> _stars: None, forks: None, open issues:None_
* [engo](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm. -> _stars: None, forks: None, open issues:None_
* [GarageEngine](https://github.com/vova616/GarageEngine) - 2d game engine written in Go working on OpenGL. -> _stars: None, forks: None, open issues:None_
* [glop](https://github.com/runningwild/glop) - Glop (Game Library Of Power) is a fairly simple cross-platform game library. -> _stars: None, forks: None, open issues:None_
* [go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm. -> _stars: None, forks: None, open issues:None_
* [go-collada](https://github.com/GlenKelley/go-collada) - Go package for working with the Collada file format. -> _stars: None, forks: None, open issues:None_
* [go-sdl2](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/). -> _stars: None, forks: None, open issues:None_
* [go3d](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go. -> _stars: None, forks: None, open issues:None_
* [gonet](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang. -> _stars: None, forks: None, open issues:None_
* [goworld](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping -> _stars: None, forks: None, open issues:None_
* [Leaf](https://github.com/name5566/leaf) - Lightweight game server framework. -> _stars: None, forks: None, open issues:None_
* [nano](https://github.com/lonnng/nano) - Lightweight, facility, high performance golang based game server framework -> _stars: None, forks: None, open issues:None_
* [Oak](https://github.com/oakmound/oak) - Pure Go game engine. -> _stars: None, forks: None, open issues:None_
* [Pixel](https://github.com/faiface/pixel) - Hand-crafted 2D game library in Go. -> _stars: None, forks: None, open issues:None_
* [raylib-go](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming. -> _stars: None, forks: None, open issues:None_
* [termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox. -> _stars: None, forks: None, open issues:None_

## Generation and Generics

*Tools to enhance the language with features like generics via code generation.*

* [efaceconv](https://github.com/t0pep0/efaceconv) - Code generation tool for high performance conversion from interface{} to immutable type without allocations. -> _stars: None, forks: None, open issues:None_
* [gen](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality. -> _stars: None, forks: None, open issues:None_
* [go-enum](https://github.com/abice/go-enum) - Code generation for enums from code comments. -> _stars: None, forks: None, open issues:None_
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go. -> _stars: None, forks: None, open issues:None_
* [interfaces](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions. -> _stars: None, forks: None, open issues:None_
* [jennifer](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates. -> _stars: None, forks: None, open issues:None_
* [pkgreflect](https://github.com/ungerik/pkgreflect) - Go preprocessor for package scoped reflection. -> _stars: None, forks: None, open issues:None_

## Go Compilers

*Tools for compiling Go to other languages.*

* [gopherjs](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript. -> _stars: None, forks: None, open issues:None_
* [llgo](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go. -> _stars: None, forks: None, open issues:None_
* [tardisgo](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler. -> _stars: None, forks: None, open issues:None_

## Goroutines

*Tools for managing and working with Goroutines.*

* [go-floc](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease. -> _stars: None, forks: None, open issues:None_
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order. -> _stars: None, forks: None, open issues:None_
* [goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker. -> _stars: None, forks: None, open issues:None_
* [grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool. -> _stars: None, forks: None, open issues:None_
* [pool](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation. -> _stars: None, forks: None, open issues:None_
* [semaphore](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context. -> _stars: None, forks: None, open issues:None_
* [tunny](https://github.com/Jeffail/tunny) - Goroutine pool for golang. -> _stars: None, forks: None, open issues:None_

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* [app](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. -> _stars: None, forks: None, open issues:None_
* [go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron). -> _stars: None, forks: None, open issues:None_
* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK.
* [go-qml](https://github.com/go-qml/qml) - QML support for the Go language. -> _stars: None, forks: None, open issues:None_
* [go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform. -> _stars: None, forks: None, open issues:None_
* [goqt](https://github.com/visualfc/goqt) - Golang bindings to the Qt cross-platform application framework. -> _stars: None, forks: None, open issues:None_
* [gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3. -> _stars: None, forks: None, open issues:None_
* [gowd](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform. -> _stars: None, forks: None, open issues:None_
* [qt](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi). -> _stars: None, forks: None, open issues:None_
* [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform. -> _stars: None, forks: None, open issues:None_
* [walk](https://github.com/lxn/walk) - Windows application library kit for Go. -> _stars: None, forks: None, open issues:None_

*Interaction*

* [gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go. -> _stars: None, forks: None, open issues:None_
* [robotgo](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation;Control the mouse, keyboard and other. -> _stars: None, forks: None, open issues:None_
* [systray](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area. -> _stars: None, forks: None, open issues:None_
* [trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar. -> _stars: None, forks: None, open issues:None_


## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## Images

*Libraries for manipulating images.*

* [bild](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go. -> _stars: None, forks: None, open issues:None_
* [bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips. -> _stars: None, forks: None, open issues:None_
* [geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string. -> _stars: None, forks: None, open issues:None_
* [gg](https://github.com/fogleman/gg) - 2D rendering in pure Go. -> _stars: None, forks: None, open issues:None_
* [gift](https://github.com/disintegration/gift) - Package of image processing filters. -> _stars: None, forks: None, open issues:None_
* [go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library. -> _stars: None, forks: None, open issues:None_
* [go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library. -> _stars: None, forks: None, open issues:None_
* [go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go. -> _stars: None, forks: None, open issues:None_
* [go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV. -> _stars: None, forks: None, open issues:None_
* [go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go. -> _stars: None, forks: None, open issues:None_
* [imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API. -> _stars: None, forks: None, open issues:None_
* [imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing. -> _stars: None, forks: None, open issues:None_
* [imaging](https://github.com/disintegration/imaging) - Simple Go image processing package. -> _stars: None, forks: None, open issues:None_
* [img](https://github.com/hawx/img) - Selection of image manipulation tools. -> _stars: None, forks: None, open issues:None_
* [ln](https://github.com/fogleman/ln) - 3D line art rendering in Go. -> _stars: None, forks: None, open issues:None_
* [mpo](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos. -> _stars: None, forks: None, open issues:None_
* [picfit](https://github.com/thoas/picfit) - An image resizing server written in Go. -> _stars: None, forks: None, open issues:None_
* [pt](https://github.com/fogleman/pt) - Path tracing engine written in Go. -> _stars: None, forks: None, open issues:None_
* [resize](https://github.com/nfnt/resize) - Image resizing for the Go with common interpolation methods. -> _stars: None, forks: None, open issues:None_
* [rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD. -> _stars: None, forks: None, open issues:None_
* [smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes. -> _stars: None, forks: None, open issues:None_
* [svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation. -> _stars: None, forks: None, open issues:None_
* [tga](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder. -> _stars: None, forks: None, open issues:None_

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* [connectordb](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT. -> _stars: None, forks: None, open issues:None_
* [devices](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io. -> _stars: None, forks: None, open issues:None_
* [eywa](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices. -> _stars: None, forks: None, open issues:None_
* [flogo](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration. -> _stars: None, forks: None, open issues:None_
* [gatt](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals. -> _stars: None, forks: None, open issues:None_
* [gobot](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things. -> _stars: None, forks: None, open issues:None_
* [mainflux](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server. -> _stars: None, forks: None, open issues:None_
* [sensorbee](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT. -> _stars: None, forks: None, open issues:None_

## Logging

*Libraries for generating and working with log files.*

* [glg](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go. -> _stars: None, forks: None, open issues:None_
* [glog](https://github.com/golang/glog) - Leveled execution logs for Go. -> _stars: None, forks: None, open issues:None_
* [go-cronowriter](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog. -> _stars: None, forks: None, open issues:None_
* [go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers. -> _stars: None, forks: None, open issues:None_
* [go-log](https://github.com/ian-kent/go-log) - Log4j implementation in Go. -> _stars: None, forks: None, open issues:None_
* [go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers. -> _stars: None, forks: None, open issues:None_
* [gologger](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch. -> _stars: None, forks: None, open issues:None_
* [gomol](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs. -> _stars: None, forks: None, open issues:None_
* [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library. -> _stars: None, forks: None, open issues:None_
* [log](https://github.com/apex/log) - Structured logging package for Go. -> _stars: None, forks: None, open issues:None_
* [log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go. -> _stars: None, forks: None, open issues:None_
* [log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang. -> _stars: None, forks: None, open issues:None_
* [log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go. -> _stars: None, forks: None, open issues:None_
* [logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging. -> _stars: None, forks: None, open issues:None_
* [logex](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib. -> _stars: None, forks: None, open issues:None_
* [logger](https://github.com/azer/logger) - Minimalistic logging library for Go. -> _stars: None, forks: None, open issues:None_
* [logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go. -> _stars: None, forks: None, open issues:None_
* [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). -> _stars: None, forks: None, open issues:None_
* [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger. -> _stars: None, forks: None, open issues:None_
* [logxi](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy. -> _stars: None, forks: None, open issues:None_
* [lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser. -> _stars: None, forks: None, open issues:None_
* [mlog](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. -> _stars: None, forks: None, open issues:None_
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail). -> _stars: None, forks: None, open issues:None_
* [seelog](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting. -> _stars: None, forks: None, open issues:None_
* [slf](https://github.com/ventu-io/slf) - The Structured Logging Facade (SLF) for Go (like SLF4J but structured and for Go). -> _stars: None, forks: None, open issues:None_
* [slog](https://github.com/ventu-io/slog) - The reference implementation of the Structured Logging Facade (SLF) for Go. -> _stars: None, forks: None, open issues:None_
* [spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging. -> _stars: None, forks: None, open issues:None_
* [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. -> _stars: None, forks: None, open issues:None_
* [tail](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program. -> _stars: None, forks: None, open issues:None_
* [xlog](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format. -> _stars: None, forks: None, open issues:None_
* [xlog](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching. -> _stars: None, forks: None, open issues:None_
* [zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go. -> _stars: None, forks: None, open issues:None_
* [zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger. -> _stars: None, forks: None, open issues:None_

## Machine Learning

*Libraries for Machine Learning.*

* [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang. -> _stars: None, forks: None, open issues:None_
* [CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. -> _stars: None, forks: None, open issues:None_
* [gago](https://github.com/MaxHalford/gago) - Multi-population, flexible, parallel genetic algorithm. -> _stars: None, forks: None, open issues:None_
* [go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library. -> _stars: None, forks: None, open issues:None_
* [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang. -> _stars: None, forks: None, open issues:None_
* [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang. -> _stars: None, forks: None, open issues:None_
* [gobrain](https://github.com/goml/gobrain) - Neural Networks written in go. -> _stars: None, forks: None, open issues:None_
* [godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods. -> _stars: None, forks: None, open issues:None_
* [goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go. -> _stars: None, forks: None, open issues:None_
* [GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go. -> _stars: None, forks: None, open issues:None_
* [golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go. -> _stars: None, forks: None, open issues:None_
* [goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go. -> _stars: None, forks: None, open issues:None_
* [goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go. -> _stars: None, forks: None, open issues:None_
* [gorgonia](https://github.com/chewxy/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms. -> _stars: None, forks: None, open issues:None_
* [libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14. -> _stars: None, forks: None, open issues:None_
* [mlgo](https://github.com/NullHypothesis/mlgo) - This project aims to provide minimalistic machine learning algorithms in Go. -> _stars: None, forks: None, open issues:None_
* [neat](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT). -> _stars: None, forks: None, open issues:None_
* [neural-go](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation. -> _stars: None, forks: None, open issues:None_
* [probab](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go. -> _stars: None, forks: None, open issues:None_
* [regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine. -> _stars: None, forks: None, open issues:None_
* [shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go. -> _stars: None, forks: None, open issues:None_

## Messaging

*Libraries that implement messaging systems.*

* [Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go. -> _stars: None, forks: None, open issues:None_
* [dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus. -> _stars: None, forks: None, open issues:None_
* [drone-line](https://github.com/appleboy/drone-line) - Sending [Line](https://business.line.me/en/services/bot) notifications using a binary, docker or Drone CI. -> _stars: None, forks: None, open issues:None_
* [emitter](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins. -> _stars: None, forks: None, open issues:None_
* [event](https://github.com/agoalofalife/event) - Implementation of the pattern observer. -> _stars: None, forks: None, open issues:None_
* [EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility. -> _stars: None, forks: None, open issues:None_
* [gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go. -> _stars: None, forks: None, open issues:None_
* [Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io). -> _stars: None, forks: None, open issues:None_
* [go-longpoll](https://github.com/ventu-io/go-longpoll) - PubSub with long polling. -> _stars: None, forks: None, open issues:None_
* [go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec. -> _stars: None, forks: None, open issues:None_
* [go-nsq](https://github.com/nsqio/go-nsq) - the official Go package for NSQ. -> _stars: None, forks: None, open issues:None_
* [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework. -> _stars: None, forks: None, open issues:None_
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service. -> _stars: None, forks: None, open issues:None_
* [Gollum](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations. -> _stars: None, forks: None, open issues:None_
* [golongpoll](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple. -> _stars: None, forks: None, open issues:None_
* [goose](https://github.com/ian-kent/goose) - Server Sent Events in Go. -> _stars: None, forks: None, open issues:None_
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster. -> _stars: None, forks: None, open issues:None_
* [gorush](https://github.com/appleboy/gorush) - Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm). -> _stars: None, forks: None, open issues:None_
* [guble](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence. -> _stars: None, forks: None, open issues:None_
* [machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing. -> _stars: None, forks: None, open issues:None_
* [mangos](https://github.com/go-mangos/mangos) - Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability. -> _stars: None, forks: None, open issues:None_
* [melody](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling. -> _stars: None, forks: None, open issues:None_
* [NATS Go Client](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library. -> _stars: None, forks: None, open issues:None_
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel. -> _stars: None, forks: None, open issues:None_
* [oplog](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs. -> _stars: None, forks: None, open issues:None_
* [pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go. -> _stars: None, forks: None, open issues:None_
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue. -> _stars: None, forks: None, open issues:None_
* [sarama](https://github.com/Shopify/sarama) - Go library for Apache Kafka. -> _stars: None, forks: None, open issues:None_
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices. -> _stars: None, forks: None, open issues:None_
* [zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). -> _stars: None, forks: None, open issues:None_

## Miscellaneous

*These libraries were placed here because none of the other categories seemed to fit.*

* [alice](https://github.com/magic003/alice) - Additive dependency injection container for Golang. -> _stars: None, forks: None, open issues:None_
* [archiver](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives. -> _stars: None, forks: None, open issues:None_
* [autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields. -> _stars: None, forks: None, open issues:None_
* [avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation. -> _stars: None, forks: None, open issues:None_
* [banner](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications. -> _stars: None, forks: None, open issues:None_
* [battery](https://github.com/distatus/battery) - Cross-platform, normalized battery information library. -> _stars: None, forks: None, open issues:None_
* [bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go. -> _stars: None, forks: None, open issues:None_
* [browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/). -> _stars: None, forks: None, open issues:None_
* [conv](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types. -> _stars: None, forks: None, open issues:None_
* [datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter. -> _stars: None, forks: None, open issues:None_
* [errors](https://github.com/pkg/errors) - Package that provides simple error handling primitives. -> _stars: None, forks: None, open issues:None_
* [go-chat-bot](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go. -> _stars: None, forks: None, open issues:None_
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang. -> _stars: None, forks: None, open issues:None_
* [go-multierror](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error. -> _stars: None, forks: None, open issues:None_
* [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas. -> _stars: None, forks: None, open issues:None_
* [go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang. -> _stars: None, forks: None, open issues:None_
* [go-sarah](https://github.com/oklahomer/go-sarah) - Framework to build bot for desired chat services including LINE, Slack, Gitter and more. -> _stars: None, forks: None, open issues:None_
* [go-shortid](https://github.com/ventu-io/go-shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs. -> _stars: None, forks: None, open issues:None_
* [go-unarr](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives. -> _stars: None, forks: None, open issues:None_
* [go.uuid](https://github.com/satori/go.uuid) - Implementation of Universally Unique Identifier (UUID). Supported both creation and parsing of UUIDs. -> _stars: None, forks: None, open issues:None_
* [gofakeit](https://github.com/brianvoe/gofakeit) - Random data generator written in go. -> _stars: None, forks: None, open issues:None_
* [goid](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs. -> _stars: None, forks: None, open issues:None_
* [gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). -> _stars: None, forks: None, open issues:None_
* [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS. -> _stars: None, forks: None, open issues:None_
* [gountries](https://github.com/pariz/gountries) - Package that exposes country and subdivision data. -> _stars: None, forks: None, open issues:None_
* [hanu](https://github.com/sbstjn/hanu) - Framework for writing Slack bots. -> _stars: None, forks: None, open issues:None_
* [health](https://github.com/dimiro1/health) - Easy to use, extensible health check library. -> _stars: None, forks: None, open issues:None_
* [indigo](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58. -> _stars: None, forks: None, open issues:None_
* [jobs](https://github.com/albrow/jobs) - Persistent and flexible background jobs library. -> _stars: None, forks: None, open issues:None_
* [margelet](https://github.com/zhulik/margelet) - Framework for building Telegram bots. -> _stars: None, forks: None, open issues:None_
* [secdl](https://github.com/xor-gate/secdl) - Lighttpd ModSecDownload algorithm ported to go to secure download urls. -> _stars: None, forks: None, open issues:None_
* [slacker](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots. -> _stars: None, forks: None, open issues:None_
* [stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... -> _stars: None, forks: None, open issues:None_
* [uuid](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier. -> _stars: None, forks: None, open issues:None_
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and ouput handling. -> _stars: None, forks: None, open issues:None_
* [werr](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called. -> _stars: None, forks: None, open issues:None_
* [xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber. -> _stars: None, forks: None, open issues:None_
* [xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages. -> _stars: None, forks: None, open issues:None_

## Natural Language Processing

*Libraries for working with human languages.*

* [dpar](https://github.com/danieldk/dpar/) - Transition-based statistical dependency parser. -> _stars: None, forks: None, open issues:None_
* [go-eco](https://github.com/ThePaw/go-eco) - Similarity, dissimilarity and distance matrices; diversity, equitability and inequality measures; species richness estimators; coenocline models. -> _stars: None, forks: None, open issues:None_
* [go-i18n](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text. -> _stars: None, forks: None, open issues:None_
* [go-mystem](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer. -> _stars: None, forks: None, open issues:None_
* [go-nlp](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work. -> _stars: None, forks: None, open issues:None_
* [go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm. -> _stars: None, forks: None, open issues:None_
* [go-unidecode](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text. -> _stars: None, forks: None, open issues:None_
* [go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings. -> _stars: None, forks: None, open issues:None_
* [gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm. -> _stars: None, forks: None, open issues:None_
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2. -> _stars: None, forks: None, open issues:None_
* [gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go. -> _stars: None, forks: None, open issues:None_
* [icu](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1. -> _stars: None, forks: None, open issues:None_
* [libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. -> _stars: None, forks: None, open issues:None_
* [MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. -> _stars: None, forks: None, open issues:None_
* [nlp](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp. -> _stars: None, forks: None, open issues:None_
* [nlp](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis). -> _stars: None, forks: None, open issues:None_
* [paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm. -> _stars: None, forks: None, open issues:None_
* [porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm. -> _stars: None, forks: None, open issues:None_
* [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer. -> _stars: None, forks: None, open issues:None_
* [prose](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. -> _stars: None, forks: None, open issues:None_
* [RAKE.go](https://github.com/Obaied/RAKE.go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE). -> _stars: None, forks: None, open issues:None_
* [segment](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/) -> _stars: None, forks: None, open issues:None_
* [sentences](https://github.com/neurosnap/sentences) - Sentence tokenizer:  converts text into a list of sentences. -> _stars: None, forks: None, open issues:None_
* [shamoji](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go. -> _stars: None, forks: None, open issues:None_
* [snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). -> _stars: None, forks: None, open issues:None_
* [stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers. -> _stars: None, forks: None, open issues:None_
* [textcat](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text. -> _stars: None, forks: None, open issues:None_
* [whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc). -> _stars: None, forks: None, open issues:None_
* [when](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules. -> _stars: None, forks: None, open issues:None_

## Networking

*Libraries for working with various layers of the network.*

* [arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826. -> _stars: None, forks: None, open issues:None_
* [buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy. -> _stars: None, forks: None, open issues:None_
* [canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252). -> _stars: None, forks: None, open issues:None_
* [dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. -> _stars: None, forks: None, open issues:None_
* [dns](https://github.com/miekg/dns) - Go library for working with DNS. -> _stars: None, forks: None, open issues:None_
* [ether](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames. -> _stars: None, forks: None, open issues:None_
* [ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. -> _stars: None, forks: None, open issues:None_
* [fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http. -> _stars: None, forks: None, open issues:None_
* [ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959). -> _stars: None, forks: None, open issues:None_
* [go-getter](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL. -> _stars: None, forks: None, open issues:None_
* [go-stun](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389). -> _stars: None, forks: None, open issues:None_
* [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language. -> _stars: None, forks: None, open issues:None_
* [golibwireshark](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data. -> _stars: None, forks: None, open issues:None_
* [gopacket](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings. -> _stars: None, forks: None, open issues:None_
* [gopcap](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap. -> _stars: None, forks: None, open issues:None_
* [goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet. -> _stars: None, forks: None, open issues:None_
* [gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions. -> _stars: None, forks: None, open issues:None_
* [gotcp](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications. -> _stars: None, forks: None, open issues:None_
* [grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads. -> _stars: None, forks: None, open issues:None_
* [graval](https://github.com/koofr/graval) - Experimental FTP server framework. -> _stars: None, forks: None, open issues:None_
* [jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices. -> _stars: None, forks: None, open issues:None_
* [kcp-go](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol. -> _stars: None, forks: None, open issues:None_
* [kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol. -> _stars: None, forks: None, open issues:None_
* [lhttp](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily. -> _stars: None, forks: None, open issues:None_
* [linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces. -> _stars: None, forks: None, open issues:None_
* [llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response. -> _stars: None, forks: None, open issues:None_
* [mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang. -> _stars: None, forks: None, open issues:None_
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* [portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it. -> _stars: None, forks: None, open issues:None_
* [publicip](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress). -> _stars: None, forks: None, open issues:None_
* [raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface. -> _stars: None, forks: None, open issues:None_
* [sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt. -> _stars: None, forks: None, open issues:None_
* [ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh). -> _stars: None, forks: None, open issues:None_
* [sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance. -> _stars: None, forks: None, open issues:None_
* [tcp_server](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster. -> _stars: None, forks: None, open issues:None_
* [utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation. -> _stars: None, forks: None, open issues:None_
* [water](https://github.com/songgao/water) - Simple TUN/TAP library. -> _stars: None, forks: None, open issues:None_
* [winrm](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines. -> _stars: None, forks: None, open issues:None_
* [xtcp](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication,graceful shutdown,custom protocol. -> _stars: None, forks: None, open issues:None_

## OpenGL

*Libraries for using OpenGL in Go.*

* [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow). -> _stars: None, forks: None, open issues:None_
* [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3. -> _stars: None, forks: None, open issues:None_
* [goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). -> _stars: None, forks: None, open issues:None_
* [goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events. -> _stars: None, forks: None, open issues:None_
* [mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM. -> _stars: None, forks: None, open issues:None_

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3. -> _stars: None, forks: None, open issues:None_
* [go-pg](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance. -> _stars: None, forks: None, open issues:None_
* [go-store](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go. -> _stars: None, forks: None, open issues:None_
* [gomodel](https://github.com/cosiner/gomodel) - Lightweight, fast, orm-like library helps interactive with database. -> _stars: None, forks: None, open issues:None_
* [GORM](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly. -> _stars: None, forks: None, open issues:None_
* [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go. -> _stars: None, forks: None, open issues:None_
* [pop/soda](https://github.com/markbates/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. -> _stars: None, forks: None, open issues:None_
* [QBS](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM. -> _stars: None, forks: None, open issues:None_
* [reform](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation. -> _stars: None, forks: None, open issues:None_
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema. -> _stars: None, forks: None, open issues:None_
* [upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. -> _stars: None, forks: None, open issues:None_
* [Xorm](https://github.com/go-xorm/xorm) - Simple and powerful ORM for Go. -> _stars: None, forks: None, open issues:None_
* [Zoom](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis. -> _stars: None, forks: None, open issues:None_

## Package Management

*Libraries for package and dependency management.*

* [dep](https://github.com/golang/dep) - Go dependency tool. -> _stars: None, forks: None, open issues:None_
* [gigo](https://github.com/LyricalSecurity/gigo) - PIP-like dependency tool for golang, with support for private repositories and hashes. -> _stars: None, forks: None, open issues:None_
* [glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip. -> _stars: None, forks: None, open issues:None_
* [godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies. -> _stars: None, forks: None, open issues:None_
* [gom](https://github.com/mattn/gom) - Go Manager - bundle for go. -> _stars: None, forks: None, open issues:None_
* [goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler. -> _stars: None, forks: None, open issues:None_
* [gop](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH -> _stars: None, forks: None, open issues:None_
* [gopm](https://github.com/gpmgo/gopm) - Go Package Manager. -> _stars: None, forks: None, open issues:None_
* [govendor](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file. -> _stars: None, forks: None, open issues:None_
* [gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go. -> _stars: None, forks: None, open issues:None_
* [gvt](https://github.com/FiloSottile/gvt) - `gvt` is a simple vendoring tool made for Go native vendoring (aka GO15VENDOREXPERIMENT), based on gb-vendor. -> _stars: None, forks: None, open issues:None_
* [johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git. -> _stars: None, forks: None, open issues:None_
* [nut](https://github.com/jingweno/nut) - Vendor Go dependencies. -> _stars: None, forks: None, open issues:None_
* [VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments. -> _stars: None, forks: None, open issues:None_

## Query Language

* [graphql](https://github.com/tmc/graphql) - graphql parser + utilities. -> _stars: None, forks: None, open issues:None_
* [graphql](https://github.com/sevki/graphql) - GraphQL implementation in go. -> _stars: None, forks: None, open issues:None_
* [graphql](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use. -> _stars: None, forks: None, open issues:None_
* [graphql-go](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go. -> _stars: None, forks: None, open issues:None_
* [jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang. -> _stars: None, forks: None, open issues:None_

## Resource Embedding

* [esc](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them. -> _stars: None, forks: None, open issues:None_
* [fileb0x](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use. -> _stars: None, forks: None, open issues:None_
* [go-bindata](https://github.com/jteeuwen/go-bindata) - Package that converts any file into managable Go source code. -> _stars: None, forks: None, open issues:None_
* [go-embed](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable. -> _stars: None, forks: None, open issues:None_
* [go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go. -> _stars: None, forks: None, open issues:None_
* [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy. -> _stars: None, forks: None, open issues:None_
* [statics](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks. -> _stars: None, forks: None, open issues:None_
* [statik](https://github.com/rakyll/statik) - Embeds static files into a Go executable. -> _stars: None, forks: None, open issues:None_
* [templify](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries. -> _stars: None, forks: None, open issues:None_
* [vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem. -> _stars: None, forks: None, open issues:None_

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [blas](https://github.com/ziutek/blas) - Implementation of BLAS (Basic Linear Algebra Subprograms). -> _stars: None, forks: None, open issues:None_
* [chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types. -> _stars: None, forks: None, open issues:None_
* [evaler](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator. -> _stars: None, forks: None, open issues:None_
* [ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages. -> _stars: None, forks: None, open issues:None_
* [geom](https://github.com/skelterjohn/geom) - 2D geometry for golang. -> _stars: None, forks: None, open issues:None_
* [go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go. -> _stars: None, forks: None, open issues:None_
* [go-fn](https://github.com/ematvey/go-fn) - Mathematical functions written in Go language, that are not covered by math pkg. -> _stars: None, forks: None, open issues:None_
* [go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language. -> _stars: None, forks: None, open issues:None_
* [go.matrix](https://github.com/skelterjohn/go.matrix) - linear algebra for go (has been stalled). -> _stars: None, forks: None, open issues:None_
* [gocomplex](https://github.com/varver/gocomplex) - Complex number library for the Go programming language. -> _stars: None, forks: None, open issues:None_
* [gofrac](https://github.com/anschelsc/gofrac) - (goinstallable) fractions library for go with support for basic arithmetic. -> _stars: None, forks: None, open issues:None_
* [gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams. -> _stars: None, forks: None, open issues:None_
* [gonum/mat64](https://github.com/gonum/matrix) - The general purpose package for matrix computation. Package mat64 provides basic linear algebra operations for float64 matrices. -> _stars: None, forks: None, open issues:None_
* [gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go. -> _stars: None, forks: None, open issues:None_
* [goraph](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorith visualization). -> _stars: None, forks: None, open issues:None_
* [gostat](https://github.com/ematvey/gostat) - Statistics library for the go language. -> _stars: None, forks: None, open issues:None_
* [graph](https://github.com/yourbasic/graph) - Library of basic graph algorithms. -> _stars: None, forks: None, open issues:None_
* [ode](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions. -> _stars: None, forks: None, open issues:None_
* [pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go. -> _stars: None, forks: None, open issues:None_
* [PiHex](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi. -> _stars: None, forks: None, open issues:None_
* [sparse](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries. -> _stars: None, forks: None, open issues:None_
* [stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library. -> _stars: None, forks: None, open issues:None_
* [streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data. -> _stars: None, forks: None, open issues:None_
* [vectormath](https://github.com/spate/vectormath) - Vectormath for Go, an adaptation of the scalar C functions from Sony's Vector Math library, as found in the Bullet-2.79 source code (currently inactive). -> _stars: None, forks: None, open issues:None_

## Security

*Libraries that are used to help make your application more secure.*

* [acmetool](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal. -> _stars: None, forks: None, open issues:None_
* [BadActor](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban. -> _stars: None, forks: None, open issues:None_
* [go-yara](https://github.com/hillu/go-yara) - Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)". -> _stars: None, forks: None, open issues:None_
* [lego](https://github.com/xenolf/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt). -> _stars: None, forks: None, open issues:None_
* [memguard](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory. -> _stars: None, forks: None, open issues:None_
* [passlib](https://github.com/hlandau/passlib) - Futureproof password hashing library. -> _stars: None, forks: None, open issues:None_
* [secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins. -> _stars: None, forks: None, open issues:None_
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in. -> _stars: None, forks: None, open issues:None_
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys. -> _stars: None, forks: None, open issues:None_

## Serialization

*Libraries and tools for binary serialization.*

* [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang. -> _stars: None, forks: None, open issues:None_
* [bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go. -> _stars: None, forks: None, open issues:None_
* [colfer](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format. -> _stars: None, forks: None, open issues:None_
* [go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go. -> _stars: None, forks: None, open issues:None_
* [go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support. -> _stars: None, forks: None, open issues:None_
* [gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets. -> _stars: None, forks: None, open issues:None_
* [goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers. -> _stars: None, forks: None, open issues:None_
* [jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json". -> _stars: None, forks: None, open issues:None_
* [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures. -> _stars: None, forks: None, open issues:None_
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions. -> _stars: None, forks: None, open issues:None_
* [structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures. -> _stars: None, forks: None, open issues:None_

## Server Applications

* [algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. -> _stars: None, forks: None, open issues:None_
* [Caddy](https://github.com/mholt/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use. -> _stars: None, forks: None, open issues:None_
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [devd](https://github.com/cortesi/devd) - Local webserver for developers. -> _stars: None, forks: None, open issues:None_
* [etcd](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery. -> _stars: None, forks: None, open issues:None_
* [minio](https://github.com/minio/minio) - Minio is a distributed object storage server. -> _stars: None, forks: None, open issues:None_
* [nsq](http://nsq.io/) - A realtime distributed messaging platform.
* [yakvs](https://github.com/sci4me/yakvs) - Small, networked, in-memory key-value store. -> _stars: None, forks: None, open issues:None_

## Template Engines

*Libraries and tools for templating and lexing.*

* [ace](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold. -> _stars: None, forks: None, open issues:None_
* [amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade. -> _stars: None, forks: None, open issues:None_
* [damsel](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others. -> _stars: None, forks: None, open issues:None_
* [ego](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled. -> _stars: None, forks: None, open issues:None_
* [fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/). -> _stars: None, forks: None, open issues:None_
* [gofpdf](https://github.com/jung-kurt/gofpdf) - PDF document generator with high level support for text, drawing and images. -> _stars: None, forks: None, open issues:None_
* [grender](https://github.com/dannyvankooten/grender) - small wrapper around html/template for file-based templates that support extending other template files. -> _stars: None, forks: None, open issues:None_
* [hero](https://github.com/shiyanhui/hero) - Hero is a handy, fast and powerful go template engine. -> _stars: None, forks: None, open issues:None_
* [jet](https://github.com/CloudyKit/jet) - Jet template engine. -> _stars: None, forks: None, open issues:None_
* [kasia.go](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation. -> _stars: None, forks: None, open issues:None_
* [liquid](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates. -> _stars: None, forks: None, open issues:None_
* [mustache](https://github.com/hoisie/mustache) - Go implementation of the Mustache template language. -> _stars: None, forks: None, open issues:None_
* [pongo2](https://github.com/flosch/pongo2) - Django-like template-engine for Go. -> _stars: None, forks: None, open issues:None_
* [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it. -> _stars: None, forks: None, open issues:None_
* [raymond](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go. -> _stars: None, forks: None, open issues:None_
* [Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang. -> _stars: None, forks: None, open issues:None_
* [Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/). -> _stars: None, forks: None, open issues:None_
* [velvet](https://github.com/gobuffalo/velvet) - Complete handlebars implementation in Go. -> _stars: None, forks: None, open issues:None_

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions. -> _stars: None, forks: None, open issues:None_
    * [badio](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package. -> _stars: None, forks: None, open issues:None_
    * [baloo](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy. -> _stars: None, forks: None, open issues:None_
    * [bro](https://github.com/marioidival/bro) - Watch files in directory and run tests for them. -> _stars: None, forks: None, open issues:None_
    * [cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework. -> _stars: None, forks: None, open issues:None_
    * [dbcleaner](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby. -> _stars: None, forks: None, open issues:None_
    * [dsunit](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files. -> _stars: None, forks: None, open issues:None_
    * [frisby](https://github.com/verdverm/frisby) - REST API testing framework. -> _stars: None, forks: None, open issues:None_
    * [ginkgo](http://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
    * [go-carpet](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal. -> _stars: None, forks: None, open issues:None_
    * [go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code. -> _stars: None, forks: None, open issues:None_
    * [go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests. -> _stars: None, forks: None, open issues:None_
    * [goblin](https://github.com/franela/goblin) - Mocha like testing framework fo Go. -> _stars: None, forks: None, open issues:None_
    * [gocheck](http://labix.org/gocheck) - More advanced testing framework alternative to gotest.
    * [GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload. -> _stars: None, forks: None, open issues:None_
    * [godog](https://github.com/DATA-DOG/godog) - Cucumber or Behat like BDD framework for Go. -> _stars: None, forks: None, open issues:None_
    * [gofight](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework. -> _stars: None, forks: None, open issues:None_
    * [gomega](http://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
    * [GoSpec](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language. -> _stars: None, forks: None, open issues:None_
    * [gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec. -> _stars: None, forks: None, open issues:None_
    * [gosuite](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests. -> _stars: None, forks: None, open issues:None_
    * [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results. -> _stars: None, forks: None, open issues:None_
    * [httpexpect](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing. -> _stars: None, forks: None, open issues:None_
    * [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test. -> _stars: None, forks: None, open issues:None_
    * [testfixtures](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications. -> _stars: None, forks: None, open issues:None_
    * [Testify](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package. -> _stars: None, forks: None, open issues:None_
    * [wstest](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler. -> _stars: None, forks: None, open issues:None_

* Mock
    * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects. -> _stars: None, forks: None, open issues:None_
    * [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions. -> _stars: None, forks: None, open issues:None_
    * [go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes. -> _stars: None, forks: None, open issues:None_
    * [gock](https://github.com/h2non/gock) - Versatile HTTP mocking made easy. -> _stars: None, forks: None, open issues:None_
    * [gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language. -> _stars: None, forks: None, open issues:None_
    * [govcr](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing. -> _stars: None, forks: None, open issues:None_
    * [minimock](https://github.com/gojuno/minimock) - Mock generator for Go interfaces. -> _stars: None, forks: None, open issues:None_
    * [mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter. -> _stars: None, forks: None, open issues:None_

* Fuzzing and delta-debugging/reducing/shrinking.
    * [go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing system. -> _stars: None, forks: None, open issues:None_
    * [gofuzz](https://github.com/google/gofuzz) - Library for populating go objects with random values. -> _stars: None, forks: None, open issues:None_
    * [Tavor](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework. -> _stars: None, forks: None, open issues:None_

* Selenium and browser control tools.
    * [cdp](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it. -> _stars: None, forks: None, open issues:None_
    * [chromedp](https://github.com/knq/chromedp) - Way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol. -> _stars: None, forks: None, open issues:None_
    * [ggr](https://github.com/aandryashin/ggr) - Lightweight server that routes and proxies Selenium Wedriver requests to multiple Selenium hubs. -> _stars: None, forks: None, open issues:None_
    * [selenoid](https://github.com/aandryashin/selenoid) - alternative Selenium hub server that launches browsers within containers. -> _stars: None, forks: None, open issues:None_

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
    * [align](https://github.com/Guitarbum722/align) - A general purpose application that aligns text. -> _stars: None, forks: None, open issues:None_
    * [allot](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots. -> _stars: None, forks: None, open issues:None_
    * [bbConvert](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags. -> _stars: None, forks: None, open issues:None_
    * [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go. -> _stars: None, forks: None, open issues:None_
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer. -> _stars: None, forks: None, open issues:None_
    * [doi](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go. -> _stars: None, forks: None, open issues:None_
    * [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go. -> _stars: None, forks: None, open issues:None_
    * [enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/). -> _stars: None, forks: None, open issues:None_
    * [genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings. -> _stars: None, forks: None, open issues:None_
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
    * [go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format. -> _stars: None, forks: None, open issues:None_
    * [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language. -> _stars: None, forks: None, open issues:None_
    * [go-pkg-rss](https://github.com/jteeuwen/go-pkg-rss) - This package reads RSS and Atom feeds and provides a caching mechanism that adheres to the feed specs. -> _stars: None, forks: None, open issues:None_
    * [go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string. -> _stars: None, forks: None, open issues:None_
    * [go-slugify](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support. -> _stars: None, forks: None, open issues:None_
    * [go-vcard](https://github.com/emersion/go-vcard) - Parse and format vCard. -> _stars: None, forks: None, open issues:None_
    * [gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go. -> _stars: None, forks: None, open issues:None_
    * [gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language. -> _stars: None, forks: None, open issues:None_
    * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - Format bytes to string. -> _stars: None, forks: None, open issues:None_
    * [gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts. -> _stars: None, forks: None, open issues:None_
    * [goq](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery). -> _stars: None, forks: None, open issues:None_
    * [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language. -> _stars: None, forks: None, open issues:None_
    * [goregen](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions. -> _stars: None, forks: None, open issues:None_
    * [gotext](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go. -> _stars: None, forks: None, open issues:None_
    * [guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text. -> _stars: None, forks: None, open issues:None_
    * [inject](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector. -> _stars: None, forks: None, open issues:None_
    * [mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. -> _stars: None, forks: None, open issues:None_
    * [sh](https://github.com/mvdan/sh) - Shell parser and formatter. -> _stars: None, forks: None, open issues:None_
    * [slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support. -> _stars: None, forks: None, open issues:None_
    * [Slugify](https://github.com/avelino/slugify) - Go slugify application that handles string. -> _stars: None, forks: None, open issues:None_
    * [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection). -> _stars: None, forks: None, open issues:None_
* Utility
    * [gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go. -> _stars: None, forks: None, open issues:None_
    * [kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms. -> _stars: None, forks: None, open issues:None_
    * [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes. -> _stars: None, forks: None, open issues:None_
    * [parth](https://github.com/codemodus/parth) - URL path segmentation parsing. -> _stars: None, forks: None, open issues:None_
    * [radix](https://github.com/yourbasic/radix) - fast string sorting algorithm. -> _stars: None, forks: None, open issues:None_
    * [xurls](https://github.com/mvdan/xurls) - Extract urls from text. -> _stars: None, forks: None, open issues:None_

## Third-party APIs

*Libraries for accessing third party APIs.*

* [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html). -> _stars: None, forks: None, open issues:None_
* [anaconda](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API. -> _stars: None, forks: None, open issues:None_
* [aws-sdk-go](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language. -> _stars: None, forks: None, open issues:None_
* [brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API. -> _stars: None, forks: None, open issues:None_
* [cachet](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/). -> _stars: None, forks: None, open issues:None_
* [circleci](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API. -> _stars: None, forks: None, open issues:None_
* [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API. -> _stars: None, forks: None, open issues:None_
* [discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API. -> _stars: None, forks: None, open issues:None_
* [facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API. -> _stars: None, forks: None, open issues:None_
* [fcm](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging. -> _stars: None, forks: None, open issues:None_
* [gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API. -> _stars: None, forks: None, open issues:None_
* [gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface. -> _stars: None, forks: None, open issues:None_
* [gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging. -> _stars: None, forks: None, open issues:None_
* [geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](http://open.mapquestapi.com/nominatim/), [OpenCage](http://geocoder.opencagedata.com/api.html), [HERE](https://developer.here.com/rest-apis/documentation/geocoder), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs. -> _stars: None, forks: None, open issues:None_
* [ghost](https://github.com/neuegram/ghost) - Go Library for accessing the Snapchat API. -> _stars: None, forks: None, open issues:None_
* [github](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3. -> _stars: None, forks: None, open issues:None_
* [githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4. -> _stars: None, forks: None, open issues:None_
* [go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API. -> _stars: None, forks: None, open issues:None_
* [go-imgur](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com) -> _stars: None, forks: None, open issues:None_
* [go-jira](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira) -> _stars: None, forks: None, open issues:None_
* [go-marathon](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS. -> _stars: None, forks: None, open issues:None_
* [go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api). -> _stars: None, forks: None, open issues:None_
* [go-telegraph](https://github.com/toby3d/go-telegraph) - Telegraph publishing platform API client. -> _stars: None, forks: None, open issues:None_
* [go-tgbot](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware. -> _stars: None, forks: None, open issues:None_
* [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github. -> _stars: None, forks: None, open issues:None_
* [go-twitch](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API. -> _stars: None, forks: None, open issues:None_
* [go-twitter](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs. -> _stars: None, forks: None, open issues:None_
* [go-unsplash](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API. -> _stars: None, forks: None, open issues:None_
* [go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API. -> _stars: None, forks: None, open issues:None_
* [goamz](https://github.com/mitchellh/goamz) - Popular fork of [goamz](https://launchpad.net/goamz) which adds some missing API calls to certain packages. -> _stars: None, forks: None, open issues:None_
* [golyrics](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website. -> _stars: None, forks: None, open issues:None_
* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library. -> _stars: None, forks: None, open issues:None_
* [google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go. -> _stars: None, forks: None, open issues:None_
* [google-analytics](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting. -> _stars: None, forks: None, open issues:None_
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library. -> _stars: None, forks: None, open issues:None_
* [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/). -> _stars: None, forks: None, open issues:None_
* [gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. -> _stars: None, forks: None, open issues:None_
* [govkbot](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library. -> _stars: None, forks: None, open issues:None_
* [hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API. -> _stars: None, forks: None, open issues:None_
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP. -> _stars: None, forks: None, open issues:None_
* [Medium](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API. -> _stars: None, forks: None, open issues:None_
* [megos](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster. -> _stars: None, forks: None, open issues:None_
* [micha](https://github.com/onrik/micha) - Go Library for Telegram bot api. -> _stars: None, forks: None, open issues:None_
* [minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage. -> _stars: None, forks: None, open issues:None_
* [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications. -> _stars: None, forks: None, open issues:None_
* [patreon-go](https://github.com/mxpv/patreon-go) - Go library for Patreon API. -> _stars: None, forks: None, open issues:None_
* [paypal](https://github.com/logpacker/paypalsdk) - Wrapper for PayPal payment API. -> _stars: None, forks: None, open issues:None_
* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK. -> _stars: None, forks: None, open issues:None_
* [pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API. -> _stars: None, forks: None, open issues:None_
* [rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP. -> _stars: None, forks: None, open issues:None_
* [shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API. -> _stars: None, forks: None, open issues:None_
* [slack](https://github.com/nlopes/slack) - Slack API in Go. -> _stars: None, forks: None, open issues:None_
* [smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API. -> _stars: None, forks: None, open issues:None_
* [spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API. -> _stars: None, forks: None, open issues:None_
* [steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers. -> _stars: None, forks: None, open issues:None_
* [stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API. -> _stars: None, forks: None, open issues:None_
* [tbot](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http. -> _stars: None, forks: None, open issues:None_
* [telebot](https://github.com/tucnak/telebot) - Telegram bot framework written in Go. -> _stars: None, forks: None, open issues:None_
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client. -> _stars: None, forks: None, open issues:None_
* [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API. -> _stars: None, forks: None, open issues:None_
* [TheMovieDb](https://github.com/jbrodriguez/go-tmdb) - Simple golang package to communicate with [themoviedb.org](https://themoviedb.org). -> _stars: None, forks: None, open issues:None_
* [translate](https://github.com/poorny/translate) - Go online translation package. -> _stars: None, forks: None, open issues:None_
* [Trello](https://github.com/adlio/trello) - Go wrapper for the Trello API. -> _stars: None, forks: None, open issues:None_
* [tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API. -> _stars: None, forks: None, open issues:None_
* [webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket. -> _stars: None, forks: None, open issues:None_
* [zooz](https://github.com/gojuno/go-zooz) - Go client for the Zooz API. -> _stars: None, forks: None, open issues:None_

## Utilities

*General utilities and tools to make your life easier.*

* [abutil](https://github.com/bahlo/abutil) - Collection of often-used Golang helpers. -> _stars: None, forks: None, open issues:None_
* [apm](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API. -> _stars: None, forks: None, open issues:None_
* [boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates. -> _stars: None, forks: None, open issues:None_
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go. -> _stars: None, forks: None, open issues:None_
* [clockwerk](http://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.
* [command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher. -> _stars: None, forks: None, open issues:None_
* [coop](https://github.com/rakyll/coop) - Cheat sheet for some of the common concurrent flows in Go. -> _stars: None, forks: None, open issues:None_
* [copy-pasta](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage. -> _stars: None, forks: None, open issues:None_
* [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics. -> _stars: None, forks: None, open issues:None_
* [Death](https://github.com/vrecan/death) - Managing go application shutdown with signals. -> _stars: None, forks: None, open issues:None_
* [Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go. -> _stars: None, forks: None, open issues:None_
* [delve](https://github.com/derekparker/delve) - Go debugger. -> _stars: None, forks: None, open issues:None_
* [dlog](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls. -> _stars: None, forks: None, open issues:None_
* [excelize](https://github.com/Luxurioust/excelize) - Golang library for reading and writing Microsoft Excel (XLSX) files. -> _stars: None, forks: None, open issues:None_
* [fastlz](https://github.com/digitalcrab/fastlz) - Wrap over [FastLz](http://fastlz.org/) (free, open-source, portable real-time compression library) for GoLang. -> _stars: None, forks: None, open issues:None_
* [filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature. -> _stars: None, forks: None, open issues:None_
* [filler](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag. -> _stars: None, forks: None, open issues:None_
* [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go. -> _stars: None, forks: None, open issues:None_
* [generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex. -> _stars: None, forks: None, open issues:None_
* [gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library. -> _stars: None, forks: None, open issues:None_
* [git-time-metric](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git. -> _stars: None, forks: None, open issues:None_
* [GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code. -> _stars: None, forks: None, open issues:None_
* [go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code. -> _stars: None, forks: None, open issues:None_
* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only). -> _stars: None, forks: None, open issues:None_
* [go-cron](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. -> _stars: None, forks: None, open issues:None_
* [go-debug](https://github.com/tj/go-debug) - Conditional debug logging for Golang libraries & applications. -> _stars: None, forks: None, open issues:None_
* [go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go. -> _stars: None, forks: None, open issues:None_
* [go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...). -> _stars: None, forks: None, open issues:None_
* [go-httpheader](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields. -> _stars: None, forks: None, open issues:None_
* [go-rate](https://github.com/beefsack/go-rate) - Timed rate limiter for Go. -> _stars: None, forks: None, open issues:None_
* [go-respond](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses. -> _stars: None, forks: None, open issues:None_
* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go. -> _stars: None, forks: None, open issues:None_
* [go-torch](https://github.com/uber/go-torch) - Stochastic flame graph profiler for Go programs. -> _stars: None, forks: None, open issues:None_
* [go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project. -> _stars: None, forks: None, open issues:None_
* [go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities. -> _stars: None, forks: None, open issues:None_
* [goback](https://github.com/carlescere/goback) - Go simple exponential backoff package. -> _stars: None, forks: None, open issues:None_
* [godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons. -> _stars: None, forks: None, open issues:None_
* [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox. -> _stars: None, forks: None, open issues:None_
* [gohper](https://github.com/cosiner/gohper) - Various tools/modules help for development. -> _stars: None, forks: None, open issues:None_
* [gojq](https://github.com/elgs/gojq) - JSON query in Golang. -> _stars: None, forks: None, open issues:None_
* [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON. -> _stars: None, forks: None, open issues:None_
* [golarm](https://github.com/msempere/golarm) - Fire alarms with system events. -> _stars: None, forks: None, open issues:None_
* [golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks. -> _stars: None, forks: None, open issues:None_
* [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs. -> _stars: None, forks: None, open issues:None_
* [goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images. -> _stars: None, forks: None, open issues:None_
* [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible. -> _stars: None, forks: None, open issues:None_
* [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report. -> _stars: None, forks: None, open issues:None_
* [goreq](https://github.com/franela/goreq) - Minimal and simple request library for Go language. -> _stars: None, forks: None, open issues:None_
* [goreq](https://github.com/smallnest/goreq) - Enhanced simplified HTTP client based on gorequest. -> _stars: None, forks: None, open issues:None_
* [gorequest](https://github.com/parnurzeal/gorequest) - Simplified HTTP client with rich features for Go. -> _stars: None, forks: None, open issues:None_
* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features. -> _stars: None, forks: None, open issues:None_
* [gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go. -> _stars: None, forks: None, open issues:None_
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files. -> _stars: None, forks: None, open issues:None_
* [gpath](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection. -> _stars: None, forks: None, open issues:None_
* [grequests](https://github.com/levigross/grequests) - Elegant and simple `net/http` wrapper that follows Python's requests library. -> _stars: None, forks: None, open issues:None_
* [gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly. -> _stars: None, forks: None, open issues:None_
* [htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility. -> _stars: None, forks: None, open issues:None_
* [httpcontrol](https://github.com/facebookgo/httpcontrol) - Package httpcontrol allows for HTTP transport level control around timeouts and retries. -> _stars: None, forks: None, open issues:None_
* [hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal. -> _stars: None, forks: None, open issues:None_
* [hystrix-go](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker. -> _stars: None, forks: None, open issues:None_
* [immortal](https://github.com/immortal/immortal) - *nix cross-platform (OS agnostic) supervisor. -> _stars: None, forks: None, open issues:None_
* [intrinsic](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code. -> _stars: None, forks: None, open issues:None_
* [JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in. -> _stars: None, forks: None, open issues:None_
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference. -> _stars: None, forks: None, open issues:None_
* [jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON. -> _stars: None, forks: None, open issues:None_
* [jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects. -> _stars: None, forks: None, open issues:None_
* [jsonhal](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses. -> _stars: None, forks: None, open issues:None_
* [kazaam](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents. -> _stars: None, forks: None, open issues:None_
* [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go. -> _stars: None, forks: None, open issues:None_
* [mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems. -> _stars: None, forks: None, open issues:None_
* [mergo](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements. -> _stars: None, forks: None, open issues:None_
* [minify](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats. -> _stars: None, forks: None, open issues:None_
* [mmake](https://github.com/tj/mmake) - Modern Make. -> _stars: None, forks: None, open issues:None_
* [moldova](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template. -> _stars: None, forks: None, open issues:None_
* [mp](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON. -> _stars: None, forks: None, open issues:None_
* [mssqlx](https://github.com/linxGnu/mssqlx) - HA client for master slave (or master master) database which integrates simple, lightweight round-robin balancer. Based on sqlx. -> _stars: None, forks: None, open issues:None_
* [multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers. -> _stars: None, forks: None, open issues:None_
* [netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services. -> _stars: None, forks: None, open issues:None_
* [ngrok](https://github.com/inconshreveable/ngrok) - Introspected tunnels to localhost. -> _stars: None, forks: None, open issues:None_
* [okrun](https://github.com/xta/okrun) - go run error steamroller. -> _stars: None, forks: None, open issues:None_
* [onecache](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc). -> _stars: None, forks: None, open issues:None_
* [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump. -> _stars: None, forks: None, open issues:None_
* [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool. -> _stars: None, forks: None, open issues:None_
* [pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency. -> _stars: None, forks: None, open issues:None_
* [pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API. -> _stars: None, forks: None, open issues:None_
* [profile](https://github.com/pkg/profile) - Simple profiling support package for Go. -> _stars: None, forks: None, open issues:None_
* [rclient](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs. -> _stars: None, forks: None, open issues:None_
* [realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths. -> _stars: None, forks: None, open issues:None_
* [request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™. -> _stars: None, forks: None, open issues:None_
* [rerate](https://github.com/abo/rerate) - Redis-based rate counter and rate limiter for Go. -> _stars: None, forks: None, open issues:None_
* [rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes. -> _stars: None, forks: None, open issues:None_
* [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client. -> _stars: None, forks: None, open issues:None_
* [retry](https://github.com/kamilsk/retry) - Functional mechanism based on context to perform actions repetitively until successful. -> _stars: None, forks: None, open issues:None_
* [robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics. -> _stars: None, forks: None, open issues:None_
* [scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy. -> _stars: None, forks: None, open issues:None_
* [sling](https://github.com/dghubble/sling) - Go HTTP requests builder for API clients. -> _stars: None, forks: None, open issues:None_
* [spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options. -> _stars: None, forks: None, open issues:None_
* [sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package. -> _stars: None, forks: None, open issues:None_
* [Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB. -> _stars: None, forks: None, open issues:None_
* [Task](https://github.com/go-task/task) - simple "Make" alternative. -> _stars: None, forks: None, open issues:None_
* [toolbox](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer. -> _stars: None, forks: None, open issues:None_
* [ugo](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go. -> _stars: None, forks: None, open issues:None_
* [UNIS](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go. -> _stars: None, forks: None, open issues:None_
* [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases. -> _stars: None, forks: None, open issues:None_
* [util](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...). -> _stars: None, forks: None, open issues:None_
* [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection. -> _stars: None, forks: None, open issues:None_
* [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang. -> _stars: None, forks: None, open issues:None_
* [xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs. -> _stars: None, forks: None, open issues:None_

## Validation

*Libraries for validation.*

* [govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs. -> _stars: None, forks: None, open issues:None_
* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags. -> _stars: None, forks: None, open issues:None_
* [validate](https://github.com/markbates/validate) - This package provides a framework for writing validations for Go applications. -> _stars: None, forks: None, open issues:None_
* [validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving. -> _stars: None, forks: None, open issues:None_

## Version Control

*Libraries for version control.*

* [gh](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks. -> _stars: None, forks: None, open issues:None_
* [git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2. -> _stars: None, forks: None, open issues:None_
* [go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go. -> _stars: None, forks: None, open issues:None_
* [hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories. -> _stars: None, forks: None, open issues:None_

## Video

*Libraries for manipulating video.*

* [gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries. -> _stars: None, forks: None, open issues:None_
* [go-astisub](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.). -> _stars: None, forks: None, open issues:None_
* [goav](https://github.com/giorgisio/goav) - Comphrensive Go bindings for FFmpeg. -> _stars: None, forks: None, open issues:None_
* [gst](https://github.com/ziutek/gst) - Go bindings for GStreamer. -> _stars: None, forks: None, open issues:None_
* [libgosubs](https://github.com/wargarblgarbl/libgosubs) - Subtitle format support for go. Supports .srt, .ttml, and .ass. -> _stars: None, forks: None, open issues:None_
* [v4l](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go. -> _stars: None, forks: None, open issues:None_

## Web Frameworks

*Full stack web frameworks.*

* [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
* [Air](https://github.com/sheng/air) - Ideal RESTful web framework for Go. -> _stars: None, forks: None, open issues:None_
* [Beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language. -> _stars: None, forks: None, open issues:None_
* [Buffalo](http://gobuffalo.io) - Bringing the productivity of Rails to Go!
* [Echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework. -> _stars: None, forks: None, open issues:None_
* [Fireball](https://github.com/zpatrick/fireball) - More "natural" feeling web framework. -> _stars: None, forks: None, open issues:None_
* [Florest](https://github.com/jabong/florest-core) - High-performance workflow based REST API framework. -> _stars: None, forks: None, open issues:None_
* [Gem](https://github.com/go-gem/gem) - Simple and fast web framework, friendly to REST API. -> _stars: None, forks: None, open issues:None_
* [Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity. -> _stars: None, forks: None, open issues:None_
* [Gizmo](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times. -> _stars: None, forks: None, open issues:None_
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API. -> _stars: None, forks: None, open issues:None_
* [go-relax](https://github.com/codehack/go-relax) - Framework of pluggable components to build RESTful API's. -> _stars: None, forks: None, open issues:None_
* [go-rest](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go. -> _stars: None, forks: None, open issues:None_
* [goa](https://github.com/raphael/goa) - Framework for developing microservices based on the design of Ruby's Praxis. -> _stars: None, forks: None, open issues:None_
* [Goat](https://github.com/bahlo/goat) - Minimalistic REST API server in Go. -> _stars: None, forks: None, open issues:None_
* [Golf](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library. -> _stars: None, forks: None, open issues:None_
* [Gondola](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster. -> _stars: None, forks: None, open issues:None_
* [gongular](https://github.com/mustafaakin/gongular) - Fast Go web framework with input mapping/validation and (DI) Dependency Injection. -> _stars: None, forks: None, open issues:None_
* [Macaron](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go. -> _stars: None, forks: None, open issues:None_
* [mango](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333. -> _stars: None, forks: None, open issues:None_
* [Microservice](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang. -> _stars: None, forks: None, open issues:None_
* [neo](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API. -> _stars: None, forks: None, open issues:None_
* [Resoursea](https://github.com/resoursea/api) - REST framework for quickly writing resource based services. -> _stars: None, forks: None, open issues:None_
* [REST Layer](http://rest-layer.io) - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
* [Revel](https://github.com/revel/revel) - High-productivity web framework for the Go language. -> _stars: None, forks: None, open issues:None_
* [rex](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`. -> _stars: None, forks: None, open issues:None_
* [sawsij](https://github.com/jaybill/sawsij) - lightweight, open-source web framework for building high-performance, data-driven web applications. -> _stars: None, forks: None, open issues:None_
* [tango](https://github.com/lunny/tango) - Micro & pluggable web framework for Go. -> _stars: None, forks: None, open issues:None_
* [tigertonic](https://github.com/rcrowley/go-tigertonic) - Go framework for building JSON web services inspired by Dropwizard. -> _stars: None, forks: None, open issues:None_
* [traffic](https://github.com/pilu/traffic) - Sinatra inspired regexp/pattern mux and web framework for Go. -> _stars: None, forks: None, open issues:None_
* [utron](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang). -> _stars: None, forks: None, open issues:None_
* [violetear](https://github.com/nbari/violetear) - Go HTTP router. -> _stars: None, forks: None, open issues:None_
* [YARF](https://github.com/yarf-framework/yarf) - Fast micro-framework designed to build REST APIs and web services in a fast and simple way. -> _stars: None, forks: None, open issues:None_
* [Zerver](https://github.com/cosiner/zerver) - Zerver is an expressive, modular, feature completed RESTful framework. -> _stars: None, forks: None, open issues:None_

### Middlewares

#### Actual middlewares

* [CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API. -> _stars: None, forks: None, open issues:None_
* [formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST. -> _stars: None, forks: None, open issues:None_
* [Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go. -> _stars: None, forks: None, open issues:None_
* [Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler. -> _stars: None, forks: None, open issues:None_
* [XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends. -> _stars: None, forks: None, open issues:None_

#### Libraries for creating HTTP middlewares

* [alice](https://github.com/justinas/alice) - Painless middleware chaining for Go. -> _stars: None, forks: None, open issues:None_
* [catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain"). -> _stars: None, forks: None, open issues:None_
* [chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware"). -> _stars: None, forks: None, open issues:None_
* [go-wrap](https://github.com/go-on/wrap) - Small middlewares package for net/http. -> _stars: None, forks: None, open issues:None_
* [gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs. -> _stars: None, forks: None, open issues:None_
* [interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang. -> _stars: None, forks: None, open issues:None_
* [muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http. -> _stars: None, forks: None, open issues:None_
* [negroni](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang. -> _stars: None, forks: None, open issues:None_
* [render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses. -> _stars: None, forks: None, open issues:None_
* [rye](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context. -> _stars: None, forks: None, open issues:None_
* [stats](https://github.com/thoas/stats) - Go middleware that stores various information about your web application. -> _stars: None, forks: None, open issues:None_
* [Volatile](https://github.com/volatile/core) - Minimalist middleware stack promoting flexibility, good practices and clean code. -> _stars: None, forks: None, open issues:None_

### Routers

* [alien](https://github.com/gernest/alien) - Lightweight and fast http router from outer space. -> _stars: None, forks: None, open issues:None_
* [Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer. -> _stars: None, forks: None, open issues:None_
* [Bxog](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters. -> _stars: None, forks: None, open issues:None_
* [chi](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context. -> _stars: None, forks: None, open issues:None_
* [fasthttprouter](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`. -> _stars: None, forks: None, open issues:None_
* [gocraft/web](https://github.com/gocraft/web) - Mux and middleware package in Go. -> _stars: None, forks: None, open issues:None_
* [Goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`. -> _stars: None, forks: None, open issues:None_
* [GoRouter](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`. -> _stars: None, forks: None, open issues:None_
* [gowww/router](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface. -> _stars: None, forks: None, open issues:None_
* [httprouter](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework. -> _stars: None, forks: None, open issues:None_
* [httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter. -> _stars: None, forks: None, open issues:None_
* [lars](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks. -> _stars: None, forks: None, open issues:None_
* [medeina](https://github.com/imdario/medeina) - Medeina is a HTTP routing tree based on HttpRouter, inspired by Roda and Cuba. -> _stars: None, forks: None, open issues:None_
* [mux](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang. -> _stars: None, forks: None, open issues:None_
* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs. -> _stars: None, forks: None, open issues:None_
* [pat](https://github.com/bmizerany/pat) - Sinatra style pattern muxer for Go’s net/http library, by the author of Sinatra. -> _stars: None, forks: None, open issues:None_
* [pure](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation. -> _stars: None, forks: None, open issues:None_
* [Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers. -> _stars: None, forks: None, open issues:None_
* [vestigo](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications. -> _stars: None, forks: None, open issues:None_
* [xmux](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support. -> _stars: None, forks: None, open issues:None_
* [zeus](https://github.com/daryl/zeus) - Very simple and fast HTTP router for Go. -> _stars: None, forks: None, open issues:None_

## Windows

* [d3d9](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9. -> _stars: None, forks: None, open issues:None_
* [go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang. -> _stars: None, forks: None, open issues:None_

## XML

*Libraries and tools for manipulating XML.*

* [go-pkg-xmlx](https://github.com/jteeuwen/go-pkg-xmlx) - Extension to the standard Go XML package. Maintains a node tree that allows forward/backwards browsing and exposes some simple single/multi-node search functions. -> _stars: None, forks: None, open issues:None_
* [XML-Comp](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags. -> _stars: None, forks: None, open issues:None_
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module. -> _stars: None, forks: None, open issues:None_
* [xpath](https://github.com/antchfx/xpath) - XPath package for Go. -> _stars: None, forks: None, open issues:None_
* [xquery](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression. -> _stars: None, forks: None, open issues:None_

# Tools

*Go software and plugins.*

## Code Analysis

* [apicompat](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes. -> _stars: None, forks: None, open issues:None_
* [dupl](https://github.com/mibk/dupl) - Tool for code clone detection. -> _stars: None, forks: None, open issues:None_
* [errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs. -> _stars: None, forks: None, open issues:None_
* [gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time. -> _stars: None, forks: None, open issues:None_
* [Go Metalinter](https://github.com/alecthomas/gometalinter) - Metalinter is a tool to automatically apply all static analysis tool and report their output in normalized form. -> _stars: None, forks: None, open issues:None_
* [go-checkstyle](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style refered to some points in Go Code Review Comments. -> _stars: None, forks: None, open issues:None_
* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects. -> _stars: None, forks: None, open issues:None_
* [go-outdated](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages. -> _stars: None, forks: None, open issues:None_
* [goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer. -> _stars: None, forks: None, open issues:None_
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [GoLint](https://github.com/golang/lint) - Golint is a linter for Go source code. -> _stars: None, forks: None, open issues:None_
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple is a linter for Go source code that specialises on simplifying code. -> _stars: None, forks: None, open issues:None_
* [gostatus](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages. -> _stars: None, forks: None, open issues:None_
* [interfacer](https://github.com/mvdan/interfacer) - Linter that suggests interface types. -> _stars: None, forks: None, open issues:None_
* [lint](https://github.com/surullabs/lint) - Run linters as part of go test. -> _stars: None, forks: None, open issues:None_
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#. -> _stars: None, forks: None, open issues:None_
* [unconvert](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source. -> _stars: None, forks: None, open issues:None_
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - unused checks Go code for unused constants, variables, functions and types. -> _stars: None, forks: None, open issues:None_
* [validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags. -> _stars: None, forks: None, open issues:None_

## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
* [go-lang-idea-plugin](https://github.com/go-lang-plugin-org/go-lang-idea-plugin) (deprecated) - The previous Go plugin for IntelliJ (JetBrains) IDEA, now replaced by the official plugin (above). -> _stars: None, forks: None, open issues:None_
* [go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs. -> _stars: None, forks: None, open issues:None_
* [go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting. -> _stars: None, forks: None, open issues:None_
* [Goclipse](https://github.com/GoClipse/goclipse) - Eclipse plugin for Go. -> _stars: None, forks: None, open issues:None_
* [gocode](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language. -> _stars: None, forks: None, open issues:None_
* [GoSublime](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 2 providing code completion and other IDE-like features. -> _stars: None, forks: None, open issues:None_
* [velour](https://github.com/velour/velour) - IRC client for the acme editor. -> _stars: None, forks: None, open issues:None_
* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save. -> _stars: None, forks: None, open issues:None_
* [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim. -> _stars: None, forks: None, open issues:None_
* [vscode-go](https://github.com/Microsoft/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language. -> _stars: None, forks: None, open issues:None_
* [Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes. -> _stars: None, forks: None, open issues:None_

## Go Tools

* [colorgo](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output. -> _stars: None, forks: None, open issues:None_
* [depth](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports. -> _stars: None, forks: None, open issues:None_
* [gb](https://getgb.io/) - An easy to use project based build tool for the Go programming language.
* [go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format. -> _stars: None, forks: None, open issues:None_
* [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo. -> _stars: None, forks: None, open issues:None_
* [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API. -> _stars: None, forks: None, open issues:None_
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub. -> _stars: None, forks: None, open issues:None_
* [rts](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses. -> _stars: None, forks: None, open issues:None_

## Software Packages

*Software written in Go.*

### DevOps Tools

* [aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool. -> _stars: None, forks: None, open issues:None_
* [aurora](https://github.com/Luxurioust/aurora) - Cross-platform web-based Beanstalkd queue server console. -> _stars: None, forks: None, open issues:None_
* [awsenv](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile. -> _stars: None, forks: None, open issues:None_
* [Banshee](https://github.com/eleme/banshee) - Anomalies detection system for periodic metrics. -> _stars: None, forks: None, open issues:None_
* [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool. -> _stars: None, forks: None, open issues:None_
* [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework. -> _stars: None, forks: None, open issues:None_
* [dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart). -> _stars: None, forks: None, open issues:None_
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI. -> _stars: None, forks: None, open issues:None_
* [drone-scp](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI. -> _stars: None, forks: None, open issues:None_
* [Dropship](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn. -> _stars: None, forks: None, open issues:None_
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`. -> _stars: None, forks: None, open issues:None_
* [Gitea](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven. -> _stars: None, forks: None, open issues:None_
* [Go Metrics](https://github.com/rcrowley/go-metrics) - Go port of Coda Hale's Metrics library: https://github.com/codahale/metrics. -> _stars: None, forks: None, open issues:None_
* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update. -> _stars: None, forks: None, open issues:None_
* [gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go. -> _stars: None, forks: None, open issues:None_
* [godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application. -> _stars: None, forks: None, open issues:None_
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages. -> _stars: None, forks: None, open issues:None_
* [govvv](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries. -> _stars: None, forks: None, open issues:None_
* [gox](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool. -> _stars: None, forks: None, open issues:None_
* [goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging. -> _stars: None, forks: None, open issues:None_
* [grapes](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease. -> _stars: None, forks: None, open issues:None_
* [GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions. -> _stars: None, forks: None, open issues:None_
* [Hey](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application. -> _stars: None, forks: None, open issues:None_
* [kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler. -> _stars: None, forks: None, open issues:None_
* [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google. -> _stars: None, forks: None, open issues:None_
* [Moby](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems. -> _stars: None, forks: None, open issues:None_
* [Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data. -> _stars: None, forks: None, open issues:None_
* [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB. -> _stars: None, forks: None, open issues:None_
* [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. -> _stars: None, forks: None, open issues:None_
* [Pewpew](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester. -> _stars: None, forks: None, open issues:None_
* [Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies. -> _stars: None, forks: None, open issues:None_
* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3. -> _stars: None, forks: None, open issues:None_
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker). -> _stars: None, forks: None, open issues:None_
* [sg](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the reponse code and data between each call for specific server stress based on its previous response. -> _stars: None, forks: None, open issues:None_
* [StatusOK](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected. -> _stars: None, forks: None, open issues:None_
* [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000! -> _stars: None, forks: None, open issues:None_
* [webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server. -> _stars: None, forks: None, open issues:None_
* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
* [winrm-cli](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines. -> _stars: None, forks: None, open issues:None_

### Other Software
* [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets. -> _stars: None, forks: None, open issues:None_
* [boxed](https://github.com/tejo/boxed) - Dropbox based blog engine. -> _stars: None, forks: None, open issues:None_
* [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go. -> _stars: None, forks: None, open issues:None_
* [Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications. -> _stars: None, forks: None, open issues:None_
* [Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections. -> _stars: None, forks: None, open issues:None_
* [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul. -> _stars: None, forks: None, open issues:None_
* [DDNS](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend. -> _stars: None, forks: None, open issues:None_
* [Docker](http://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* [Documize](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools. -> _stars: None, forks: None, open issues:None_
* [fleet](https://github.com/coreos/fleet) - Distributed init System. -> _stars: None, forks: None, open issues:None_
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH. -> _stars: None, forks: None, open issues:None_
* [gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go. -> _stars: None, forks: None, open issues:None_
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at funciton list. -> _stars: None, forks: None, open issues:None_
* [Gogland](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
* [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time. -> _stars: None, forks: None, open issues:None_
* [hugo](http://gohugo.io/) - Fast and Modern Static Website Engine.
* [ipe](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO. -> _stars: None, forks: None, open issues:None_
* [JayDiff](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go. -> _stars: None, forks: None, open issues:None_
* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [Leaps](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms. -> _stars: None, forks: None, open issues:None_
* [limetext](http://limetext.org/) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE. -> _stars: None, forks: None, open issues:None_
* [mockingjay](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests. -> _stars: None, forks: None, open issues:None_
* [myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go. -> _stars: None, forks: None, open issues:None_
* [naclpipe](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go. -> _stars: None, forks: None, open issues:None_
* [nes](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go. -> _stars: None, forks: None, open issues:None_
* [orange-cat](https://github.com/noraesae/orange-cat) - Markdown previewer written in Go. -> _stars: None, forks: None, open issues:None_
* [Orbit](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates. -> _stars: None, forks: None, open issues:None_
* [peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. -> _stars: None, forks: None, open issues:None_
* [Postman](https://github.com/zachlatta/postman) - Command-line utility for batch-sending email. -> _stars: None, forks: None, open issues:None_
* [restic](https://github.com/restic/restic) - De-duplicating backup program. -> _stars: None, forks: None, open issues:None_
* [rkt](https://github.com/coreos/rkt) - App Container runtime that integrates with init systems, is compatible with other container formats like Docker, and supports alternative execution engines like KVM. -> _stars: None, forks: None, open issues:None_
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek. -> _stars: None, forks: None, open issues:None_
* [shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control). -> _stars: None, forks: None, open issues:None_
* [snap](https://github.com/intelsdi-x/snap) - Powerful telemetry framework. -> _stars: None, forks: None, open issues:None_
* [Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers. -> _stars: None, forks: None, open issues:None_
* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* [Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging. -> _stars: None, forks: None, open issues:None_
* [toto](https://github.com/blogcin/ToTo) - Simple proxy server written in Go language, can be used together with browser. -> _stars: None, forks: None, open issues:None_
* [toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests. -> _stars: None, forks: None, open issues:None_
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [vFlow](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector. -> _stars: None, forks: None, open issues:None_
* [websysd](https://github.com/ian-kent/websysd) - Web based process manager (like Marathon or Upstart). -> _stars: None, forks: None, open issues:None_
* [wellington](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass). -> _stars: None, forks: None, open issues:None_

# Resources

*Where to discover new Go libraries.*

## Benchmarks

* [autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions. -> _stars: None, forks: None, open issues:None_
* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results. -> _stars: None, forks: None, open issues:None_
* [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches. -> _stars: None, forks: None, open issues:None_
* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison. -> _stars: None, forks: None, open issues:None_
* [go-type-assertion-benchmark](https://github.com/hgfischer/go-type-assertion-benchmark) - Naive performance test of two ways to do type assertion in Go. -> _stars: None, forks: None, open issues:None_
* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark. -> _stars: None, forks: None, open issues:None_
* [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods. -> _stars: None, forks: None, open issues:None_
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language. -> _stars: None, forks: None, open issues:None_
* [golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks) - Tiny collection of Go micro benchmarks. The intent is to compare some language features to others. -> _stars: None, forks: None, open issues:None_
* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities. -> _stars: None, forks: None, open issues:None_
* [gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs. -> _stars: None, forks: None, open issues:None_
* [kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark. -> _stars: None, forks: None, open issues:None_
* [skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark. -> _stars: None, forks: None, open issues:None_
* [speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language. -> _stars: None, forks: None, open issues:None_

## Conferences

* [Capital Go](http://www.capitalgolang.com) - Washington, D.C., USA
* [dotGo](http://www.dotgo.eu) - Paris, France
* [GoCon](http://gocon.connpass.com/) - Tokyo, Japan
* [GolangUK](http://golanguk.com/) - London, UK
* [GopherChina](http://gopherchina.org) - Shanghai, China
* [GopherCon](http://www.gophercon.com/) - Denver, USA
* [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, BR
* [GopherCon Dubai](http://www.gophercon.ae/) - Dubai, UAE
* [GopherCon India](http://www.gophercon.in/) - Pune, India
* [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore
* [GothamGo](http://gothamgo.com/) - New York City, USA

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go Bootcamp](http://golangbootcamp.com)
* [GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books. -> _stars: None, forks: None, open issues:None_
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

## Websites

* [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them is looking for Go hackers. -> _stars: None, forks: None, open issues:None_
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists. -> _stars: None, forks: None, open issues:None_
* [Flipboard - Go Magazine](https://flipboard.com/section/the-golang-magazine-bVP7nS) - Collection of Go articles and tutorials.
* [Go Blog](http://blog.golang.org) - The official Go blog.
* [Go Challenge](http://golang-challenge.org/) - Learn Go by solving problems and getting feedback from Go experts.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki. -> _stars: None, forks: None, open issues:None_
* [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go. -> _stars: None, forks: None, open issues:None_
* [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
* [Golang Flow](http://golangflow.io) - Post Updates, News, Packages and more.
* [Golang News](https://golangnews.com) - Links and news about Go programming.
* [golang-graphics](https://github.com/mholt/golang-graphics) - Collection of Go images, graphics, and art. -> _stars: None, forks: None, open issues:None_
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [r/Golang](https://www.reddit.com/r/golang) - News about Go.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries. -> _stars: None, forks: None, open issues:None_

### Tutorials

* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go.
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang. -> _stars: None, forks: None, open issues:None_
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card. -> _stars: None, forks: None, open issues:None_
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* [Working with Go](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers. -> _stars: None, forks: None, open issues:None_
