# Top collections

This is ERC-721A nft collection consisting of top ethereum nfts like CryptoPunks, BAYCs and others. Users need to be whitelisted to have the right to mint a token. Whitelist feature was implemented by using MerkleTree.

Note that app supports only Goerli testnet for now.

## Whitelist

All whitelisted addresses must be in [whitelist.json](whitelist.json), merkle tree root will be generated (with `npm run root`) from this file, and then the root have to be added to contract by calling `setMerkleRoot`.

## Try out

If you want to mint an nft, i have added some addresses to whitelist. You can import one of them by any private key in [testPrivateKeys.txt](testprivatekeys.txt)
