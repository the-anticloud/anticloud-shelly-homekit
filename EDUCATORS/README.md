# Educators — SHELLY_HOMEKIT

**Project:** SHELLY_HOMEKIT  
**Category:** CONSUMER_APPLIANCES  
**Upstream:** https://github.com/mongoose-os-apps/shelly-homekit  
**Pinned commit:** `8dbd9447497e642620d32dd08e3a2c1d8e729ed6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `63f4eb167bdb11acba1f6036b1454d369c4fd597f219632239aa6135c3be065d`  
**Date:** October 2026

## Teaching with SHELLY_HOMEKIT

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `63f4eb167bdb11acba1f6036b1454d369c4fd597f219632239aa6135c3be065d` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
