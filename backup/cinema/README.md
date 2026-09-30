# Cinema model backup

Git-friendly backup for the R/J/K/M cinema preference model.

## Roles
- R — Rojer, primary taste model
- J — Юля
- K — Катерина
- M — Маруся

## Files
- `model-rjkm-master-2026-09-29.txt` — parsed snapshot of the recovered multi-sheet master workbook.
- `legacy-rj-76.tsv` — legacy 75-title R/J calibration layer recovered from `Kino_Temp.xlsx`.
- The repository root already contains historical interactive quiz/source files used for Model R/J/K/M calibration.

## Source workbook checksums
- `Kino_RJKM_master_2026-09-29.xlsx`: SHA-256 `aeacd77858a8bee631cf70d83bdcae515f7b64470033d8111c58c6a6968829ce`
- `Kino_Temp.xlsx`: SHA-256 `6c42aa8c164c95613449f7a6e7aa144ed820ff062cd5b04038914c7398dbe0ca`

## Policy
The spreadsheet is the working view; this directory is the durable, diff-friendly backup.
Do not infer missing ratings. Keep `0`, `?`, status and Heat as separate signals.
Obsession and Absentia (2011) are different films and must never be merged.

Snapshot date: 2026-09-29.


## Unified catalog v1.0 — final · 30.09.2026

- `catalog-2026-09-30.json` — канонический объединённый каталог для интерфейса.
- `catalog-observations-2026-09-30.tsv` — плоский аудит всех наблюдений с источниками.
- `catalog-discrepancies-2026-09-30.md` — финально зафиксированные архивные конфликты.
- `index.html` — браузерный интерфейс каталога.

### Final recovery policy

Recovery is **closed without exporting the two old chats**.

FAST 101 is accepted as a `recovered_secondary_final` source layer: the rows came from saved search/history evidence, not verbatim chat exports. This provenance remains visible, but it is no longer treated as an unfinished task.

Conflicting values are never silently resolved. Both values and both sources remain in the catalog. A conflict can be superseded later only by a new explicit user rating.

Existing master, legacy, recovery package and source forms remain historical snapshots and are not overwritten.

**Catalog status: v1.0 final / closed.**
