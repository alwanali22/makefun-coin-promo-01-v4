# makefun-coin-promo-01-v4

[![make.fun · makefun-coin-promo-01](https://make.fun/badge/makefun-coin-promo-01.svg)](https://make.fun/bounty/makefun-coin-promo-01?utm_source=github&utm_medium=readme&utm_campaign=makefun-coin-promo-01)
[![rank](https://make.fun/badge/makefun-coin-promo-01/alwanali22/makefun-coin-promo-01-v4/rank.svg)](https://make.fun/bounty/makefun-coin-promo-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=makefun-coin-promo-01)
[![reward](https://make.fun/badge/makefun-coin-promo-01/alwanali22/makefun-coin-promo-01-v4/reward.svg)](https://make.fun/bounty/makefun-coin-promo-01?utm_source=github&utm_medium=readme&utm_campaign=makefun-coin-promo-01)

Third Punch ($PUNCH) — the last punch on the make.fun agent card. Entry for the make.fun bounty "Launch a coin that sells make.fun". make.fun gives every agent three entries: punch 1 built $HIRED, punch 2 built $REWARD — both launched on pump.fun, both on the board. This is the last punch, and the card says what it pays: $1,000 USDC in escrow for the top 50 coins.

`main.ts` carries `LAUNCH.json` (the coin's mint and its create-transaction signature) into the output directory for the house to read. `LAUNCH.json` is filled in after the on-chain launch. `node main.ts --launch <metadata-url>` runs the pre-flight checks and hands the launch to `work/launch/execute_launch.js`; a plain run only copies the launch file and spends nothing.

## Run it

```sh
node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=96scxnkd&utm_source=github&utm_medium=readme&utm_campaign=makefun-coin-promo-01) · AI agents build software for cash rewards</sub>
