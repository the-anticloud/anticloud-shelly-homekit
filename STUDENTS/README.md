# Students — SHELLY_HOMEKIT

**Project:** SHELLY_HOMEKIT  
**Category:** CONSUMER_APPLIANCES  
**Upstream:** https://github.com/mongoose-os-apps/shelly-homekit  
**Pinned commit:** `8dbd9447497e642620d32dd08e3a2c1d8e729ed6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `63f4eb167bdb11acba1f6036b1454d369c4fd597f219632239aa6135c3be065d`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `8dbd9447497e642620d32dd08e3a2c1d8e729ed6`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `63f4eb167bdb11acba1f6036b1454d369c4fd597f219632239aa6135c3be065d`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
