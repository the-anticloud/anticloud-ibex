# Academic Use — IBEX

**Project:** IBEX  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `af456e25575013668ab56725268126f6b0feca35`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `52064f5a45ed886cac623b6a504d0f056222800d905f5c353ef678621e41a584`  
**Date:** October 2026

## Scope

IBEX is available for academic research under the Apache 2.0 terms of the
Anticommons 0.1.0 dual licence. Citation details are in `23_HOW_TO_CITE`.

## What is available to researchers

- The full upstream source, pinned at `af456e25575013668ab56725268126f6b0feca35`
- The 16-check assurance register with per-check evidence and hashes
- The AIOSS ledger attesting the project artifacts
- Benchmark output in `BENCH.json`

## Reproducing the result

```
python tools/run_bench.py --out BENCH.json
```

Then recompute any row's SHA3-256 from `ISOLATED_LAB_RESULTS/04_Evidence/`.

## Contact

lois@0-1.gg · 0-1.gg
