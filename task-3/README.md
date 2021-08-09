## Task Submission
1. A screenshot of the console output immediately after you have successfully issued a smart contract call.

![Alt text](https://github.com/knnlrts/nervos-hackaton/blob/main/task-3/smart-contract-call.png)

2. The transaction hash from the console output (in text format).
```sh
0x216e8e3bd794abc6d265cad4ba86cacf62905f4976a047531ae1da1bcd3ac986
```
3. The contract address that you called (in text format).
```sh
0x235DB0ECeB9470Dbcfe44213db0D5fA0D707BDE9
```
4. The ABI for contract you made a call on (in text format).
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