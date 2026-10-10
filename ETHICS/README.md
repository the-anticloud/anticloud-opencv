# Ethics — OPENCV

**Project:** OPENCV  
**Category:** CAMERAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `73a26a423163d0284a41e997717b00933978b256`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `758477e7b49f8cd0cad83f94133f04fa9823a4498400b994f1dcf5a12e8ae832`  
**Date:** October 2026

## Position

OPENCV is packaged for offline deployment with a verifiable audit trail. The
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
