# Educators — METABCI

**Project:** METABCI  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** https://github.com/TBC-TJU/MetaBCI.git  
**Pinned commit:** `3bc9643f3c39a616e73fa4872e6a77c536ad6107`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `bee88cb493d77cf6009634c9c566fc04c1c8c9ab0004d613e582afe78e357b96`  
**Date:** October 2026

## Teaching with METABCI

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `bee88cb493d77cf6009634c9c566fc04c1c8c9ab0004d613e582afe78e357b96` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
