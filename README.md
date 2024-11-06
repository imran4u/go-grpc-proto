# go-grpc

The Github repository should contains the following folders:

proto/... : to store protocol buffers schema

protogen/go/... : to store generated Go source files

Create Github Actions file (see here for reference) on pull request or push to particular branch (main or master), with following steps:

Checkout source code ([reference](https://github.com/marketplace/actions/checkout))

Install Go ([reference](https://github.com/marketplace/actions/setup-go-environment))

Generate Go source (run custom Makefile or shell script, [reference](https://docs.github.com/en/actions/about-github-actions/understanding-github-actions))

If this is a push to main or master : tag the updated repository ([reference](https://github.com/marketplace/actions/github-tag))

If this is a push to main or master : commit the updated repository ([reference](https://github.com/marketplace/actions/git-auto-commit))

## Commands used
    1. init module

        `go mod init github.com/imran4u/go-grpc`
    2. 