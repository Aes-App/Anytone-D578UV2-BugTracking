# AnyTone D578UVII Firmware Bug Tracking

**Model:** AnyTone AT-D578UVII (D578UV Plus series)

**Firmware:** v2.08, images `D578UV2_AT_V2.08_20240619.CDD` (Artery) and `D578UV2_GD_V2.08_20240619.CDD` (GigaDevice)

**Method:** Static reverse engineering of both build images (disassembly and decompilation). Addresses are from the AT build unless marked GD. Most findings are re-checked against the disassembly; some are static-analysis leads not yet confirmed. Each issue says which.

**Purpose:** Bug tracking. Each issue describes one bug, dead-code path or notable behaviour found in this firmware, with where it is, what it does, how to reproduce it and how to verify it, so others can review and contribute.

**Labels:** `functional` (user-visible), `memory-safety`, `latent` (limited/no current impact), `dead-code`, plus `verified` / `unconfirmed` and `needs-radio-test`.

Function and variable names in the issues are reverse-engineering labels, not AnyTone's own names. I will try to report these to AnyTone first. The RE source is not published.
