# Changelog

## 2026-02-25 (v2)
- **MEDLINE verification**: Replaced 3 journals that failed NLM Catalog check (not actually MEDLINE):
  - #10 Frontiers in Oncology → Global Health Action (NLM 101496665)
  - #16 Cancers (MDPI) → European J Cancer Prevention (NLM 9300837)
  - #25 Cancer Management and Research → Journal of Medical Screening (NLM 9433359)
- Fixed 3 incorrect NLM IDs: Medicine (Baltimore) → 2985248R, Current Oncology → 9502503, Translational Behavioral Medicine → 101554668
- Softened context card text (focus on acceptance likelihood, removed KAP/prestige language)
- Removed "No Saudi journals" pill from selection criteria

## 2026-02-25 (v1)
- **Major update**: Replaced entire journal list with 30 MEDLINE-only journals (was mixed PubMed/PMC/MEDLINE)
- Removed BMJ Open from list per user request
- Removed Indexing column from table (all journals are now MEDLINE — column redundant)
- Removed badge CSS classes (`.badge-medline`, `.badge-pmc`, `.badge-pubmed`)
- Updated from 4 cascade tiers to 3 tiers (Highest / High / Stretch)
- All journal links now point to NLM Catalog pages
- Updated stats bar: "100% MEDLINE" (was "100% PubMed"), "3 Cascade Tiers" (was 4)
- Updated hero meta: "30 MEDLINE-Indexed Journals" (was "PubMed-Indexed")
- Updated context card description and selection criteria pills
- Removed tier 4 CSS variables and related styles
- Rebuilt submission cascade with new journal selections

## 2026-02-24
- Fixed indexing badges after PubMed verification
- Fixed broken EMHJ link to updated WHO EMRO URL
- Removed Journals to Avoid section and added clickable journal links

## 2026-02-23
- Initial CRC screening journal recommendations report
