# Gitcoin: 7) Port An Existing Ethereum DApp To Polyjuice 
### Grocery Management DApp

1- Screenshot and Video

<a href="https://youtu.be/bFndOyUQFmo"> Video Link </a>

<img src="https://github.com/jordanflick75/Nervos-gitcoin-hackathon/blob/master/gitcoin7-DApp/grocery.png" />

2- Project Link

<a href="https://github.com/jordanflick75/Gitcoin-Dapp">Project Code Link</a>

3- Contract 

Deployed Contract Address:

```bash
0x8a3165A21D44E4AF8275fd299563a9f21e830fbf
```

Transaction Hash:

```bash
0x5fa11aaf6f659c175331a5364022bcc6ede26b2716b8f96ee6035dd029e065d2
```

ABI

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
