# GitCoin_Nervos-Task_3

1. A screenshot of the console output immediately after you have successfully issued a smart contract call.

![image](https://user-images.githubusercontent.com/87713875/128681656-c1250d60-bc68-492d-8ef2-5282438c92d7.png)

2. The transaction hash from the console output (in text format).

0x18e2fab204716d183ada08e3ea8403e8131912fa445d1b9e636e340b26a1387a

3. The contract address that you called (in text format).

0x0C7B0DFc7EeC067584D75a3ba8c8E323750136F4

4. The ABI for contract you made a call on (in text format).

const CONTRACT_ABI = [
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
]; // this should be an Array []
