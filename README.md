# OKX Spot Trading Tutorial: What to Tap First, Why Your Limit Order Sits Unfilled, and What a $1,000 Round Trip Really Costs

Open the OKX app, go to **Trade** then **Spot**, pick a USDT pair, and check that your money is sitting in your trading account before you touch the order panel. If it isn't there, go to **Assets > Transfer** and move it from your funding account first. Standard accounts pay 0.08% maker and 0.10% taker on spot, so a $1,000 buy-then-sell round trip costs about $2.00 in fees.

Those three sentences cover the mechanics. The rest of this tutorial handles the parts that actually stop people: the transfer step most walkthroughs skip, the limit order that never fills, and where your money ends up after you sell.

> **Quick pick:** For a first spot order, the standard fee tier is the right account and there is no reason to chase VIP. VIP drops maker to 0.06% and taker to 0.08%, and the tier is assigned by 30-day trading volume, so it only becomes relevant once you're trading regularly. If you want to rehearse without risking money, OKX's own beginner guide points to demo trading with a demo account.
> 👉 [Register on OKX and start in the standard spot account](https://okx.com/join/CASH20)

## OKX spot fee tiers, and the arithmetic nobody does before their first trade

| Account tier | Spot maker | Spot taker | Who it suits | Get started |
| --- | --- | --- | --- | --- |
| Standard | 0.08% | 0.10% | First orders, occasional buys, long holds | [Create a standard OKX account](https://okx.com/join/CASH20) |
| VIP | 0.06% | 0.08% | Accounts whose 30-day volume qualifies | [Register and check your tier](https://okx.com/join/CASH20) |

VIP is split into several levels by 30-day trading volume. The threshold for each level lives on OKX's fee page and is revised over time, so read it there instead of trusting a number quoted in an article.

Now the part that changes behavior. A taker trade pays 0.10% per side. Buying $1,000 of BTC and later selling it costs 0.20% in total, which is **$2.00**. Do that a hundred times across the year and you've paid roughly **$200** in fees on $100,000 of turnover, without a single losing trade. Post limit orders that rest in the book instead and you pay the 0.08% maker rate, saving 0.02 percentage points a side: $0.20 on a $1,000 order, $0.40 per round trip, $40 across a hundred round trips. The saving is small per trade and real over a year.

Two more costs sit outside that table. Withdrawal fees are charged per coin and network and are shown on the withdrawal screen before you confirm. Perpetual futures carry funding payments, but those don't touch spot.

One related note: OKX's instant Buy and Convert screens don't display a separate trading fee, because the rate is set by OKX in the quote. If you care about the fee line, place the order on the spot order book where maker and taker rates apply openly.

## What your account needs before the first order

**Verification.** OKX says identity verification is required "for certain activities" and runs multiple KYC levels. Completing them speeds up withdrawals and unlocks advanced features. Treat it as something you'll need for full use rather than a wall in front of every tap, and finish it early so nothing blocks you later.

**Location.** The full OKX exchange is not available to US residents, who cannot trade, deposit, or withdraw on it. Decentralized services such as OKX Wallet remain accessible. Check your own jurisdiction before depositing anything.

**Funding.** OKX accepts crypto deposits from an external wallet, card purchases with Visa or Mastercard, P2P trades with local payment methods, and fiat-to-crypto purchases through partners such as Simplex or MoonPay. Card purchases are the fastest and usually the most expensive route; an on-chain transfer from a wallet you already control is cheaper if you already hold crypto.

Spot markets run 24/7 with live pricing, so there's no opening bell to wait for. Newly listed coins are the exception: their spot trading start time follows the official announcement.

## Step 1: Move funds from your funding account to your trading account

This is the step that generates the most "I clicked Buy and nothing happened" complaints, and it's the one OKX's help documentation states plainly: before you start spot trading, you need to transfer funds from your **funding account** to your **trading account**.

1. Open the app and go to **Assets > Transfer**.
2. Select the asset, for example USDT.
3. Set **From: Funding account** and **To: Trading account**.
4. Enter the amount and tap **Confirm**.

Some third-party guides describe OKX as a unified account where funds don't need to move between wallets. OKX's own help page, updated in March 2026, says otherwise for spot: the money has to be in the trading account. Follow the official flow. If your balance shows on the Assets screen but the order panel refuses to place anything, this is almost always why.

👉 [Create your OKX account and make the funding-to-trading transfer](https://okx.com/join/CASH20)

## Step 2: Find the trading pair

From the app, open **Trade** and then **Spot**. OKX's help doc describes the same path as "Trade (tap twice) > Spot". The pair selector sits in the top-left corner of the trading screen, and you can also search the market list directly.

Pairs are quoted as base/quote. In ETH/BTC, ETH is the asset being bought or sold and BTC is what prices it, so you're using BTC to buy ETH. OKX runs several spot zones, including USDT, TRY, and crypto-to-crypto pairs. BTC/USDT, ETH/USDT, and DOGE/USDT are the usual starting points because liquidity is deep and spreads are tight.

## Step 3: Place a limit order

A limit order only fills at your price or better, which is why it's the safer default when you're not in a hurry.

1. With the pair selected, tap **Buy**.
2. Choose **Limit order**.
3. Enter your target price and the amount, either in USDT or in the coin.
4. Tap **Buy** and confirm on the order screen.

The order drops into the **open orders** section below the chart. Nothing has been bought yet. It fills when the market price reaches your limit. If the price never comes back to your level, the order sits there indefinitely, and it will keep sitting there until you cancel it manually from the same panel.

That cuts both ways. A limit buy placed 5% below market protects you from overpaying during a spike and also means you miss the trade entirely if the dip never arrives. Decide which of those you can live with before you set the price.

## Step 4: Place a market order

A market order fills immediately at the best price available. The price field is locked to the market, so the only input is how much you want to spend or sell.

1. Tap **Buy**, then **Market order**.
2. Enter the amount, for example $100 of BTC.
3. Tap **Buy** and confirm.

The fill is instant and does not appear in open orders. You'll find it in your trade history instead. The tradeoff is slippage: in a fast or thin market, the average fill price can come in slightly worse than the price you saw on screen. On a major pair like BTC/USDT the gap is normally tiny; on a low-liquidity altcoin during a news spike, it can be meaningful.

👉 [Open an OKX account and try a small limit order first](https://okx.com/join/CASH20)

## Selling, and where your money sits afterward

Selling mirrors buying. Select the pair, tap **Sell**, choose Limit or Market, enter the price (limit only) and the amount, then confirm.

After a spot sale, the proceeds stay on the platform in your trading account. To withdraw or convert them through a payment method, transfer them back from the trading account to the funding account, then withdraw from Assets. Skipping that return transfer is the second most common reason someone can't find their money.

One hard constraint: some coins have minimum trade amounts, and orders below the minimum won't execute. The threshold varies by asset and is displayed on the order form, so check it before you try to sell a small leftover balance.

## Three things on the trading screen worth understanding

**The order book.** Red rows are sell orders, green rows are buy orders. The expand arrow on the order panel changes the view if the default layout feels cramped.

**The chart.** Tapping the chart button opens candlesticks with adjustable indicators and time intervals. OKX embeds TradingView, with timeframes down to 1 second and up through 1 minute, 5 minutes, 15 minutes, 1 hour, and 4 hours. A toggle switches back to OKX's original chart if you prefer it. The header strip above the chart carries the last price, the 24-hour low and high, and 24-hour volume in both coin and USDT terms.

**Order history.** The orders section splits into open orders and order history. History includes completed *and* canceled orders, with order time, pair, and volume. If you're reconciling what you actually did last month, this is the page, not the open orders list.

## Set the exit before you need it

OKX lets you manage an order from the order section after placing it, including take-profit and stop-loss levels. The full order-type menu goes further:

| Order type | What it does |
| --- | --- |
| Market | Fills at the best current price, immediately |
| Limit | Fills at your set price or better |
| Stop | Triggers a market order once a set price is reached |
| Trigger | Executes a pre-defined order when a price is triggered |
| Trailing stop | A stop that moves with the price in your favor |
| OCO | Two linked orders; when one fills, the other cancels |

A stop-limit is the practical version most people use. Say you hold BTC and want out if it breaks down: you set a stop price of $60,000 and a limit price of $59,900. Once BTC trades at $60,000, a limit sell at $59,900 is placed on the book. That price is an illustration of the mechanic, not a view on where BTC trades.

The catch with stop-limit: in a violent move, price can gap straight through your limit and leave you holding a position you wanted to exit. A plain stop turns into a market order and fills, just at whatever the book offers.

**Account security is part of position sizing.** Use a unique password of 12 characters or more, prefer an authenticator app over SMS for 2FA, turn on the anti-phishing code, and reach support only through OKX's official page. OKX publishes proof-of-reserves reports, holds the majority of assets in cold storage, and maintains a security fund. Those reduce exchange-level risk; they don't remove it. Funds on any exchange are held by that exchange, not by you, which is why long-term holdings often end up on a hardware wallet.

## FAQ

**Do I need to complete KYC to trade spot?**
OKX states verification is required for certain activities and offers multiple KYC levels, with completed verification speeding up withdrawals and unlocking advanced features. Requirements vary by activity and region, so check what your account asks for rather than assuming either extreme.

**Can I use OKX in the US?**
Not the full exchange. US residents can't access trading, deposits, or withdrawals on it, though decentralized services like OKX Wallet remain available.

**Why is my limit order still sitting in open orders?**
The market hasn't reached your price. Limit orders don't expire on their own; cancel and reprice it if you've changed your mind.

**Why did nothing happen when I tapped Buy?**
Check the source of your funds. Money in the funding account can't be used for spot orders until you transfer it to the trading account via Assets > Transfer.

**How is the fee calculated?**
As a percentage of order value at the maker or taker rate for your tier: 0.08% and 0.10% on standard. Market orders that fill immediately are taker trades; limit orders that rest in the book are maker trades.

**Is there a minimum order size?**
Yes, for some coins. Orders below the minimum won't execute, and the required amount shows on the order form for that pair.

## Which setup fits you

Placing a first order or buying to hold: use the standard tier, fund the trading account, and start with a limit order you're happy to have filled or not filled. Watch the fee line on your first few trades so the 0.08% versus 0.10% difference stops being abstract.

Trading most weeks: check the VIP levels on OKX's fee page and see how far your 30-day volume is from the next one. Don't restructure your trading to chase a 0.02% maker discount you won't reach.

Want to learn the interface without money at risk: use demo trading until the order panel, the open orders section, and the cancel button feel routine.

Before you tap Buy on the real thing, confirm two details: the money is in your trading account, and the order type matches what you actually want (instant fill versus waiting for your price). Everything else on the screen you can learn afterward.

👉 [Start with a small limit order on OKX](https://okx.com/join/CASH20)
