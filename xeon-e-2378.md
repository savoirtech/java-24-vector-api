Intel Xeon E-2378
===


CPU Specs:
===

```
processor	: 0
vendor_id	: GenuineIntel
cpu family	: 6
model		: 167
model name	: Intel(R) Xeon(R) E-2378 CPU @ 2.60GHz
stepping	: 1
microcode	: 0x63
cpu MHz		: 800.000
cache size	: 16384 KB
physical id	: 0
siblings	: 16
core id		: 0
cpu cores	: 8
apicid		: 0
initial apicid	: 0
fpu		: yes
fpu_exception	: yes
cpuid level	: 27
wp		: yes
flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36
clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc
art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf
tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx smx est tm2 ssse3 sdbg fma
cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave
avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb ssbd ibrs ibpb stibp
ibrs_enhanced tpr_shadow flexpriority ept vpid ept_ad fsgsbase tsc_adjust bmi1
avx2 smep bmi2 erms invpcid mpx avx512f avx512dq rdseed adx smap avx512ifma
clflushopt intel_pt avx512cd sha_ni avx512bw avx512vl xsaveopt xsavec xgetbv1 xsaves
dtherm arat pln pts hwp hwp_act_window hwp_epp hwp_pkg_req vnmi avx512vbmi umip pku ospke
avx512_vbmi2 gfni vaes vpclmulqdq avx512_vnni avx512_bitalg avx512_vpopcntdq rdpid fsrm
md_clear flush_l1d arch_capabilities
vmx flags	: vnmi preemption_timer posted_intr invvpid ept_x_only ept_ad ept_1gb
flexpriority apicv tsc_offset vtpr mtf vapic ept vpid unrestricted_guest vapic_reg vid ple
shadow_vmcs pml ept_mode_based_exec tsc_scaling
bugs		: spectre_v1 spectre_v2 spec_store_bypass swapgs mmio_stale_data retbleed
eibrs_pbrsb gds bhi
bogomips	: 5184.00
clflush size	: 64
cache_alignment	: 64
address sizes	: 39 bits physical, 48 bits virtual
power management:
```

SimpleSum
```
Benchmark          (arraySize)  Mode  Cnt         Score         Error  Units
SimpleSum.arrays            64  avgt   25        14.739 ±       0.008  ns/op
SimpleSum.arrays           512  avgt   25        45.668 ±       0.004  ns/op
SimpleSum.arrays          4096  avgt   25       841.041 ±     602.200  ns/op
SimpleSum.arrays         32768  avgt   25      5574.510 ±     444.420  ns/op
SimpleSum.arrays        262144  avgt   25     85193.279 ±    1440.210  ns/op
SimpleSum.arrays       2097152  avgt   25    932851.529 ±   15753.083  ns/op
SimpleSum.arrays      16777216  avgt   25   9186763.478 ±    7284.348  ns/op
SimpleSum.arrays     134217728  avgt   25  76605208.191 ±  636390.656  ns/op
SimpleSum.vectors           64  avgt   25         7.232 ±       0.003  ns/op
SimpleSum.vectors          512  avgt   25        54.946 ±       0.187  ns/op
SimpleSum.vectors         4096  avgt   25       479.792 ±       0.454  ns/op
SimpleSum.vectors        32768  avgt   25      6619.429 ±    1086.239  ns/op
SimpleSum.vectors       262144  avgt   25     81617.457 ±    1852.533  ns/op
SimpleSum.vectors      2097152  avgt   25    910626.920 ±    9801.197  ns/op
SimpleSum.vectors     16777216  avgt   25   9555248.483 ±   88952.764  ns/op
SimpleSum.vectors    134217728  avgt   25  79854665.287 ± 1457736.806  ns/op
```

SimpleSumNoSuperWord
```
Benchmark                     (arraySize)  Mode  Cnt         Score        Error  Units
SimpleSumNoSuperWord.arrays            64  avgt   25        33.489 ±      0.019  ns/op
SimpleSumNoSuperWord.arrays           512  avgt   25       396.188 ±      0.009  ns/op
SimpleSumNoSuperWord.arrays          4096  avgt   25      3545.053 ±      2.310  ns/op
SimpleSumNoSuperWord.arrays         32768  avgt   25     29537.496 ±   1685.405  ns/op
SimpleSumNoSuperWord.arrays        262144  avgt   25    235820.323 ±   3457.393  ns/op
SimpleSumNoSuperWord.arrays       2097152  avgt   25   1371219.192 ±   7923.252  ns/op
SimpleSumNoSuperWord.arrays      16777216  avgt   25  12222206.103 ±  60594.864  ns/op
SimpleSumNoSuperWord.arrays     134217728  avgt   25  98386711.008 ± 551976.471  ns/op
SimpleSumNoSuperWord.vectors           64  avgt   25         7.243 ±      0.018  ns/op
SimpleSumNoSuperWord.vectors          512  avgt   25        52.372 ±      0.036  ns/op
SimpleSumNoSuperWord.vectors         4096  avgt   25       484.810 ±      0.695  ns/op
SimpleSumNoSuperWord.vectors        32768  avgt   25      6481.476 ±    950.805  ns/op
SimpleSumNoSuperWord.vectors       262144  avgt   25     83512.860 ±   2640.089  ns/op
SimpleSumNoSuperWord.vectors      2097152  avgt   25    924674.682 ±  15443.534  ns/op
SimpleSumNoSuperWord.vectors     16777216  avgt   25   9597707.610 ± 134626.512  ns/op
SimpleSumNoSuperWord.vectors    134217728  avgt   25  78878268.541 ± 669181.516  ns/op
```

