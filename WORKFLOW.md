# PER-CLIENT WORKFLOW

## Intake template (user pastes this)

```
New client: [NAME]
Niche: [NICHE — flag if it needs narrowing/deciding]
System name: [MECHANISM NAME]

[UPLOAD ALL CLIENT DOCS — Niche Validation, Offer, Unique Mechanism, sales scripts]
[OPTIONAL: website / portfolio URLs — visit for additional depth]

Read and internalize everything before forming any opinion. Do not write any copy yet.

Then deliver:
1. Synthesis: exact guarantee language (word for word), system name and pillars,
   credibility proof points, and ideal client profile.
2. Flags: anything missing, unverifiable, or that cannot go in the copy as written.
3. Strategy: core angle for Script 1 and Problem-First, angle assignments for all other
   assets, credibility approach, and tone recommendation.
Wait for my approval before writing anything.
```

## Step by step

1. **Read everything.** Extract docx (python zipfile/docx) and PDFs (pdfplumber / Read tool). Visit URLs given.
   Store docs in `clients/<name>/docs/`.
2. **Synthesis.** Guarantee verbatim (quote it, blockquoted). System + pillars. Credibility inventory —
   separate INSTITUTIONAL (years, projects, reviews, team) from CASE STUDIES (with real numbers) and mark
   which are niche-native vs adjacent. ICP with qualifying conditions.
3. **Flags.** Doc contradictions (numbers, years). Weak/undocumented risk reversal. Missing proof for the
   niche. Unverifiable claims (unnamed clients, sales-script-only stories). Meta/compliance risks.
   Kill-list words inside the client's own docs that must be translated.
4. **Strategy.** Core angle for Script 1 + Problem-First (they share it). One hook structure per asset from
   `HOOK_BANKS.md`. Credibility approach (results-led vs authority-led vs hybrid). Tone + tribal vocabulary
   list drafted BEFORE writing. Callout choice (how the audience self-identifies; address the owner's seat).
5. **WAIT for approval.** Ask the numbered questions; make decisive recommendations, never guess guarantees.
6. **Write the full 3-3-3.** Guarantee spine identical in all 9 assets. Support line (what "qualified"
   means) pulled from the offer doc's own definition and kept consistent.
7. **Run `final-package-review` skill.** Fix, re-sweep, deliver clean with a short DELIVERY NOTES block
   (outside the package) covering judgment calls and open items for the client.
8. **Iterate.** Apply each note package-wide. Re-run the pattern sweep after every revision round.
9. **Close out.** Save final package to `clients/<name>/package_vN.md`. Append lessons to `LEARNINGS.md`.
   Add/update the client entry in `COMPLETED_CLIENTS.md` (guarantee, pillars, angles, decisions, open items).

## Model guidance

Draft and iterate on any strong model; run the final-package-review pass (and voice-sensitive rewrites)
on the most capable model available. Quality lives mostly in this system; the model adds the last-mile nuance.
