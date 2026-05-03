# Multi-Language Build Benchmark Report

## Recently CPU Information

- **Model**: AMD EPYC 7763 64-Core Processor
- **Sockets**: 1
- **Cores per Socket**: 2
- **Logical CPUs**: 4

## Build Time (Current Run)

![Build Time](build_time.svg)

## Max Memory Usage (Current Run)

![Max RSS](max_rss.svg)

## CPU Model + Run Based Trend Graphs

### Python

#### Build Time by CPU Model + Run

![Python Build Time by CPU Model + Run](python_build_time_cpu_trend.svg)

#### Max RSS by CPU Model + Run

![Python Max RSS by CPU Model + Run](python_max_rss_cpu_trend.svg)

### C

#### Build Time by CPU Model + Run

![C Build Time by CPU Model + Run](c_build_time_cpu_trend.svg)

#### Max RSS by CPU Model + Run

![C Max RSS by CPU Model + Run](c_max_rss_cpu_trend.svg)

### Java

#### Build Time by CPU Model + Run

![Java Build Time by CPU Model + Run](java_build_time_cpu_trend.svg)

#### Max RSS by CPU Model + Run

![Java Max RSS by CPU Model + Run](java_max_rss_cpu_trend.svg)

## Raw Results (Current Run)

### Python

```json
{
  "language": "Python",
  "max_rss_kb": 48852,
  "build_time_sec": 29
}
```

### C

```json
{
  "language": "C",
  "max_rss_kb": 156632,
  "build_time_sec": 49
}
```

### Java

```json
{
  "language": "Java",
  "max_rss_kb": 718572,
  "build_time_sec": 96
}
```