ComplexExpression
```
Benchmark                  (arraySize)  Mode  Cnt         Score         Error  Units
ComplexExpression.arrays            64  avgt   25        35.227 ±       0.005  ns/op
ComplexExpression.arrays           512  avgt   25       181.565 ±       0.003  ns/op
ComplexExpression.arrays          4096  avgt   25      2193.803 ±    1508.383  ns/op
ComplexExpression.arrays         32768  avgt   25     11607.380 ±    3108.887  ns/op
ComplexExpression.arrays        262144  avgt   25     93080.041 ±    5176.074  ns/op
ComplexExpression.arrays       2097152  avgt   25    941820.772 ±   11383.353  ns/op
ComplexExpression.arrays      16777216  avgt   25   9230106.425 ±   69090.710  ns/op
ComplexExpression.arrays     134217728  avgt   25  76263327.304 ±  765917.269  ns/op
ComplexExpression.vectors           64  avgt   25        16.975 ±       0.001  ns/op
ComplexExpression.vectors          512  avgt   25       136.982 ±       0.005  ns/op
ComplexExpression.vectors         4096  avgt   25      2168.297 ±    1527.491  ns/op
ComplexExpression.vectors        32768  avgt   25     11805.389 ±    2078.670  ns/op
ComplexExpression.vectors       262144  avgt   25     90305.668 ±    5214.943  ns/op
ComplexExpression.vectors      2097152  avgt   25    929207.045 ±   15052.443  ns/op
ComplexExpression.vectors     16777216  avgt   25   9275991.243 ±  117392.027  ns/op
ComplexExpression.vectors    134217728  avgt   25  75498722.122 ± 1043162.170  ns/op
```

ComplexExpressionNoSuperWord
```
Benchmark                             (arraySize)  Mode  Cnt          Score        Error  Units
ComplexExpressionNoSuperWord.arrays            64  avgt   25        112.215 ±      0.009  ns/op
ComplexExpressionNoSuperWord.arrays           512  avgt   25        928.453 ±      0.146  ns/op
ComplexExpressionNoSuperWord.arrays          4096  avgt   25       7412.637 ±      1.250  ns/op
ComplexExpressionNoSuperWord.arrays         32768  avgt   25      60504.307 ±   1380.207  ns/op
ComplexExpressionNoSuperWord.arrays        262144  avgt   25     495615.243 ±   7420.743  ns/op
ComplexExpressionNoSuperWord.arrays       2097152  avgt   25    3678967.689 ±   2316.724  ns/op
ComplexExpressionNoSuperWord.arrays      16777216  avgt   25   29702013.860 ±  10080.490  ns/op
ComplexExpressionNoSuperWord.arrays     134217728  avgt   25  237698404.193 ±  85744.797  ns/op
ComplexExpressionNoSuperWord.vectors           64  avgt   25         16.976 ±      0.001  ns/op
ComplexExpressionNoSuperWord.vectors          512  avgt   25        137.001 ±      0.008  ns/op
ComplexExpressionNoSuperWord.vectors         4096  avgt   25       1092.102 ±      1.108  ns/op
ComplexExpressionNoSuperWord.vectors        32768  avgt   25      11282.646 ±   3412.486  ns/op
ComplexExpressionNoSuperWord.vectors       262144  avgt   25     102023.512 ±   7466.729  ns/op
ComplexExpressionNoSuperWord.vectors      2097152  avgt   25     930267.126 ±   5359.077  ns/op
ComplexExpressionNoSuperWord.vectors     16777216  avgt   25    9351845.956 ± 101798.180  ns/op
ComplexExpressionNoSuperWord.vectors    134217728  avgt   25   75490340.921 ± 688483.494  ns/op
```

ArrayStats
```
Benchmark           (arraySize)  Mode  Cnt          Score          Error  Units
ArrayStats.arrays            64  avgt   25         96.607 ±        1.000  ns/op
ArrayStats.arrays           512  avgt   25        596.310 ±       11.407  ns/op
ArrayStats.arrays          4096  avgt   25       4823.197 ±      138.118  ns/op
ArrayStats.arrays         32768  avgt   25     175888.836 ±      531.419  ns/op
ArrayStats.arrays        262144  avgt   25    1657860.085 ±    50108.515  ns/op
ArrayStats.arrays       2097152  avgt   25   13129644.379 ±   434694.293  ns/op
ArrayStats.arrays      16777216  avgt   25  110198824.754 ±   636939.401  ns/op
ArrayStats.arrays     134217728  avgt   25  874283637.496 ± 19701977.971  ns/op
ArrayStats.vectors           64  avgt   25         36.682 ±        0.007  ns/op
ArrayStats.vectors          512  avgt   25         96.377 ±        0.015  ns/op
ArrayStats.vectors         4096  avgt   25        707.772 ±        0.120  ns/op
ArrayStats.vectors        32768  avgt   25       6623.923 ±        6.583  ns/op
ArrayStats.vectors       262144  avgt   25      62954.623 ±     3852.355  ns/op
ArrayStats.vectors      2097152  avgt   25     535494.242 ±     1546.725  ns/op
ArrayStats.vectors     16777216  avgt   25    6226629.073 ±    28868.123  ns/op
ArrayStats.vectors    134217728  avgt   25   51972797.706 ±   546543.218  ns/op
```
