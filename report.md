# Multi-Language Build Benchmark Report

## Current CPU Information

- **Model**: Intel(R) Xeon(R) Platinum 8370C CPU @ 2.80GHz
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
  "max_rss_kb": 48688,
  "build_time_sec": 20
}
```

### C

```json
{
  "language": "C",
  "max_rss_kb": 156476,
  "build_time_sec": 49
}
```

### Java

```json
{
  "language": "Java",
  "max_rss_kb": 819852,
  "build_time_sec": 99
}
```
