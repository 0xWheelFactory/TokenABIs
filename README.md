# token-abis

Several common used token abi in an npm package.

## Installation

```sh
    npm install token-abis
```

## Usage

Just simply import it.

```javascript
    import commonErc20 from "token-abis/erc20/common-erc20.json";

    const erc20Token = new Contract(commonErc20, address, provider)
```

## Contribute

Any contribution is welcomed to make it better.

If you have any questions or want to add new token abi, please create an [issue](https://github.com/0xWheelFactory/TokenABIs/issues).

## License

[MIT](LICENSE)
