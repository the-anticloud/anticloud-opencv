# Educators — OPENCV

**Project:** OPENCV  
**Category:** CAMERAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `73a26a423163d0284a41e997717b00933978b256`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `758477e7b49f8cd0cad83f94133f04fa9823a4498400b994f1dcf5a12e8ae832`  
**Date:** October 2026

## Teaching with OPENCV

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `758477e7b49f8cd0cad83f94133f04fa9823a4498400b994f1dcf5a12e8ae832` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
