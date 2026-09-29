# FAST 101 recovery status — 2026-09-29

This note supersedes the older Recovery_log embedded in the first recovered XLSX snapshot.

## Model roles
- R = Rojer — primary taste model.
- J = Юля, K = Катерина, M = Маруся — comparison/control family context.
- Do not use J/K/M as substitutes for R when forming R taste hypotheses.
- Rating semantics: 1–5 = watched/rated; 0 = not watched; ? = watched but rating/impression not remembered.
- Heat is a separate signal.
- The early R&J pilot was a UI/UX test and is excluded from the model.

## FAST 101 source forms
Recovered and backed up in this repository:
- R — model_r_101_films_v2_exact_wiki.html
- J — j_fast101_external_ratings.html
- K — k_101_shots_mgik_v4_verified.html
- M — model_m_fast101_quiz.html

These preserve the exact questionnaire/title sets and ordering.

## Completed-run evidence found in prior chat history
- R: 54 numeric ratings; 15 "watched, rating not remembered"; 32 not watched. Distribution of numeric ratings: 47×5, 3×4, 2×3, 2×1. 41 titles had Heat 🔥🔥🔥.
- M: 42 numeric ratings; average 4.33/5; average Heat 2.6; 28/42 had 🔥🔥🔥.
- J: 20 watched titles; 13 numeric ratings; average ≈4.62/5; average Heat ≈2.62.
- K: 49 watched titles; 36 numeric ratings; average 4.08/5; average Heat 1.25.

## Recovery state
The exact 101-question forms are safe.
The completed result dumps existed in chat history for all four contours; reconstruction of row-level answers should be performed from those dumps and cross-checked against the questionnaire order.
Do not infer missing row-level values from aggregate statistics.

## Other recovered layers
- Legacy R/J 75-title calibration snapshot is stored as ../legacy-rj-76.tsv (header + 75 data rows).
- Current reconstructed multi-sheet model snapshot is stored as ../model-rjkm-master-2026-09-29.txt.
- Obsession ("Обсессия") and Absentia (2011, "Отсутствие") are different titles and must never be merged.
