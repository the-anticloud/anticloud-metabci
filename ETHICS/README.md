# Ethics — METABCI

**Project:** METABCI  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** https://github.com/TBC-TJU/MetaBCI.git  
**Pinned commit:** `3bc9643f3c39a616e73fa4872e6a77c536ad6107`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `bee88cb493d77cf6009634c9c566fc04c1c8c9ab0004d613e582afe78e357b96`  
**Date:** October 2026

## Position

METABCI is packaged for offline deployment with a verifiable audit trail. The
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
