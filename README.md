# Soken

Web3 development, smart contract audits and legal structuring for crypto projects. One team covers the product, its security and its legal setup.

This is the working account of the Soken team. Everything we publish lives in the organization **[Soken-LTD](https://github.com/Soken-LTD)**, which carries the Verified badge for our only domain, **[soken.dev](https://soken.dev)**.

## Start here

| Repository | What it is |
|---|---|
| [contract-review](https://github.com/Soken-LTD/contract-review) | Open source MCP server that runs a smart contract review pipeline: static analysis, semantic checks and a reviewer workflow for Solidity, Rust, Move, Cairo and FunC. The same engine runs behind our hosted connector. |
| [smart-contract-audits](https://github.com/Soken-LTD/smart-contract-audits) | Archive of published audit reports. The same list, with dates, is at [soken.dev/audits](https://soken.dev/audits.html). |
| [free-smart-contract-audit](https://github.com/Soken-LTD/free-smart-contract-audit) | Reports from our free audit program for early stage projects. |
| [Solidity-Audit-Reports](https://github.com/Soken-LTD/Solidity-Audit-Reports) | EVM audits: Ethereum, BNB Chain, Polygon, Arbitrum, Optimism, Base, zkSync. |
| [Rust-Audit-Reports](https://github.com/Soken-LTD/Rust-Audit-Reports) | Solana and Near audits. |
| [KYC-Certificates](https://github.com/Soken-LTD/KYC-Certificates) | KYC certificates issued to project teams we verified. |

## How we audit

Manual line by line review first, tooling second. Slither, Aderyn and Mythril for static analysis, Foundry invariant tests, Echidna and Medusa for property based fuzzing, and economic attack modelling for DeFi: flash loans, oracle manipulation, MEV, donation attacks, governance capture. Every Critical and High finding ships with a proof of concept test that reproduces it, remediation guidance and a re-audit pass once the fixes land.

| Ecosystem | Languages |
|---|---|
| Ethereum and EVM L2s | Solidity, Vyper |
| Solana, Near | Rust, Anchor |
| Aptos, Sui | Move |
| StarkNet | Cairo |
| TON | FunC, Tact |

## Verify a Soken report

A report is ours only if it is served from `github.com/Soken-LTD/` or from soken.dev. We used to publish under a GitHub account and a domain we no longer control and do not vouch for anything published there now. If a report reached you by email or messenger, check it against the archive before acting on it.

## Contact

Email [hello@soken.dev](mailto:hello@soken.dev) or Telegram [@soken_ai](https://t.me/soken_ai) with the repository or contract address, the target chain and your deadline. Security issues in something we audited go to the same address; see the organization [SECURITY.md](https://github.com/Soken-LTD/.github/blob/main/SECURITY.md).

Soken Limited, England and Wales, company number [15253906](https://find-and-update.company-information.service.gov.uk/company/15253906).
