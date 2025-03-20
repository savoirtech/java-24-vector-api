Apple M4 BaseModel
===

CPU Specs:
===

```
% system_profiler SPHardwareDataType
Hardware:

    Hardware Overview:

      Model Name: Mac mini
      Model Identifier: Mac16,10
      Model Number: MU9D3VC/A
      Chip: Apple M4
      Total Number of Cores: 10 (4 performance and 6 efficiency)
      Memory: 16 GB
      System Firmware Version: 11881.81.4
```

```
% sysctl -a machdep.cpu
machdep.cpu.cores_per_package: 10
machdep.cpu.core_count: 10
machdep.cpu.logical_per_package: 10
machdep.cpu.thread_count: 10
machdep.cpu.brand_string: Apple M4
```

SimpleSum
```
Benchmark          (arraySize)  Mode  Cnt         Score       Error  Units
SimpleSum.arrays            64  avgt   25         5.500 ±     0.002  ns/op
SimpleSum.arrays           512  avgt   25        26.363 ±     0.005  ns/op
SimpleSum.arrays          4096  avgt   25       196.715 ±     0.041  ns/op
SimpleSum.arrays         32768  avgt   25      3303.210 ±     1.092  ns/op
SimpleSum.arrays        262144  avgt   25    167923.552 ±    82.809  ns/op
SimpleSum.arrays       2097152  avgt   25    242459.944 ±  2907.701  ns/op
SimpleSum.arrays      16777216  avgt   25   2868336.194 ±  5745.640  ns/op
SimpleSum.arrays     134217728  avgt   25  23149604.561 ± 44935.858  ns/op
SimpleSum.vectors           64  avgt   25         4.264 ±     0.001  ns/op
SimpleSum.vectors          512  avgt   25        28.299 ±     0.026  ns/op
SimpleSum.vectors         4096  avgt   25       255.869 ±     0.279  ns/op
SimpleSum.vectors        32768  avgt   25      4081.471 ±     1.575  ns/op
SimpleSum.vectors       262144  avgt   25    164464.920 ±   120.666  ns/op
SimpleSum.vectors      2097152  avgt   25    240874.851 ±  2910.091  ns/op
SimpleSum.vectors     16777216  avgt   25   2866729.212 ±  4759.103  ns/op
SimpleSum.vectors    134217728  avgt   25  23168153.567 ± 48745.591  ns/op
```

SimpleSumNoSuperWord
```
Benchmark                     (arraySize)  Mode  Cnt         Score       Error  Units
SimpleSumNoSuperWord.arrays            64  avgt   25        13.114 ±     0.002  ns/op
SimpleSumNoSuperWord.arrays           512  avgt   25        96.468 ±     0.056  ns/op
SimpleSumNoSuperWord.arrays          4096  avgt   25       766.489 ±     0.102  ns/op
SimpleSumNoSuperWord.arrays         32768  avgt   25      7077.397 ±     2.239  ns/op
SimpleSumNoSuperWord.arrays        262144  avgt   25    194596.874 ±   526.248  ns/op
SimpleSumNoSuperWord.arrays       2097152  avgt   25    468825.750 ±   390.244  ns/op
SimpleSumNoSuperWord.arrays      16777216  avgt   25   3748815.819 ±  1507.444  ns/op
SimpleSumNoSuperWord.arrays     134217728  avgt   25  30192580.788 ±  5118.896  ns/op
SimpleSumNoSuperWord.vectors           64  avgt   25         4.485 ±     0.001  ns/op
SimpleSumNoSuperWord.vectors          512  avgt   25        28.328 ±     0.021  ns/op
SimpleSumNoSuperWord.vectors         4096  avgt   25       256.732 ±     0.070  ns/op
SimpleSumNoSuperWord.vectors        32768  avgt   25      4085.032 ±     0.956  ns/op
SimpleSumNoSuperWord.vectors       262144  avgt   25    166906.800 ±   195.511  ns/op
SimpleSumNoSuperWord.vectors      2097152  avgt   25    242086.813 ±  2285.679  ns/op
SimpleSumNoSuperWord.vectors     16777216  avgt   25   2891239.149 ±   951.467  ns/op
SimpleSumNoSuperWord.vectors    134217728  avgt   25  23269152.081 ± 13186.531  ns/op
```

