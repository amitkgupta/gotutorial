### Why go?

* Great toolchain
* Rich standard library, especially for systems-level and network-level programming (e.g. HTTP servers)
* Simple primitives for concurrency
* Light-weight, statically linked binaries
* Strongly typed, fast & informative compiler
* Very simple language, often only one way to do things
* Vibrant community

### Getting Started

* Install Golang (brew)
* Install Sublime Text 3 (or your favourite editor)

### go Toolchain

Most commonly used commands:

* `go get [-t -u -v -d]`
* `go install`
* `go run`

Also used:

* `go fmt` (if your editor doesn't do it for you)
* `go test [-c]`
* `go build`
* `go list`

### Code Organization

* `$GOPATH`
* `pkg`, `bin`, `src`
* `PATH=$GOPATH/bin:$PATH`
* Optional: `direnv`
* libraries and executables

### Editor Tools

* Autocompletion
* Autoformatting
* Auto-imports
* (For Sublime): `GoSublime` + `goimports`

### Testing

* Ginkgo and Gomega
* Advanced: `gbytes`, `gexec`, `ghttp`
* Advanced: custom Gomega matchers

### Scripting and Experimentation

* `go run`, again
* [Playground](play.golang.org)

### Learning

* [Tour](tour.golang.org)
* Go Koans
* [Documentation](godoc.org)
	* Standard library is very well documented
	* Many other libraries' documentation can be found on godoc.org
	* Advanced: spin up your own godoc server

### Dependency Management

* `godep`
* Advanced: vendoring via submodules
	* Gotcha: `hg`

### Advanced: Debugging and Profiling

* pprof (debug server, profiling tool)

### Advanced: Version Management

* `gvm`