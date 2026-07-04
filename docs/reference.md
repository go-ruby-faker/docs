# Reference

The public API lives at the module root (`github.com/go-ruby-faker/faker`). It is
**Ruby-shaped but Go-idiomatic**: names mirror Ruby's `faker`, while the surface follows
Go conventions — value types, explicit errors, no global state.

## Install

```sh
go get github.com/go-ruby-faker/faker
```

## Import

```go
import "github.com/go-ruby-faker/faker"
```

## API reference

The authoritative, always-current API reference is generated from the source by
pkg.go.dev:

- **[pkg.go.dev/github.com/go-ruby-faker/faker](https://pkg.go.dev/github.com/go-ruby-faker/faker)**

The module's [README](https://github.com/go-ruby-faker/faker#readme) carries worked
examples and the full, up-to-date surface. This page intentionally links to those
canonical sources rather than duplicating signatures that could drift out of date.

## Conformance

Behaviour is pinned by a **differential oracle** against reference Ruby: a corpus
is run through both the `ruby` binary and this library and the results are compared,
gated on the reference where relevant and skipping itself where `ruby` is absent so
the cross-arch lanes still validate the library.
