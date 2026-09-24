# Working Configs

## Statistics
- Tested: 9179
- Answered at least one pass: 31
- Passed every pass: 13
- Published (>= 3/3): 13
- Content-verified: 13
- Throughput sampled: 0
- Updated: 2026-09-24 18:53 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 1197ms | 128ms | - | 73.5 |
| 2 | ⚡ b2n.ir/v2ray-configs | 565 | 3/3 | 1490ms | 103ms | - | 73.4 |
| 3 | EPODONIOS | 3/3 | 1176ms | 143ms | - | 73.2 |
| 4 | EPODONIOS | 3/3 | 1530ms | 347ms | - | 68.8 |
| 5 | EPODONIOS | 3/3 | 927ms | 1233ms | - | 68.3 |
| 6 | EPODONIOS | 3/3 | 855ms | 1901ms | - | 68.2 |
| 7 | EPODONIOS | 3/3 | 1995ms | 445ms | - | 67.0 |
| 8 | EPODONIOS | 3/3 | 1421ms | 934ms | - | 66.6 |
| 9 | EPODONIOS | 3/3 | 1667ms | 858ms | - | 66.1 |
| 10 | EPODONIOS | 3/3 | 2490ms | 502ms | - | 65.9 |
| 11 | EPODONIOS | 3/3 | 2318ms | 816ms | - | 65.0 |
| 12 | EPODONIOS | 3/3 | 3261ms | 1100ms | - | 63.5 |
| 13 | EPODONIOS | 3/3 | 3519ms | 1037ms | - | 63.4 |

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
