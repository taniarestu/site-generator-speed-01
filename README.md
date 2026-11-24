# site-generator-speed-01

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/taniarestu/site-generator-speed-01/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/taniarestu/site-generator-speed-01/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A faster drop-in for makefun-site 1.0.0: it builds the same static sites, byte for byte, at about 2.6x the speed of the house baseline on the practice set. One dependency-free ES module (`solve.js`, `run(input)`) re-implements the reference pipeline — front matter, permalinks, Markdown, collections, tags, layouts, report — with fused single-pass rendering, batched HTML escaping, and per-case caches. No code generation, no network, no clock, no randomness.

## Run it

```sh
MAKEFUN_INPUT_DIR=<input dir with cases.json> MAKEFUN_OUTPUT_DIR=<output dir> node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
