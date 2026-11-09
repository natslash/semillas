# Monthly viz (after monthly-insights)

Regenerate `viz/` from the ledgers. Provider-neutral outputs only: Mermaid in markdown, plus one self-contained `viz/index.html` (inline CSS/JS, no CDN) that renders the same data. Overwrite previous month's files; git keeps history.

1. `viz/timeline.md` — Mermaid timeline (or gantt) per key person: one row each, entries as points labelled by date and first tag. Silences >3 weeks marked.
2. `viz/tag-person.md` — table: rows = people, columns = tags, cells = count of entries this quarter. Bold cells ≥3. One line under the table naming any tag that appears under ≥3 people.
3. `viz/commitments.md` — board: Open / Due this week / Overdue / Closed this month, each line `owner → what → due → source entry`.
4. `viz/read-drift.md` — for each key person, the "my read" field of every entry in date order, verbatim, one block per person. No commentary; the point is to see hardening or reversal.
5. `viz/stake-map.md` — Mermaid quadrant chart: x = alignment with Shashi's 180-day goals (low→high), y = influence over those goals (low→high). Position every person in `10-stakeholders.md`; note moves since last month.
6. `viz/graph.md` — Mermaid graph of `[[links]]` co-occurring within the same entry this quarter, weighted by count (edge label). Drop edges with weight 1.
7. `viz/index.html` — the same five views in one page, tabs, built from the data above.

Rules: code names only; no speculation in generated views — they render what the ledgers say. If an entry lacks the fields a view needs, skip it and list the skipped entries at the bottom of that view. Mind maps for a single topic are produced on request and not kept.
