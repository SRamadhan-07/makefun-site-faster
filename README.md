# makefun-site-faster

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/SRamadhan-07/makefun-site-faster/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/SRamadhan-07/makefun-site-faster/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A byte-exact reimplementation of the makefun-site 1.0.0 static site generator that runs about 3.4× faster. The house driver (main.ts) is kept as the rules prescribe; solve.js reproduces the reference output — tag pages, build-report.txt and every static file — byte for byte, with a fused single-pass Markdown renderer, single-scan HTML escaping, per-source cards built once and shared by every render, and a hand-scanned reading-time word count. Verified identical to the reference on the practice set and on 300 generated fuzz cases.

## Run it

```sh
node main.ts
```

---

Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards
