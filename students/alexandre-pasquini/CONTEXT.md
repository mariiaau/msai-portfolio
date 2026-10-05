# My page — status

## Who I am
- Name: Alexandre Pasquini
- GitHub username: a13x4ndr3
- Student folder: students/alexandre-pasquini/
- Branch: student/alexandre-pasquini (on my fork a13x4ndr3/msai-portfolio)

## My links (on the live page)
- LinkedIn: https://www.linkedin.com/in/a13x4ndr3
- GitHub: https://github.com/a13x4ndr3
- Résumé: resume.pdf (phone number removed, since the page is public)
- Portfolio site: https://www.alexandrepasquini.online

## Files in my student folder
- index.html — main page, all four links filled in, no CHANGE-ME left
- photo.jpg — my real photo, square, 800x800, ~108 KB
- resume.pdf — my CV without phone number
- CLAUDE.md, CONTEXT.md — notes for my AI assistant

## What is done
- Folder copied from _template and renamed to students/alexandre-pasquini
- index.html: name in title/h1/nav badge, one-line quote, 4 project cards
  (Monday Supplier Dashboard skill, RAG client-intake assistant, Axelis AI, The AI Revenue Engine),
  education and experience
- Photo, résumé and all four links are real
- Files uploaded to my fork and moved to branch student/alexandre-pasquini
- Pull request opened against rodolfocapdevilla-au/msai-portfolio main: PR #62 (https://github.com/rodolfocapdevilla-au/msai-portfolio/pull/62)

## Round two (Module 5.2)
- PR #62 was merged into rodolfocapdevilla-au/msai-portfolio main — round one is done and live.
- Replaced all 4 placeholder.jpg images on the project cards with real, custom pictures made for
  each project, saved inside my own folder (not assets/): project-monday-dashboard.svg,
  project-rag-assistant.svg, project-axelis-ai.svg, project-ai-revenue-engine.svg. Each is under
  1.5 KB and matches the site's own palette (blue #1E6FE0, red #E23B3B) instead of a generic stock
  image.
- Same branch (student/alexandre-pasquini) — no new branch created, per the rule that a merged
  request never reopens but the branch keeps going.
- Opened a new pull request, "Round two — Alexandre Pasquini", against
  rodolfocapdevilla-au/msai-portfolio main.

## What went wrong in round two, and the fix
- My first upload went to the repository root, not students/alexandre-pasquini/, and overwrote the
  shared CLAUDE.md, CONTEXT.md, REPORT.md and index.html. Deleting my copies also deleted the originals.
- Fix: re-uploaded inside students/alexandre-pasquini/, added the instructor's repo as a second
  remote (upstream), merged upstream/main, and restored the four shared files from upstream/main.
- Check that worked: PR #77 changes only files under students/alexandre-pasquini/.
- Rewrote the first two project cards to three sentences each (what it is, what I did, what came out).

## Next step
1. Push the card rewrite (index.html, CONTEXT.md, REPORT.md) to the same branch; PR #77 updates itself
2. Wait for #77 to be merged; if there are review notes, answer them and push again (no second PR)
3. Open the live page signed out and on a phone, click the CV button and all four links
4. Submit the live address and REPORT.md in the portal (due 4 October 2026, 11:59 PM)
