# solidity-typescript-template

Solidity/Truffle Template With TypeScript Tests

## Developer Tools 🛠️

- [Truffle](https://trufflesuite.com/)
- [TypeChain](https://github.com/ethereum-ts/TypeChain)
- [Openzeppelin Contracts](https://openzeppelin.com/contracts/)

## Start

Create `.infura` and `.secret` files. Install the dependencies:

```bash
$ yarn install
```

## Tests

```bash
$ yarn test
```

## Coverage

```bash
$ yarn coverage
```

## Deploying

Deploy to Kovan:

```bash
$ NETWORK=kovan yarn deploy
```

## Verifying Contract Code

```bash
$ NETWORK=kovan yarn run verify YourContractName
```
