# claude-s-pick-101

where we build cool stuff 🔥
(I kinda vibe code here. check other repos for my actual work)

## ⚖️ Excuse Court

Type your excuse for being late. A very judgmental judge rates how believable it is, stamps a verdict, and bangs the gavel. The worse the excuse, the more it bangs.

**▶️ Play it: https://kyamavictor854-del.github.io/claude-s-pick-101/**

### What it does

- **Believability score (0–100)**: classics like "my dog ate my homework" lose points, an honest "I forgot" gains them
- **Four verdicts**: ACQUITTED, PROBATION, GUILTY, and CONTEMPT OF COURT
- **Exhibits**: a list of what helped and what hurt your case
- **Terribleness percentile**: how your excuse ranks against 360 sample excuses
- **Gavel sound**: generated in the browser with the Web Audio API, no sound files
- **Same excuse, same verdict**: rulings are deterministic, so you can't re-roll your way to freedom
- **Hall of Shame**: on the claude.ai version, excuses worse than 99% of the cases on record get filed into a shared hall automatically

### How it's built

One file, `index.html`: plain HTML, CSS, and JavaScript, with no frameworks and no build step. Open it in a browser and it runs.
