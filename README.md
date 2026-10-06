# BOT HOUSE · public receipts

Everything in this repository is written automatically by the BOT HOUSE bot. Nothing here is edited by hand.

| File | What it holds |
|---|---|
| `receipts/<coin>/round-0001.json` … | Every Payday: each wallet paid, the amount, and the on-chain transactions |
| `stats/<coin>.json` | The live numbers shown on the website |
| `state/<coin>.json` | The round tracker: current round and how full the pot is |

Every payout transaction also carries the on-chain note `BOT HOUSE Payday R{n}`, so anyone can check it on Solscan.
