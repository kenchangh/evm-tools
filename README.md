# evm-tools

A collection of tools for working with the evm

Some of these tools (`evm`, `disasm`) are forked directly from
[go-ethereum](https://github.com/ethereum/go-ethereum),
though `evm` has been modified to support persistence.

See the [analysis/guide.md](analysis/guide.md) for an extensive guide of the EVM using these tools.

# Install

Uses [`dep`](https://github.com/golang/dep) for dependencies and `make` to build
all tools: 

```
dep ensure
make
```

See the [install instructions](INSTALL.md) for more details.
