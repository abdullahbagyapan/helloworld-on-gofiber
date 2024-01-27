# Hello World on GoFiber

## What is GoFiber

Fiber is an [Express](https://github.com/expressjs/express) inspired web framework built on top of [Fasthttp](https://github.com/valyala/fasthttp), the fastest HTTP engine for Go.
Designed to ease things up for fast development with zero memory allocation and performance in mind.

## Installation

First of all, download and install [Go](https://go.dev/doc/install). 1.17 or higher is required for gofiber.

## Quick Start

You need the initialize new go module.

```bash
go mod init <module-name>
```

Then, we need the download dependencies.

```bash
go get
```

Finally, we can run our little web server.

```bash
go run main.go
```

View the website at: http://localhost:3000/