# SEATrax 🌊

> **Shipping Excellence Across Borders** - Blockchain-based trade finance platform connecting exporters, investors, and administrators

[![Next.js 15](https://img.shields.io/badge/Next.js-15-black)](https://nextjs.org/) [![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)](https://www.typescriptlang.org/) [![Lisk Sepolia](https://img.shields.io/badge/Blockchain-Lisk%20Sepolia-purple)](https://sepolia.lisk.com/) [![Solidity](https://img.shields.io/badge/Solidity-0.8.20-orange)](https://soliditylang.org/)

---

## 🌊 About SEATrax

SEATrax is a revolutionary **blockchain platform** that transforms trade finance by tokenizing shipping invoices as NFTs and enabling decentralized funding through investor pools. The platform provides a secure, transparent, and efficient way for exporters to access immediate liquidity while offering investors attractive returns on trade finance investments.

### How It Works

1. **Exporters** submit shipping invoices and receive up to 70-100% advance funding
2. **Investors** browse curated invoice pools and invest to earn 4% returns
3. **Admin** verifies exporters, approves invoices, and manages investment pools
4. **Smart Contracts** automate fund distribution, payments, and profit sharing
5. **Blockchain** ensures transparency, immutability, and trust

---

## 🚀 Key Repositories

### [📱 SEATrax Apps](https://github.com/SEATrax/apps)
The main web application built with Next.js 15 and TypeScript, providing a user-friendly interface for exporters, investors, and administrators.

**Features:**
- Multi-role dashboard (Exporter, Investor, Admin)
- Invoice tokenization and management
- Pool creation and investment tracking
- Real-time USD ↔ ETH conversion
- IPFS document storage via Pinata
- Mobile-first responsive design

**Tech Stack:** Next.js 15, TypeScript, Tailwind CSS, shadcn/ui, Thirdweb SDK, Panna Wallet

### [⛓️ Smart Contracts](https://github.com/SEATrax/smart-contract)
The blockchain infrastructure powering the SEATrax platform, built with Solidity and Foundry on Lisk Sepolia testnet.

**Core Contracts:**
- **AccessControl**: Role-based permission management
- **InvoiceNFT**: Individual invoice tokenization (ERC-721)
- **PoolNFT**: Curated invoice pool NFTs
- **PoolFundingManager**: Investment and funding logic
- **PaymentOracle**: Payment confirmation system
- **PaymentPool**: Fund distribution management

**Tech Stack:** Solidity 0.8.20, Foundry, Lisk Sepolia Testnet

---

## ✨ Platform Features

### For Exporters
- ✅ Convert shipping invoices into NFTs
- ✅ Access funds when invoices reach 70% funding
- ✅ Secure IPFS-based document storage
- ✅ Real-time funding progress tracking
- ✅ Automatic withdrawal to wallet

### For Investors
- ✅ Browse curated investment opportunities
- ✅ View pool risk categories and details
- ✅ Earn 4% yield on successful settlements
- ✅ Monitor portfolio and claimed returns
- ✅ Transparent real-time analytics

### For Administrators
- ✅ Approve exporter applications with KYC
- ✅ Validate and approve invoices
- ✅ Create curated invoice pools
- ✅ Verify importer payments via oracle
- ✅ Monitor platform-wide metrics

---

## 🛠️ Technology Stack

**Frontend:**
- Next.js 15 with App Router
- TypeScript 5
- Tailwind CSS 4
- shadcn/ui (Radix UI)
- Panna SDK (Wallet)
- Thirdweb SDK (Blockchain)

**Backend:**
- Supabase (Database & Auth)
- IPFS via Pinata (Storage)
- CurrencyFreaks API (Exchange rates)

**Blockchain:**
- Lisk Sepolia Testnet
- Solidity 0.8.20
- Foundry Framework
- 6 Specialized Smart Contracts

---

## 🚀 Quick Start

### Prerequisites
- Node.js v18.0.0 or higher
- Git
- Foundry (for smart contract development)
- Wallet with Lisk Sepolia ETH

### Get Started with Apps
```bash
# Clone the repository
git clone https://github.com/SEATrax/apps.git
cd apps

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local

# Run development server
npm run dev
```

### Get Started with Smart Contracts
```bash
# Clone the repository
git clone https://github.com/SEATrax/smart-contract.git
cd smart-contract

# Initialize dependencies
git submodule update --init --recursive

# Build contracts
forge build

# Run tests
forge test
```

---

## 📚 Documentation

- **Apps Documentation**: Check the [apps repository](https://github.com/SEATrax/apps) for detailed setup and development guides
- **Smart Contract Docs**: Check the [smart-contract repository](https://github.com/SEATrax/smart-contract) for contract architecture and deployment guides
- **Network Details**: Lisk Sepolia Testnet (Chain ID: 4202)
- **Block Explorer**: [https://sepolia-blockscout.lisk.com](https://sepolia-blockscout.lisk.com)

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. **Fork** the repository you want to contribute to
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

Please ensure:
- All tests pass
- Code follows existing style conventions
- Commits are clear and descriptive

---

## 🌐 Resources

- **Lisk Sepolia Faucet**: [https://sepolia-faucet.lisk.com](https://sepolia-faucet.lisk.com)
- **Next.js Documentation**: [https://nextjs.org/docs](https://nextjs.org/docs)
- **Foundry Book**: [https://book.getfoundry.sh](https://book.getfoundry.sh)
- **Solidity Docs**: [https://docs.soliditylang.org](https://docs.soliditylang.org)

---

## 📄 License

This project is part of the SEATrax ecosystem. Please refer to individual repository licenses for specific terms.

---

## 🔗 Links

- **Organization**: [@SEATrax](https://github.com/SEATrax)
- **Apps Repository**: [SEATrax/apps](https://github.com/SEATrax/apps)
- **Smart Contract Repository**: [SEATrax/smart-contract](https://github.com/SEATrax/smart-contract)

---

<div align="center">
  <strong>Built with ❤️ for the future of trade finance</strong>
  <br>
  <sub>Empowering exporters, investors, and global trade</sub>
</div>