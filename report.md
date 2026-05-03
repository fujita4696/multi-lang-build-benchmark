# Multi-Language Build Benchmark Report

## CPU Information (Current Run)

- **Model**: AMD EPYC 9V74 80-Core Processor
- **Short Name**: EPYC 9V74 80-Core Processor
- **Sockets**: 1
- **Cores per Socket**: 2
- **Logical CPUs**: 4

## Build Time (Current Run)

![Build Time](build_time.svg)

## Max Memory Usage (Current Run)

![Max RSS](max_rss.svg)

## Max CPU Usage (Current Run)

![Max CPU](max_cpu.svg)

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
  "max_cpu_percent": 73,
  "max_rss_kb": 48824,
  "build_time_sec": 20
}
```

### C

```json
{
  "language": "Python",
  "max_cpu_percent": 357,
  "max_rss_kb": 156496,
  "build_time_sec": 45
}
```

### Java

```json
{
  "language": "Python",
  "max_cpu_percent": 162,
  "max_rss_kb": 878208,
  "build_time_sec": 97
}
```
