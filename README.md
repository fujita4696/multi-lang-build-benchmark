# Multi-Language Build Benchmark
This repository benchmarks build performance for:

| Language | Sample OSS Project | Code Size | Build Command |
| --- | --- | --- | --- |
| Python | <img src="https://avatars.githubusercontent.com/pallets?s=40" width="20" /> [`pallets/flask`](https://github.com/pallets/flask) | approx. 12,000 lines | ``python ``setup.py ``build`` |
| C | <img src="https://avatars.githubusercontent.com/u/16928085?s=40" width="20" /> [`curl/curl`](https://github.com/curl/curl) | approx. 20,000 lines | ``./configure ``&& ``make`` |
| Java | <img src="https://avatars.githubusercontent.com/u/317776?s=40" width="20" /> [`spring-projects/spring-petclinic`](https://github.com/spring-projects/spring-petclinic) | approx. 15,000 lines | ``mvn ``-B ``package`` |

The GitHub Actions workflow:

- Clones each project
- Measures:
  - Build time
  - Max CPU Usage
  - Max memory usage (Max RSS)
- Generates SVG graphs
- Produces a Markdown report
- Accumulates history and trend graphs

Run manually from GitHub Actions → "Run workflow".

