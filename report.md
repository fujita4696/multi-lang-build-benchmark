# Multi-Language Build Benchmark Report

## CPU Information (Current Run)

- **Model**: AMD EPYC 9V74 80-Core Processor
- **Short Name**: EPYC 9V74 80-Core Processor
- **Sockets**: 1
- **Cores per Socket**: 2
- **Logical CPUs**: 4

## Build Time (Current Run)

![Build Time](build_time.svg)

## Max CPU Usage (Current Run)

![Max CPU](max_cpu.svg)

## Max Memory Usage (Current Run)

![Max RSS](max_rss.svg)

## Trend Graphs (Python + C + Java)

### Build Time Trend by CPU Model + Run

![Build Time Trend](build_time_cpu_trend.svg)

### Max CPU Usage Trend by CPU Model + Run

![Max CPU Usage Trend](max_cpu_cpu_trend.svg)

### Max RSS Trend by CPU Model + Run

![Max RSS Trend](max_rss_cpu_trend.svg)

## Raw Results (Current Run)

### Python

```json
{
  "language": "Python",
  "max_cpu_percent": 54,
  "max_rss_kb": 48672,
  "build_time_sec": 30
}
```

### C

```json
{
  "language": "Python",
  "max_cpu_percent": 351,
  "max_rss_kb": 157552,
  "build_time_sec": 58
}
```

### Java

```json
{
  "language": "Python",
  "max_cpu_percent": 138,
  "max_rss_kb": 921852,
  "build_time_sec": 113
}
```
