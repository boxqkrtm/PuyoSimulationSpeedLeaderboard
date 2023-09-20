# Puyo Simulation Speed Leaderboard
- pop [kenny 19rensa puyo field](https://puyonexus.com/wiki/Miscellaneous_Chains#Kenny_Formula)
- unit = simulate times per frame (in 60fps game = 16ms) for realtime ai

# LeaderBoard (tested on intel i7-1165G7)<br>
1. bitboard PEXT by citrus610 ([github](https://github.com/boxqkrtm/puyo-core-benchmark/tree/530ff1dd9ffe5572bad616ea5450ed3b67432064))<br>
14828.544949times/16ms<br>
2. partial search + dfs by Riemann-rbrb ([github](https://github.com/Riemann-rbrb/PuyoBenchmarkCPP/tree/7c0b711da30b3d0b8bed6c5114f62e8a8950e9ff))<br>
6607.744times/16ms<br>

# Etc LeaderBoard for Unknown (closed source and no benchmark executable)
1. SSE3 ([picture](https://twitter.com/waruo_t/status/1297516969210425344))<br>
19083.968times/16ms<br>
