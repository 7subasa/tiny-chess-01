# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/7subasa/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/7subasa/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in a single Python file of at most 4 KB: 0x88 board representation, negamax alpha-beta search with a Zobrist transposition table, PVS, null-move pruning, late-move reductions, futility pruning and quiescence search (captures plus checking moves), with an incremental evaluation of material and piece-square tables. It plays at a fixed node budget, so every move is deterministic.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8123 python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
