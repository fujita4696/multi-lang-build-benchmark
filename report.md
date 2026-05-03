# Multi-Language Build Benchmark Report

## CPU Information (Current Run)

- **Model**: Intel(R) Xeon(R) Platinum 8370C CPU @ 2.80GHz
- **Short Name**: Xeon Plat 8370C
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

### Max RSS Trend by CPU Model + Run

![Max RSS Trend](max_rss_cpu_trend.svg)

## Raw Results (Current Run)

### Python

```json
{
  "language": "Python",
  "max_cpu_percent": 89,
  "max_rss_kb": 48584,
  "build_time_sec": 24
}
```

### C

```json
{
  "language": "Python",
  "max_cpu_percent": 353,
  "max_rss_kb": 156600,
  "build_time_sec": 44
}
```

### Java

```json
{
  "language": "Python",
  "max_cpu_percent": 159,
  "max_rss_kb": 759964,
  "build_time_sec": 104
}
```
