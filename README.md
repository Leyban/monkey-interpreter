# monkey-interpreter

A lexer, parser, and REPL for the Monkey programming language, written in Go — following Thorsten Ball's *Writing an Interpreter in Go*.

- `lexer/` — tokenizes Monkey source into a token stream
- `ast/` — abstract syntax tree node definitions
- `parser/` — recursive-descent (Pratt) parser building the AST from tokens
- `repl/` — interactive read-eval-print loop

Each package has its own test suite (`go test ./...`).

## Run the REPL

```
go run main.go
```
