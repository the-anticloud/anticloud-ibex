# Students — IBEX

**Project:** IBEX  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `af456e25575013668ab56725268126f6b0feca35`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `52064f5a45ed886cac623b6a504d0f056222800d905f5c353ef678621e41a584`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `af456e25575013668ab56725268126f6b0feca35`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `52064f5a45ed886cac623b6a504d0f056222800d905f5c353ef678621e41a584`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
