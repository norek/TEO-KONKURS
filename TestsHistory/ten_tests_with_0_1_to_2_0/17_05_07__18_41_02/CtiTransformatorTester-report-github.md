``` ini

BenchmarkDotNet=v0.10.5, OS=Windows 10.0.15063
Processor=Intel Core i7-4710MQ CPU 2.50GHz (Haswell), ProcessorCount=8
Frequency=2435773 Hz, Resolution=410.5473 ns, Timer=TSC
  [Host]            : Clr 4.0.30319.42000, 32bit LegacyJIT-v4.7.2046.0
  LegacyJit-Clr-X86 : Clr 4.0.30319.42000, 32bit LegacyJIT-v4.7.2046.0

Job=LegacyJit-Clr-X86  Jit=LegacyJit  Platform=X86  
Runtime=Clr  

```
 |                    Method |      Mean |     Error |    StdDev | Scaled |     Gen 0 | Allocated |
 |-------------------------- |----------:|----------:|----------:|-------:|----------:|----------:|
 |  Test_v_0_1_transformator | 37.434 ms | 0.0965 ms | 0.0806 ms |   1.00 | 4908.3333 |  16.31 MB |
 |  Test_v_0_2_transformator | 11.229 ms | 0.0284 ms | 0.0266 ms |   0.30 | 2409.3750 |   7.69 MB |
 |  Test_v_0_3_transformator |  9.684 ms | 0.0211 ms | 0.0198 ms |   0.26 | 1839.5833 |   5.91 MB |
 |  Test_v_0_4_transformator |  9.709 ms | 0.0340 ms | 0.0318 ms |   0.26 | 1835.4167 |   5.91 MB |
 |  Test_v_0_5_transformator |  5.489 ms | 0.0147 ms | 0.0130 ms |   0.15 | 1556.2500 |   4.88 MB |
 |  Test_v_0_6_transformator |  5.142 ms | 0.0223 ms | 0.0198 ms |   0.14 | 2020.8333 |   6.29 MB |
 |  Test_v_0_7_transformator |  3.786 ms | 0.0093 ms | 0.0087 ms |   0.10 | 1991.6667 |    6.1 MB |
 |  Test_v_0_8_transformator |  3.298 ms | 0.0070 ms | 0.0065 ms |   0.09 | 1408.0729 |   4.33 MB |
 |  Test_v_0_9_transformator |  2.453 ms | 0.0065 ms | 0.0060 ms |   0.07 | 1396.6146 |   4.33 MB |
 | Test_v_0_10_transformator |  2.443 ms | 0.0092 ms | 0.0086 ms |   0.07 | 1401.8229 |   4.33 MB |
 | Test_v_0_11_transformator |  2.438 ms | 0.0074 ms | 0.0069 ms |   0.07 | 1399.7396 |   4.33 MB |
 | Test_v_0_12_transformator |  2.544 ms | 0.0108 ms | 0.0101 ms |   0.07 | 1522.9167 |   4.69 MB |
 |  Test_v_1_1_transformator |  2.400 ms | 0.0107 ms | 0.0100 ms |   0.06 | 1407.0313 |   4.33 MB |
 |  Test_v_1_2_transformator |  2.427 ms | 0.0098 ms | 0.0076 ms |   0.06 | 1408.0729 |   4.33 MB |
 |  Test_v_2_0_transformator |  2.982 ms | 0.0085 ms | 0.0075 ms |   0.08 | 1404.9479 |   4.33 MB |