# Theologia Moralis (1835) — Latin/English Aligned Translations

**Release:** v1 — Public Domain (CC0).  
**Translator/Editor:** Frank Pearson.  
**Source edition:** *Theologia Moralis* (Paris, Gauthier Fratres & Soc., 1835), cura et studio Domini Receveur, Professoris in Sorbona (see title page).

## Contents
- `txt/TheologiaMoralisNN.translation.txt` (NN=01–10): Latin and English aligned line-by-line (one Latin sentence, then its English translation).
- `jsonl/TheologiaMoralisNN.draft_translations.jsonl`: sentence-level records (`id`, `latin`, `draft_translation`), useful for downstream processing or alignment checks.
- `manifest.csv`: file metadata (size, sha256, line counts).
- `sha256sums.txt`: checksums for integrity.
- `LICENSE`: CC0 dedication (translations and packaging).

## How it was built (summary)
1) OCR and cleanup of the 1835 Paris edition.
2) Citation stripping and paragraph normalization.
3) Sentence-level translation with placeholder preservation `(n)` for citations.
4) Light postprocessing to keep literal fidelity and reduce noise; aligned Latin/English output.

## Suggested citation
“Theologia Moralis — Latin/English aligned translations (Paris, 1835 ed.), translated and released CC0 by Frank Pearson, 2025.” (If you mint a DOI via Zenodo/OSF, include it here.)

## License
All translations and packaging in this release are dedicated to the public domain via CC0 1.0. Original Latin source is public domain (1835). See `LICENSE`.

## Integrity
Verify with `sha256sum -c sha256sums.txt` from this folder.
