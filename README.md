# Working Configs

## Statistics
- Tested: 8138
- Answered at least one pass: 23
- Passed every pass: 12
- Published (>= 3/3): 12
- Content-verified: 12
- Throughput sampled: 0
- Updated: 2026-10-11 05:53 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 2330ms | 185ms | - | 69.5 |
| 2 | EPODONIOS | 3/3 | 1056ms | 644ms | - | 68.8 |
| 3 | EPODONIOS | 3/3 | 2736ms | 270ms | - | 67.6 |
| 4 | EPODONIOS | 3/3 | 1884ms | 498ms | - | 66.9 |
| 5 | EPODONIOS | 3/3 | 2706ms | 579ms | - | 65.3 |
| 6 | Reality, Яндекс [V.O.I.D] | 3/3 | 2108ms | 878ms | - | 65.2 |
| 7 | EPODONIOS | 3/3 | 2866ms | 1178ms | - | 63.7 |
| 8 | EPODONIOS | 3/3 | 3399ms | 1212ms | - | 63.2 |
| 9 | EPODONIOS | 3/3 | 5013ms | 841ms | - | 63.0 |
| 10 | EPODONIOS | 3/3 | 4707ms | 917ms | - | 63.0 |
| 11 | EPODONIOS | 3/3 | 4038ms | 1143ms | - | 62.9 |
| 12 | Reality, Rutube [V.O.I.D] | 3/3 | 4502ms | 1267ms | - | 62.5 |

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
