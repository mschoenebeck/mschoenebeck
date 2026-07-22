# Matthias Schönebeck

**Blockchain & DeFi infrastructure engineer** building deterministic trading systems, privacy-preserving protocols, lending infrastructure, and applied cryptography in C++ and Rust.

I focus on protocol-level systems where accounting correctness, economic invariants, privacy, custody boundaries, and deterministic execution matter.

## Flagship Work

### CLOAK / ZEOS Caterpillar — Shielded Protocol

A multi-asset privacy protocol for Antelope-based blockchains using Groth16 proofs, BLS12-381 cryptography, shielded notes, nullifiers, Merkle trees, Pedersen commitments, and client-side proof generation.

The system spans smart contracts, a Rust/WASM cryptographic engine, desktop and web applications, and privacy-preserving integrations with DeFi protocols.

- [Launch the CLOAK app](https://app.cloak.today/dashboard)
- [CLOAK website](https://cloak.today)
- [ZEOS Caterpillar](https://github.com/mschoenebeck/zeos-caterpillar)
- [ZEOS Caterpillar MPC](https://github.com/mschoenebeck/zeos-caterpillar-mpc)
- [CLOAK on X](https://x.com/cloak_today)

### Native Hybrid DEX

A live decentralized exchange built around a deterministic C++ trading engine that combines three native liquidity models inside one market:

- limit order book;
- constant-product AMM;
- concentrated liquidity.

Execution moves through price space segment by segment and routes across the best available native liquidity without reducing every model to synthetic order-book rows.

- [Open the live DEX](https://app.cloak.today/advanced)
- Public architecture documentation and presentation repository coming soon

### CLOAK Lending

A privacy-enabled Antelope lending protocol inspired by the Vigor economic model and rebuilt around deterministic fixed-point arithmetic, oracle-driven risk pricing, staged resumable processing, insurance, savings, bailouts, and protocol backstops.

The protocol is approaching launch readiness.

- [Open the lending application](https://app.cloak.today/lending/dashboard)
- Public architecture and protocol documentation repository coming soon

## Selected Open-Source Work

### BLS12-381 Cryptography

High-performance BLS12-381 elliptic-curve and pairing primitives implemented in C++ and x86 assembly.

- [BLS12-381 repository](https://github.com/mschoenebeck/bls12-381)
- [BLS12-381 contribution to Antelope Leap](https://github.com/AntelopeIO/leap/pull/1071)

### Fixed-Point Integer Type `fp128`

A deterministic signed 128-bit decimal fixed-point type for pricing, fees, curve mathematics, accounting, risk calculations, and reproducible financial execution in C++.

An MIT-licensed public release is in preparation.

## Technical Focus

- DeFi protocol and smart-contract architecture
- Deterministic financial and market infrastructure
- Order books, AMMs, concentrated liquidity, and lending systems
- Privacy protocols and zero-knowledge systems
- Groth16, Halo 2, BLS12-381, Merkle trees, nullifiers, and commitments
- EOSIO / Antelope smart contracts
- C++, Rust, TypeScript, WebAssembly, Qt, React / Next.js, and Linux

My earlier engineering background includes embedded systems, FPGA/ARM hardware-software co-design, and image-processing research at Fraunhofer HHI.

## Work With Me

I am open to selected **freelance, consulting, and full-time remote opportunities** involving:

- blockchain and DeFi infrastructure;
- smart-contract and protocol architecture;
- exchange, lending, tokenization, custody, and wallet systems;
- privacy and applied cryptography;
- technical due diligence and architecture review.

## Contact

- Email: [matthias.schoenebeck@gmail.com](mailto:matthias.schoenebeck@gmail.com)
- X: [@mschoenebeck1](https://x.com/mschoenebeck1)
- Telegram: [@mschoenebeck](https://t.me/mschoenebeck)
- GitHub: [github.com/mschoenebeck](https://github.com/mschoenebeck)
- CLOAK: [cloak.today](https://cloak.today)
