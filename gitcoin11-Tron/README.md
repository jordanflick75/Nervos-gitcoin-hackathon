## Gitcoin: 11) Use A Tron Wallet To Execute A Smart Contract Call


- 1- A screenshot of the accounts you created (account list)

<img src="https://github.com/jordanflick75/Nervos-gitcoin-hackathon/blob/master/gitcoin11-Tron/accs.png" />

- 2- A link to the Layer 1 address you funded on the Testnet Explorer

 <a href="https://explorer.nervos.org/aggron/address/ckt1qyqwl2zrhyyrzavglq08g9c726mvnk5445tqlvz9zw"> Explorer Link </a>

- 3- A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account

<img src="https://github.com/jordanflick75/Nervos-gitcoin-hackathon/blob/master/gitcoin11-Tron/dpst.png" />

- 4- A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

<img src="https://github.com/jordanflick75/Nervos-gitcoin-hackathon/blob/master/gitcoin11-Tron/cc.png" />

- 5- The transaction hash of the "Contract call" from the console output

```bash
Ox7b6194659494b10d2f8e75e5b70b7ad3f482f363b2be631de1bbae75e4c80e1e
```

- 6- The contract address that you called

```bash
0x8a3165A21D44E4AF8275fd299563a9f21e830fbf
```


- 7- The ABI for contract you made a call on

```javascript
[
    {
      "inputs": [],
      "stateMutability": "nonpayable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "items",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "name",
          "type": "string"
        },
        {
          "internalType": "uint256",
          "name": "qty",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "store",
      "outputs": [
        {
          "internalType": "string",
          "name": "",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "_itemId",
          "type": "uint256"
        },
        {
          "internalType": "uint256",
          "name": "_newQty",
          "type": "uint256"
        }
      ],
      "name": "changeQty",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    }
  ]
```


- 8- Your Tron address

```bash
TMNd6ENyphM3UgBHF7CJWyXgaUb2KF1VnN
```

