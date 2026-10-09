# Zarel

**Governed AI operations. The AI proposes; the contract decides; the runtime enforces.**

Zarel is a runtime for AI that acts on money, customer data or production records. The model proposes an action as data. A contract you declare and approve decides which actions may run and with which values, and the runtime enforces it outside the model. Every state transition and flow step is hash-chained and sealed with signed checkpoints, so an auditor can check the record offline with a verifier they run themselves. It is tamper-evident: it detects an alteration, it does not prevent one.

Pre-launch. No certifications.

## Public today, on npm

| Package | What it is | License |
| --- | --- | --- |
| [`@zarel-ai/audit-chain`](https://www.npmjs.com/package/@zarel-ai/audit-chain) | Offline verifier for the audit hash chain. Zero runtime dependencies. | Apache-2.0 |
| [`@zarel-ai/audit-tsa`](https://www.npmjs.com/package/@zarel-ai/audit-tsa) | Offline RFC 3161 timestamp-token verifier and Merkle inclusion proofs. | Apache-2.0 |
| [`@zarel-ai/cli`](https://www.npmjs.com/package/@zarel-ai/cli) | The `zarel` CLI, including `zarel verify`. | MIT |
| [`@zarel-ai/sdk`](https://www.npmjs.com/package/@zarel-ai/sdk) | TypeScript SDK for the Zarel API. | MIT |

Their source is public in this organization:

- [`zarel-audit-verifier`](https://github.com/Zarel-AI/zarel-audit-verifier): `audit-chain` and `audit-tsa`.
- [`zarel-cli`](https://github.com/Zarel-AI/zarel-cli): `cli`.
- [`zarel-sdk-typescript`](https://github.com/Zarel-AI/zarel-sdk-typescript): `sdk`.

The runtime itself is closed source.

## Reading

The reasoning behind the design is at [zarel.ai/blog](https://zarel.ai/blog), starting with [You can't fight probabilism with probabilism](https://zarel.ai/blog/you-cant-fight-probabilism-with-probabilism).

## Contact

[hello@zarel.ai](mailto:hello@zarel.ai) · [LinkedIn](https://www.linkedin.com/company/zarel/) · Security reports: see [SECURITY.md](https://github.com/Zarel-AI/.github/blob/main/SECURITY.md).
