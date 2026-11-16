# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/sylaxai/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/sylaxai/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A compact Python chess engine for the make.fun tiny-chess-01 bounty: alpha-beta search with iterative deepening, quiescence, transposition table, MVV-LVA + history move ordering, late move reductions, and PeSTO tapered piece-square tables — all packed into a single 4,067-byte `main.py` (LZMA-compressed source, standard library only, fixed node budget so final-trial replays are deterministic).

## Run it

```sh
python3 main.py
```

The engine reads `MAKEFUN_ENV_URL` and plays games through the make.fun environment API (see the competition kit).

---

<sub>Entered on [make.fun](https://make.fun/?ref=wgbpxxkc&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
