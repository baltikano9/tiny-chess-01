# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/baltikano9/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/baltikano9/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine: 10x12 mailbox with full legal move generation, incremental Zobrist hashing and a tapered piece-square evaluation with a bishop-pair bonus. It searches with iterative-deepening PVS alpha-beta under a fixed 60,000-node budget (transposition table, null move, late-move reductions, futility pruning, killer/history ordering and a quiescence search over captures, promotions and check evasions), so its moves are deterministic. Measured practice Elo: 1654 on trial-0 (mean 1682 over the three practice instances).

## Run it

    MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 -P -s main.py

<sub>Entered on [make.fun](https://make.fun/?ref=ftn0yn4s&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
