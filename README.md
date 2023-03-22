# sample

Sample project to showcase StackAid discovering dependencies across two ecosystems (Go and NodeJS), and user provided repositories in the form of a `stackaid.json` file.

Our hypothetical project that uses Go, NodeJS, and Postgres. We've declared our dependencies in the `go.mod` and `package.json` files. For dependencies not in either of those files, we explicit specify them in the `stackaid.json` file.
