AMD Ryzen 9 9950x
===


CPU Specs:
===

```
processor	: 0
vendor_id	: AuthenticAMD
cpu family	: 26
model		: 68
model name	: AMD Ryzen 9 9950X 16-Core Processor
stepping	: 0
microcode	: 0xb404023
cpu MHz		: 3617.325
cache size	: 1024 KB
physical id	: 0
siblings	: 32
core id		: 15
cpu cores	: 16
apicid		: 31
initial apicid	: 31
fpu		: yes
fpu_exception	: yes
cpuid level	: 16
wp		: yes
flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2
ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good amd_lbr_v2 nopl nonstop_tsc cpuid
extd_apicid aperfmperf rapl pni pclmulqdq monitor ssse3 fma cx16 sse4_1 sse4_2 movbe popcnt aes xsave avx
f16c rdrand lahf_lm cmp_legacy svm extapic cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw ibs skinit
wdt tce topoext perfctr_core perfctr_nb bpext perfctr_llc mwaitx cpb cat_l3 cdp_l3 hw_pstate ssbd mba
perfmon_v2 ibrs ibpb stibp ibrs_enhanced vmmcall fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid
cqm rdt_a avx512f avx512dq rdseed adx smap avx512ifma clflushopt clwb avx512cd sha_ni avx512bw avx512vl
xsaveopt xsavec xgetbv1 xsaves cqm_llc cqm_occup_llc cqm_mbm_total cqm_mbm_local user_shstk avx_vnni
avx512_bf16 clzero irperf xsaveerptr rdpru wbnoinvd cppc arat npt lbrv svm_lock nrip_save tsc_scale
vmcb_clean flushbyasid decodeassists pausefilter pfthreshold avic v_vmsave_vmload vgif x2avic v_spec_ctrl
vnmi avx512vbmi umip pku ospke avx512_vbmi2 gfni vaes vpclmulqdq avx512_vnni avx512_bitalg avx512_vpopcntdq
 rdpid bus_lock_detect movdiri movdir64b overflow_recov succor smca fsrm avx512_vp2intersect flush_l1d
bugs		: sysret_ss_attrs spectre_v1 spectre_v2 spec_store_bypass
bogomips	: 8584.39
TLB size	: 192 4K pages
clflush size	: 64
cache_alignment	: 64
address sizes	: 48 bits physical, 48 bits virtual
power management: ts ttp tm hwpstate cpb eff_freq_ro [13] [14]
```


SimpleSum
```
Benchmark          (arraySize)  Mode  Cnt         Score       Error  Units
SimpleSum.arrays            64  avgt   25         5.600 ±     0.087  ns/op
SimpleSum.arrays           512  avgt   25        20.642 ±     0.249  ns/op
SimpleSum.arrays          4096  avgt   25       146.131 ±     4.897  ns/op
SimpleSum.arrays         32768  avgt   25      1818.321 ±    76.107  ns/op
SimpleSum.arrays        262144  avgt   25     24735.943 ±   580.826  ns/op
SimpleSum.arrays       2097152  avgt   25    186041.022 ±  3056.283  ns/op
SimpleSum.arrays      16777216  avgt   25   5657439.764 ±  7862.904  ns/op
SimpleSum.arrays     134217728  avgt   25  49111862.541 ± 81476.003  ns/op
SimpleSum.vectors           64  avgt   25         3.818 ±     0.050  ns/op
SimpleSum.vectors          512  avgt   25        27.112 ±     0.253  ns/op
SimpleSum.vectors         4096  avgt   25       215.087 ±    18.518  ns/op
SimpleSum.vectors        32768  avgt   25      2333.535 ±   153.409  ns/op
SimpleSum.vectors       262144  avgt   25     25442.170 ±   309.703  ns/op
SimpleSum.vectors      2097152  avgt   25    186714.015 ±  2878.447  ns/op
SimpleSum.vectors     16777216  avgt   25   5624798.445 ±  3536.730  ns/op
SimpleSum.vectors    134217728  avgt   25  49046563.416 ± 44056.786  ns/op
```

SimpleSumNoSuperWord
```
Benchmark                     (arraySize)  Mode  Cnt         Score        Error  Units
SimpleSumNoSuperWord.arrays            64  avgt   25        14.445 ±      0.155  ns/op
SimpleSumNoSuperWord.arrays           512  avgt   25       104.756 ±      0.261  ns/op
SimpleSumNoSuperWord.arrays          4096  avgt   25       928.259 ±     95.049  ns/op
SimpleSumNoSuperWord.arrays         32768  avgt   25     10741.149 ±   1487.684  ns/op
SimpleSumNoSuperWord.arrays        262144  avgt   25     78204.518 ±   1295.675  ns/op
SimpleSumNoSuperWord.arrays       2097152  avgt   25    474780.120 ±   5586.357  ns/op
SimpleSumNoSuperWord.arrays      16777216  avgt   25   5787441.771 ±  28621.893  ns/op
SimpleSumNoSuperWord.arrays     134217728  avgt   25  50224350.667 ± 202537.290  ns/op
SimpleSumNoSuperWord.vectors           64  avgt   25         3.807 ±      0.050  ns/op
SimpleSumNoSuperWord.vectors          512  avgt   25        26.866 ±      0.220  ns/op
SimpleSumNoSuperWord.vectors         4096  avgt   25       225.594 ±     20.723  ns/op
SimpleSumNoSuperWord.vectors        32768  avgt   25      1946.914 ±     66.478  ns/op
SimpleSumNoSuperWord.vectors       262144  avgt   25     25916.566 ±    499.381  ns/op
SimpleSumNoSuperWord.vectors      2097152  avgt   25    184202.024 ±   2275.961  ns/op
SimpleSumNoSuperWord.vectors     16777216  avgt   25   5627075.033 ±   5695.608  ns/op
SimpleSumNoSuperWord.vectors    134217728  avgt   25  49092245.309 ±  49418.393  ns/op
```

