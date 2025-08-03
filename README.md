SuperNova is a 1inch Fusion+ Cross-Chain Swap Extension for Sui and Aptos

Our project extends the 1inch Fusion+ protocol to enable trust-minimized, atomic token swaps between Ethereum (EVM) and Move-based chains like Sui and Aptos. It bridges the interoperability gap between fundamentally different virtual machines — the account-based EVM and the resource-oriented MoveVM — while preserving hashlock and timelock guarantees that are central to Fusion+’s secure swap mechanism.

✅ Ethereum side uses EVM-compatible smart contracts (1inch Limit Order Protocol).

✅ Sui/Aptos side uses Move-based smart contracts (non-EVM).

We introduce a novel bidirectional HTLC architecture, where swaps can be initiated from either Ethereum or MoveVM chains and redeemed on the other. The system leverages:

🛠 1inch Limit Order Protocol (on Ethereum)

🧱 Custom Move smart contracts (on Sui/Aptos)

🤖 A decentralized off-chain agent to relay swap states and secrets across chains

This allows:

Seamless token swaps between ETH and SUI/APT

Timelock-based refunding if conditions are unmet

Secure preimage revelation handling on both ends

Optional stretch goals include:

🧩 Partial fill support

🖼️ A unified React-based UI

🌀 Integration with protocols like Zap Protocol for deeper liquidity or use-case layering

Our implementation demonstrates a proof-of-concept bridge that not only solves the Fusion+ expansion goal but also opens up future pathways for generic EVM ↔ MoveVM cross-chain applications.

