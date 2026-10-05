# Report — Alexandre Pasquini

- **Name:** Alexandre Pasquini
- **GitHub username:** a13x4ndr3
- **Live page:** https://rodolfocapdevilla-au.github.io/msai-portfolio/students/alexandre-pasquini/
- **Pull requests:** #62 "Add Alexandre Pasquini page" (merged, round one). #77 "Round two — Alexandre Pasquini" (open when this was written; update to Merged after the instructor accepts it).

## Project cards and what each says

1. **Monday Supplier Dashboard (Claude Skill)**: A reusable Claude skill that turns a week of supplier meeting notes, a delivery export and a quality-incident log into one decision dashboard for a procurement committee. I wrote the procedure once, tested it on one week of data, then ran it unchanged on a second week it had never seen. It applied the same traffic-light rules and layout both times and correctly flipped which supplier was red.
2. **RAG Client-Intake Assistant for Small Law Firms**: A retrieval assistant that answers routine intake questions for a small law firm from its own policy documents, shown here on six fictional documents. I fixed a retrieval bug where it confused two similar policies, added a rule that makes it say "I don't have enough information" instead of guessing, and tested it on 11 questions. The right source now comes first for all 9 answerable questions (it was 6 of 7 before), and it refused both questions the documents cannot answer.
3. **Axelis AI**: My company building AI-driven CRM and automation systems for service businesses — voice agents, client intake, and follow-up, so a small business can respond to every client without hiring a bigger front desk.
4. **The AI Revenue Engine**: A business book I wrote on applying AI to revenue operations — the same intersection of B2B sales, operations and practical automation that Axelis AI and my coursework both come back to.

## Notes received on my pull request and how I answered them

None so far on #77 (no review comments when this was written). If the instructor leaves notes, add each one here with my reply.

## Commits

| Commit | Date | Message |
|---|---|---|
| be7e4a0 | 2026-09-28 | Add files via upload |
| 26d30d3 | 2026-09-28 | Add Alexandre Pasquini page |
| 42486b2 | 2026-09-28 | Add REPORT.md and PR number in CONTEXT.md |
| 83b2c90 | 2026-09-30 | Add files via upload (round two files — landed in the repository root by mistake) |
| 550a299 … e6c979f | 2026-09-30 | Ten commits "Delete <file>" to remove those misplaced root files (CLAUDE.md, CONTEXT.md, resume.pdf, REPORT.md, index.html, photo.jpg and the 4 project-*.svg) |
| 7268238 | 2026-09-30 | Add files via upload (same files, this time inside students/alexandre-pasquini) |
| 49516a7 | 2026-09-30 | Merge latest main to restore shared root files |
| dd861ba | 2026-09-30 | Restore shared root files deleted by mistake |

The mistake: my first round-two upload went to the repository root and overwrote four shared files; deleting them removed the originals too. I restored them from the instructor's main branch, so pull request #77 changes only files inside students/alexandre-pasquini/.
