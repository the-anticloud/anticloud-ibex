# Educators — IBEX

**Project:** IBEX  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `af456e25575013668ab56725268126f6b0feca35`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `52064f5a45ed886cac623b6a504d0f056222800d905f5c353ef678621e41a584`  
**Date:** October 2026

## Teaching with IBEX

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `52064f5a45ed886cac623b6a504d0f056222800d905f5c353ef678621e41a584` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
