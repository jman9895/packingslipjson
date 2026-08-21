# Packing Slip JSON

Public cloud configuration for the Etsy Packing Slips Android app.

This repository intentionally contains **no Etsy credentials, OAuth tokens, customer information, order information, or other secrets**. It stores only non-sensitive packing metadata such as SKU pick notes, bin locations, warnings, and the global packing-slip banner.

The Android app reads `packing-config.json` from this repository and caches the last valid copy locally for offline use.

The JSON schema and editing workflow are documented in the private `etsypackingslips` app repository in `PACKING_CONFIG.md`.
