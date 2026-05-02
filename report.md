# Multi-Language Build Benchmark Report

## CPU Information

- **Model**: AMD EPYC 7763 64-Core Processor
- **Sockets**: 1
- **Cores per Socket**: 2
- **Logical CPUs**: 4

## Build Time (Current Run)

![Build Time](build_time.svg)

## Max Memory Usage (Current Run)

![Max RSS](max_rss.svg)

## Trend Graphs

### Python Build Time Trend

![Python Build Time Trend](python_build_time_trend.svg)

### Python Max RSS Trend

![Python Max RSS Trend](python_max_rss_trend.svg)

### C Build Time Trend

![C Build Time Trend](c_build_time_trend.svg)

### C Max RSS Trend

![C Max RSS Trend](c_max_rss_trend.svg)

### Java Build Time Trend

![Java Build Time Trend](java_build_time_trend.svg)

### Java Max RSS Trend

![Java Max RSS Trend](java_max_rss_trend.svg)

## Raw Results (Current Run)

### Python

```json
{
  "language": "Python",
  "max_rss_kb": 48880,
  "build_time_sec": 22
}
```

### C

```json
{
  "language": "C",
  "max_rss_kb": 156464,
  "build_time_sec": 57
}
```

### Java

```json
{
  "language": "Java",
  "max_rss_kb": 906200,
  "build_time_sec": 98
}
```
