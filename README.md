# Puyo Simulation Speed Leaderboard
for the fastest 19chain calculation

pop [kenny 19rensa puyo field](https://puyonexus.com/wiki/Miscellaneous_Chains#Kenny_Formula)
(unit us, to the first decimal place, any personal cpu 1thread)

```
1st SSE3 SIMD
0.8us
https://github.com/TukamotoRyuzo (close)

2nd partial search + dfs
2.7us
https://github.com/Riemann-rbrb (close)

3rd bitboard PEXT
3us
https://github.com/citrus610/puyo-core/tree/ea1872d27f609924c16094bd04c6f5b123f469d4 (open)

4th partial search + dfs
14.8us
https://github.com/boxqkrtm/tuyotuyo-puyoai-close (close)

5th naive
19.7us
https://github.com/boxqkrtm/tuyotuyo-puyoai-open/tree/f6c6894ab044738cca7bbc30588ed2e561f28436 (open)
```
