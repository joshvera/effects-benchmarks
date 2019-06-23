*** Time benchmarks ***
benchmarked Countdown/Put/fused-effects
time                 5.900 μs   (5.777 μs .. 6.014 μs)
                     0.994 R²   (0.986 R² .. 0.999 R²)
mean                 6.252 μs   (6.137 μs .. 6.439 μs)
std dev              497.5 ns   (333.0 ns .. 704.7 ns)
variance introduced by outliers: 53% (severely inflated)

benchmarked Countdown/Put/mtl
time                 6.209 μs   (6.088 μs .. 6.300 μs)
                     0.999 R²   (0.998 R² .. 1.000 R²)
mean                 6.014 μs   (5.989 μs .. 6.049 μs)
std dev              98.27 ns   (74.26 ns .. 135.5 ns)

benchmarked Countdown/Put/polysemy
time                 2.316 ms   (2.046 ms .. 2.531 ms)
                     0.957 R²   (0.939 R² .. 0.978 R²)
mean                 2.223 ms   (2.157 ms .. 2.323 ms)
std dev              256.9 μs   (194.9 μs .. 318.1 μs)
variance introduced by outliers: 68% (severely inflated)

benchmarked Countdown/Put/freer-simple
time                 1.353 ms   (1.310 ms .. 1.400 ms)
                     0.979 R²   (0.951 R² .. 0.994 R²)
mean                 1.544 ms   (1.492 ms .. 1.609 ms)
std dev              206.0 μs   (169.0 μs .. 238.7 μs)
variance introduced by outliers: 77% (severely inflated)

benchmarked Countdown/Put/extensible-effects
time                 1.490 ms   (1.450 ms .. 1.530 ms)
                     0.991 R²   (0.983 R² .. 0.997 R²)
mean                 1.591 ms   (1.547 ms .. 1.654 ms)
std dev              184.2 μs   (133.7 μs .. 245.5 μs)
variance introduced by outliers: 71% (severely inflated)

benchmarked Countdown/Put/shallow
time                 294.9 μs   (285.9 μs .. 308.5 μs)
                     0.987 R²   (0.968 R² .. 0.998 R²)
mean                 308.5 μs   (300.8 μs .. 321.8 μs)
std dev              32.98 μs   (21.64 μs .. 46.00 μs)
variance introduced by outliers: 67% (severely inflated)

benchmarked Countdown/Put+Exc/fused-effects
time                 11.38 μs   (10.82 μs .. 12.15 μs)
                     0.976 R²   (0.949 R² .. 0.998 R²)
mean                 11.35 μs   (11.13 μs .. 11.71 μs)
std dev              893.4 ns   (559.3 ns .. 1.311 μs)
variance introduced by outliers: 51% (severely inflated)

benchmarked Countdown/Put+Exc/mtl
time                 11.19 μs   (10.81 μs .. 11.63 μs)
                     0.991 R²   (0.982 R² .. 0.997 R²)
mean                 11.27 μs   (11.10 μs .. 11.57 μs)
std dev              764.4 ns   (346.9 ns .. 1.226 μs)
variance introduced by outliers: 41% (moderately inflated)

benchmarked Countdown/Put+Exc/polysemy
time                 435.9 μs   (419.5 μs .. 457.9 μs)
                     0.982 R²   (0.962 R² .. 0.998 R²)
mean                 460.5 μs   (452.6 μs .. 478.8 μs)
std dev              38.67 μs   (24.90 μs .. 65.71 μs)
variance introduced by outliers: 54% (severely inflated)

benchmarked Countdown/Put+Exc/freer-simple
time                 1.256 ms   (1.186 ms .. 1.343 ms)
                     0.977 R²   (0.964 R² .. 0.992 R²)
mean                 1.178 ms   (1.158 ms .. 1.214 ms)
std dev              89.84 μs   (62.80 μs .. 126.6 μs)
variance introduced by outliers: 50% (moderately inflated)

benchmarked Countdown/Put+Exc/extensible-effects
time                 1.354 ms   (1.264 ms .. 1.472 ms)
                     0.944 R²   (0.880 R² .. 0.985 R²)
mean                 1.321 ms   (1.291 ms .. 1.397 ms)
std dev              151.0 μs   (85.87 μs .. 285.1 μs)
variance introduced by outliers: 68% (severely inflated)

benchmarked Countdown/Put+Exc/shallow
time                 61.33 μs   (60.34 μs .. 62.82 μs)
                     0.992 R²   (0.979 R² .. 1.000 R²)
mean                 63.32 μs   (62.21 μs .. 66.60 μs)
std dev              5.941 μs   (2.661 μs .. 12.18 μs)
variance introduced by outliers: 61% (severely inflated)

benchmarked HTTP/fused-effects
time                 9.658 μs   (9.169 μs .. 10.19 μs)
                     0.987 R²   (0.981 R² .. 0.997 R²)
mean                 9.127 μs   (9.016 μs .. 9.295 μs)
std dev              462.0 ns   (306.6 ns .. 632.7 ns)
variance introduced by outliers: 29% (moderately inflated)

benchmarked HTTP/polysemy
time                 16.12 ms   (15.35 ms .. 17.10 ms)
                     0.973 R²   (0.940 R² .. 0.994 R²)
mean                 16.73 ms   (16.26 ms .. 17.54 ms)
std dev              1.479 ms   (935.0 μs .. 2.079 ms)
variance introduced by outliers: 42% (moderately inflated)

benchmarked HTTP/extensible-effects
time                 1.757 ms   (1.662 ms .. 1.871 ms)
                     0.975 R²   (0.962 R² .. 0.988 R²)
mean                 1.774 ms   (1.724 ms .. 1.825 ms)
std dev              167.8 μs   (135.0 μs .. 219.2 μs)
variance introduced by outliers: 59% (severely inflated)

benchmarked HTTP/Deep embedding
time                 2.322 ms   (2.171 ms .. 2.522 ms)
                     0.958 R²   (0.937 R² .. 0.975 R²)
mean                 2.403 ms   (2.315 ms .. 2.528 ms)
std dev              345.2 μs   (257.2 μs .. 483.3 μs)
variance introduced by outliers: 77% (severely inflated)

benchmarked HTTP/Shallow embedding
time                 16.71 μs   (16.23 μs .. 17.42 μs)
                     0.991 R²   (0.985 R² .. 0.997 R²)
mean                 16.63 μs   (16.38 μs .. 17.05 μs)
std dev              1.055 μs   (593.9 ns .. 1.591 μs)
variance introduced by outliers: 39% (moderately inflated)

benchmarked HTTP/freer-simple
time                 1.524 ms   (1.432 ms .. 1.628 ms)
                     0.943 R²   (0.891 R² .. 0.981 R²)
mean                 1.722 ms   (1.657 ms .. 1.828 ms)
std dev              286.1 μs   (186.0 μs .. 381.8 μs)
variance introduced by outliers: 83% (severely inflated)

*** Space benchmarks (these will take some time to run) ***

Countdown

  Case                Allocated  GCs
  fused-effects              40    0
  mtl                        40    0
  polysemy                4,864    0
  freer-simple            1,096    0
  extensible-effects      1,304    0
  shallow                -3,640    0

Countdown + exc

  Case                Allocated  GCs
  fused-effects              16    0
  mtl                    -3,864    0
  polysemy                  480    0
  freer-simple              544    0
  extensible-effects        664    0
  shallow                     0    0
Benchmark effects-benchmarks: FINISH
