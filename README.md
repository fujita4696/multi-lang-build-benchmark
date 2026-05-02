# Multi-Language Build Benchmark
This repository benchmarks build performance for:

- Python (Flask)
- C (curl)
- Java (Spring PetClinic)

The GitHub Actions workflow:

- Clones each project
- Measures:
  - Build time
  - Max memory usage (Max RSS)
  - CPU info
- Generates SVG graphs
- Produces a Markdown report
- Accumulates history and trend graphs

Run manually from GitHub Actions → "Run workflow".