ComplexExpression
```
Benchmark                  (arraySize)  Mode  Cnt         Score        Error  Units
ComplexExpression.arrays            64  avgt   25        13.398 ±      0.135  ns/op
ComplexExpression.arrays           512  avgt   25        39.966 ±      0.472  ns/op
ComplexExpression.arrays          4096  avgt   25       242.905 ±      7.318  ns/op
ComplexExpression.arrays         32768  avgt   25      1922.940 ±     54.458  ns/op
ComplexExpression.arrays        262144  avgt   25     26262.674 ±    380.812  ns/op
ComplexExpression.arrays       2097152  avgt   25    197464.489 ±   2781.672  ns/op
ComplexExpression.arrays      16777216  avgt   25   5444371.389 ±   2146.216  ns/op
ComplexExpression.arrays     134217728  avgt   25  49212241.442 ±  28693.864  ns/op
ComplexExpression.vectors           64  avgt   25         4.855 ±      0.137  ns/op
ComplexExpression.vectors          512  avgt   25        32.513 ±      0.516  ns/op
ComplexExpression.vectors         4096  avgt   25       247.478 ±     10.829  ns/op
ComplexExpression.vectors        32768  avgt   25      2137.897 ±    100.628  ns/op
ComplexExpression.vectors       262144  avgt   25     26555.607 ±    466.807  ns/op
ComplexExpression.vectors      2097152  avgt   25    210501.169 ±   4729.537  ns/op
ComplexExpression.vectors     16777216  avgt   25   5510624.078 ±  16761.358  ns/op
ComplexExpression.vectors    134217728  avgt   25  49457576.798 ± 328508.808  ns/op
```

ComplexExpressionNoSuperWord
```
Benchmark                             (arraySize)  Mode  Cnt         Score        Error  Units
ComplexExpressionNoSuperWord.arrays            64  avgt   25        41.579 ±      0.269  ns/op
ComplexExpressionNoSuperWord.arrays           512  avgt   25       329.601 ±      3.668  ns/op
ComplexExpressionNoSuperWord.arrays          4096  avgt   25      2605.873 ±     25.031  ns/op
ComplexExpressionNoSuperWord.arrays         32768  avgt   25     20999.102 ±    216.643  ns/op
ComplexExpressionNoSuperWord.arrays        262144  avgt   25    168656.528 ±   1889.220  ns/op
ComplexExpressionNoSuperWord.arrays       2097152  avgt   25   1360747.343 ±  18669.855  ns/op
ComplexExpressionNoSuperWord.arrays      16777216  avgt   25  10872239.074 ±  20525.829  ns/op
ComplexExpressionNoSuperWord.arrays     134217728  avgt   25  87363168.362 ± 230188.414  ns/op
ComplexExpressionNoSuperWord.vectors           64  avgt   25         4.639 ±      0.071  ns/op
ComplexExpressionNoSuperWord.vectors          512  avgt   25        32.343 ±      0.521  ns/op
ComplexExpressionNoSuperWord.vectors         4096  avgt   25       257.727 ±      8.433  ns/op
ComplexExpressionNoSuperWord.vectors        32768  avgt   25      2131.920 ±     82.987  ns/op
ComplexExpressionNoSuperWord.vectors       262144  avgt   25     26212.961 ±    521.303  ns/op
ComplexExpressionNoSuperWord.vectors      2097152  avgt   25    206928.863 ±   6996.359  ns/op
ComplexExpressionNoSuperWord.vectors     16777216  avgt   25   5493995.722 ±  11757.069  ns/op
ComplexExpressionNoSuperWord.vectors    134217728  avgt   25  49511284.504 ±  62652.112  ns/op
```

ArrayStats
```
Benchmark           (arraySize)  Mode  Cnt          Score          Error  Units
ArrayStats.arrays            64  avgt   25         38.581 ±        0.310  ns/op
ArrayStats.arrays           512  avgt   25        212.634 ±       15.893  ns/op
ArrayStats.arrays          4096  avgt   25       1814.133 ±      115.577  ns/op
ArrayStats.arrays         32768  avgt   25      15838.151 ±      449.539  ns/op
ArrayStats.arrays        262144  avgt   25     963129.900 ±    11461.205  ns/op
ArrayStats.arrays       2097152  avgt   25    7727454.048 ±   123708.801  ns/op
ArrayStats.arrays      16777216  avgt   25   62474792.032 ±   734136.122  ns/op
ArrayStats.arrays     134217728  avgt   25  504252258.024 ± 10400544.664  ns/op
ArrayStats.vectors           64  avgt   25         19.411 ±        0.208  ns/op
ArrayStats.vectors          512  avgt   25         42.748 ±        0.373  ns/op
ArrayStats.vectors         4096  avgt   25        270.534 ±        3.766  ns/op
ArrayStats.vectors        32768  avgt   25       2270.910 ±       36.513  ns/op
ArrayStats.vectors       262144  avgt   25      21249.466 ±       87.750  ns/op
ArrayStats.vectors      2097152  avgt   25     212619.118 ±     2471.727  ns/op
ArrayStats.vectors     16777216  avgt   25    4597135.550 ±   293666.544  ns/op
ArrayStats.vectors    134217728  avgt   25   37904807.211 ±   401942.362  ns/op
```
