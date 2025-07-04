# Go Fundamentals

A quick reference for common Go commands used in development.

## Commands

### `go build`
Compiles a set of Go source files into an executable binary, but does **not** install it.

```bash
go build
```

### `go run`
Compiles and runs Go source files in a single step. Useful for quick execution of small programs.

```bash
go run main.go
```

### `go fmt`
Automatically formats Go source code according to the Go style guide.

```bash
go fmt ./...
```

### `go get`
Downloads and installs packages and dependencies from a remote repository.

```bash
go get github.com/user/repo
```

### `go install`
Compiles and installs the package, placing the resulting binary in your `$GOBIN` directory.

```bash
go install ./...
```

### `go test`
Runs test functions (`*_test.go`) associated with the current package.

```bash
go test
```

