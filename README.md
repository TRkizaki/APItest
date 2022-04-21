# REST API TEST

## Developing a RESTful API with Go and Gin

reference: https://go.dev/doc/tutorial/web-service-gin

### 1. Installation

[Gin Web Framework/Quickstart](https://gin-gonic.com/docs/quickstart/)

```
$ go get -u github.com/gin-gonic/gin
```

### 2. setting CPATH and CGO before `go run . `

```
export CPATH="/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX.sdk/usr/include/"
export CGO_ENABLED=1; export CC=gcc;
```

reference: <https://stackoverflow.com/a/61515424>
<https://github.com/golang/go/issues/27921#issuecomment-545347475>