ComplexExpression
```
Benchmark                  (arraySize)  Mode  Cnt         Score        Error  Units
ComplexExpression.arrays            64  avgt   25        16.724 ±      0.007  ns/op
ComplexExpression.arrays           512  avgt   25       112.020 ±      0.991  ns/op
ComplexExpression.arrays          4096  avgt   25       903.174 ±     29.254  ns/op
ComplexExpression.arrays         32768  avgt   25      7050.270 ±     94.785  ns/op
ComplexExpression.arrays        262144  avgt   25    371457.963 ±    112.572  ns/op
ComplexExpression.arrays       2097152  avgt   25    442885.858 ±    145.422  ns/op
ComplexExpression.arrays      16777216  avgt   25   3913994.328 ± 147134.392  ns/op
ComplexExpression.arrays     134217728  avgt   25  32375395.998 ±   3135.084  ns/op
ComplexExpression.vectors           64  avgt   25        14.692 ±      0.004  ns/op
ComplexExpression.vectors          512  avgt   25       117.987 ±      0.290  ns/op
ComplexExpression.vectors         4096  avgt   25       887.636 ±      5.512  ns/op
ComplexExpression.vectors        32768  avgt   25      7589.495 ±     51.007  ns/op
ComplexExpression.vectors       262144  avgt   25    379561.066 ±    493.871  ns/op
ComplexExpression.vectors      2097152  avgt   25    504010.736 ±    141.165  ns/op
ComplexExpression.vectors     16777216  avgt   25   3757397.112 ± 180054.608  ns/op
ComplexExpression.vectors    134217728  avgt   25  28417053.716 ±   5946.564  ns/op
```

ComplexExpressionNoSuperWord
```
Benchmark                             (arraySize)  Mode  Cnt          Score        Error  Units
ComplexExpressionNoSuperWord.arrays            64  avgt   25         58.195 ±      0.342  ns/op
ComplexExpressionNoSuperWord.arrays           512  avgt   25        480.075 ±     19.050  ns/op
ComplexExpressionNoSuperWord.arrays          4096  avgt   25       3930.206 ±     36.636  ns/op
ComplexExpressionNoSuperWord.arrays         32768  avgt   25      27415.824 ±     33.213  ns/op
ComplexExpressionNoSuperWord.arrays        262144  avgt   25     398582.702 ±    723.675  ns/op
ComplexExpressionNoSuperWord.arrays       2097152  avgt   25    1757025.329 ±  15702.367  ns/op
ComplexExpressionNoSuperWord.arrays      16777216  avgt   25   14016857.279 ±   6308.343  ns/op
ComplexExpressionNoSuperWord.arrays     134217728  avgt   25  112273733.277 ±  28273.314  ns/op
ComplexExpressionNoSuperWord.vectors           64  avgt   25         14.614 ±      0.032  ns/op
ComplexExpressionNoSuperWord.vectors          512  avgt   25        117.821 ±      0.021  ns/op
ComplexExpressionNoSuperWord.vectors         4096  avgt   25        890.827 ±      6.802  ns/op
ComplexExpressionNoSuperWord.vectors        32768  avgt   25       7697.905 ±     44.077  ns/op
ComplexExpressionNoSuperWord.vectors       262144  avgt   25     377736.418 ±    208.109  ns/op
ComplexExpressionNoSuperWord.vectors      2097152  avgt   25     503904.906 ±    181.597  ns/op
ComplexExpressionNoSuperWord.vectors     16777216  avgt   25    3756278.565 ± 179965.672  ns/op
ComplexExpressionNoSuperWord.vectors    134217728  avgt   25   28407028.631 ±   2628.066  ns/op
```

ArrayStats
```
Benchmark           (arraySize)  Mode  Cnt          Score         Error  Units
ArrayStats.arrays            64  avgt   25         22.662 ±       1.079  ns/op
ArrayStats.arrays           512  avgt   25        206.063 ±      16.837  ns/op
ArrayStats.arrays          4096  avgt   25       2136.981 ±      35.192  ns/op
ArrayStats.arrays         32768  avgt   25      22563.881 ±     743.513  ns/op
ArrayStats.arrays        262144  avgt   25     548555.508 ±    6815.500  ns/op
ArrayStats.arrays       2097152  avgt   25    6810573.305 ±   14705.388  ns/op
ArrayStats.arrays      16777216  avgt   25   61683361.263 ± 1816374.452  ns/op
ArrayStats.arrays     134217728  avgt   25  504842991.722 ± 1671395.445  ns/op
ArrayStats.vectors           64  avgt   25          9.184 ±       1.567  ns/op
ArrayStats.vectors          512  avgt   25         66.896 ±       0.005  ns/op
ArrayStats.vectors         4096  avgt   25        481.176 ±       0.169  ns/op
ArrayStats.vectors        32768  avgt   25       4287.050 ±       4.767  ns/op
ArrayStats.vectors       262144  avgt   25      32026.725 ±     132.983  ns/op
ArrayStats.vectors      2097152  avgt   25     258071.296 ±     477.969  ns/op
ArrayStats.vectors     16777216  avgt   25    2106596.070 ±   14921.970  ns/op
ArrayStats.vectors    134217728  avgt   25   17031651.054 ±   92872.915  ns/op
```
