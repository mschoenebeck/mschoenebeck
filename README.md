# Matthias Schönebeck

**Blockchain and DeFi infrastructure engineer working on privacy, trading, lending, and applied cryptography in C++ and Rust.**

I build protocol-level systems where deterministic execution, accounting correctness, economic invariants, custody boundaries, and cryptographic soundness matter.

## Flagship Systems

### ZEOS Caterpillar — Shielded Protocol

[ZEOS Caterpillar](https://github.com/mschoenebeck/zeos-caterpillar) brings Sapling-style shielded transactions to programmable Antelope blockchains.

It extends the note model to fungible tokens issued by independent contracts, indivisible NFTs, and private smart-contract authorization through auth tokens. The Rust engine handles keys, notes, encryption, wallet state, transaction construction, and Groth16 proof generation; its on-chain counterpart verifies proofs and maintains the authoritative commitment and nullifier state.

CLOAK is a live implementation of the protocol.

- [ZEOS Caterpillar](https://github.com/mschoenebeck/zeos-caterpillar)
- [ZEOS Caterpillar MPC](https://github.com/mschoenebeck/zeos-caterpillar-mpc)
- [Launch the CLOAK app](https://app.cloak.today/dashboard)
- [CLOAK website](https://cloak.today)

### Hybrid Exchange Engine

A deterministic C++ trading engine that combines three native liquidity models inside one market:

- a central limit order book;
- a constant-product AMM;
- concentrated liquidity.

Execution moves through price space segment by segment and routes against the best available native liquidity without flattening every model into synthetic order-book rows.

- [Architecture and protocol documentation](https://github.com/mschoenebeck/hybrid-exchange-engine)
- [Open the live DEX](https://app.cloak.today/advanced)

### CLOAK Lending

A lending protocol for Antelope built around deterministic fixed-point accounting, oracle-driven risk pricing, staged and resumable processing, insurance, savings, bailouts, and protocol backstops.

The design is inspired by the Vigor economic model but substantially reworked for CLOAK's asset model, privacy integrations, and implementation requirements. The protocol is currently being tested ahead of launch.

- [Architecture and protocol documentation](https://github.com/mschoenebeck/cloak-lending)
- [Open the lending application](https://app.cloak.today/lending/dashboard)

## Open-Source Foundations

### BLS12-381 and Antelope Integration

A high-performance BLS12-381 implementation in C++ and x86 assembly, together with the smart-contract integration layer used for Groth16 verification on Antelope.

The work spans finite-field arithmetic, elliptic-curve groups, pairings, serialization, hash-to-curve support, CDT-facing types, and native Leap host functions.

- [BLS12-381](https://github.com/mschoenebeck/bls12-381)
- [BLS12-381 CDT](https://github.com/mschoenebeck/bls12-381-cdt)
- [Contribution to Antelope Leap](https://github.com/AntelopeIO/leap/pull/1071)

### `fp128`

A deterministic signed 128-bit decimal fixed-point type for financial and numerical code in C++.

It is designed for pricing, fees, curve mathematics, accounting, risk calculations, and other systems where floating-point behavior is not acceptable.

- [`fp128` repository](https://github.com/mschoenebeck/fp128)

## Technical Focus

- DeFi protocol and smart-contract architecture
- Deterministic financial accounting and market execution
- Order books, AMMs, concentrated liquidity, and lending systems
- Privacy protocols, zero-knowledge proofs, and applied cryptography
- Groth16, Halo 2, BLS12-381, Merkle trees, nullifiers, and commitments
- EOSIO / Antelope smart contracts
- C++, Rust, TypeScript, WebAssembly, Qt, React / Next.js, and Linux

My earlier engineering work includes embedded systems, FPGA/ARM hardware-software co-design, and image-processing research at Fraunhofer HHI.

## Work With Me

I am open to selected consulting, freelance, and full-time remote work involving:

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
