# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/zara655/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/zara655/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Glintfish: a chess engine in 4 KB of Python. `main.py` (4,068 bytes) is the
whole engine — an lzma-packed payload that unpacks to a 0x88-board engine
with negamax alpha-beta search, quiescence, a transposition table, null-move
pruning, late move reductions, MVV-LVA ordering and hand-tuned piece-square
tables. It plays the make.fun gauntlet over HTTP at a fixed 50,000 nodes per
move, so every game is deterministic and replayable. In local practice
trials against the kit's house ladder it won 5 of 6 games (practice Elo
1654 on trial-0).

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=cgsv8n01&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
