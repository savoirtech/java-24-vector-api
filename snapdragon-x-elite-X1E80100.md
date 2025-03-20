Qualcomm SnapDragon X Elite X1E80100
===

CPU Specs:
===

```
processor       : 9
BogoMIPS        : 38.40
Features        : fp asimd aes pmull sha1 sha2 crc32 atomics fphp asimdhp cpuid asimdrdm jscvt fcma
lrcpc dcpop sha3 sm3 sm4 asimddp sha512 asimdfhm uscat ilrcpc flagm ssbs sb dcpodp flagm2 frint i8mm
bf16 rng afp rpres
CPU implementer : 0x51
CPU architecture: 8
CPU variant     : 0x1
CPU part        : 0x001
CPU revision    : 1
```


SimpleSum
```
Benchmark          (arraySize)  Mode  Cnt         Score        Error  Units
SimpleSum.arrays            64  avgt   25         7.248 ±      0.327  ns/op
SimpleSum.arrays           512  avgt   25        29.914 ±      0.540  ns/op
SimpleSum.arrays          4096  avgt   25       254.430 ±      2.778  ns/op
SimpleSum.arrays         32768  avgt   25      3303.234 ±     29.628  ns/op
SimpleSum.arrays        262144  avgt   25     26357.635 ±    200.875  ns/op
SimpleSum.arrays       2097152  avgt   25    283307.857 ±   4529.370  ns/op
SimpleSum.arrays      16777216  avgt   25   3343609.316 ±   5872.197  ns/op
SimpleSum.arrays     134217728  avgt   25  27305000.095 ± 247646.016  ns/op
SimpleSum.vectors           64  avgt   25         5.212 ±      0.044  ns/op
SimpleSum.vectors          512  avgt   25        40.208 ±      0.138  ns/op
SimpleSum.vectors         4096  avgt   25       321.360 ±      3.636  ns/op
SimpleSum.vectors        32768  avgt   25      3659.747 ±     28.911  ns/op
SimpleSum.vectors       262144  avgt   25     25882.112 ±    226.058  ns/op
SimpleSum.vectors      2097152  avgt   25    280411.634 ±   2567.822  ns/op
SimpleSum.vectors     16777216  avgt   25   3201927.906 ±  13540.028  ns/op
SimpleSum.vectors    134217728  avgt   25  26447023.665 ± 362411.485  ns/op
```

SimpleSumNoSuperWord
```
Benchmark                     (arraySize)  Mode  Cnt         Score        Error  Units
SimpleSumNoSuperWord.arrays            64  avgt   25        14.576 ±      0.023  ns/op
SimpleSumNoSuperWord.arrays           512  avgt   25        99.834 ±      0.732  ns/op
SimpleSumNoSuperWord.arrays          4096  avgt   25       788.448 ±     11.003  ns/op
SimpleSumNoSuperWord.arrays         32768  avgt   25      8231.097 ±     15.974  ns/op
SimpleSumNoSuperWord.arrays        262144  avgt   25     63052.221 ±    356.218  ns/op
SimpleSumNoSuperWord.arrays       2097152  avgt   25    638093.956 ±   5650.360  ns/op
SimpleSumNoSuperWord.arrays      16777216  avgt   25   4273947.580 ±   5872.709  ns/op
SimpleSumNoSuperWord.arrays     134217728  avgt   25  36848394.602 ± 208902.171  ns/op
SimpleSumNoSuperWord.vectors           64  avgt   25         5.963 ±      0.018  ns/op
SimpleSumNoSuperWord.vectors          512  avgt   25        41.492 ±      0.628  ns/op
SimpleSumNoSuperWord.vectors         4096  avgt   25       329.512 ±      0.812  ns/op
SimpleSumNoSuperWord.vectors        32768  avgt   25      3732.939 ±      2.794  ns/op
SimpleSumNoSuperWord.vectors       262144  avgt   25     26501.727 ±    167.861  ns/op
SimpleSumNoSuperWord.vectors      2097152  avgt   25    288576.433 ±   2927.003  ns/op
SimpleSumNoSuperWord.vectors     16777216  avgt   25   3266354.922 ±   9332.059  ns/op
SimpleSumNoSuperWord.vectors    134217728  avgt   25  27788239.442 ± 171920.355  ns/op
```

