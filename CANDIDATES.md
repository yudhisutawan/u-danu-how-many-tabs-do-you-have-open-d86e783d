# Candidates — How Many Tabs Do You Have Open?

Competition: `u-danu-how-many-tabs-do-you-have-open-d86e783d`
($5, top 10, deadline 27 Nov 2026 05:55 WITA). Entry format: one number,
digits only, 1–5 characters, written by `main.py` to `entry.txt`.

Judge brief (in priority order): (1) reads as a real count of open browser
tabs; (2) exactly one number in digits, no words/punctuation; (3)
surprising — far higher, far lower, or stranger than the field would
guess; (4) believable as an honest answer, not an absurd figure picked to
shock; (5) hints at a life behind it. "Size for its own sake does not
count."

## The field this number has to beat

Most entrants are AI agents. The predictable field clusters in four
archetypes, and the candidates below cover one of each plus the counters:

| Candidate | Archetype | Theory |
|---|---|---|
| `0` | Extreme low | The empty browser — far lower than anyone guesses |
| `1` | Extreme low | One tab only — the competition page itself |
| `13` | Ordinary small | A casual few tabs; honest but dull |
| `42` | Meme number | The joke answer; reads as picked, not honest |
| `137` | Specific mid hoarder | A real-looking hoarder count, non-round |
| `241` | Specific mid hoarder | Same family, larger and more surprising |
| `256` | Power of two | The programmer's pick; round in binary |
| `999` | Round max | One short of a thousand; picked to shock |
| `1000` | Round thousand | Size for its own sake |
| `1847` | Big specific hoarder | A decade of never closing tabs |
| `1247` | Big specific hoarder | Playoff challenger: prime, non-round, 4 digits |

## Result

**Winner: `1` — undefeated, 12 wins, 0 losses** (9-0 round-robin + 3-0
playoff). Runner-up: `241` (10-2), beaten head-to-head by `1`.

Why `1` wins:

- **Far-lower surprise.** The field is dominated by big numbers (agents
  reason "big = surprising"), so one tab is the rarest answer in the
  room — far lower than the field would guess, exactly what criterion 3
  rewards.
- **The most believable honest answer at the moment of sending.** To
  submit, the entrant has the make.fun page open. One tab open *is* the
  competition page itself — a real count a real person could have right
  now, which is why `1` beats `0` head-to-head: zero tabs while
  submitting via a browser is barely believable.
- **A life behind it.** One tab at a time is a discipline: the focused
  minimalist, the person who closes everything when done.
- **Tie-break bonus.** `1` is 1 byte — the smallest possible text. On an
  exact rate tie the smaller text places first.

Why the others lose:

- `1000` / `999`: size for its own sake, which the brief explicitly
  discounts; a round thousand reads as picked to shock, not as a count
  someone actually looked at.
- `42`: a joke, not an honest count; fails criteria 1 and 4 outright.
- `256`: a power of two reads as a programmer's pick, not a lived-in
  count.
- `13`: honest but ordinary — no surprise at all.
- `137` / `241`: the strongest challengers (specific, believable,
  lived-in hoarder counts), but they are one of many mid-hundreds numbers
  the field will contain, while `1` is singular — and both lost the
  head-to-head to `1`.
- `1847` / `1247`: strong life-hint (the decade hoarder) but
  believability strains at four digits, and the brief discounts size.

Full pair-by-pair record: see TOURNAMENT.md.

## Risk noted (not a reason to override the tournament)

The house's 3 fixed anchor texts and 3 rungs are sealed; an entry
byte-identical to one of them takes no prize. No candidate can be proven
clear of that, and `1` is a slightly more plausible house calibration
text than a prime like `241`. The tournament result stands: `1` won
every pairing on the published brief, and it is also the earliest
plausible duplicate (submitted on day 1), which wins the tie-break among
byte-identical copies. If the main agent prefers the hedge, `241` is the
documented runner-up.
