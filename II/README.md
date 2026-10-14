# Independent Insurance — METABCI

**Project:** METABCI  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** https://github.com/TBC-TJU/MetaBCI.git  
**Pinned commit:** `3bc9643f3c39a616e73fa4872e6a77c536ad6107`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `bee88cb493d77cf6009634c9c566fc04c1c8c9ab0004d613e582afe78e357b96`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | METABCI with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `bee88cb493d77cf6009634c9c566fc04c1c8c9ab0004d613e582afe78e357b96`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
