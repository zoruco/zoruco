<picture>
  <source media="(prefers-color-scheme: light)" srcset="./assets/zoru-header-light.svg">
  <img src="./assets/zoru-header-dark.svg" alt="ZORU — Proof of Work on Vexanium." width="100%">
</picture>

<p align="center">
  <a href="https://github.com/zoruco/zoru-miner/releases/latest"><strong>Download ZORU Miner</strong></a> &nbsp; · &nbsp;
  <a href="https://github.com/zoruco/zoru-pow/blob/main/docs/PROTOCOL.md">Protocol</a> &nbsp; · &nbsp;
  <a href="https://github.com/zoruco/zoru-pow/blob/main/docs/MAINNET.md">Mainnet deployment</a>
</p>

ZORU is a CPU-mined Keccak proof-of-work token on **Vexanium EVM mainnet (chain ID 6736)**. Miners submit proofs to the Ledger, and accepted work shares the rewards of each nonempty mining epoch.

| Token | Lifetime supply cap | Mining epoch | Network |
| :--- | :--- | :--- | :--- |
| ZORU · 8 decimals | **21,000,000 ZORU** | **60 seconds** | **VEX EVM · 6736** |

ZORU starts with zero minted supply and no premine. The initial emission is **5 ZORU per nonempty epoch**, halving every **2,100,000 nonempty epochs**. The on-chain launch time is **29 October 2026 at 15:13:01 UTC (22:13:01 WIB)**.

### Mainnet contracts

| Contract | Address |
| :--- | :--- |
| Token | `0xb972753d17C5131D127B6c22DDE79B91a3132D03` |
| Ledger | `0xFf53a9079C2853C39C5adBfca788cb0f12aCFF03` |
| Engine | `0x9eD52C07691Cd26758ed1Ebe05d86698a9e54e8C` |
| Beacon | `0x562249B5c3922fAfa31f350EfDb89E4F3F9a82fE` |

The Token's supply cap is immutable, while the owner may change the issuer and upgrade mining modules. See [security considerations](https://github.com/zoruco/zoru-pow/blob/main/docs/SECURITY.md).

### Get ZORU Miner

**[Releases — Linux and Windows](https://github.com/zoruco/zoru-miner/releases)**

The Rust CLI supports mining and reward accounting. The Qt desktop app provides wallet, mining and rewards controls. Check the listed platforms and verify each download against `SHA256SUMS.txt` attached to the same release before installing.

| Repository | Contents |
| :--- | :--- |
| **[zoru-miner](https://github.com/zoruco/zoru-miner)** | Rust CLI, Qt GUI, wallet and reward tools |
| **[zoru-pow](https://github.com/zoruco/zoru-pow)** | Solidity contracts, proof rules, deployment and tests |

VEX is required for network transaction fees. A valid proof does not guarantee profit or immediate rewards.

### Contribute

Issues, documentation improvements and code contributions are welcome. See [Miner contributing](https://github.com/zoruco/zoru-miner/blob/main/CONTRIBUTING.md) and [PoW contributing](https://github.com/zoruco/zoru-pow/blob/main/CONTRIBUTING.md).

<p align="center">
  <img src="./assets/241127.png" alt="ZORU red panda" width="560">
</p>

<p align="center">
  <strong>Small panda. Big dreams.</strong><br>
  <a href="mailto:zorucore@gmail.com">zorucore@gmail.com</a> &nbsp; · &nbsp;
  <a href="https://github.com/zoruco/zoru-miner/releases">Releases</a> &nbsp; · &nbsp;
  <a href="https://github.com/zoruco/zoru-miner/issues">Report an issue</a>
</p>
