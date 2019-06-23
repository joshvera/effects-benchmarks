*** Time benchmarks ***
benchmarked Countdown/Put/fused-effects
time                 12.04 μs   (11.90 μs .. 12.27 μs)
                     0.998 R²   (0.995 R² .. 0.999 R²)
mean                 12.31 μs   (12.22 μs .. 12.42 μs)
std dev              332.1 ns   (271.5 ns .. 400.1 ns)
variance introduced by outliers: 11% (moderately inflated)

benchmarked Countdown/Put/mtl
time                 6.137 μs   (6.079 μs .. 6.190 μs)
                     0.999 R²   (0.997 R² .. 1.000 R²)
mean                 6.141 μs   (6.104 μs .. 6.195 μs)
std dev              151.4 ns   (112.0 ns .. 206.8 ns)

benchmarked Countdown/Put/polysemy
time                 2.372 ms   (2.295 ms .. 2.450 ms)
                     0.991 R²   (0.983 R² .. 0.998 R²)
mean                 2.527 ms   (2.451 ms .. 2.682 ms)
std dev              355.9 μs   (195.6 μs .. 634.6 μs)
variance introduced by outliers: 79% (severely inflated)

benchmarked Countdown/Put/freer-simple
time                 1.441 ms   (1.413 ms .. 1.477 ms)
                     0.997 R²   (0.994 R² .. 0.999 R²)
mean                 1.455 ms   (1.438 ms .. 1.484 ms)
std dev              71.67 μs   (49.53 μs .. 106.2 μs)
variance introduced by outliers: 28% (moderately inflated)

benchmarked Countdown/Put/extensible-effects
time                 1.595 ms   (1.561 ms .. 1.646 ms)
                     0.994 R²   (0.988 R² .. 0.999 R²)
mean                 1.600 ms   (1.584 ms .. 1.629 ms)
std dev              71.97 μs   (49.05 μs .. 98.31 μs)
variance introduced by outliers: 26% (moderately inflated)

benchmarked Countdown/Put/shallow
time                 303.4 μs   (295.5 μs .. 314.7 μs)
                     0.993 R²   (0.987 R² .. 0.998 R²)
mean                 308.9 μs   (305.5 μs .. 313.7 μs)
std dev              13.77 μs   (9.588 μs .. 18.70 μs)
variance introduced by outliers: 26% (moderately inflated)

benchmarked Countdown/Put+Exc/fused-effects
time                 6.101 μs   (5.987 μs .. 6.238 μs)
                     0.998 R²   (0.997 R² .. 0.999 R²)
mean                 6.152 μs   (6.103 μs .. 6.232 μs)
std dev              211.1 ns   (149.8 ns .. 300.7 ns)
variance introduced by outliers: 15% (moderately inflated)

benchmarked Countdown/Put+Exc/mtl
time                 11.06 μs   (10.92 μs .. 11.24 μs)
                     0.999 R²   (0.998 R² .. 1.000 R²)
mean                 11.03 μs   (10.99 μs .. 11.09 μs)
std dev              153.2 ns   (113.1 ns .. 203.7 ns)

benchmarked Countdown/Put+Exc/polysemy
time                 461.1 μs   (443.8 μs .. 479.5 μs)
                     0.994 R²   (0.991 R² .. 0.998 R²)
mean                 450.2 μs   (446.5 μs .. 455.7 μs)
std dev              15.49 μs   (11.24 μs .. 20.03 μs)
variance introduced by outliers: 15% (moderately inflated)

benchmarked Countdown/Put+Exc/freer-simple
time                 1.256 ms   (1.185 ms .. 1.365 ms)
                     0.973 R²   (0.951 R² .. 0.999 R²)
mean                 1.221 ms   (1.204 ms .. 1.265 ms)
std dev              89.87 μs   (50.29 μs .. 152.8 μs)
variance introduced by outliers: 48% (moderately inflated)

benchmarked Countdown/Put+Exc/extensible-effects
time                 1.556 ms   (1.363 ms .. 1.774 ms)
                     0.913 R²   (0.866 R² .. 0.972 R²)
mean                 1.554 ms   (1.484 ms .. 1.663 ms)
std dev              294.6 μs   (221.6 μs .. 409.8 μs)
variance introduced by outliers: 86% (severely inflated)

benchmarked Countdown/Put+Exc/shallow
time                 56.64 μs   (55.24 μs .. 59.16 μs)
                     0.984 R²   (0.957 R² .. 0.998 R²)
mean                 59.29 μs   (58.44 μs .. 60.56 μs)
std dev              3.498 μs   (2.309 μs .. 6.253 μs)
variance introduced by outliers: 36% (moderately inflated)

benchmarked HTTP/fused-effects
time                 6.238 μs   (5.944 μs .. 6.610 μs)
                     0.981 R²   (0.958 R² .. 0.998 R²)
mean                 6.307 μs   (6.169 μs .. 6.533 μs)
std dev              602.0 ns   (413.2 ns .. 798.5 ns)
variance introduced by outliers: 63% (severely inflated)

benchmarked HTTP/polysemy
time                 19.98 ms   (17.80 ms .. 22.24 ms)
                     0.960 R²   (0.936 R² .. 0.984 R²)
mean                 17.00 ms   (16.36 ms .. 17.91 ms)
std dev              1.832 ms   (1.232 ms .. 2.537 ms)
variance introduced by outliers: 51% (severely inflated)

benchmarked HTTP/extensible-effects
time                 1.734 ms   (1.699 ms .. 1.776 ms)
                     0.985 R²   (0.960 R² .. 0.996 R²)
mean                 1.835 ms   (1.794 ms .. 1.895 ms)
std dev              178.4 μs   (124.5 μs .. 266.5 μs)
variance introduced by outliers: 62% (severely inflated)

benchmarked HTTP/Deep embedding
time                 2.159 ms   (2.127 ms .. 2.204 ms)
                     0.995 R²   (0.990 R² .. 0.999 R²)
mean                 2.191 ms   (2.168 ms .. 2.229 ms)
std dev              97.13 μs   (56.29 μs .. 142.7 μs)
variance introduced by outliers: 24% (moderately inflated)

benchmarked HTTP/Shallow embedding
time                 16.46 μs   (16.28 μs .. 16.62 μs)
                     0.998 R²   (0.997 R² .. 1.000 R²)
mean                 16.58 μs   (16.47 μs .. 16.78 μs)
std dev              463.4 ns   (294.3 ns .. 774.6 ns)
variance introduced by outliers: 11% (moderately inflated)

benchmarked HTTP/freer-simple
time                 1.615 ms   (1.554 ms .. 1.724 ms)
                     0.974 R²   (0.952 R² .. 0.996 R²)
mean                 1.615 ms   (1.587 ms .. 1.660 ms)
std dev              114.1 μs   (65.45 μs .. 181.3 μs)
variance introduced by outliers: 45% (moderately inflated)

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
  mtl                    -3,864    0
  polysemy                4,336    0
  freer-simple              544    0
  extensible-effects        664    0
  shallow                     0    0
Benchmark effects-benchmarks: FINISH
