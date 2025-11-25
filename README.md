
# Onion-Wallet

The Onion Wallet
Abstract
This is a solo, open-source, privacy-oriented multi-chain crypto wallet for secure, local
management of funds for Bitcoin, Litecoin, Ethereum (and other EVM chains), Solana, and
Monero. It has industry-grade key management (BIP-39/BIP-32 HD wallets), robust local
encryption (SHA-512 → AES-256-GCM with salt & IV), and air-gapped signing workflows so
private keys never get exposed to the internet. All network traffic — RPC requests and tx
broadcasts — can be proxied over Tor (SOCKS5) or a local Tor-supported proxy to reduce
network-level metadata exposure.
In addition to simple send/receive, the wallet has a modular decentralized exchange engine that
facilitates privacy-protecting multi-hop routes (e.g., BTC → Monero → ETH). These
chain-swaps use privacy coin primitives and decentralized exchange protocols to escape
on-chain linkability while maintaining the user in complete control over keys and signing. The
design is intentionally modular and cross-platform: a secure core engine (embeddable
Rust/Node.js library) provides CLI APIs and a thin GUI (Electron for desktop; React
Native/Flutter alternative for mobile), supporting deployment on Linux, Windows, macOS,
Android, and iOS.
For quick demonstration and secure development, the repo comes with a Sepolia (Ethereum
testnet) demo: local mnemonic generation, encrypted storage, local signing and Sepolia
transaction broadcasting (with optional Tor routing), and encryption and signing test suites.
Detailed documentation is provided on the security model, Tor setup, air-gapped signing, swap
workflows, and stringent warnings regarding legal/operational boundaries. The project is also
designed to serve as a professional portfolio piece for exhibiting strong skills in cryptography,
multi-chain engineering, privacy networking, and secure application design


this project is still under construction  
:)
