## 🔐 Authentication (Twitter & Phantom Wallet)

Chain of Lands supports secure authentication via Twitter (X) and Phantom Wallet, following modern Web2 and Web3 security standards.

### Twitter (X)
- OAuth 2.0–based authentication
- Passwordless login (no credentials handled or stored)
- Identity verification fully delegated to Twitter’s official API
- Used only to establish a verified user session

### Phantom Wallet
- Wallet-based authentication via cryptographic message signing
- One-time nonce signature (no on-chain transaction, no gas fee)
- Private keys remain entirely on the client device
- No seed phrase, private key, or wallet balance is accessed

### Security Model
- No centralized password storage
- No custodial wallet access
- Authentication based on account ownership proof
- Reduced risk of credential theft and phishing
- Suitable for hybrid Web2 / Web3 architectures
