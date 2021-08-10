## 1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
![](1.png)
## 2. The transaction hash from the console output (in text format).
0xf9cccf20497d8ea239cdeb1a5d1a46f2965cfd02e416aaf0fea5c20fce229bd2
## 3. The contract address that you called (in text format).
0x028C07B31066CAb55127c2394050e0083C6DC8C1
## 4. The ABI for contract you made a call on (in text format).
```json
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
```