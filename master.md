*** Time benchmarks ***
benchmarked Countdown/Put/fused-effects
time                 6.339 μs   (6.206 μs .. 6.519 μs)
                     0.995 R²   (0.990 R² .. 0.998 R²)
mean                 6.178 μs   (6.115 μs .. 6.259 μs)
std dev              238.2 ns   (191.0 ns .. 335.7 ns)
variance introduced by outliers: 20% (moderately inflated)

benchmarked Countdown/Put/mtl
time                 6.200 μs   (6.076 μs .. 6.346 μs)
                     0.996 R²   (0.994 R² .. 0.998 R²)
mean                 6.282 μs   (6.210 μs .. 6.381 μs)
std dev              286.7 ns   (242.2 ns .. 344.8 ns)
variance introduced by outliers: 26% (moderately inflated)

benchmarked Countdown/Put/polysemy
time                 2.377 ms   (2.337 ms .. 2.412 ms)
                     0.998 R²   (0.997 R² .. 0.999 R²)
mean                 2.317 ms   (2.295 ms .. 2.341 ms)
std dev              77.31 μs   (60.52 μs .. 107.4 μs)
variance introduced by outliers: 16% (moderately inflated)

benchmarked Countdown/Put/freer-simple
time                 1.643 ms   (1.623 ms .. 1.669 ms)
                     0.998 R²   (0.997 R² .. 0.999 R²)
mean                 1.629 ms   (1.618 ms .. 1.641 ms)
std dev              39.06 μs   (31.08 μs .. 49.68 μs)

benchmarked Countdown/Put/extensible-effects
time                 1.812 ms   (1.786 ms .. 1.834 ms)
                     0.998 R²   (0.997 R² .. 0.999 R²)
mean                 1.826 ms   (1.808 ms .. 1.844 ms)
std dev              60.12 μs   (49.00 μs .. 75.38 μs)
variance introduced by outliers: 15% (moderately inflated)

benchmarked Countdown/Put/shallow
time                 331.2 μs   (324.6 μs .. 341.2 μs)
                     0.995 R²   (0.987 R² .. 0.999 R²)
mean                 329.4 μs   (326.8 μs .. 333.3 μs)
std dev              10.96 μs   (7.163 μs .. 18.20 μs)
variance introduced by outliers: 15% (moderately inflated)

benchmarked Countdown/Put+Exc/fused-effects
time                 10.90 μs   (10.72 μs .. 11.07 μs)
                     0.998 R²   (0.997 R² .. 0.999 R²)
mean                 10.92 μs   (10.84 μs .. 11.02 μs)
std dev              315.4 ns   (255.8 ns .. 401.7 ns)
variance introduced by outliers: 13% (moderately inflated)

benchmarked Countdown/Put+Exc/mtl
time                 11.01 μs   (10.79 μs .. 11.22 μs)
                     0.998 R²   (0.996 R² .. 0.999 R²)
mean                 10.97 μs   (10.88 μs .. 11.06 μs)
std dev              315.9 ns   (264.5 ns .. 375.1 ns)
variance introduced by outliers: 13% (moderately inflated)

benchmarked Countdown/Put+Exc/polysemy
time                 514.7 μs   (510.3 μs .. 519.0 μs)
                     0.999 R²   (0.998 R² .. 1.000 R²)
mean                 510.3 μs   (506.4 μs .. 515.9 μs)
std dev              15.83 μs   (11.07 μs .. 23.53 μs)
variance introduced by outliers: 15% (moderately inflated)

benchmarked Countdown/Put+Exc/freer-simple
time                 1.400 ms   (1.368 ms .. 1.424 ms)
                     0.994 R²   (0.983 R² .. 0.998 R²)
mean                 1.456 ms   (1.433 ms .. 1.498 ms)
std dev              102.8 μs   (67.97 μs .. 173.9 μs)
variance introduced by outliers: 46% (moderately inflated)

benchmarked Countdown/Put+Exc/extensible-effects
time                 1.565 ms   (1.549 ms .. 1.597 ms)
                     0.998 R²   (0.996 R² .. 1.000 R²)
mean                 1.570 ms   (1.559 ms .. 1.585 ms)
std dev              41.56 μs   (29.88 μs .. 59.68 μs)
variance introduced by outliers: 11% (moderately inflated)

benchmarked Countdown/Put+Exc/shallow
time                 66.37 μs   (64.81 μs .. 68.64 μs)
                     0.994 R²   (0.990 R² .. 0.998 R²)
mean                 66.38 μs   (65.62 μs .. 67.17 μs)
std dev              2.669 μs   (2.184 μs .. 3.448 μs)
variance introduced by outliers: 22% (moderately inflated)

benchmarked HTTP/fused-effects
time                 11.00 μs   (10.80 μs .. 11.19 μs)
                     0.997 R²   (0.996 R² .. 0.998 R²)
mean                 11.06 μs   (10.95 μs .. 11.19 μs)
std dev              433.4 ns   (349.9 ns .. 538.4 ns)
variance introduced by outliers: 22% (moderately inflated)

benchmarked HTTP/polysemy
time                 18.31 ms   (18.03 ms .. 18.55 ms)
                     0.999 R²   (0.999 R² .. 1.000 R²)
mean                 18.56 ms   (18.38 ms .. 19.06 ms)
std dev              708.0 μs   (283.8 μs .. 1.318 ms)
variance introduced by outliers: 13% (moderately inflated)

benchmarked HTTP/extensible-effects
time                 2.145 ms   (2.125 ms .. 2.167 ms)
                     0.998 R²   (0.996 R² .. 0.999 R²)
mean                 2.110 ms   (2.092 ms .. 2.133 ms)
std dev              65.65 μs   (49.92 μs .. 99.65 μs)
variance introduced by outliers: 13% (moderately inflated)

benchmarked HTTP/Deep embedding
time                 2.437 ms   (2.404 ms .. 2.476 ms)
                     0.998 R²   (0.995 R² .. 0.999 R²)
mean                 2.472 ms   (2.447 ms .. 2.501 ms)
std dev              92.35 μs   (74.25 μs .. 115.5 μs)
variance introduced by outliers: 18% (moderately inflated)

benchmarked HTTP/Shallow embedding
time                 19.99 μs   (19.64 μs .. 20.31 μs)
                     0.998 R²   (0.996 R² .. 0.999 R²)
mean                 19.95 μs   (19.77 μs .. 20.16 μs)
std dev              699.8 ns   (590.5 ns .. 853.5 ns)
variance introduced by outliers: 17% (moderately inflated)

benchmarked HTTP/freer-simple
time                 1.879 ms   (1.847 ms .. 1.917 ms)
                     0.996 R²   (0.992 R² .. 0.999 R²)
mean                 1.930 ms   (1.912 ms .. 1.960 ms)
std dev              76.87 μs   (54.93 μs .. 131.0 μs)
variance introduced by outliers: 22% (moderately inflated)

*** Space benchmarks (these will take some time to run) ***

Countdown

  Case                Allocated  GCs
  fused-effects              40    0
  mtl                        40    0
  polysemy                1,032    0
  freer-simple            4,944    0
  extensible-effects      1,304    0
  shallow                   232    0

Countdown + exc

  Case                Allocated  GCs
  fused-effects           3,888    0
  mtl                        16    0
  polysemy                  480    0
  freer-simple              544    0
  extensible-effects        664    0
  shallow                     0    0
Benchmark effects-benchmarks: FINISH
