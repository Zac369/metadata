# Install instructions

### Install foundry
https://book.getfoundry.sh/getting-started/installation
### Clone the repo
`git clone https://github.com/Zac369/metadata.git`
### Adjust tokenId
To choose which token you can edit tokenId in the file test/Metadata.t.sol


## Useful commands

### Get the uri for a specific tokenID and write it to a file(result located in the uri folder)
`forge test --match-test testGetTokenURI -vv --rpc-url wss://mainnet.gateway.tenderly.co`

### Get the image for a specific tokenID and write it to a file(result located in the images folder)
`forge test --match-test testWriteImage -vv --rpc-url wss://mainnet.gateway.tenderly.co`

### Get both the token uri and the image
`forge test -vv --rpc-url wss://mainnet.gateway.tenderly.co`