ComplexExpression
```
Benchmark                  (arraySize)  Mode  Cnt         Score        Error  Units
ComplexExpression.arrays            64  avgt   25        13.364 ±      0.028  ns/op
ComplexExpression.arrays           512  avgt   25        97.869 ±      0.590  ns/op
ComplexExpression.arrays          4096  avgt   25      1090.796 ±      5.919  ns/op
ComplexExpression.arrays         32768  avgt   25      8778.099 ±     22.862  ns/op
ComplexExpression.arrays        262144  avgt   25     72661.925 ±    255.414  ns/op
ComplexExpression.arrays       2097152  avgt   25    394695.769 ±   1558.470  ns/op
ComplexExpression.arrays      16777216  avgt   25   3581818.028 ±   7472.428  ns/op
ComplexExpression.arrays     134217728  avgt   25  29845650.230 ± 846537.550  ns/op
ComplexExpression.vectors           64  avgt   25        11.637 ±      0.201  ns/op
ComplexExpression.vectors          512  avgt   25       115.211 ±      0.028  ns/op
ComplexExpression.vectors         4096  avgt   25      1169.743 ±      0.477  ns/op
ComplexExpression.vectors        32768  avgt   25      9434.381 ±     29.531  ns/op
ComplexExpression.vectors       262144  avgt   25     70719.385 ±    594.749  ns/op
ComplexExpression.vectors      2097152  avgt   25    390692.982 ±   3312.194  ns/op
ComplexExpression.vectors     16777216  avgt   25   3475458.274 ±  18877.356  ns/op
ComplexExpression.vectors    134217728  avgt   25  29284085.870 ± 210708.504  ns/op
```

ComplexExpressionNoSuperWord
```
Benchmark                             (arraySize)  Mode  Cnt         Score        Error  Units
ComplexExpressionNoSuperWord.arrays            64  avgt   25        44.772 ±      0.300  ns/op
ComplexExpressionNoSuperWord.arrays           512  avgt   25       361.622 ±      1.761  ns/op
ComplexExpressionNoSuperWord.arrays          4096  avgt   25      2902.716 ±      7.537  ns/op
ComplexExpressionNoSuperWord.arrays         32768  avgt   25     23287.923 ±     22.412  ns/op
ComplexExpressionNoSuperWord.arrays        262144  avgt   25    186374.027 ±    310.529  ns/op
ComplexExpressionNoSuperWord.arrays       2097152  avgt   25   1531918.080 ±   4140.981  ns/op
ComplexExpressionNoSuperWord.arrays      16777216  avgt   25  12133880.473 ±  13074.682  ns/op
ComplexExpressionNoSuperWord.arrays     134217728  avgt   25  97881468.670 ± 127773.547  ns/op
ComplexExpressionNoSuperWord.vectors           64  avgt   25        11.938 ±      0.171  ns/op
ComplexExpressionNoSuperWord.vectors          512  avgt   25       117.634 ±      0.153  ns/op
ComplexExpressionNoSuperWord.vectors         4096  avgt   25      1229.378 ±      1.310  ns/op
ComplexExpressionNoSuperWord.vectors        32768  avgt   25     10160.851 ±     17.427  ns/op
ComplexExpressionNoSuperWord.vectors       262144  avgt   25     74963.819 ±    160.522  ns/op
ComplexExpressionNoSuperWord.vectors      2097152  avgt   25    401730.838 ±   2165.931  ns/op
ComplexExpressionNoSuperWord.vectors     16777216  avgt   25   3652178.075 ±  40500.783  ns/op
ComplexExpressionNoSuperWord.vectors    134217728  avgt   25  30363134.925 ± 129461.593  ns/op
```

ArrayStats
```
Benchmark           (arraySize)  Mode  Cnt          Score         Error  Units
ArrayStats.arrays            64  avgt   25        141.883 ±       1.110  ns/op
ArrayStats.arrays           512  avgt   25        442.343 ±       4.086  ns/op
ArrayStats.arrays          4096  avgt   25       2932.162 ±     117.101  ns/op
ArrayStats.arrays         32768  avgt   25      69675.146 ±     620.463  ns/op
ArrayStats.arrays        262144  avgt   25     763331.377 ±    3134.906  ns/op
ArrayStats.arrays       2097152  avgt   25    6750570.364 ±   15295.787  ns/op
ArrayStats.arrays      16777216  avgt   25   57756207.529 ± 3706081.660  ns/op
ArrayStats.arrays     134217728  avgt   25  506867050.291 ± 4195552.728  ns/op
ArrayStats.vectors           64  avgt   25        111.710 ±       0.197  ns/op
ArrayStats.vectors          512  avgt   25        182.240 ±       0.527  ns/op
ArrayStats.vectors         4096  avgt   25        725.628 ±       1.290  ns/op
ArrayStats.vectors        32768  avgt   25       5327.005 ±      12.573  ns/op
ArrayStats.vectors       262144  avgt   25      37757.626 ±      78.804  ns/op
ArrayStats.vectors      2097152  avgt   25     346084.032 ±     516.323  ns/op
ArrayStats.vectors     16777216  avgt   25    2539949.075 ±   12704.836  ns/op
ArrayStats.vectors    134217728  avgt   25   20258899.916 ±   90946.903  ns/op
```
