---
section: Changed
---

- **Keep incomplete observation evidence separate from mutation attribution (refs #2984)** — the observational mutation net reports hashless captures, including size-only changes, as unverifiable, never replays them, and leaves attribution unchanged while retaining bounded coverage evidence.
