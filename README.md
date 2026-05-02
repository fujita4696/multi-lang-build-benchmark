# Multi-Language Build Benchmark
This repository benchmarks build performance for:

| Language | Sample OSS Project | Code Size | Build Command |
| --- | --- | --- | --- |
| Python | ``pallets/flask`` | approx. 12,000 lines | ``python ``setup.py ``build`` |
| C | ``curl/curl`` | approx. 20,000 lines | ``./configure ``&& ``make`` |
| Java | ``spring-projects/spring-petclinic`` | approx. 15,000 lines | ``mvn ``-B ``package`` |

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

