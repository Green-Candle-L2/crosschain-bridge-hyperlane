Hyperlane CLI
Hyperlane permissionless core deployment
------------------------------------------------
All multisig configs in /home/support_devlabs/configs/ism.yaml are valid
Found configs for chains: greencandle, sepolia, scrollsepolia

Deployment plan
===============
Transaction signer and owner of new contracts will be 0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b
Deploying to greencandle, sepolia, scrollsepolia
There are several contracts required for each chain but contracts in your provided registries will be skipped
? Is this deployment plan correct? yes
Running pre-flight checks for chains...
✅ Chains are valid
✅ Signer is valid
✅ Balances are sufficient
All systems ready, captain! Beginning deployment...
Deploying ISM factory contracts
Deploying to greencandle from https://explorer.candl.green/address/0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b
Deploy staticMerkleRootMultisigIsmFactory on greencandle with constructor args ()
Pending https://explorer.candl.green/tx/0x3a2ccec17bee07b8c0f42f119860a8bdd2f96a7f8ab58fd3fda5b096643a66d1 (waiting 10 blocks for confirmation)
Deploy staticMessageIdMultisigIsmFactory on greencandle with constructor args ()
Pending https://explorer.candl.green/tx/0x1b456eebe785ac758d5dd194b0e0663d53a44ca19f5403f421cd3ef7ec6b1b48 (waiting 10 blocks for confirmation)
Deploy staticAggregationIsmFactory on greencandle with constructor args ()
Pending https://explorer.candl.green/tx/0x012864f201ad498054fe249048d1c39f5d940052893b084899d7116060940bc7 (waiting 10 blocks for confirmation)
Deploy staticAggregationHookFactory on greencandle with constructor args ()
Pending https://explorer.candl.green/tx/0x05381651d543e65e20a5a247434ca09289b439a62e616206b841cc39df460082 (waiting 10 blocks for confirmation)
Deploy domainRoutingIsmFactory on greencandle with constructor args ()
Pending https://explorer.candl.green/tx/0xbb5914e8ae2edd856bfefa8b331ec549baf74aad128c1ae47483feb28d629c94 (waiting 10 blocks for confirmation)
{ chain: 'greencandle' } Successfully deployed contracts
Deploying to sepolia from https://sepolia.etherscan.io/address/0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b
{ chain: 'sepolia' } Successfully deployed contracts
Deploying to scrollsepolia from https://sepolia.scrollscan.dev/address/0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b
{ chain: 'scrollsepolia' } Successfully deployed contracts
Skipping updating chain greencandle at github registry
Now updating chain greencandle at filesystem registry at /home/support_devlabs/.hyperlane
Done updating chain greencandle at filesystem registry
Skipping updating chain sepolia at github registry
Now updating chain sepolia at filesystem registry at /home/support_devlabs/.hyperlane
Done updating chain sepolia at filesystem registry
Skipping updating chain scrollsepolia at github registry
Now updating chain scrollsepolia at filesystem registry at /home/support_devlabs/.hyperlane
Done updating chain scrollsepolia at filesystem registry
ISM factory contracts deployed
Deploying core contracts to greencandle, sepolia, scrollsepolia
Deploying to greencandle from https://explorer.candl.green/address/0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b
Deploy proxyAdmin on greencandle with constructor args ()
Pending https://explorer.candl.green/tx/0x4675f9acaca7e22d1fa750dcae8f51e17b100a7fd13427b9ee35c9de5423e699 (waiting 10 blocks for confirmation)
Deploy mailbox on greencandle with constructor args (77788777)
Pending https://explorer.candl.green/tx/0x4710094550c422ffcf178798af0e5f127423f708284e58b2f4bd7e153877c7cd (waiting 10 blocks for confirmation)
Deploy TransparentUpgradeableProxy on greencandle with constructor args (0xeD5B7fbBB7F2cfb22C87582BFD755a7D51592396, 0x31c0be7995CE85373ddFae41b36247Ea85a6E2cf, 0x)
Pending https://explorer.candl.green/tx/0xeb9c2bd2af3e289d95625378676a42f6e927022aa178bcb816641e3deefdf994 (waiting 10 blocks for confirmation)
Pending https://explorer.candl.green/tx/0x58244b3ecf1b2a33b432464c98554a35be58b571c972c8c512a7b8951b12255e (waiting 10 blocks for confirmation)
Pending https://explorer.candl.green/tx/0x7f86966eb4226259f19dea00a9a0500c7f052636cd400e2927f88f0609aa519b (waiting 10 blocks for confirmation)
Pending https://explorer.candl.green/tx/0xcae3893248bda53be1c3699f32d92e75b7e1f71b5a737f88f71e239f534e9272 (waiting 10 blocks for confirmation)
Pending https://explorer.candl.green/tx/0xab811dd27cbd422fc485b80dc2ab417d86d1a9c19ef1c3b1d19af61586bed462 (waiting 10 blocks for confirmation)
Pending https://explorer.candl.green/tx/0xf0c6f19ae5e900c6f62fcea2f66f93bc775498e634054b6ed5eb8740a7303490 (waiting 10 blocks for confirmation)
Pending https://explorer.candl.green/tx/0xd363b15c1924b238184979bb22815a91ffd751411341bd445ed70234c82a6896 (waiting 10 blocks for confirmation)
Pending https://explorer.candl.green/tx/0x31bae02ceaff876122140f58bb539cd125ccf66b564977d39b5c4380973f2c22 (waiting 10 blocks for confirmation)
Deploy merkleTreeHook on greencandle with constructor args (0xE22136641eFbfD59bBfC7395daDcB4C7AC499c38)
Pending https://explorer.candl.green/tx/0x751c161d4013ba8005c79a829408ce2541665bfa0baa369814272b2ce8cc7d46 (waiting 10 blocks for confirmation)
Deploy protocolFee on greencandle with constructor args (1000000000, 0, 0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b, 0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b)
Pending https://explorer.candl.green/tx/0x16d40bf4607c569c104acd4c4144ed5f12c14ee7d1e80264ac89f9aee3721f47 (waiting 10 blocks for confirmation)
Pending https://explorer.candl.green/tx/0xaf2731b2f31dae03606736f059c76de690bb82834e1178739edb41b5caff1d6a (waiting 10 blocks for confirmation)
Deploy validatorAnnounce on greencandle with constructor args (0xE22136641eFbfD59bBfC7395daDcB4C7AC499c38)
Pending https://explorer.candl.green/tx/0x810d5ed80437ddc687d65066d959307f0cca0e7a0cf018d3befe94731aed76ce (waiting 10 blocks for confirmation)
Deploy testRecipient on greencandle with constructor args ()
Pending https://explorer.candl.green/tx/0x1f1ed4f2df70122c17699214534a05c546116a7e0775f7b88f25ffa4138af2b2 (waiting 10 blocks for confirmation)
Sent tx 0x2a7774c841344ea7e73b8c52db2708bfa7890a55d0456ec827888ea87b96862b
Pending https://explorer.candl.green/tx/0x2a7774c841344ea7e73b8c52db2708bfa7890a55d0456ec827888ea87b96862b (waiting 10 blocks for confirmation)
{ chain: 'greencandle' } Successfully deployed contracts
Deploying to sepolia from https://sepolia.etherscan.io/address/0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b
Pending https://sepolia.etherscan.io/tx/0xdeb1de1e6dc8d1df9b0fb8b5ab3644d76abf033403584da69660a9e13009d361 (waiting 1 blocks for confirmation)
Pending https://sepolia.etherscan.io/tx/0x76bcdc8c751729594f6aaf9868fe69224b9b4b2ebb24a6058c121150279b3fa0 (waiting 1 blocks for confirmation)
Pending https://sepolia.etherscan.io/tx/0xe250db2f63df1b2f4b8319b0cf17374f2f5abedbcfb738f396a6c145e97105fa (waiting 1 blocks for confirmation)
Pending https://sepolia.etherscan.io/tx/0x06dda5f9ba3d60ddf81e6c24a223a8f47f81f55c470d94bd8a0a485f1ab23d64 (waiting 1 blocks for confirmation)
Error from provider #0: Error: cannot estimate gas; transaction may fail or may require manual gas limit [ See: https://links.ethers.org/v5-errors-UNPREDICTABLE_GAS_LIMIT ] (reason="execution reverted: Initializable: contract is already initialized", method="estimateGas", transaction={"from":"0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b","maxPriorityFeePerGas":{"type":"BigNumber","hex":"0x59682f00"},"maxFeePerGas":{"type":"BigNumber","hex":"0x0a4945b2aa"},"to":"0xfFAEF09B3cd11D9b20d1a19bECca54EEC2884766","data":"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5","type":2,"accessList":null}, error={"reason":"processing response error","code":"SERVER_ERROR","body":"{\"jsonrpc\":\"2.0\",\"id\":114,\"error\":{\"code\":3,\"message\":\"execution reverted: Initializable: contract is already initialized\",\"data\":\"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000\"}}\n","error":{"code":3,"data":"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000"},"requestBody":"{\"method\":\"eth_estimateGas\",\"params\":[{\"type\":\"0x2\",\"maxFeePerGas\":\"0xa4945b2aa\",\"maxPriorityFeePerGas\":\"0x59682f00\",\"from\":\"0x0000184b36fdee9997d10ad5ea2cc883bb4ff85b\",\"to\":\"0xffaef09b3cd11d9b20d1a19becca54eec2884766\",\"data\":\"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5\"}],\"id\":114,\"jsonrpc\":\"2.0\"}","requestMethod":"POST","url":"https://ethereum-sepolia.publicnode.com"}, code=UNPREDICTABLE_GAS_LIMIT, version=providers/5.7.2) -  Triggering next provider.
Error from provider #1: Error: cannot estimate gas; transaction may fail or may require manual gas limit [ See: https://links.ethers.org/v5-errors-UNPREDICTABLE_GAS_LIMIT ] (reason="execution reverted: Initializable: contract is already initialized", method="estimateGas", transaction={"from":"0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b","maxPriorityFeePerGas":{"type":"BigNumber","hex":"0x59682f00"},"maxFeePerGas":{"type":"BigNumber","hex":"0x0a4945b2aa"},"to":"0xfFAEF09B3cd11D9b20d1a19bECca54EEC2884766","data":"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5","type":2,"accessList":null}, error={"reason":"processing response error","code":"SERVER_ERROR","body":"{\"jsonrpc\":\"2.0\",\"id\":42,\"error\":{\"code\":3,\"message\":\"execution reverted: Initializable: contract is already initialized\",\"data\":\"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000\"}}\n","error":{"code":3,"data":"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000"},"requestBody":"{\"method\":\"eth_estimateGas\",\"params\":[{\"type\":\"0x2\",\"maxFeePerGas\":\"0xa4945b2aa\",\"maxPriorityFeePerGas\":\"0x59682f00\",\"from\":\"0x0000184b36fdee9997d10ad5ea2cc883bb4ff85b\",\"to\":\"0xffaef09b3cd11d9b20d1a19becca54eec2884766\",\"data\":\"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5\"}],\"id\":42,\"jsonrpc\":\"2.0\"}","requestMethod":"POST","url":"https://ethereum-sepolia.blockpi.network/v1/rpc/public"}, code=UNPREDICTABLE_GAS_LIMIT, version=providers/5.7.2) -  Triggering next provider.
Error from provider #2: Error: cannot estimate gas; transaction may fail or may require manual gas limit [ See: https://links.ethers.org/v5-errors-UNPREDICTABLE_GAS_LIMIT ] (reason="execution reverted: Initializable: contract is already initialized", method="estimateGas", transaction={"from":"0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b","maxPriorityFeePerGas":{"type":"BigNumber","hex":"0x59682f00"},"maxFeePerGas":{"type":"BigNumber","hex":"0x0a4945b2aa"},"to":"0xfFAEF09B3cd11D9b20d1a19bECca54EEC2884766","data":"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5","type":2,"accessList":null}, error={"reason":"processing response error","code":"SERVER_ERROR","body":"{\"jsonrpc\":\"2.0\",\"id\":42,\"error\":{\"code\":3,\"message\":\"execution reverted: Initializable: contract is already initialized\",\"data\":\"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000\"}}\n","error":{"code":3,"data":"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000"},"requestBody":"{\"method\":\"eth_estimateGas\",\"params\":[{\"type\":\"0x2\",\"maxFeePerGas\":\"0xa4945b2aa\",\"maxPriorityFeePerGas\":\"0x59682f00\",\"from\":\"0x0000184b36fdee9997d10ad5ea2cc883bb4ff85b\",\"to\":\"0xffaef09b3cd11d9b20d1a19becca54eec2884766\",\"data\":\"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5\"}],\"id\":42,\"jsonrpc\":\"2.0\"}","requestMethod":"POST","url":"https://rpc.sepolia.org"}, code=UNPREDICTABLE_GAS_LIMIT, version=providers/5.7.2) - 
All providers failed for method estimateGas and params {
  "transaction": {
    "from": "0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b",
    "maxPriorityFeePerGas": {
      "type": "BigNumber",
      "hex": "0x59682f00"
    },
    "maxFeePerGas": {
      "type": "BigNumber",
      "hex": "0x0a4945b2aa"
    },
    "to": "0xfFAEF09B3cd11D9b20d1a19bECca54EEC2884766",
    "data": "0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5",
    "type": 2,
    "accessList": null
  }
}
Error from provider #0: Error: cannot estimate gas; transaction may fail or may require manual gas limit [ See: https://links.ethers.org/v5-errors-UNPREDICTABLE_GAS_LIMIT ] (reason="execution reverted: Initializable: contract is already initialized", method="estimateGas", transaction={"from":"0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b","maxPriorityFeePerGas":{"type":"BigNumber","hex":"0x59682f00"},"maxFeePerGas":{"type":"BigNumber","hex":"0x0a4945b2aa"},"to":"0xfFAEF09B3cd11D9b20d1a19bECca54EEC2884766","data":"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5","type":2,"accessList":null}, error={"reason":"processing response error","code":"SERVER_ERROR","body":"{\"jsonrpc\":\"2.0\",\"id\":116,\"error\":{\"code\":3,\"message\":\"execution reverted: Initializable: contract is already initialized\",\"data\":\"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000\"}}\n","error":{"code":3,"data":"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000"},"requestBody":"{\"method\":\"eth_estimateGas\",\"params\":[{\"type\":\"0x2\",\"maxFeePerGas\":\"0xa4945b2aa\",\"maxPriorityFeePerGas\":\"0x59682f00\",\"from\":\"0x0000184b36fdee9997d10ad5ea2cc883bb4ff85b\",\"to\":\"0xffaef09b3cd11d9b20d1a19becca54eec2884766\",\"data\":\"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5\"}],\"id\":116,\"jsonrpc\":\"2.0\"}","requestMethod":"POST","url":"https://ethereum-sepolia.publicnode.com"}, code=UNPREDICTABLE_GAS_LIMIT, version=providers/5.7.2) -  Triggering next provider.
Error from provider #1: Error: cannot estimate gas; transaction may fail or may require manual gas limit [ See: https://links.ethers.org/v5-errors-UNPREDICTABLE_GAS_LIMIT ] (reason="execution reverted: Initializable: contract is already initialized", method="estimateGas", transaction={"from":"0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b","maxPriorityFeePerGas":{"type":"BigNumber","hex":"0x59682f00"},"maxFeePerGas":{"type":"BigNumber","hex":"0x0a4945b2aa"},"to":"0xfFAEF09B3cd11D9b20d1a19bECca54EEC2884766","data":"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5","type":2,"accessList":null}, error={"reason":"processing response error","code":"SERVER_ERROR","body":"{\"jsonrpc\":\"2.0\",\"id\":43,\"error\":{\"code\":3,\"message\":\"execution reverted: Initializable: contract is already initialized\",\"data\":\"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000\"}}\n","error":{"code":3,"data":"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000"},"requestBody":"{\"method\":\"eth_estimateGas\",\"params\":[{\"type\":\"0x2\",\"maxFeePerGas\":\"0xa4945b2aa\",\"maxPriorityFeePerGas\":\"0x59682f00\",\"from\":\"0x0000184b36fdee9997d10ad5ea2cc883bb4ff85b\",\"to\":\"0xffaef09b3cd11d9b20d1a19becca54eec2884766\",\"data\":\"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5\"}],\"id\":43,\"jsonrpc\":\"2.0\"}","requestMethod":"POST","url":"https://ethereum-sepolia.blockpi.network/v1/rpc/public"}, code=UNPREDICTABLE_GAS_LIMIT, version=providers/5.7.2) -  Triggering next provider.
Error from provider #2: Error: cannot estimate gas; transaction may fail or may require manual gas limit [ See: https://links.ethers.org/v5-errors-UNPREDICTABLE_GAS_LIMIT ] (reason="execution reverted: Initializable: contract is already initialized", method="estimateGas", transaction={"from":"0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b","maxPriorityFeePerGas":{"type":"BigNumber","hex":"0x59682f00"},"maxFeePerGas":{"type":"BigNumber","hex":"0x0a4945b2aa"},"to":"0xfFAEF09B3cd11D9b20d1a19bECca54EEC2884766","data":"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5","type":2,"accessList":null}, error={"reason":"processing response error","code":"SERVER_ERROR","body":"{\"jsonrpc\":\"2.0\",\"id\":43,\"error\":{\"code\":3,\"message\":\"execution reverted: Initializable: contract is already initialized\",\"data\":\"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000\"}}\n","error":{"code":3,"data":"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000"},"requestBody":"{\"method\":\"eth_estimateGas\",\"params\":[{\"type\":\"0x2\",\"maxFeePerGas\":\"0xa4945b2aa\",\"maxPriorityFeePerGas\":\"0x59682f00\",\"from\":\"0x0000184b36fdee9997d10ad5ea2cc883bb4ff85b\",\"to\":\"0xffaef09b3cd11d9b20d1a19becca54eec2884766\",\"data\":\"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5\"}],\"id\":43,\"jsonrpc\":\"2.0\"}","requestMethod":"POST","url":"https://rpc.sepolia.org"}, code=UNPREDICTABLE_GAS_LIMIT, version=providers/5.7.2) - 
All providers failed for method estimateGas and params {
  "transaction": {
    "from": "0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b",
    "maxPriorityFeePerGas": {
      "type": "BigNumber",
      "hex": "0x59682f00"
    },
    "maxFeePerGas": {
      "type": "BigNumber",
      "hex": "0x0a4945b2aa"
    },
    "to": "0xfFAEF09B3cd11D9b20d1a19bECca54EEC2884766",
    "data": "0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5",
    "type": 2,
    "accessList": null
  }
}
Error from provider #0: Error: cannot estimate gas; transaction may fail or may require manual gas limit [ See: https://links.ethers.org/v5-errors-UNPREDICTABLE_GAS_LIMIT ] (reason="execution reverted: Initializable: contract is already initialized", method="estimateGas", transaction={"from":"0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b","maxPriorityFeePerGas":{"type":"BigNumber","hex":"0x59682f00"},"maxFeePerGas":{"type":"BigNumber","hex":"0x0a4945b2aa"},"to":"0xfFAEF09B3cd11D9b20d1a19bECca54EEC2884766","data":"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5","type":2,"accessList":null}, error={"reason":"processing response error","code":"SERVER_ERROR","body":"{\"jsonrpc\":\"2.0\",\"id\":117,\"error\":{\"code\":3,\"message\":\"execution reverted: Initializable: contract is already initialized\",\"data\":\"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000\"}}\n","error":{"code":3,"data":"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000"},"requestBody":"{\"method\":\"eth_estimateGas\",\"params\":[{\"type\":\"0x2\",\"maxFeePerGas\":\"0xa4945b2aa\",\"maxPriorityFeePerGas\":\"0x59682f00\",\"from\":\"0x0000184b36fdee9997d10ad5ea2cc883bb4ff85b\",\"to\":\"0xffaef09b3cd11d9b20d1a19becca54eec2884766\",\"data\":\"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5\"}],\"id\":117,\"jsonrpc\":\"2.0\"}","requestMethod":"POST","url":"https://ethereum-sepolia.publicnode.com"}, code=UNPREDICTABLE_GAS_LIMIT, version=providers/5.7.2) -  Triggering next provider.
Error from provider #1: Error: cannot estimate gas; transaction may fail or may require manual gas limit [ See: https://links.ethers.org/v5-errors-UNPREDICTABLE_GAS_LIMIT ] (reason="execution reverted: Initializable: contract is already initialized", method="estimateGas", transaction={"from":"0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b","maxPriorityFeePerGas":{"type":"BigNumber","hex":"0x59682f00"},"maxFeePerGas":{"type":"BigNumber","hex":"0x0a4945b2aa"},"to":"0xfFAEF09B3cd11D9b20d1a19bECca54EEC2884766","data":"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5","type":2,"accessList":null}, error={"reason":"processing response error","code":"SERVER_ERROR","body":"{\"jsonrpc\":\"2.0\",\"id\":44,\"error\":{\"code\":3,\"message\":\"execution reverted: Initializable: contract is already initialized\",\"data\":\"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000\"}}\n","error":{"code":3,"data":"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000"},"requestBody":"{\"method\":\"eth_estimateGas\",\"params\":[{\"type\":\"0x2\",\"maxFeePerGas\":\"0xa4945b2aa\",\"maxPriorityFeePerGas\":\"0x59682f00\",\"from\":\"0x0000184b36fdee9997d10ad5ea2cc883bb4ff85b\",\"to\":\"0xffaef09b3cd11d9b20d1a19becca54eec2884766\",\"data\":\"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5\"}],\"id\":44,\"jsonrpc\":\"2.0\"}","requestMethod":"POST","url":"https://ethereum-sepolia.blockpi.network/v1/rpc/public"}, code=UNPREDICTABLE_GAS_LIMIT, version=providers/5.7.2) -  Triggering next provider.
Error from provider #2: Error: cannot estimate gas; transaction may fail or may require manual gas limit [ See: https://links.ethers.org/v5-errors-UNPREDICTABLE_GAS_LIMIT ] (reason="execution reverted: Initializable: contract is already initialized", method="estimateGas", transaction={"from":"0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b","maxPriorityFeePerGas":{"type":"BigNumber","hex":"0x59682f00"},"maxFeePerGas":{"type":"BigNumber","hex":"0x0a4945b2aa"},"to":"0xfFAEF09B3cd11D9b20d1a19bECca54EEC2884766","data":"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5","type":2,"accessList":null}, error={"reason":"processing response error","code":"SERVER_ERROR","body":"{\"jsonrpc\":\"2.0\",\"id\":44,\"error\":{\"code\":3,\"message\":\"execution reverted: Initializable: contract is already initialized\",\"data\":\"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000\"}}\n","error":{"code":3,"data":"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000"},"requestBody":"{\"method\":\"eth_estimateGas\",\"params\":[{\"type\":\"0x2\",\"maxFeePerGas\":\"0xa4945b2aa\",\"maxPriorityFeePerGas\":\"0x59682f00\",\"from\":\"0x0000184b36fdee9997d10ad5ea2cc883bb4ff85b\",\"to\":\"0xffaef09b3cd11d9b20d1a19becca54eec2884766\",\"data\":\"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5\"}],\"id\":44,\"jsonrpc\":\"2.0\"}","requestMethod":"POST","url":"https://rpc.sepolia.org"}, code=UNPREDICTABLE_GAS_LIMIT, version=providers/5.7.2) - 
All providers failed for method estimateGas and params {
  "transaction": {
    "from": "0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b",
    "maxPriorityFeePerGas": {
      "type": "BigNumber",
      "hex": "0x59682f00"
    },
    "maxFeePerGas": {
      "type": "BigNumber",
      "hex": "0x0a4945b2aa"
    },
    "to": "0xfFAEF09B3cd11D9b20d1a19bECca54EEC2884766",
    "data": "0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b000000000000000000000000040369fd5bfd412aebd9451658c6a94e67a301080000000000000000000000004917a9746a7b6e0a57159ccb7f5a6744247f2d0d00000000000000000000000013ac3349cb159fe86a22cf42dda803d9f7309db5",
    "type": 2,
    "accessList": null
  }
}
Deploy testRecipient on sepolia with constructor args ()
Pending https://sepolia.etherscan.io/tx/0xbf8faa1d2750eb8dfa21eeee023e8d31cd2f5f41fb5607db9b4f49c473896338 (waiting 1 blocks for confirmation)
Sent tx 0x9541959a4847aabd7ae78d07442812b9687f98efc968520da1210a57fdc00e5a
Pending https://sepolia.etherscan.io/tx/0x9541959a4847aabd7ae78d07442812b9687f98efc968520da1210a57fdc00e5a (waiting 1 blocks for confirmation)
{ chain: 'sepolia' } Successfully deployed contracts
Deploying to scrollsepolia from https://sepolia.scrollscan.dev/address/0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b
Pending https://sepolia.scrollscan.dev/tx/0x5fa75f15806a901e78e72a1337159ab9a3c1ce7797bbf0a146e9c9eacc4513b4 (waiting 1 blocks for confirmation)
Pending https://sepolia.scrollscan.dev/tx/0x8727c10cb8fd70977bc069fb26812fc23a4cf840766ba85a6d57ad3c21ff334a (waiting 1 blocks for confirmation)
Pending https://sepolia.scrollscan.dev/tx/0x1e22efe65c874d408d7a1495b624fa6bf4923d4a08671b3648abf3900e2b0822 (waiting 1 blocks for confirmation)
Pending https://sepolia.scrollscan.dev/tx/0x7c9bd905bf41ab411eb6643248dbb71c541342ac6f77b1572cbe90821ec62aac (waiting 1 blocks for confirmation)
Error from provider #0: Error: cannot estimate gas; transaction may fail or may require manual gas limit [ See: https://links.ethers.org/v5-errors-UNPREDICTABLE_GAS_LIMIT ] (reason="execution reverted: Initializable: contract is already initialized", method="estimateGas", transaction={"from":"0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b","gasPrice":{"type":"BigNumber","hex":"0x05f5e100"},"to":"0x3C5154a193D6e2955650f9305c8d80c18C814A68","data":"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b0000000000000000000000008522514f1caa6c1eb69d0743687ebd860d82d41c000000000000000000000000863e8c26621c52aca1849c53500606e73ba272f00000000000000000000000005821f3b6ee05f3dc62b43b74ab1c8f8e6904b1c8","accessList":null}, error={"reason":"processing response error","code":"SERVER_ERROR","body":"{\"jsonrpc\":\"2.0\",\"id\":117,\"error\":{\"code\":3,\"message\":\"execution reverted: Initializable: contract is already initialized\",\"data\":\"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000\"}}\n","error":{"code":3,"data":"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000"},"requestBody":"{\"method\":\"eth_estimateGas\",\"params\":[{\"gasPrice\":\"0x5f5e100\",\"from\":\"0x0000184b36fdee9997d10ad5ea2cc883bb4ff85b\",\"to\":\"0x3c5154a193d6e2955650f9305c8d80c18c814a68\",\"data\":\"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b0000000000000000000000008522514f1caa6c1eb69d0743687ebd860d82d41c000000000000000000000000863e8c26621c52aca1849c53500606e73ba272f00000000000000000000000005821f3b6ee05f3dc62b43b74ab1c8f8e6904b1c8\"}],\"id\":117,\"jsonrpc\":\"2.0\"}","requestMethod":"POST","url":"https://sepolia-rpc.scroll.io"}, code=UNPREDICTABLE_GAS_LIMIT, version=providers/5.7.2) - 
All providers failed for method estimateGas and params {
  "transaction": {
    "from": "0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b",
    "gasPrice": {
      "type": "BigNumber",
      "hex": "0x05f5e100"
    },
    "to": "0x3C5154a193D6e2955650f9305c8d80c18C814A68",
    "data": "0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b0000000000000000000000008522514f1caa6c1eb69d0743687ebd860d82d41c000000000000000000000000863e8c26621c52aca1849c53500606e73ba272f00000000000000000000000005821f3b6ee05f3dc62b43b74ab1c8f8e6904b1c8",
    "type": 0,
    "accessList": null
  }
}
Error from provider #0: Error: cannot estimate gas; transaction may fail or may require manual gas limit [ See: https://links.ethers.org/v5-errors-UNPREDICTABLE_GAS_LIMIT ] (reason="execution reverted: Initializable: contract is already initialized", method="estimateGas", transaction={"from":"0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b","gasPrice":{"type":"BigNumber","hex":"0x05f5e100"},"to":"0x3C5154a193D6e2955650f9305c8d80c18C814A68","data":"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b0000000000000000000000008522514f1caa6c1eb69d0743687ebd860d82d41c000000000000000000000000863e8c26621c52aca1849c53500606e73ba272f00000000000000000000000005821f3b6ee05f3dc62b43b74ab1c8f8e6904b1c8","accessList":null}, error={"reason":"processing response error","code":"SERVER_ERROR","body":"{\"jsonrpc\":\"2.0\",\"id\":120,\"error\":{\"code\":3,\"message\":\"execution reverted: Initializable: contract is already initialized\",\"data\":\"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000\"}}\n","error":{"code":3,"data":"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000"},"requestBody":"{\"method\":\"eth_estimateGas\",\"params\":[{\"gasPrice\":\"0x5f5e100\",\"from\":\"0x0000184b36fdee9997d10ad5ea2cc883bb4ff85b\",\"to\":\"0x3c5154a193d6e2955650f9305c8d80c18c814a68\",\"data\":\"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b0000000000000000000000008522514f1caa6c1eb69d0743687ebd860d82d41c000000000000000000000000863e8c26621c52aca1849c53500606e73ba272f00000000000000000000000005821f3b6ee05f3dc62b43b74ab1c8f8e6904b1c8\"}],\"id\":120,\"jsonrpc\":\"2.0\"}","requestMethod":"POST","url":"https://sepolia-rpc.scroll.io"}, code=UNPREDICTABLE_GAS_LIMIT, version=providers/5.7.2) - 
All providers failed for method estimateGas and params {
  "transaction": {
    "from": "0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b",
    "gasPrice": {
      "type": "BigNumber",
      "hex": "0x05f5e100"
    },
    "to": "0x3C5154a193D6e2955650f9305c8d80c18C814A68",
    "data": "0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b0000000000000000000000008522514f1caa6c1eb69d0743687ebd860d82d41c000000000000000000000000863e8c26621c52aca1849c53500606e73ba272f00000000000000000000000005821f3b6ee05f3dc62b43b74ab1c8f8e6904b1c8",
    "type": 0,
    "accessList": null
  }
}
Error from provider #0: Error: cannot estimate gas; transaction may fail or may require manual gas limit [ See: https://links.ethers.org/v5-errors-UNPREDICTABLE_GAS_LIMIT ] (reason="execution reverted: Initializable: contract is already initialized", method="estimateGas", transaction={"from":"0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b","gasPrice":{"type":"BigNumber","hex":"0x05f5e100"},"to":"0x3C5154a193D6e2955650f9305c8d80c18C814A68","data":"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b0000000000000000000000008522514f1caa6c1eb69d0743687ebd860d82d41c000000000000000000000000863e8c26621c52aca1849c53500606e73ba272f00000000000000000000000005821f3b6ee05f3dc62b43b74ab1c8f8e6904b1c8","accessList":null}, error={"reason":"processing response error","code":"SERVER_ERROR","body":"{\"jsonrpc\":\"2.0\",\"id\":124,\"error\":{\"code\":3,\"message\":\"execution reverted: Initializable: contract is already initialized\",\"data\":\"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000\"}}\n","error":{"code":3,"data":"0x08c379a00000000000000000000000000000000000000000000000000000000000000020000000000000000000000000000000000000000000000000000000000000002e496e697469616c697a61626c653a20636f6e747261637420697320616c726561647920696e697469616c697a6564000000000000000000000000000000000000"},"requestBody":"{\"method\":\"eth_estimateGas\",\"params\":[{\"gasPrice\":\"0x5f5e100\",\"from\":\"0x0000184b36fdee9997d10ad5ea2cc883bb4ff85b\",\"to\":\"0x3c5154a193d6e2955650f9305c8d80c18c814a68\",\"data\":\"0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b0000000000000000000000008522514f1caa6c1eb69d0743687ebd860d82d41c000000000000000000000000863e8c26621c52aca1849c53500606e73ba272f00000000000000000000000005821f3b6ee05f3dc62b43b74ab1c8f8e6904b1c8\"}],\"id\":124,\"jsonrpc\":\"2.0\"}","requestMethod":"POST","url":"https://sepolia-rpc.scroll.io"}, code=UNPREDICTABLE_GAS_LIMIT, version=providers/5.7.2) - 
All providers failed for method estimateGas and params {
  "transaction": {
    "from": "0x0000184b36FdEe9997d10ad5ea2cC883Bb4fF85b",
    "gasPrice": {
      "type": "BigNumber",
      "hex": "0x05f5e100"
    },
    "to": "0x3C5154a193D6e2955650f9305c8d80c18C814A68",
    "data": "0xf8c8765e0000000000000000000000000000184b36fdee9997d10ad5ea2cc883bb4ff85b0000000000000000000000008522514f1caa6c1eb69d0743687ebd860d82d41c000000000000000000000000863e8c26621c52aca1849c53500606e73ba272f00000000000000000000000005821f3b6ee05f3dc62b43b74ab1c8f8e6904b1c8",
    "type": 0,
    "accessList": null
  }
}
Deploy testRecipient on scrollsepolia with constructor args ()
Pending https://sepolia.scrollscan.dev/tx/0xdb7689e4a5b30bf261abb2890977ec10c441c064be1d86ced221f3722300d547 (waiting 1 blocks for confirmation)
Sent tx 0x1944d911a2229234f27aecaa863434045ffed688a07ef1f36381117e52b2b18b
Pending https://sepolia.scrollscan.dev/tx/0x1944d911a2229234f27aecaa863434045ffed688a07ef1f36381117e52b2b18b (waiting 1 blocks for confirmation)
{ chain: 'scrollsepolia' } Successfully deployed contracts
Skipping updating chain greencandle at github registry
Now updating chain greencandle at filesystem registry at /home/support_devlabs/.hyperlane
Done updating chain greencandle at filesystem registry
Skipping updating chain sepolia at github registry
Now updating chain sepolia at filesystem registry at /home/support_devlabs/.hyperlane
Done updating chain sepolia at filesystem registry
Skipping updating chain scrollsepolia at github registry
Now updating chain scrollsepolia at filesystem registry at /home/support_devlabs/.hyperlane
Done updating chain scrollsepolia at filesystem registry
✅ Core contracts deployed
{
  "greencandle": {
    "staticMerkleRootMultisigIsmFactory": "0xc082c2905441a2A1e4bEf81993135805591fBA11",
    "staticMessageIdMultisigIsmFactory": "0x45F0Cd5c30748A1B4a680985D4d11D1f5dC2495f",
    "staticAggregationIsmFactory": "0x66f463660Ed5BCDA6D9676f5Bea998f7f6dAE6d4",
    "staticAggregationHookFactory": "0x8B4d5f07708170E09A6fB7ad11ddFB8ce7422a23",
    "domainRoutingIsmFactory": "0x7938305a7b3C459D16eEB560D990d0b66B0D64b9",
    "interchainSecurityModule": "0x72ed5C6e33098a8Ca1AF64CA54806f3CC08d469a",
    "domainRoutingIsm": "0x72ed5C6e33098a8Ca1AF64CA54806f3CC08d469a",
    "merkleTreeHook": "0xd294eDeeA28E374cC58B8dc616AF34D8FeA5d5F0",
    "protocolFee": "0x8c4D9bDf49AA720C7b4eBcfc5816D0e0938B05D1",
    "testRecipient": "0xf4F7a3fAF3Cd3A980336322D568e9F9C5449142d",
    "mailbox": "0xE22136641eFbfD59bBfC7395daDcB4C7AC499c38",
    "proxyAdmin": "0x31c0be7995CE85373ddFae41b36247Ea85a6E2cf",
    "validatorAnnounce": "0xeb8C93954e6835CfaE466650E1bEc71dAEf6D0d4"
  },
  "sepolia": {
    "staticMerkleRootMultisigIsmFactory": "0x0a71AcC99967829eE305a285750017C4916Ca269",
    "staticMessageIdMultisigIsmFactory": "0xFEb9585b2f948c1eD74034205a7439261a9d27DD",
    "staticAggregationIsmFactory": "0xC83e12EF2627ACE445C298e6eC418684918a6002",
    "staticAggregationHookFactory": "0x160C28C92cA453570aD7C031972b58d5Dd128F72",
    "domainRoutingIsmFactory": "0x3F100cBBE5FD5466BdB4B3a15Ac226957e7965Ad",
    "interchainSecurityModule": "0x040369Fd5BFd412AEBd9451658C6a94e67a30108",
    "domainRoutingIsm": "0x040369Fd5BFd412AEBd9451658C6a94e67a30108",
    "merkleTreeHook": "0x4917a9746A7B6E0A57159cCb7F5a6744247f2d0d",
    "protocolFee": "0x13AC3349Cb159fE86A22cf42DdA803D9f7309DB5",
    "customHook": "0x4917a9746A7B6E0A57159cCb7F5a6744247f2d0d",
    "testRecipient": "0xCa1699f3AE330fd3a1cE9D4f42F3e396b85723b0",
    "mailbox": "0xfFAEF09B3cd11D9b20d1a19bECca54EEC2884766",
    "proxyAdmin": "0x97Bbc6bBaFa5Ce3b2FA966c121Af63bD09e940f8",
    "validatorAnnounce": "0xE6105C59480a1B7DD3E4f28153aFdbE12F4CfCD9"
  },
  "scrollsepolia": {
    "staticMerkleRootMultisigIsmFactory": "0x275aCcCa81cAD931dC6fB6E49ED233Bc99Bed4A7",
    "staticMessageIdMultisigIsmFactory": "0xeb6f11189197223c656807a83B0DD374f9A6dF44",
    "staticAggregationIsmFactory": "0x16B710b86CAd07E6F1C531861a16F5feC29dba37",
    "staticAggregationHookFactory": "0x44b764045BfDC68517e10e783E69B376cef196B2",
    "domainRoutingIsmFactory": "0x17866ebE0e503784a9461d3e753dEeD0d3F61153",
    "interchainSecurityModule": "0x8522514f1caa6c1eB69d0743687EBD860d82d41c",
    "domainRoutingIsm": "0x8522514f1caa6c1eB69d0743687EBD860d82d41c",
    "merkleTreeHook": "0x863E8c26621c52ACa1849C53500606e73BA272F0",
    "protocolFee": "0x5821f3B6eE05F3dC62b43B74AB1C8F8E6904b1C8",
    "customHook": "0x863E8c26621c52ACa1849C53500606e73BA272F0",
    "testRecipient": "0x66f463660Ed5BCDA6D9676f5Bea998f7f6dAE6d4",
    "mailbox": "0x3C5154a193D6e2955650f9305c8d80c18C814A68",
    "proxyAdmin": "0x598facE78a4302f11E3de0bee1894Da0b2Cb71F8",
    "validatorAnnounce": "0x527768930D889662Fe7ACF64294871e86e4C2381"
  }
}
Writing agent configs
Agent configs written
Deployment is complete!
⛽️ Gas Usage Statistics
        - Gas required for core deploy on greencandle: 0.042163743409667468 undefined
        - Gas required for core deploy on sepolia: 0.029644758499244114 ETH
        - Gas required for core deploy on scrollsepolia: 0.000394897643780443 ETH