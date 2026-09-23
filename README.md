# Working Configs

## Statistics
- Tested: 9180
- Answered at least one pass: 22
- Passed every pass: 14
- Published (>= 3/3): 14
- Content-verified: 14
- Throughput sampled: 0
- Updated: 2026-09-23 16:48 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | ⚡ b2n.ir/v2ray-configs | 878 | 3/3 | 1072ms | 36ms | - | 78.2 |
| 2 | ⚡ b2n.ir/v2ray-configs | 268 | 3/3 | 1287ms | 215ms | - | 71.2 |
| 3 | EPODONIOS | 3/3 | 1971ms | 222ms | - | 69.4 |
| 4 | EPODONIOS | 3/3 | 1501ms | 375ms | - | 68.6 |
| 5 | EPODONIOS | 3/3 | 3606ms | 184ms | - | 68.3 |
| 6 | EPODONIOS | 3/3 | 1311ms | 712ms | - | 67.5 |
| 7 | EPODONIOS | 3/3 | 1398ms | 775ms | - | 67.1 |
| 8 | ⚡ b2n.ir/v2ray-configs | 990 | 3/3 | 1733ms | 596ms | - | 66.8 |
| 9 | EPODONIOS | 3/3 | 1270ms | 1200ms | - | 66.7 |
| 10 | EPODONIOS | 3/3 | 2108ms | 1211ms | - | 64.6 |
| 11 | EPODONIOS | 3/3 | 2339ms | 989ms | - | 64.6 |
| 12 | ⚡ b2n.ir/v2ray-configs | 116 | 3/3 | 2273ms | 1122ms | - | 64.5 |
| 13 | EPODONIOS | 3/3 | 2797ms | 923ms | - | 64.2 |
| 14 | EPODONIOS | 3/3 | 3381ms | 1403ms | - | 63.0 |

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
