<b>Nervos hacakthon Gitcoin Task 11
 Use a Tron Wallet to Execute a Smart Contract Call





1)A screenshot of the accounts you created (account list) in ckb-cli.

![account list](https://github.com/tharunrai14/nervos-hackathon/blob/main/task11/accountlist.jpg)




2)A link to the Layer 1 address you funded on the Testnet Explorer.

[Link](https://explorer.nervos.org/aggron/transaction/0x8a5035cba167ae624806be2a30bb10a7d9c150f168621c5a7cc027d4b9700aed)



3)A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2.

![layer 2 deposit](https://github.com/tharunrai14/nervos-hackathon/blob/main/task11/layer2dep1.jpg)
![layer 2 deposit](https://github.com/tharunrai14/nervos-hackathon/blob/main/task11/layer2dep2.jpg)


4)A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2.
![contract call](https://github.com/tharunrai14/nervos-hackathon/blob/main/task11/contrcall.jpg)



5)The transaction hash of the "Contract call" from the console output (in text format).

<code> 0xdf9c4ccf42917453eab094f1f66fa2a0fff9fe480ec4d121b91bd98ffaca3492</code>


6)The contract address that you called (in text format).
<code> 0x030Eba4D2720ac441888861B32f1B7D88db5B16c</code>

7)The ABI for contract you made a call on (in text format).
<code>
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

</code>
8)Your Tron address (in text format).
<code>

TCCvNqME8xXjPsQJuBZdaakYhjcDAHmfRD
</code>

</b>
