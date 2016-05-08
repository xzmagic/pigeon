[![Build Status](https://travis-ci.org/kamlesh-bambarde/pigeon.svg?branch=master)](https://travis-ci.org/kamlesh-bambarde/pigeon)  [![Gitter chat](https://badges.gitter.im/gitterHQ/services.png)](https://gitter.im/kamlesh-bambarde/pigeon)

##Pigeon

Pigeon is a high performance micro web framework written in C++. It is built on top of libuv which is an abstraction of evented io mechanisms like epoll/kqueue/event ports and IOCP (not exactly an evented io) on windows developed in C.

Pigeon is capable of serving static web content and supports native web api, which makes it possible to run Html5 application built using AngularJs/ReactJs. The native web api can be used to serve data, that is requested via ajax calls from the Html5 Applications.

##Features

- HTTP Compression
- Native WebAPI
- Http Filters (intercept request/response)
- Static Resource Cache
- File Upload Handlers (multipart/form-data parser)

##Todo
- SSL Implementation
- Built-in Json Parser

##Getting Started

Please refer wiki to get started.

