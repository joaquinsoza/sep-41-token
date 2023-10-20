# SEP-0041 Token
Exposes the interface of the SEP-0041 Token alongside a mock token contract.

SEP-0041 Definition: https://github.com/stellar/stellar-protocol/blob/master/ecosystem/sep-0041.md

## Getting Started

Add the package to your `Cargo.toml`:

```toml
[dependencies]
sep-41-token = "<desired version>"
```

You can optionally include the `testutils` feature in your `dev-dependencies` to deploy a mock version of the `sep-41-token` for testing:

```toml
[dev_dependencies]
sep-40-token = { version = "<desired version>", features = ["testutils"] }
```
