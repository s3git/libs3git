libs3git
========

This is the C interface for s3git.

How to generate
---------------

Do not edit this code as it is auto-generated from the libs3git.go file that serves as the interface to the s3git-go library

```sh
$ go build -buildmode=c-shared -o libs3git.so libs3git.go
```

Please also see the other wrappers via libs3git to higher level languages such as [Ruby](https://github.com/s3git/s3git-rb).
