# Adding Liquidity - Base

Today we’re going to give you the A-Z guide of bringing liquidity to Sobal on Base. At the time of writing, the only chain supported to bridge from is Ethereum Mainnet.

### Prerequisites <a href="#980d" id="980d"></a>

* Wallet supporting EVM with custom RPCs (such as Metamask)

### Steps <a href="#79f6" id="79f6"></a>

* [Setting up Metamask for the Base chain](https://blog.sobal.fi/#7f20)
* [Bridging ETH to Base from Ethereum](https://blog.sobal.fi/#8f29)
* [Depositing Liquidity to Sobal pools.](https://blog.sobal.fi/#f96d)

## Setting up Metamask for the Neon chain <a href="#7f20" id="7f20"></a>

1. Visit [https://www.chainlist.org](https://chainlist.org/chain/8453)
2. Search for **Base**
3. Click “Add to Metamask” for the **Base** entry

<figure><img src="../.gitbook/assets/add base network.gif" alt=""><figcaption></figcaption></figure>

## Bridging ETH to Base from Ethereum <a href="#8f29" id="8f29"></a>

Bridging ETH from Ethereum is very simple.

**IMPORTANT** Make sure you are bridging ETH not WETH or other types of ETH otherwise your funds may be lost!

1. You can bridge ETH tokens from the Ethereum network to Base by sending ETH to \`portal.base.eth\` or the following contract address:\
   \`0x49048044D57e1C92A77f79988d21Fa8fAF74E97e\`
2. You will need to wait up to 10 minutes for the ETH to arrive on your wallet. The ETH will appear as a SELF transaction — so if the transaction nonce number of your wallet is important — for example — if you’re deploying contracts, transfer to a different wallet first.
3. You can read the steps above from the official Base documentation here: [https://docs.base.org/tools/bridges](https://docs.base.org/tools/bridges)

## Depositing Liquidity to Sobal pools <a href="#f96d" id="f96d"></a>

1. Visit [https://app.sobal.fi](https://app.sobal.fi/)
2. Select the Pool you wish to add liquidity to, in this example we’ll use the [**NEON/SOL**](https://app.sobal.fi/#/neon/pool/0xb04aba41dc9ed9b1c534b8239c4ffdfc526c5409000200000000000000000004) pool.
3. Click add liquidity and set the amount of tokens you wish to add\
   _⚠️ Pay careful attention to the price impact of the liquidity you’re adding. We recommend keeping it as balanced as possible (<0.01%). There is an `optimize` button you can use on the screen that will help you do so._
4. Sign the `approval` transactions and add liquidity!
5. All done! You can check your liquidity at anytime on the `Portfolio` tab of Sobal or opening the liquidity pool you participated in and scroll down.

<figure><img src="../.gitbook/assets/add liquidity.gif" alt=""><figcaption></figcaption></figure>

> Congratulations, you are now a Liquidity Provider!
