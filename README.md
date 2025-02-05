### Background:

- **dataparser-syn-lib**: Data parser source and results based syn library.
- **elasticsearch**: A project for various of elasticsearch and REST API with Rust.
- **pg_query**: A project that Postgresql database interaction with Rust.
- **rust-postgresql**: A simple project for Postgresql integration with Rust.

## Makefile

Each subdirectory project uses this style to make it easy to test and run

```
format:
	cargo fmt --quiet

lint:
	cargo clippy --quiet

test:
	cargo test --quiet

run:
	cargo run 

all: format lint test run
```
