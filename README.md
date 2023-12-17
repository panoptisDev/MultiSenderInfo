# CobraSender

![alt text](https://iili.io/JnHoQ8F.png)

![alt text](https://iili.io/JupXMFf.png)

## Multisender app
A multisender is a tool that allows you to send tokens or cryptocurrency to multiple addresses at once. 
This can be particularly useful in several scenarios:

1. **Airdrops**: If you're a project owner and you want to distribute tokens to a large number of
2. wallet addresses, a multisender can automate this process and save you a significant amount of time.

3. **Batch Payments**: If you need to make payments to multiple people at the same time (for example, paying
4. out rewards or salaries), a multisender can make this process more efficient.

5. **Token Swaps**: If you're migrating from one token to another, a multisender can help you distribute
6. the new token to holders of the old token.

7. **You Hold multiple wallet addresses**: If you manage multiple wallet addresses and need to distribute
8.  tokens to each of them, a multisender tool can be extremely useful. Instead of manually sending tokens
9.  to each address one by one, which can be time-consuming and prone to errors, the multisender tool allows
10.  you to send tokens to all these addresses in one go. This not only saves time but also ensures accuracy
11.   in the distribution of tokens.

---
### How to list on Multisender app
To expedite the process of listing your chain or token in the Multisender app, we appreciate receiving the 
necessary information in a specific format. The more complete and accurate the information you 
provide, the quicker we can proceed with the listing.

For a chain listing request, please provide the ChainId and the RPC URL. For instance, if you're listing 
the Fantom mainnet, which has a native cryptocurrency, your submission should look like this:
```
{
    "250": "https://rpcapi.fantom.network" // Fantom mainnet "FTM"
}
```
For a token listing request, we need the chain ID, the token address, the token symbol, and the token name.
The first address in the list is the native cryptocurrency for that chain ID. Here's an example:
```
'137': [
  '0x000000000000000000000000000000000000beef', // MATIC
  '0x50dDe7cD84B2C6f365109a1131Ccd557DbACCaa2', // LUKE / LukeToken
  '0x01431c445cC454C72DFD3415aB52065a74A0ecAa', // USDT / usdt
  '0x4d89d310c5E3fEFB95B5E9f2F941BC13B6C6C78A'  // SCRL / Scroll
]
```
If your chain isn't already listed in the Multisender app, we'll need to create two contracts. 
If you're using a testnet, it would be helpful if you could send some gas tokens to the developer's 
wallet address to cover gas costs.
Wallet:

Please note that the Multisender app is a community project aimed at assisting other developers. 
There are no fees for sending tokens; you only need to cover your own gas fees.

If we need to deploy the contracts for your chain, we'll need the following information
to be able to add the chain to metamask for remix deployment:
```
Network name:
New RPC URL:
Chain ID:
Currency symbol:
Block explorer URL:
```




