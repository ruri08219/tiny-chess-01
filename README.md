# ruri08 tiny chess

A chess engine in 4 KB of Python for make.fun bounty `tiny-chess-01`.

0x88 board, negamax alpha-beta with iterative deepening (fixed 40,000
nodes/move), quiescence search with futility pruning, transposition
table, killer moves, null-move pruning and LMR. Deterministic: no clock,
no unseeded randomness. Plays the gauntlet through the env at
`MAKEFUN_ENV_URL` (`/game`, `/move`, `/resign`).

Run: `MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py`

Entry for make.fun: https://make.fun/bounty/tiny-chess-01
