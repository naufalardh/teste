### Purpose

Mint candy machine NFTs from your CLI. Use your preferred rpc provider. Avoid rage quitting because the candy machine GUI fails.

### Installation

```shell
cd ts
yarn
tsc
npm link
```

### Use
1) Find the public key for the candy machine you want to mint
```shell
willy-wonka search -k ~/config/solana/devnet-beta.json -u https://ssc-dao.genesysgo.net/ "Fenix*"
```
2) Check when it drops
```shell
 willy-wonka wen -k ~/config/solana/devnet-beta.json -u https://ssc-dao.genesysgo.net/ w2u3npYqjJG9N92PpdD48f4jLxv8NpbXnLT1CAZTu8i
```
3) Start minting scripts ~X minutes before drop
```shell
willy-wonka mint -k ~/config/solana/devnet-beta.json -u https://ssc-dao.genesysgo.net/ 45WzTnfT8QEYbj3746DJckWY5UQqd6o1955J69Qdj4pN
```
willy-wonka mint -k ~/config/solana/devnet-beta.json -u https://api.devnet.solana.com/ 4pzGKbVjTUamiXfnfAf62JnRYQtf5A3VP21YvQGoQCKu

solana config set --url https://ssc-dao.genesysgo.net/


willy-wonka mint -k ~/config/solana/devnet-beta.json -u https://ssc-dao.genesysgo.net/ 8HKnzmsXYpjzrdV7fUqKoCaBbuweynfyzshVw1obiiDB

willy-wonka mint -k ~/config/solana/devnet-beta.json -u https://ssc-dao.genesysgo.net/ HNQ8w8qDo6LbDrBu2NcgvxMbxLzxrtBesepqGSdvdLGn

willy-wonka mint -k ~/config/solana/devnet-beta.json -u https://ssc-dao.genesysgo.net/ E83HBsUJxfPzBetQT8AipTfqwNvkyVLcBQK1NUNEpjfY

willy-wonka mint -k ~/config/solana/devnet-beta.json -u https://ssc-dao.genesysgo.net/ FNLeX4xgXnJr2BcV5sczVUQ4VWF1QeEFxKVQHJBQRtuH

willy-wonka mint -k ~/config/solana/devnet-beta.json -u https://ssc-dao.genesysgo.net/ EgakLzLnFtBBJPjz17k6y4fE6LC1LW9BH4LCbP4WG8W8