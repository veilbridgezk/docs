# How It Works

VeilBridge uses Ethereum as a secure privacy hub while allowing entry and exit from any chain.

### User Flow (Any → Any)
1. **Deposit** — Lock assets on source chain (e.g., BSC)
2. **Route** — Wrapped asset sent to Ethereum anonymity pool
3. **Anonymize** — Funds mixed with others using ZK-SNARKs
4. **Withdraw** — Redeem private note → assets unlocked on target chain (e.g., Polygon) to a new address

No relayer or observer can link origin to destination.

### Privacy Guarantees
- Zero-knowledge proofs hide all transaction details
- Fixed denominations prevent amount linkage
- Mandatory anonymity pass through Ethereum pools
