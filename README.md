# SupMart

Single-file decentralized marketplace for testnet3 object operations.

## Run locally
Open `index.html` in a browser.

The app uses:
- `p2fl.io` (with `p2fk.io` fallback) for profile/object lookup
- `mempool.space/testnet` for UTXO, fee, and transaction broadcast

Wallet compatibility constants match SupSpace/SupTV/SupRadio built-in wallet settings:
- `sup_iw_v1`
- `sup:testnet3:change:`
- 2 deterministic change keys
