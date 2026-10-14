# Students — METABCI

**Project:** METABCI  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** https://github.com/TBC-TJU/MetaBCI.git  
**Pinned commit:** `3bc9643f3c39a616e73fa4872e6a77c536ad6107`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `bee88cb493d77cf6009634c9c566fc04c1c8c9ab0004d613e582afe78e357b96`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `3bc9643f3c39a616e73fa4872e6a77c536ad6107`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `bee88cb493d77cf6009634c9c566fc04c1c8c9ab0004d613e582afe78e357b96`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
