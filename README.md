# Working Configs

## Statistics
- Tested: 9206
- Answered at least one pass: 11
- Passed every pass: 5
- Published (>= 3/3): 5
- Content-verified: 5
- Throughput sampled: 0
- Updated: 2026-09-28 20:53 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | XHTTP, Яндекс [V.O.I.D] | 3/3 | 439ms | 520ms | - | 74.6 |
| 2 | EPODONIOS | 3/3 | 3438ms | 345ms | - | 66.2 |
| 3 | EPODONIOS | 3/3 | 2880ms | 750ms | - | 64.5 |
| 4 | EPODONIOS | 3/3 | 4082ms | 611ms | - | 64.2 |
| 5 | EPODONIOS | 3/3 | 4874ms | 949ms | - | 62.9 |

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
