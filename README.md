# Fulcrum

Pick a side. Fulcrum is a clean, non-custodial front end for Solana memecoins.

- **Trade:** buy and sell BONK, WIF, POPCAT, PENGU, FARTCOIN, PNUT and BOME at the best price, routed through the Jupiter Swap API.
- **Earn:** deposit USDC, SOL and other assets into Jupiter Lend vaults at live rates, and withdraw any time liquidity allows.
- **Calculator:** see how leveraged longs and shorts would play out from today's live price. Leverage is not live yet.

Your wallet signs every transaction. Fulcrum never holds funds.

## Run it

It's a single static file. Open `index.html`, or serve the folder with GitHub Pages.

Optional: put a free Jupiter API key from portal.jup.ag in `JUP_KEY` near the top of the script for higher rate limits.

## Risk

Memecoins are extremely volatile. Swaps and deposits run on third-party Solana programs (Jupiter, Jupiter Lend). Only trade what you can afford to lose.
