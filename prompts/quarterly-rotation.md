# Quarterly rotation

For each rotating ledger (`20-*`, `25-*`, `30-*`, `40-*`, `50-*`, `60-*`, `90-*`):

1. Move entries older than ~3 months into `archive/<file>-<YYYY-Qn>.md`, unchanged.
2. Replace them in the live file with one dated summary paragraph under `## Summary <YYYY-Qn>`: the durable facts, decisions taken, how the relationship stood at quarter end. No speculation in summaries.
3. Keep every open commitment in the live file, regardless of age.
4. `70-threads.md`, `05-self.md`, `00-context.md`, `10-stakeholders.md`, `80-skip-levels.md` never rotate. At year end, a `Y<YYYY> retrospective` session writes a long-view summary that becomes the top of `00-context.md`.
5. Commit as `rotation <YYYY-Qn>`.
