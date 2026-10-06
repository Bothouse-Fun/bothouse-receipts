# BOT HOUSE · public receipts

Everything in this repository is written automatically by the BOT HOUSE bot. Nothing here is edited by hand.

| File | What it holds |
|---|---|
| `receipts/<coin>/round-0001.json` … | Every Payday: each wallet paid, the exact amount, and the on-chain transaction that paid it |
| `receipts/<coin>/index.json` | One line per Payday: round, time, SOL paid, number of wallets |
| `receipts/<coin>/wallets/<letter>.json` | "Paste your wallet" lookup: every Payday each wallet got, filed by the first letter of the address (lower-case) |
| `stats/<coin>.json` | The live numbers shown on the website |
| `state/<coin>.json` | The round tracker: current round and how full the pot is |
| `dryrun/…` | Practice runs before launch (no SOL sent), kept apart from the real receipts |

Every payout transaction also carries the on-chain note `BOT HOUSE Payday R{n}`, so anyone can check it on Solscan.
