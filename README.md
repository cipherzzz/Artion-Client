# Client for Artion Marketplace - Powered by Fantom

A client side implementation of the Artion Marketplace for NFT trading on Fantom Opera network.

Artion allows users: 
- to explore existing NFTs on Fantom Opera network.
- to create a new collection of a new NFT
- to register a collection of already deployed NFT.
- to buy / sell / collect rare NFTs.

See [Guide](https://docs.fantom.foundation/tutorials/collection-and-bundle-guide-on-artion)

## Project Setup
```
# Note that you will need to use Node 14 & yarn
yarn install
```

## Compile
```
# This is not working for me - too many files open
yarn run start
```

### Compiles and minifies for production
```
yarn run build
yarn add --dev serve
npx serve -s build
```

#### .env file sample
```
REACT_APP_API_URL=
SKIP_PREFLIGHT_CHECK=true
REACT_APP_ENV=
REACT_APP_USDC=
REACT_APP_FUSDT=
```
