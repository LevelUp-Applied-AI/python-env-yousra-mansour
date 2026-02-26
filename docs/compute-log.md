==================================================
SYSTEM INFORMATION
==================================================
OS:         Windows 11
Version:    10.0.26200
Machine:    AMD64
Processor:  Intel64 Family 6 Model 140 Stepping 1, GenuineIntel
Python:     3.14.0 (tags/v3.14.0:ebf955d, Oct  7 2025, 10:15:03) [MSC v.1944 64 bit (AMD64)]

Benchmark 1 — sum(range(5,000,000))
  Result:  12,499,997,500,000
  Time:    0.0448 seconds

Benchmark 2 — list comprehension (n=1,000,000)
  First 5: [0, 1, 4, 9, 16]
  Time:    0.0615 seconds

Benchmark 3 — string join (n=100,000)
  Length:  588,889 characters
  Time:    0.0103 seconds

==================================================
SUMMARY
==================================================
  sum benchmark:    0.0448s
  list benchmark:   0.0615s
  string benchmark: 0.0103s


## RAM

Total RAM: 35.6 GB GB