# 30-Day Pool Practice

A free, one-page pool player's guide with a pool cue giveaway. Tabs:

- **Drills**: 30 daily drills in 5 weeks (fundamentals, cutting, position, kicks/banks/safeties, break and pressure). Each drill has a top-down table diagram, setup, goal and scoring. Progress is tracked on the player's own device.
- **Rules**: plain-English summaries of 8-ball, 9-ball, 10-ball, straight pool and one pocket, how APA, BCAPL/CSI/USAPL and VNEA differ from the WPA rules, and two original games (Drill Duel and Ladder Climb).
- **Score**: scoreboards for 8-ball, 9-ball, one pocket, straight pool, Drill Duel and Ladder Climb, with undo and a printable sheet.
- **Giveaway**: entries are earned by saving drills. Each calendar day with a saved drill counts as one day, and every 6 days earns one entry (up to 5). Free to enter, one winner picked at random.

Plain HTML, CSS and JavaScript in `index.html`. No build step, no accounts, no server. Scores are saved in the browser (localStorage) and never leave the device. Works on a phone at the table, in light and dark mode.

## Giveaway settings

All giveaway details live in the `GIVEAWAY` object near the bottom of `index.html` (prize, value, sponsor, contact email, start, end and draw dates, entries per day count). The Giveaway tab stays hidden until the required fields are filled in. Current run: opens 2026-10-19, entries close 2027-01-01, drawing 2027-01-04.

Entries arrive by email. Each entry email carries an entry code, the days counted and the number of entries. Pick the winner with a random draw from all eligible entries, weighted by entries, and keep a record of how it was done.

## Deploy (free)

GitHub Pages: Settings > Pages > Deploy from branch `main`, folder `/ (root)`.
Or connect this repo to Cloudflare Pages with no build command and output directory `/`.

## Notes

- Drill setups are written generally so they work on any table. Have an experienced player review them before they go into a printed book.
- Rules summaries are in our own words from public rule summaries, not the official text. Rule sets change, so recheck them before publishing.
- Giveaway rules are a template, not legal advice. Entry requires effort (saving drills) and no purchase. Some states may treat required effort as consideration, so consider adding a free alternate entry and having the rules reviewed.
- Add a mailing address to `sponsorAddress` if you want it shown in the Official Rules.
