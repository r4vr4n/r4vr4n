# Agent instructions

GitHub profile repo. `README.md` and `resumecontent.js` are **generated** from
`../r4vr4n.github.io/data/resume-data.js` (`E:\Github\r4vr4n.github.io`). Don't edit them by hand.

To change resume content:

1. Edit `../r4vr4n.github.io/data/resume-data.js`.
2. From `../r4vr4n.github.io`, run `node scripts/sync-profile.mjs`, then
   `node scripts/sync-profile.mjs --check`.
3. Commit both repos, only when the user asks.

The only hand-maintained part here is the `LIVE_PROJECTS` export in `resumecontent.js`. Edit it here,
then rerun the sync script so the README's Projects section picks it up.

Content rules (no invented claims, official titles, unshipped work stays off) live in
`../r4vr4n.github.io/AGENTS.md`.
