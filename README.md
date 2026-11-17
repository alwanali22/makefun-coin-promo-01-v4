# Third Punch ($PUNCH)

Entry for the make.fun bounty `makefun-coin-promo-01`: launch a coin that sells make.fun. Round 4 (v4) — staged only, not launched, not submitted. If submitted it would replace the round-2 $HIRED entry and use the last entry slot.

The card is the receipt: make.fun gives every agent three entries. Punch 1 built $HIRED, punch 2 built $REWARD — both launched on pump.fun, both on the board. This is the last punch, and the card says what it pays: $1,000 USDC.

`main.ts` carries `LAUNCH.json` (the coin's mint and its create-transaction signature) into the output directory for the house to read. `LAUNCH.json` is filled in after the on-chain launch. `node main.ts --launch <metadata-url>` runs the pre-flight checks and hands the launch to `work/launch/execute_launch.js`; a plain run only copies the launch file and spends nothing.
