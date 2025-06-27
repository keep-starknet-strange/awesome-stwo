# Awesome STWO [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<div align="center">
  <img src="stwo-logo.png" width="200" alt="STWO Logo">
  <br>
  <br>
  <p>
    <b>A curated list of awesome projects and resources for STWO - The Circle STARKs next generation prover developed by <a href="https://starkware.co">StarkWare</a>.</b>
  </p>
  <p>
   Stwo is a next generation implementation of a CSTARK prover and verifier, written in Rust 🦀
  </p>
  <p>
    <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome"></a>
    <a href="https://github.com/keep-starknet-strange/awesome-stwo/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT"></a>
    <a href="https://github.com/keep-starknet-strange/awesome-stwo/graphs/contributors"><img src="https://img.shields.io/github/contributors/keep-starknet-strange/awesome-stwo" alt="Contributors"></a>
  </p>
</div>

## Contents

- [Awesome STWO ](#awesome-stwo-)
  - [Contents](#contents)
  - [Resources](#resources)
  - [Tutorials](#tutorials)
  - [Client Side Proving](#client-side-proving)
    - [Starknet](#starknet)
    - [Bitcoin](#bitcoin)
  - [General Proving](#general-proving)
  - [ZK-VMs](#zk-vms)
  - [Contributing](#contributing)
  - [License](#license)

## Resources

_Official resources and documentation._

- [STWO](https://github.com/starkware-libs/stwo) - Official STWO repository.
- [Circle STARKs paper](https://eprint.iacr.org/2024/278) - Official Circle STARKs paper.
- [Documentation - Coming soon](https://starkware.co) - Official STWO documentation.

## Tutorials

_Tutorials and guides for STWO._

> Coming soon...

## Client Side Proving

_Projects using STWO for client-side proof generation._

- [Stwo-web-STARK](https://github.com/Okm165/stwo-web-stark) - Client-side proving, trace generation, and proof verification using STWO in a web-based interface.
- [zkemail-cairo](https://github.com/iosis-tech/zkemail-cairo) - DKIM RSA-SHA256 verification circuit, prove email content and domain ownership leveraging ZKP. 

### Starknet

_Projects integrating STWO with Starknet._

> Coming soon...

### Bitcoin

_Projects using STWO with Bitcoin and symbiotic ecosystems._

- [Raito](https://github.com/starkware-bitcoin/raito) — Bitcoin ZK client using Stwo to recursively verify block validation and to generate one succinct proof of chain correctness.
- [Cashu Cairo Spending Conditions](https://github.com/tdelabro/cdk/tree/stow-spending-condition) - Define Cashu spending conditions using Cairo and STWO for proving.
- [starkstr](https://github.com/AbdelStark/starkstr) - Nostr x STARKs exploration project using STWO to generate STARK proofs for various Nostr use cases. First one being explored is [Delegated aggregate signature verification](https://github.com/nostr-protocol/nips/pull/1682).
- [s2morrow](https://github.com/starkware-bitcoin/s2morrow) — Exploring PQ signature schemes aggregation with STARKs.
- [Bitcoin Wildlife Sanctuary](https://github.com/Bitcoin-Wildlife-Sanctuary) — Verifying Stwo proofs on Bitcoin with enabled OP_CAT opcode.
- [Stark symphony](https://github.com/starkware-bitcoin/stark-symphony) — Verifying Stwo proofs on Liquid with Simplicity script.

## General Proving

_Projects using STWO for proof generation._

- [Keth](https://github.com/kkrt-labs/keth) - An open-source proving backend for the Ethereum Execution Layer built with on Starkware's provable VM, Cairo.
- [LuminAIR](https://github.com/gizatechxyz/LuminAIR) - An open-source Machine Learning framework that leverages STWO to ensure the integrity of computational graphs.
- [VEX](https://github.com/trade-vex/vex-prover) - A fast provable orderbook that reduces the entire order matching engine to hash operations. Implemented in STWO

## ZK-VMs

_ZK-VMs provable with Stwo._

- [Stwo-Brainfuck](https://github.com/kkrt-labs/stwo-brainfuck) - A ZK-VM for the Brainfuck language, provable with Stwo.
- [Cairo](https://github.com/starkware-libs/stwo-cairo) — Cairo VM used for running Starknet OS, Starknet contracts, and general programs written in Cairo.
- [RiscV](https://github.com/nexus-xyz/nexus-zkvm) — A framework for writing verifiable programs in Rust.
- [Cairo-M](https://github.com/kkrt-labs/cairo-m) — A new zkVM leveraging M31 field to unleash the maximum power of Stwo for mobile proving.

## Circuit Libraries

_Libraries and utilities for building STWO based programs._

- [NumerAir](https://github.com/gizatechxyz/NumerAir) - A fixed-point arithmetic library providing constrained fixed-point operations for Stwo-based circuits using M31 field elements with configurable decimal precision.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
