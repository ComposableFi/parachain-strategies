
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Twitter][twitter-shield]][twitter-url]
<a href="https://discord.gg/3tHHD4VUKW"><img src="https://img.shields.io/discord/733027681184251937.svg?style=flat&label=Join%20Community&color=7289DA" alt="Join Community Badge"/></a>

<img src="assets/composable-logo.png" alt="Composable Finance logo" title="Composable Finance logo" width="400" height="400">



## Reimagining Parachain Auctions with an Ethereum Vault Strategy


Amidst all of the hype in the DeFi space over parachains, Composable Finance is introducing a new solution which allows for participation in our parachain with ETH or any ERC-20 token asset, rather than purchasing DOT/KSM and leaving it to sit. With our novel approach, we expand our ability to stake DOT/KSM and allow for users to continue to gain profits on their staked assets.

Parachain vault strategies [details](https://composablefi.medium.com/reimagining-parachain-auctions-with-an-ethereum-vault-strategy-a0dcc3481759).


Users participating through our strategies get:
- Exposure to Composable Tokens
- Exposure to Polkadot parachain auction
- Exposure to DOT/KSM
- Yield on staking
- Minting our cross-layer stablecoin, Equal Cash off the receipt token from the vault


In addition to its direct benefits to users, this strategy fits into our overall mission as a platform; one of our main goals is connecting the spaces of Ethereum and Polkadot, and that begins even at the parachain auction level.


## Parachain Auction Tokens

Parachain Auction Tokens (or pAT) are the receipt token minted for participation in our parachain vault strategy, representing a user’s stake in the vault. Whenever someone deposits in our vault strategies, they get back pAT in an amount depending upon their investment and strategy type.

If we take for example the Harvest stablecoins strategies, whenever you invest Token (Dai/Usdc/Usdt), you’ll get back fToken (fDai/fUsdc/fUsdt). The value of fToken is usually a bit lower than the amount of Token you invested.

For example, investing $100 in DAI in the Harvest DAI strategy, will get you around 95 fDai and the amount of pAT you’ll receive is equal to the amount of fDai, which is 95 in this case.

Each strategy has its own pAT token, similar to how an AMM transfers LP tokens once you add liquidity. One of the use cases for pAT is to mint EQLC (our stablecoin). This provides additional capital efficiency by having a stablecoin collateralized by locked funds. This will be released at a later date.


## Risks

Parachain vault strategies provide an annual percentage yield (APY) for users who invest and at the same time gives ETH or stable coin holders exposure to KSM/DOT auctions, opening gates that were chained shut in the past.

Opportunities for yield farming have inherent risks associated with them. Please take note of the following risk associated with our solution:

### Smart Contract Related Risks

Even though smart contracts are known for being a stable and a secure way of processing data, bugs can still be discovered, and with the recent uptick in creative hacks, you never know when hackers can interfere with your application, no matter how protected it is. 
Remediation for this risk includes the following:
 - We tried to minimize the risk as much as possible. Trail of Bits audited our solution and changes have been reviewed by Stela Labs. 
 - Another way of tackling the risk is by having a smaller cap per strategy at the beginning, minimizing the available funds from that smart contract. Cap will slowly be increased over time. 
 - We also don’t keep user’s funds in our contract, and we re-route them to yield farms that are proven to be secure so far.

### Market Related Risks

DeFi can be a very profitable space, but comes with risks, one of them being the high fluctuations of various assets. Our strategies, depending on the one you chose to invest into, might swap your initial asset to another one. In case of a withdrawal, that asset is swapped back to your initial one. The amount you receive back plus the APY depends on the price variation between the initial asset and the under the hood asset.

Remediation for this risk includes the following:
- We tackle this risk by providing a boosted APY generated by Composable Tokens, which are distributed at the token generation event (TGE) and after the launch event.
- Each strategy will illustrate exactly what happens under the hood in order for users to determine for themselves if they are comfortable taking on a given level of risk.
- To further mitigate market risk, all the strategies supported through Composable use assets having high liquidity in most of the AMMs, making it harder for people to manipulate them.

### Yield Farms' Related Risks

All the risks associated with any dApp are also available in the case of yield farming through Composable. 

Remediation for this risk includes the following:
- In order to have a high APY and a higher degree of stability, we chose to connect to farms that were proven to be strong performers so far.  



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/company/composable-finance
[twitter-shield]: https://img.shields.io/twitter/follow/ComposableFin?style=social
[twitter-url]: https://twitter.com/ComposableFin
