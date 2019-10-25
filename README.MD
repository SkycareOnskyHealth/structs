# Struct Helper

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://github.com/nguyencatpham/request-handler)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/nguyencatpham/request-handler)

Merge two different structs, and overwrite fields
## Why created

To make creating struct for tests easier.

# Getting Started!

  #### Model input
  ```
  type RequestModel struct {
	URL       string
	TokenType TokenType
	Token     string
	Username  string
	Password  string
	Body      string
}
  ```

### Installation

Request handler requires [Go](https://golang.org/) v1.11+ to run.

Install the package.

```sh
$ go get github.com/onskycloud/structs
```

#### Kubernetes + Google Cloud

See [KUBERNETES.md](https://github.com/joemccann/dillinger/blob/master/KUBERNETES.md)


### Todos

 - Write MORE Tests
 - Add Night Mode

License
----

MIT
