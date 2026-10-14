# Ethics — SHELLY_HOMEKIT

**Project:** SHELLY_HOMEKIT  
**Category:** CONSUMER_APPLIANCES  
**Upstream:** https://github.com/mongoose-os-apps/shelly-homekit  
**Pinned commit:** `8dbd9447497e642620d32dd08e3a2c1d8e729ed6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `63f4eb167bdb11acba1f6036b1454d369c4fd597f219632239aa6135c3be065d`  
**Date:** October 2026

## Position

SHELLY_HOMEKIT is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
