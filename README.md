<h1 align="center">
  <br>
  <a href="https://leofvo.github.io/go4hackers/"><img src="docs/public/logo.png" width="200px" alt="go4hackers"></a>
</h1>

<h4 align="center">go4hackers is a starter template typically made for create open-source tool in Go.</h4>
<p align="center">
<img src="https://img.shields.io/github/go-mod/go-version/leofvo/go4hackers?filename=go.mod">
<a href="https://github.com/leofvo/go4hackers/releases"><img src="https://img.shields.io/github/downloads/leofvo/go4hackers/total">
<a href="https://github.com/leofvo/go4hackers/graphs/contributors"><img src="https://img.shields.io/github/contributors-anon/leofvo/go4hackers">
<a href="https://github.com/leofvo/go4hackers/releases/"><img src="https://img.shields.io/github/release/leofvo/go4hackers">
<a href="https://github.com/leofvo/go4hackers/issues"><img src="https://img.shields.io/github/issues-raw/leofvo/go4hackers">
<a href="https://github.com/leofvo/go4hackers/discussions"><img src="https://img.shields.io/github/discussions/leofvo/go4hackers">
<a href="https://twitter.com/leofvo"><img src="https://img.shields.io/twitter/follow/leofvo.svg?logo=twitter"></a>

</p>
      
<p align="center">
  <a href="#how-to-use">How</a> •
  <a href="#install">Install</a> •
  <a href="https://leofvo.github.io/go4hackers/">Documentation</a> •
</p>

## How to use

```bash
go4hackers -h
```

This will display help for the tool. Here are all the switches it supports.

## Install

If you have a [Go](https://golang.org/) environment ready to go (at least go 1.19), it's as easy as:

```bash
go install github.com/LeoFVO/go4hackers@latest
```

PS: You need at least go 1.19 to compile go4hackers.

<details>
  <summary>Docker</summary>
  ```bash
  docker pull ghcr.io/leofvo/go4hackers:latest
  docker run go4hackers:latest
  ```
</details>

<details>
  <summary>Binary Releases</summary>
We are now shipping binaries for each of the releases so that you don't even have to build them yourself! How wonderful is that!

If you're stupid enough to trust binaries that I've put together, you can download them from the [releases](https://github.com/LeoFVO/go4hackers/releases) page.

</details>
<details>
  <summary>Build from source</summary>

#### Prerequisites

Since this tool is written in [Go](https://golang.org/) you need to install the Go language/compiler/etc. Full details of installation and set up can be found [on the Go language website](https://golang.org/doc/install). Once installed you have two options. You need at least go 1.19 to compile go4hackers.

#### Clone the repository

```bash
git clone git@github.com:LeoFVO/go4hackers.git
```

#### Compiling

`go4hackers` has external dependencies, and so they need to be pulled in first:

```bash
go get && go build
```

This will create a `go4hackers` binary for you. If you want to install it in the `$GOPATH/bin` folder you can run:

```bash
go install
```

</details>

## Setup

### Documentation

The documentation is available at [https://leofvo.github.io/go4hackers/](https://leofvo.github.io/go4hackers/).

In order to deploy documentation for your project, you need to allow github actions to deploy github pages. To do so, go to your repository settings > Pages, and in the `Build and deployment` section, select `Github Actions` as the source.

# License

go4hackers is distributed under [MIT License](https://github.com/leofvo/go4hackers/blob/main/LICENSE)
