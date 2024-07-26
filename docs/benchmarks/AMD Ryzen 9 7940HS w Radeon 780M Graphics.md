# Benchmark Report
> Generated by [`@nestia/benchmark`](https://github.com/samchon/nestia)

  - Specifications
    - CPU: AMD Ryzen 9 7940HS w/ Radeon 780M Graphics     
    - RAM: 31 GB
    - NodeJS Version: v20.10.0
    - Backend Server: 1 core / 1 thread
  - Arguments
    - Count: 1,024
    - Threads: 4
    - Simultaneous: 32
  - Time
    - Start: 2024-07-15T15:34:52.096Z
    - Complete: 2024-07-15T15:34:52.825Z
    - Elapsed: 729 ms

Type | Count | Success | Mean. | Stdev. | Minimum | Maximum
----|----|----|----|----|----|----
Total | 1,052 | 1,052 | 20.39 | 8.57 | 3 | 89

> Unit: milliseconds

## Endpoints
Type | Count | Success | Mean. | Stdev. | Minimum | Maximum
----|----|----|----|----|----|----
GET /monitors/system | 507 | 507 | 20.6 | 8.72 | 5 | 87
GET /monitors/health | 545 | 545 | 20.19 | 8.43 | 3 | 89

> Unit: milliseconds

## Failures
Method | Path | Count | Failures
-------|------|-------|----------