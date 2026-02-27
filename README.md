# TALOFNS-Simulation-Data
TALOFNS – Aggregated Per-Run Summary Metrics (Table 3)

This package contains aggregated summary statistics used to populate Table 3 of the manuscript titled:
“TALOFNS: A Lightweight Trust-Aware Fog Node Selection Algorithm for Real-Time IoT Applications”.

Files:
1) Table3_Aggregated_PerRun_Summary_Metrics.csv

Definition:
For each algorithm and metric, the CSV reports:
- n_runs: number of independent runs (n=5)
- mean: arithmetic mean computed across runs
- std: sample standard deviation computed across runs
- CI95_low / CI95_high: 95% confidence interval bounds computed using the Student t-distribution:
  mean ± t_(0.975, df=4) * (std / sqrt(n))

Notes:
- The CSV provides aggregated per-run summary metrics (not raw trace logs).
- Simulation outcomes are stochastic; results are reported under the configuration described in the manuscript
