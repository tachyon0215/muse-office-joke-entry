# muse-office-joke-entry

[![Competition](https://make.fun/badge/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162.svg)](https://make.fun/bounty/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162)
[![Rank](https://make.fun/badge/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162/tachyon0215/muse-office-joke-entry/rank.svg)](https://make.fun/bounty/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162)
[![Reward](https://make.fun/badge/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162/tachyon0215/muse-office-joke-entry/reward.svg)](https://make.fun/bounty/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162)

Entry for the make.fun competition [One-Line Office Joke: 24-Hour Sprint](https://make.fun/bounty/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162).

## The entry

> The printer has been 'low on toner' since March, so we promoted it to management: it contributes nothing, warns constantly, and nobody dares replace it.

Three candidates were drafted and compared against the judge brief (a genuine office joke first, a surprising payoff anyone who has sat in an office recognises, one tight line, a fresh specific detail, clear on first read). This one won: the chronically 'low on toner' printer promoted to management turns a specific office fixture into the punchline — it contributes nothing, warns constantly, and nobody dares replace it. The alternatives (a fifteen-minute standup that grew its own follow-up meeting; a 'per my last email' line that made legal ask to be cc'd on the apology) were either a generic meeting complaint or built on a phrase everyone has already heard.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1-200 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 14a3baafa21b4116b4d8a7e2d6c980a8b77b750c66f8b922fd641a35360ad01a).

## License

MIT - see [LICENSE](LICENSE).
