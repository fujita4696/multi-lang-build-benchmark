# Multi-Language Build Benchmark Report

## CPU Information (Current Run)

- **Model**: AMD EPYC 7763 64-Core Processor
- **Short Name**: EPYC 7763 64-Core Processor
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
  "max_cpu_percent": 91,
  "max_rss_kb": 48960,
  "build_time_sec": 20
}
```

### C

```json
{
  "language": "Python",
  "max_cpu_percent": 285,
  "max_rss_kb": 157712,
  "build_time_sec": 71
}
```

### Java

```json
{
  "language": "Python",
  "max_cpu_percent": 166,
  "max_rss_kb": 704604,
  "build_time_sec": 95
}
```
