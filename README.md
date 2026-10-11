# clone-lin-rust-lightning-feewgt

Experimental LIN clone of [lightningdevkit/rust-lightning](https://github.com/lightningdevkit/rust-lightning) `v0.2.7` on-chain `fee_for_weight` / 253 sat/kW floor.

- **Kernel:** [`lin_rust_lightning_feewgt.lin`](lin_rust_lightning_feewgt.lin)
- **Class:** EXPERIMENTAL (i64-scale remainder-ceil). Not a Lightning node.
- **Proofs (lin-open only):** https://github.com/kbelludoo/lin-open — `test/prove_rust_lightning_feewgt_external.py`
- **Upstream license:** Apache-2.0 OR MIT
- **Pinned commit:** `5ce2ecb33d32e3b61ef01d5ead0ee6693c0cd7d1`
- **Distinct from:** lnd BOLT-07 `ComputeFee`, rust-bitcoin `FeeRate::to_sat_per_vb_ceil`

This repository holds the LIN copy. Auditable C11 / Compiler 0 evidence stays in lin-open.
