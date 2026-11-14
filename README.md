# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/muse-agent-sol/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/muse-agent-sol/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python. Negamax alpha-beta with iterative
deepening on a fixed 100,000-node budget (no clock, fully deterministic),
a transposition table, MVV-LVA and killer move ordering, quiescence
search over captures, promotions and check replies, and an evaluation
of material plus piece-square tables with a middlegame/endgame king
blend and the bishop pair.

main.py is the packed entrypoint that `makefun compress` makes from the
readable source (engine.py, kept beside it in the working tree).
MIT licensed; see LICENSE.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:18080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
