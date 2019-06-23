*** Time benchmarks ***
benchmarked Countdown/Put/fused-effects
time                 6.076 μs   (6.014 μs .. 6.191 μs)
                     0.994 R²   (0.984 R² .. 0.999 R²)
mean                 6.101 μs   (6.049 μs .. 6.212 μs)
std dev              242.5 ns   (134.2 ns .. 428.4 ns)
variance introduced by outliers: 20% (moderately inflated)

benchmarked Countdown/Put/mtl
time                 6.064 μs   (5.959 μs .. 6.273 μs)
                     0.994 R²   (0.984 R² .. 1.000 R²)
mean                 6.004 μs   (5.972 μs .. 6.130 μs)
std dev              180.5 ns   (59.51 ns .. 391.4 ns)
variance introduced by outliers: 13% (moderately inflated)

benchmarked Countdown/Put/polysemy
time                 2.225 ms   (2.162 ms .. 2.287 ms)
                     0.986 R²   (0.976 R² .. 0.993 R²)
mean                 2.541 ms   (2.450 ms .. 2.689 ms)
std dev              380.3 μs   (238.0 μs .. 586.0 μs)
variance introduced by outliers: 80% (severely inflated)

benchmarked Countdown/Put/freer-simple
time                 1.414 ms   (1.369 ms .. 1.471 ms)
                     0.989 R²   (0.978 R² .. 0.997 R²)
mean                 1.442 ms   (1.407 ms .. 1.492 ms)
std dev              140.1 μs   (94.88 μs .. 190.3 μs)
variance introduced by outliers: 62% (severely inflated)

benchmarked Countdown/Put/extensible-effects
time                 1.535 ms   (1.509 ms .. 1.570 ms)
                     0.993 R²   (0.984 R² .. 0.998 R²)
mean                 1.606 ms   (1.576 ms .. 1.682 ms)
std dev              152.7 μs   (76.13 μs .. 281.1 μs)
variance introduced by outliers: 62% (severely inflated)

benchmarked Countdown/Put/shallow
time                 305.6 μs   (295.2 μs .. 319.2 μs)
                     0.988 R²   (0.972 R² .. 0.998 R²)
mean                 308.3 μs   (302.4 μs .. 318.2 μs)
std dev              25.13 μs   (16.99 μs .. 33.81 μs)
variance introduced by outliers: 52% (severely inflated)

benchmarked Countdown/Put+Exc/fused-effects
time                 11.08 μs   (10.68 μs .. 11.62 μs)
                     0.989 R²   (0.975 R² .. 0.998 R²)
mean                 11.21 μs   (11.05 μs .. 11.55 μs)
std dev              744.8 ns   (459.8 ns .. 1.120 μs)
variance introduced by outliers: 41% (moderately inflated)

benchmarked Countdown/Put+Exc/mtl
time                 11.26 μs   (10.90 μs .. 11.85 μs)
                     0.989 R²   (0.980 R² .. 0.998 R²)
mean                 11.23 μs   (11.09 μs .. 11.55 μs)
std dev              667.3 ns   (381.7 ns .. 1.048 μs)
variance introduced by outliers: 37% (moderately inflated)

benchmarked Countdown/Put+Exc/polysemy
time                 457.1 μs   (442.6 μs .. 478.8 μs)
                     0.989 R²   (0.979 R² .. 0.998 R²)
mean                 450.6 μs   (445.3 μs .. 463.3 μs)
std dev              24.32 μs   (13.32 μs .. 45.36 μs)
variance introduced by outliers: 31% (moderately inflated)

benchmarked Countdown/Put+Exc/freer-simple
time                 1.227 ms   (1.152 ms .. 1.341 ms)
                     0.976 R²   (0.964 R² .. 0.998 R²)
mean                 1.171 ms   (1.156 ms .. 1.201 ms)
std dev              73.42 μs   (43.76 μs .. 121.4 μs)
variance introduced by outliers: 38% (moderately inflated)

benchmarked Countdown/Put+Exc/extensible-effects
time                 1.307 ms   (1.283 ms .. 1.342 ms)
                     0.993 R²   (0.984 R² .. 0.999 R²)
mean                 1.300 ms   (1.288 ms .. 1.325 ms)
std dev              54.45 μs   (29.31 μs .. 86.65 μs)
variance introduced by outliers: 22% (moderately inflated)

benchmarked Countdown/Put+Exc/shallow
time                 58.85 μs   (57.86 μs .. 60.92 μs)
                     0.989 R²   (0.966 R² .. 1.000 R²)
mean                 58.71 μs   (58.21 μs .. 60.75 μs)
std dev              2.755 μs   (608.4 ns .. 6.164 μs)
variance introduced by outliers: 27% (moderately inflated)

benchmarked HTTP/fused-effects
time                 11.20 μs   (10.90 μs .. 11.74 μs)
                     0.983 R²   (0.963 R² .. 0.998 R²)
mean                 11.35 μs   (11.14 μs .. 11.68 μs)
std dev              1.007 μs   (683.7 ns .. 1.332 μs)
variance introduced by outliers: 57% (severely inflated)

benchmarked HTTP/polysemy
time                 15.75 ms   (14.98 ms .. 16.50 ms)
                     0.983 R²   (0.962 R² .. 0.999 R²)
mean                 15.69 ms   (15.40 ms .. 16.40 ms)
std dev              1.060 ms   (536.7 μs .. 1.897 ms)
variance introduced by outliers: 32% (moderately inflated)

benchmarked HTTP/extensible-effects
time                 1.817 ms   (1.736 ms .. 1.940 ms)
                     0.980 R²   (0.963 R² .. 0.996 R²)
mean                 1.771 ms   (1.741 ms .. 1.844 ms)
std dev              145.2 μs   (81.40 μs .. 259.0 μs)
variance introduced by outliers: 52% (severely inflated)

benchmarked HTTP/Deep embedding
time                 2.053 ms   (1.970 ms .. 2.147 ms)
                     0.987 R²   (0.975 R² .. 0.996 R²)
mean                 2.031 ms   (2.004 ms .. 2.081 ms)
std dev              129.6 μs   (75.63 μs .. 201.3 μs)
variance introduced by outliers: 39% (moderately inflated)

benchmarked HTTP/Shallow embedding
time                 16.87 μs   (16.29 μs .. 17.55 μs)
                     0.991 R²   (0.979 R² .. 0.999 R²)
mean                 16.60 μs   (16.43 μs .. 17.00 μs)
std dev              861.0 ns   (403.4 ns .. 1.623 μs)
variance introduced by outliers: 30% (moderately inflated)

benchmarked HTTP/freer-simple
time                 1.604 ms   (1.514 ms .. 1.698 ms)
                     0.984 R²   (0.974 R² .. 0.997 R²)
mean                 1.565 ms   (1.545 ms .. 1.604 ms)
std dev              87.86 μs   (59.71 μs .. 132.3 μs)
variance introduced by outliers: 35% (moderately inflated)

*** Space benchmarks (these will take some time to run) ***

Countdown

  Case                Allocated  GCs
  fused-effects              40    0
  mtl                        40    0
  polysemy                5,712    0
  freer-simple            1,096    0
  extensible-effects      1,304    0
  shallow                   232    0

Countdown + exc

  Case                Allocated  GCs
  fused-effects              16    0
  mtl                    -3,864    0
  polysemy                  480    0
  freer-simple              544    0
  extensible-effects      4,560    0
  shallow                 3,856    0
Benchmark effects-benchmarks: FINISH
