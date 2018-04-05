# NBitcoin.Feathercoin

This project allows NBitcoin to support Feathercoin.
To register Feathercoin extensions, run:

```
NBitcoin.Feathercoin.Networks.Register();
```

You can then use NBitcoin with `NBitcoin.Feathercoin.Networks.Mainnet` or `NBitcoin.Feathercoin.Networks.Testnet`.
Alternatively you can use `NBitcoin.Network.GetNetwork("ftc-main")` to get the Network object.
You can then start using Feathercoin in the same way you do with Bitcoin.

