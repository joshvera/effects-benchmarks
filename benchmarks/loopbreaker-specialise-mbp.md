*** Time benchmarks ***
benchmarked Countdown/Put/fused-effects
time                 12.13 μs   (11.83 μs .. 12.56 μs)
                     0.992 R²   (0.980 R² .. 0.999 R²)
mean                 12.35 μs   (12.14 μs .. 12.72 μs)
std dev              947.2 ns   (619.1 ns .. 1.299 μs)
variance introduced by outliers: 52% (severely inflated)

benchmarked Countdown/Put/mtl
time                 5.671 μs   (5.470 μs .. 5.847 μs)
                     0.982 R²   (0.960 R² .. 0.994 R²)
mean                 6.550 μs   (6.325 μs .. 6.855 μs)
std dev              897.4 ns   (664.9 ns .. 1.158 μs)
variance introduced by outliers: 75% (severely inflated)

benchmarked Countdown/Put/polysemy
time                 2.560 ms   (2.481 ms .. 2.657 ms)
                     0.993 R²   (0.988 R² .. 0.998 R²)
mean                 2.419 ms   (2.393 ms .. 2.460 ms)
std dev              110.1 μs   (82.35 μs .. 150.4 μs)
variance introduced by outliers: 25% (moderately inflated)

benchmarked Countdown/Put/freer-simple
time                 1.431 ms   (1.400 ms .. 1.467 ms)
                     0.996 R²   (0.993 R² .. 0.998 R²)
mean                 1.508 ms   (1.487 ms .. 1.547 ms)
std dev              89.11 μs   (62.63 μs .. 138.0 μs)
variance introduced by outliers: 36% (moderately inflated)

benchmarked Countdown/Put/extensible-effects
time                 1.579 ms   (1.556 ms .. 1.596 ms)
                     0.998 R²   (0.997 R² .. 0.999 R²)
mean                 1.596 ms   (1.581 ms .. 1.613 ms)
std dev              55.20 μs   (45.64 μs .. 68.62 μs)
variance introduced by outliers: 17% (moderately inflated)

benchmarked Countdown/Put/shallow
time                 301.8 μs   (298.6 μs .. 305.5 μs)
                     0.999 R²   (0.999 R² .. 0.999 R²)
mean                 300.4 μs   (298.5 μs .. 302.9 μs)
std dev              7.304 μs   (5.853 μs .. 9.646 μs)

benchmarked Countdown/Put+Exc/fused-effects
time                 6.208 μs   (6.041 μs .. 6.426 μs)
                     0.991 R²   (0.976 R² .. 0.999 R²)
mean                 6.067 μs   (6.014 μs .. 6.230 μs)
std dev              285.8 ns   (126.7 ns .. 547.8 ns)
variance introduced by outliers: 27% (moderately inflated)

benchmarked Countdown/Put+Exc/mtl
time                 11.00 μs   (10.91 μs .. 11.22 μs)
                     0.994 R²   (0.979 R² .. 1.000 R²)
mean                 10.98 μs   (10.91 μs .. 11.24 μs)
std dev              422.2 ns   (85.47 ns .. 887.9 ns)
variance introduced by outliers: 20% (moderately inflated)

benchmarked Countdown/Put+Exc/polysemy
time                 448.3 μs   (440.7 μs .. 460.7 μs)
                     0.995 R²   (0.990 R² .. 0.999 R²)
mean                 445.6 μs   (442.2 μs .. 451.3 μs)
std dev              15.50 μs   (10.15 μs .. 22.58 μs)
variance introduced by outliers: 17% (moderately inflated)

benchmarked Countdown/Put+Exc/freer-simple
time                 1.178 ms   (1.137 ms .. 1.242 ms)
                     0.981 R²   (0.957 R² .. 0.998 R²)
mean                 1.213 ms   (1.186 ms .. 1.261 ms)
std dev              120.2 μs   (74.92 μs .. 174.2 μs)
variance introduced by outliers: 61% (severely inflated)

benchmarked Countdown/Put+Exc/extensible-effects
time                 1.437 ms   (1.335 ms .. 1.546 ms)
                     0.960 R²   (0.928 R² .. 0.985 R²)
mean                 1.425 ms   (1.378 ms .. 1.501 ms)
std dev              204.4 μs   (135.9 μs .. 359.7 μs)
variance introduced by outliers: 78% (severely inflated)

benchmarked Countdown/Put+Exc/shallow
time                 56.49 μs   (53.74 μs .. 59.35 μs)
                     0.982 R²   (0.966 R² .. 0.995 R²)
mean                 58.40 μs   (57.02 μs .. 60.98 μs)
std dev              6.061 μs   (3.611 μs .. 9.362 μs)
variance introduced by outliers: 64% (severely inflated)

benchmarked HTTP/fused-effects
time                 6.267 μs   (5.898 μs .. 6.736 μs)
                     0.978 R²   (0.963 R² .. 0.997 R²)
mean                 6.258 μs   (6.156 μs .. 6.414 μs)
std dev              427.4 ns   (303.8 ns .. 595.7 ns)
variance introduced by outliers: 44% (moderately inflated)

benchmarked HTTP/polysemy
time                 15.68 ms   (14.78 ms .. 16.82 ms)
                     0.966 R²   (0.921 R² .. 0.995 R²)
mean                 16.29 ms   (15.80 ms .. 17.09 ms)
std dev              1.628 ms   (872.4 μs .. 2.385 ms)
variance introduced by outliers: 48% (moderately inflated)

benchmarked HTTP/extensible-effects
time                 1.763 ms   (1.697 ms .. 1.870 ms)
                     0.987 R²   (0.977 R² .. 0.998 R²)
mean                 1.709 ms   (1.687 ms .. 1.743 ms)
std dev              91.75 μs   (49.39 μs .. 141.3 μs)
variance introduced by outliers: 31% (moderately inflated)

benchmarked HTTP/Deep embedding
time                 2.252 ms   (2.146 ms .. 2.360 ms)
                     0.988 R²   (0.979 R² .. 0.997 R²)
mean                 2.178 ms   (2.149 ms .. 2.220 ms)
std dev              117.3 μs   (75.20 μs .. 181.2 μs)
variance introduced by outliers: 33% (moderately inflated)

benchmarked HTTP/Shallow embedding
time                 16.95 μs   (16.39 μs .. 17.81 μs)
                     0.992 R²   (0.986 R² .. 0.999 R²)
mean                 16.55 μs   (16.41 μs .. 16.84 μs)
std dev              662.5 ns   (420.5 ns .. 1.111 μs)
variance introduced by outliers: 20% (moderately inflated)

benchmarked HTTP/freer-simple
time                 1.529 ms   (1.505 ms .. 1.569 ms)
                     0.992 R²   (0.982 R² .. 0.999 R²)
mean                 1.576 ms   (1.560 ms .. 1.603 ms)
std dev              67.92 μs   (44.56 μs .. 109.3 μs)
variance introduced by outliers: 23% (moderately inflated)

*** Space benchmarks (these will take some time to run) ***

Countdown

  Case                Allocated  GCs
  fused-effects              40    0
  mtl                        40    0
  polysemy                1,880    0
  freer-simple            1,096    0
  extensible-effects      1,304    0
  shallow                   232    0

Countdown + exc

  Case                Allocated  GCs
  fused-effects              16    0
  mtl                        16    0
  polysemy                  480    0
  freer-simple            4,416    0
  extensible-effects        664    0
  shallow                     0    0
Benchmark effects-benchmarks: FINISH
