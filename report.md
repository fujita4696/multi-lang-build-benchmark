# Multi-Language Build Benchmark Report

## Recently CPU Information

- **Model**: AMD EPYC 9V74 80-Core Processor
- **Sockets**: 1
- **Cores per Socket**: 2
- **Logical CPUs**: 4

## Build Time (Current Run)

![Build Time](build_time.svg)

## Max Memory Usage (Current Run)

![Max RSS](max_rss.svg)

## CPU Model Based Trend Graphs

### Python Build Time by CPU Model

![Python Build Time by CPU Model](python_build_time_cpu_trend.svg)

### Python Max RSS by CPU Model

![Python Max RSS by CPU Model](python_max_rss_cpu_trend.svg)

### C Build Time by CPU Model

![C Build Time by CPU Model](c_build_time_cpu_trend.svg)

### C Max RSS by CPU Model

![C Max RSS by CPU Model](c_max_rss_cpu_trend.svg)

### Java Build Time by CPU Model

![Java Build Time by CPU Model](java_build_time_cpu_trend.svg)

### Java Max RSS by CPU Model

![Java Max RSS by CPU Model](java_max_rss_cpu_trend.svg)

## Raw Results (Current Run)

### Python

```json
{
  "language": "Python",
  "max_rss_kb": 49112,
  "build_time_sec": 22
}
```

### C

```json
{
  "language": "C",
  "max_rss_kb": 156484,
  "build_time_sec": 51
}
```

### Java

```json
{
  "language": "Java",
  "max_rss_kb": 721860,
  "build_time_sec": 106
}
```
