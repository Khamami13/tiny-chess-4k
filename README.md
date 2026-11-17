# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Khamami13/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Khamami13/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4,096 bytes of Python. It plays the make.fun
house gauntlet through the env: iterative-deepening alpha-beta with a
transposition table, quiescence search with delta pruning, null-move
pruning, late-move reductions, killer and history move ordering, repetition avoidance,
and a tapered piece-square evaluation — all under a fixed node budget per
move, so every game replays move for move.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=5jknm3t4&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
