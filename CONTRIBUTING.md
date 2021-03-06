Contributing Guide
------------------

Thank you for your interest in contributing! Improvements and reports of bugs
or documentation flaws are welcomed.

This is a small and simple project, but as my first public Go project I've
tried to establish good habits to follow. If you're unsure about anything,
don't hesitate to ask.

Please submit fixes or enhancements via GitHub pull requests, ensuring that
changes have passing test coverage and a clean bill of health from `golint`,
`gofmt`, and preferably `go vet`. The latter checks are not yet automated so
your diligence is appreciated.

You can inspect the `.travis.yml` file to see how the build is executed on CI,
pull requests will be checked to pass the same procedure. The convenience `make
get-devtools` target can install any tools that you're missing.

If you wish to contribute a change that involves updating dependencies, please
use Go 1.11 or later for your work so that [the `go` tool supports managing
`go.mod`][mod].

[mod]: https://tip.golang.org/cmd/go/#hdr-Maintaining_module_requirements
