# Working Configs

## Statistics
- Tested: 8939
- Answered at least one pass: 29
- Passed every pass: 16
- Published (>= 3/3): 16
- Content-verified: 16
- Throughput sampled: 0
- Updated: 2026-10-12 07:29 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 2115ms | 374ms | - | 67.3 |
| 2 | EPODONIOS | 3/3 | 2703ms | 301ms | - | 67.2 |
| 3 | EPODONIOS | 3/3 | 2178ms | 742ms | - | 65.4 |
| 4 | EPODONIOS | 3/3 | 4719ms | 438ms | - | 64.7 |
| 5 | EPODONIOS | 3/3 | 2977ms | 985ms | - | 63.9 |
| 6 | EPODONIOS | 3/3 | 2943ms | 1026ms | - | 63.9 |
| 7 | EPODONIOS | 3/3 | 2327ms | 1844ms | - | 63.8 |
| 8 | EPODONIOS | 3/3 | 5460ms | 611ms | - | 63.6 |
| 9 | EPODONIOS | 3/3 | 4312ms | 818ms | - | 63.4 |
| 10 | EPODONIOS | 3/3 | 3164ms | 1418ms | - | 63.2 |
| 11 | EPODONIOS | 3/3 | 4080ms | 994ms | - | 63.1 |
| 12 | EPODONIOS | 3/3 | 4267ms | 963ms | - | 63.1 |
| 13 | EPODONIOS | 3/3 | 4191ms | 1263ms | - | 62.7 |
| 14 | EPODONIOS | 3/3 | 4606ms | 1172ms | - | 62.6 |
| 15 | EPODONIOS | 3/3 | 4407ms | 1254ms | - | 62.6 |

## How this was measured

Each config is checked over several passes spaced in time, through a core
process shared by its chunk. A pass is two 204 connectivity checks plus,
on the final pass, a real HTTPS body whose exact length is verified.
Throughput is the median of fixed-length windows measured after a warm-up,
not an average over the whole transfer.

Score is a weighted mean of four normalised components: the Wilson lower
bound of the success rate, median latency, latency stability (mean absolute
deviation around the median) and throughput. Components without data are
dropped and the remaining weights renormalised.

Results depend on your ISP and the time of day. Re-test before relying on a link.
