*** Time benchmarks ***
benchmarked Countdown/Put/fused-effects
time                 6.698 μs   (6.122 μs .. 7.338 μs)
                     0.967 R²   (0.943 R² .. 0.993 R²)
mean                 6.287 μs   (6.140 μs .. 6.550 μs)
std dev              648.4 ns   (412.2 ns .. 999.0 ns)
variance introduced by outliers: 62% (severely inflated)

benchmarked Countdown/Put/mtl
time                 6.610 μs   (5.880 μs .. 7.574 μs)
                     0.929 R²   (0.884 R² .. 0.988 R²)
mean                 6.550 μs   (6.341 μs .. 6.845 μs)
std dev              864.1 ns   (589.1 ns .. 1.256 μs)
variance introduced by outliers: 75% (severely inflated)

benchmarked Countdown/Put/polysemy
time                 1.243 ms   (672.2 μs .. 1.817 ms)
                     0.223 R²   (0.050 R² .. 0.512 R²)
mean                 3.591 ms   (3.042 ms .. 4.401 ms)
std dev              2.079 ms   (1.538 ms .. 2.913 ms)
variance introduced by outliers: 97% (severely inflated)

benchmarked Countdown/Put/freer-simple
time                 1.597 ms   (1.394 ms .. 1.912 ms)
                     0.910 R²   (0.871 R² .. 0.996 R²)
mean                 1.477 ms   (1.432 ms .. 1.561 ms)
std dev              217.7 μs   (141.3 μs .. 331.6 μs)
variance introduced by outliers: 81% (severely inflated)

benchmarked Countdown/Put/extensible-effects
time                 1.647 ms   (1.514 ms .. 1.793 ms)
                     0.971 R²   (0.961 R² .. 0.989 R²)
mean                 1.837 ms   (1.762 ms .. 1.985 ms)
std dev              378.1 μs   (263.5 μs .. 592.1 μs)
variance introduced by outliers: 90% (severely inflated)

benchmarked Countdown/Put/shallow
time                 292.9 μs   (286.5 μs .. 300.9 μs)
                     0.993 R²   (0.982 R² .. 0.999 R²)
mean                 301.5 μs   (294.9 μs .. 312.9 μs)
std dev              30.02 μs   (18.69 μs .. 42.93 μs)
variance introduced by outliers: 65% (severely inflated)

benchmarked Countdown/Put+Exc/fused-effects
time                 10.90 μs   (10.68 μs .. 11.14 μs)
                     0.996 R²   (0.992 R² .. 0.999 R²)
mean                 11.07 μs   (10.87 μs .. 11.39 μs)
std dev              847.3 ns   (485.4 ns .. 1.173 μs)
variance introduced by outliers: 52% (severely inflated)

benchmarked Countdown/Put+Exc/mtl
time                 10.84 μs   (10.56 μs .. 11.22 μs)
                     0.993 R²   (0.983 R² .. 0.999 R²)
mean                 11.02 μs   (10.86 μs .. 11.33 μs)
std dev              732.5 ns   (432.1 ns .. 1.090 μs)
variance introduced by outliers: 43% (moderately inflated)

benchmarked Countdown/Put+Exc/polysemy
time                 441.0 μs   (426.7 μs .. 459.9 μs)
                     0.990 R²   (0.977 R² .. 0.999 R²)
mean                 449.9 μs   (442.8 μs .. 462.7 μs)
std dev              32.76 μs   (20.72 μs .. 48.18 μs)
variance introduced by outliers: 49% (moderately inflated)

benchmarked Countdown/Put+Exc/freer-simple
time                 1.159 ms   (1.120 ms .. 1.229 ms)
                     0.987 R²   (0.974 R² .. 0.998 R²)
mean                 1.153 ms   (1.138 ms .. 1.192 ms)
std dev              74.23 μs   (41.34 μs .. 128.2 μs)
variance introduced by outliers: 42% (moderately inflated)

benchmarked Countdown/Put+Exc/extensible-effects
time                 1.304 ms   (1.260 ms .. 1.364 ms)
                     0.988 R²   (0.976 R² .. 0.999 R²)
mean                 1.288 ms   (1.273 ms .. 1.329 ms)
std dev              76.63 μs   (30.84 μs .. 145.3 μs)
variance introduced by outliers: 37% (moderately inflated)

benchmarked Countdown/Put+Exc/shallow
time                 61.92 μs   (59.96 μs .. 64.94 μs)
                     0.990 R²   (0.979 R² .. 0.999 R²)
mean                 62.39 μs   (61.75 μs .. 64.03 μs)
std dev              3.399 μs   (1.836 μs .. 6.227 μs)
variance introduced by outliers: 32% (moderately inflated)

benchmarked HTTP/fused-effects
time                 11.17 μs   (10.80 μs .. 11.65 μs)
                     0.991 R²   (0.982 R² .. 0.997 R²)
mean                 10.85 μs   (10.74 μs .. 11.14 μs)
std dev              537.0 ns   (300.9 ns .. 992.7 ns)
variance introduced by outliers: 29% (moderately inflated)

benchmarked HTTP/polysemy
time                 15.87 ms   (12.21 ms .. 18.89 ms)
                     0.777 R²   (0.544 R² .. 0.928 R²)
mean                 18.78 ms   (17.05 ms .. 21.93 ms)
std dev              5.440 ms   (3.462 ms .. 7.926 ms)
variance introduced by outliers: 90% (severely inflated)

benchmarked HTTP/extensible-effects
time                 5.224 ms   (4.377 ms .. 6.468 ms)
                     0.773 R²   (0.680 R² .. 0.874 R²)
mean                 2.882 ms   (2.455 ms .. 3.426 ms)
std dev              1.433 ms   (1.146 ms .. 1.869 ms)
variance introduced by outliers: 97% (severely inflated)

benchmarked HTTP/Deep embedding
time                 3.532 ms   (2.332 ms .. 5.441 ms)
                     0.481 R²   (0.355 R² .. 0.716 R²)
mean                 3.355 ms   (2.964 ms .. 3.902 ms)
std dev              1.514 ms   (1.159 ms .. 2.285 ms)
variance introduced by outliers: 97% (severely inflated)

benchmarked HTTP/Shallow embedding
time                 16.04 μs   (15.47 μs .. 16.85 μs)
                     0.986 R²   (0.969 R² .. 0.998 R²)
mean                 16.93 μs   (16.60 μs .. 17.55 μs)
std dev              1.487 μs   (856.1 ns .. 2.133 μs)
variance introduced by outliers: 56% (severely inflated)

benchmarked HTTP/freer-simple
time                 1.853 ms   (1.561 ms .. 2.080 ms)
                     0.939 R²   (0.915 R² .. 0.980 R²)
mean                 1.603 ms   (1.563 ms .. 1.678 ms)
std dev              173.2 μs   (116.0 μs .. 261.4 μs)
variance introduced by outliers: 65% (severely inflated)

*** Space benchmarks (these will take some time to run) ***

Countdown

  Case                Allocated  GCs
  fused-effects           3,888    0
  mtl                        40    0
  polysemy                1,032    0
  freer-simple            1,096    0
  extensible-effects      1,304    0
  shallow                   232    0

Countdown + exc

  Case                Allocated  GCs
  fused-effects              16    0
  mtl                        16    0
  polysemy                  480    0
  freer-simple              544    0
  extensible-effects        664    0
  shallow                     0    0
Benchmark effects-benchmarks: FINISH
