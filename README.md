# SeiJS

SeiJS is a monorepo that contains multiple NPM libraries for writing applications that interact with Sei.

## Documentation

Please check [our documentation](https://docs.sei.io) for notes on how to get up and running. The tutorial has examples on how to connect to a Sei wallet, query an RPC endpoint, transfer tokens, IBC transfer, and interact with contracts.

You can also refer to the [typedoc documentation](https://sei-protocol.github.io/sei-js/) for reference on the contents of the @sei-js/core and @sei-js/react library.


## Packages

SeiJS consists of smaller NPM packages within the @sei-js namespace. For more detailed documentation on each package, please refer to the table below.

| Package                           | Description                                                                                                               |
|-----------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| [@sei-js/cosmjs](packages/cosmjs) | TypeScript library containing helper functions for wallet connection, transaction signing, and RPC querying using cosmjs. |
| [@sei-js/evm](packages/evm)       | Typescript library containing helper functions for interacting with the EVM on Sei.                                       |
| [@sei-js/proto](packages/proto)   | TypeScript library for Sei protobufs generated using [Telescope](https://github.com/osmosis-labs/telescope)               |

## Development
To build all packages and docs, run `yarn install` then `yarn build:all`

This workspace was generated by [Nx, a Smart, fast and extensible build system.](https://nx.dev).
