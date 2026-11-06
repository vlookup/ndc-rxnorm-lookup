# NDC to RxNorm Lookup

Educational project that builds a clean, normalized crosswalk between FDA National Drug Codes (NDC) and RxNorm concepts.

## Objective

Create a practical NDC → RxNorm lookup table that:
- Normalizes NDC codes to a consistent 11-digit format
- Links NDCs to RxNorm concept identifiers (RxCUI)
- Enriches the data with readable concept names and term types
- Makes it easier to map pharmacy data across systems that use different drug coding standards

## What’s in the repo

- `NDC Crosswalk RxNorm.ipynb` — Notebook that builds and documents the crosswalk

## Key notes

- NDC codes from the FDA and RxNorm sources are normalized to NDC11 for consistent joining
- The crosswalk includes concept-level enrichment so the codes are human-readable
- This is a snapshot based on publicly available FDA and RxNorm data

## Disclaimer

This project is for **educational and learning purposes only**.  
The data and mappings are not validated for clinical, operational, or regulatory use. Always verify drug codes against official sources (FDA, NLM/RxNorm) before using them in any production or patient-care setting.

## Data sources

- FDA National Drug Code Directory
- NLM RxNorm (via RxNav / full prescribe files)

## License

Educational use only. No warranty is provided.
