*** Time benchmarks ***
benchmarked Countdown/Put/fused-effects
time                 13.48 μs   (13.08 μs .. 14.01 μs)
                     0.990 R²   (0.979 R² .. 0.997 R²)
mean                 13.19 μs   (13.00 μs .. 13.45 μs)
std dev              710.4 ns   (543.4 ns .. 1.055 μs)
variance introduced by outliers: 32% (moderately inflated)

benchmarked Countdown/Put/mtl
time                 6.784 μs   (6.623 μs .. 6.954 μs)
                     0.994 R²   (0.990 R² .. 0.997 R²)
mean                 7.029 μs   (6.910 μs .. 7.246 μs)
std dev              530.6 ns   (325.3 ns .. 961.6 ns)
variance introduced by outliers: 47% (moderately inflated)

benchmarked Countdown/Put/polysemy
time                 2.959 ms   (2.893 ms .. 3.073 ms)
                     0.994 R²   (0.988 R² .. 0.998 R²)
mean                 2.889 ms   (2.856 ms .. 2.933 ms)
std dev              129.6 μs   (101.9 μs .. 171.6 μs)
variance introduced by outliers: 23% (moderately inflated)

benchmarked Countdown/Put/freer-simple
time                 1.718 ms   (1.690 ms .. 1.751 ms)
                     0.998 R²   (0.997 R² .. 0.999 R²)
mean                 1.737 ms   (1.721 ms .. 1.765 ms)
std dev              67.22 μs   (42.57 μs .. 96.72 μs)
variance introduced by outliers: 19% (moderately inflated)

benchmarked Countdown/Put/extensible-effects
time                 1.922 ms   (1.869 ms .. 1.972 ms)
                     0.997 R²   (0.995 R² .. 0.998 R²)
mean                 1.906 ms   (1.888 ms .. 1.927 ms)
std dev              67.32 μs   (53.09 μs .. 87.90 μs)
variance introduced by outliers: 18% (moderately inflated)

benchmarked Countdown/Put/shallow
time                 348.2 μs   (344.0 μs .. 352.1 μs)
                     0.997 R²   (0.992 R² .. 0.999 R²)
mean                 353.8 μs   (350.5 μs .. 359.1 μs)
std dev              14.01 μs   (9.612 μs .. 19.97 μs)
variance introduced by outliers: 20% (moderately inflated)

benchmarked Countdown/Put+Exc/fused-effects
time                 6.439 μs   (6.323 μs .. 6.545 μs)
                     0.997 R²   (0.995 R² .. 0.999 R²)
mean                 6.468 μs   (6.399 μs .. 6.538 μs)
std dev              239.1 ns   (197.8 ns .. 290.7 ns)
variance introduced by outliers: 18% (moderately inflated)

benchmarked Countdown/Put+Exc/mtl
time                 11.48 μs   (11.16 μs .. 11.83 μs)
                     0.996 R²   (0.994 R² .. 0.998 R²)
mean                 11.44 μs   (11.33 μs .. 11.57 μs)
std dev              402.2 ns   (314.7 ns .. 518.9 ns)
variance introduced by outliers: 18% (moderately inflated)

benchmarked Countdown/Put+Exc/polysemy
time                 706.7 μs   (613.8 μs .. 788.3 μs)
                     0.946 R²   (0.917 R² .. 0.992 R²)
mean                 556.7 μs   (541.5 μs .. 588.6 μs)
std dev              71.38 μs   (44.59 μs .. 121.7 μs)
variance introduced by outliers: 72% (severely inflated)

benchmarked Countdown/Put+Exc/freer-simple
time                 1.533 ms   (1.460 ms .. 1.625 ms)
                     0.968 R²   (0.947 R² .. 0.984 R²)
mean                 1.778 ms   (1.716 ms .. 1.856 ms)
std dev              238.5 μs   (183.0 μs .. 353.3 μs)
variance introduced by outliers: 78% (severely inflated)

benchmarked Countdown/Put+Exc/extensible-effects
time                 1.882 ms   (1.674 ms .. 2.178 ms)
                     0.944 R²   (0.913 R² .. 0.995 R²)
mean                 1.772 ms   (1.725 ms .. 1.860 ms)
std dev              214.8 μs   (122.9 μs .. 333.2 μs)
variance introduced by outliers: 72% (severely inflated)

benchmarked Countdown/Put+Exc/shallow
time                 64.36 μs   (61.88 μs .. 68.30 μs)
                     0.988 R²   (0.978 R² .. 0.998 R²)
mean                 65.35 μs   (64.59 μs .. 66.28 μs)
std dev              3.067 μs   (2.355 μs .. 4.412 μs)
variance introduced by outliers: 27% (moderately inflated)

benchmarked HTTP/fused-effects
time                 6.475 μs   (6.246 μs .. 6.760 μs)
                     0.992 R²   (0.986 R² .. 0.997 R²)
mean                 6.540 μs   (6.452 μs .. 6.632 μs)
std dev              309.7 ns   (266.9 ns .. 366.8 ns)
variance introduced by outliers: 27% (moderately inflated)

benchmarked HTTP/polysemy
time                 20.55 ms   (18.50 ms .. 22.47 ms)
                     0.974 R²   (0.956 R² .. 0.998 R²)
mean                 19.78 ms   (19.35 ms .. 20.47 ms)
std dev              1.272 ms   (888.6 μs .. 1.774 ms)
variance introduced by outliers: 27% (moderately inflated)

benchmarked HTTP/extensible-effects
time                 2.073 ms   (1.973 ms .. 2.160 ms)
                     0.967 R²   (0.936 R² .. 0.986 R²)
mean                 2.311 ms   (2.224 ms .. 2.430 ms)
std dev              338.7 μs   (215.9 μs .. 467.4 μs)
variance introduced by outliers: 78% (severely inflated)

benchmarked HTTP/Deep embedding
time                 3.962 ms   (3.535 ms .. 4.334 ms)
                     0.952 R²   (0.935 R² .. 0.972 R²)
mean                 3.029 ms   (2.907 ms .. 3.220 ms)
std dev              458.8 μs   (345.0 μs .. 569.9 μs)
variance introduced by outliers: 78% (severely inflated)

benchmarked HTTP/Shallow embedding
time                 21.67 μs   (21.27 μs .. 22.00 μs)
                     0.997 R²   (0.996 R² .. 0.998 R²)
mean                 21.65 μs   (21.39 μs .. 21.93 μs)
std dev              902.0 ns   (747.6 ns .. 1.139 μs)
variance introduced by outliers: 22% (moderately inflated)

benchmarked HTTP/freer-simple
time                 1.924 ms   (1.897 ms .. 1.959 ms)
                     0.997 R²   (0.995 R² .. 0.998 R²)
mean                 2.038 ms   (2.014 ms .. 2.070 ms)
std dev              91.39 μs   (73.85 μs .. 113.5 μs)
variance introduced by outliers: 24% (moderately inflated)

*** Space benchmarks (these will take some time to run) ***

Countdown

  Case                Allocated  GCs
  fused-effects              40    0
  mtl                        40    0
  polysemy                1,880    0
  freer-simple            1,096    0
  extensible-effects      1,304    0
  shallow                -3,640    0

Countdown + exc

  Case                Allocated  GCs
  fused-effects              16    0
  mtl                        16    0
  polysemy                  480    0
  freer-simple              544    0
  extensible-effects        664    0
  shallow                     0    0
Benchmark effects-benchmarks: FINISH