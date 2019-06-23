*** Time benchmarks ***
benchmarked Countdown/Put/fused-effects
time                 6.979 μs   (6.713 μs .. 7.159 μs)
                     0.994 R²   (0.991 R² .. 0.997 R²)
mean                 6.725 μs   (6.628 μs .. 6.808 μs)
std dev              295.4 ns   (254.3 ns .. 351.2 ns)
variance introduced by outliers: 23% (moderately inflated)

benchmarked Countdown/Put/mtl
time                 7.593 μs   (6.946 μs .. 8.021 μs)
                     0.975 R²   (0.967 R² .. 0.986 R²)
mean                 7.160 μs   (7.000 μs .. 7.323 μs)
std dev              559.6 ns   (498.2 ns .. 636.9 ns)
variance introduced by outliers: 52% (severely inflated)

benchmarked Countdown/Put/polysemy
time                 2.957 ms   (2.714 ms .. 3.189 ms)
                     0.977 R²   (0.968 R² .. 0.994 R²)
mean                 3.087 ms   (3.027 ms .. 3.159 ms)
std dev              225.6 μs   (199.4 μs .. 272.0 μs)
variance introduced by outliers: 46% (moderately inflated)

benchmarked Countdown/Put/freer-simple
time                 1.690 ms   (1.647 ms .. 1.721 ms)
                     0.996 R²   (0.993 R² .. 0.999 R²)
mean                 1.739 ms   (1.701 ms .. 1.866 ms)
std dev              211.8 μs   (63.89 μs .. 430.7 μs)
variance introduced by outliers: 73% (severely inflated)

benchmarked Countdown/Put/extensible-effects
time                 1.886 ms   (1.845 ms .. 1.945 ms)
                     0.995 R²   (0.991 R² .. 0.998 R²)
mean                 1.899 ms   (1.877 ms .. 1.922 ms)
std dev              77.70 μs   (65.51 μs .. 96.25 μs)
variance introduced by outliers: 22% (moderately inflated)

benchmarked Countdown/Put/shallow
time                 344.1 μs   (337.5 μs .. 350.4 μs)
                     0.997 R²   (0.996 R² .. 0.998 R²)
mean                 349.8 μs   (345.9 μs .. 353.8 μs)
std dev              12.92 μs   (10.58 μs .. 16.24 μs)
variance introduced by outliers: 18% (moderately inflated)

benchmarked Countdown/Put+Exc/fused-effects
time                 11.18 μs   (11.01 μs .. 11.36 μs)
                     0.998 R²   (0.997 R² .. 0.999 R²)
mean                 11.33 μs   (11.21 μs .. 11.48 μs)
std dev              482.1 ns   (378.0 ns .. 588.1 ns)
variance introduced by outliers: 23% (moderately inflated)

benchmarked Countdown/Put+Exc/mtl
time                 11.36 μs   (11.17 μs .. 11.56 μs)
                     0.997 R²   (0.995 R² .. 0.998 R²)
mean                 11.34 μs   (11.21 μs .. 11.51 μs)
std dev              492.6 ns   (409.5 ns .. 602.8 ns)
variance introduced by outliers: 24% (moderately inflated)

benchmarked Countdown/Put+Exc/polysemy
time                 511.1 μs   (503.5 μs .. 517.9 μs)
                     0.997 R²   (0.995 R² .. 0.999 R²)
mean                 517.6 μs   (511.7 μs .. 524.1 μs)
std dev              21.27 μs   (17.99 μs .. 25.89 μs)
variance introduced by outliers: 22% (moderately inflated)

benchmarked Countdown/Put+Exc/freer-simple
time                 1.387 ms   (1.363 ms .. 1.409 ms)
                     0.998 R²   (0.996 R² .. 0.999 R²)
mean                 1.391 ms   (1.376 ms .. 1.407 ms)
std dev              53.50 μs   (42.30 μs .. 69.57 μs)
variance introduced by outliers: 19% (moderately inflated)

benchmarked Countdown/Put+Exc/extensible-effects
time                 1.572 ms   (1.540 ms .. 1.612 ms)
                     0.997 R²   (0.994 R² .. 0.999 R²)
mean                 1.542 ms   (1.530 ms .. 1.558 ms)
std dev              48.84 μs   (39.00 μs .. 62.84 μs)
variance introduced by outliers: 15% (moderately inflated)

benchmarked Countdown/Put+Exc/shallow
time                 63.09 μs   (61.44 μs .. 65.25 μs)
                     0.995 R²   (0.991 R² .. 0.998 R²)
mean                 62.90 μs   (62.18 μs .. 63.82 μs)
std dev              2.801 μs   (2.114 μs .. 3.589 μs)
variance introduced by outliers: 24% (moderately inflated)

benchmarked HTTP/fused-effects
time                 11.08 μs   (10.82 μs .. 11.37 μs)
                     0.997 R²   (0.995 R² .. 0.998 R²)
mean                 11.05 μs   (10.95 μs .. 11.16 μs)
std dev              359.2 ns   (305.6 ns .. 432.0 ns)
variance introduced by outliers: 15% (moderately inflated)

benchmarked HTTP/polysemy
time                 18.06 ms   (17.79 ms .. 18.31 ms)
                     0.998 R²   (0.997 R² .. 1.000 R²)
mean                 18.20 ms   (18.04 ms .. 18.41 ms)
std dev              444.1 μs   (330.8 μs .. 563.6 μs)

benchmarked HTTP/extensible-effects
time                 2.080 ms   (2.058 ms .. 2.110 ms)
                     0.998 R²   (0.997 R² .. 0.999 R²)
mean                 2.053 ms   (2.034 ms .. 2.075 ms)
std dev              68.45 μs   (56.34 μs .. 87.04 μs)
variance introduced by outliers: 15% (moderately inflated)

benchmarked HTTP/Deep embedding
time                 2.388 ms   (2.354 ms .. 2.422 ms)
                     0.998 R²   (0.997 R² .. 0.999 R²)
mean                 2.395 ms   (2.371 ms .. 2.426 ms)
std dev              87.90 μs   (70.45 μs .. 111.4 μs)
variance introduced by outliers: 18% (moderately inflated)

benchmarked HTTP/Shallow embedding
time                 19.93 μs   (19.52 μs .. 20.34 μs)
                     0.997 R²   (0.996 R² .. 0.999 R²)
mean                 19.80 μs   (19.61 μs .. 20.05 μs)
std dev              772.0 ns   (593.1 ns .. 1.135 μs)
variance introduced by outliers: 21% (moderately inflated)

benchmarked HTTP/freer-simple
time                 1.819 ms   (1.793 ms .. 1.859 ms)
                     0.995 R²   (0.991 R² .. 0.998 R²)
mean                 1.885 ms   (1.864 ms .. 1.913 ms)
std dev              85.75 μs   (71.04 μs .. 110.1 μs)
variance introduced by outliers: 24% (moderately inflated)

*** Space benchmarks (these will take some time to run) ***

Countdown

  Case                Allocated  GCs
  fused-effects              40    0
  mtl                     3,848    0
  polysemy                1,880    0
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