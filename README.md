# Working Configs

## Statistics
- Tested: 8967
- Answered at least one pass: 26
- Passed every pass: 5
- Published (>= 3/3): 5
- Content-verified: 5
- Throughput sampled: 0
- Updated: 2026-10-10 05:40 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 1204ms | 439ms | - | 69.2 |
| 2 | EPODONIOS | 3/3 | 1768ms | 1145ms | - | 65.4 |
| 3 | EPODONIOS | 3/3 | 2448ms | 1203ms | - | 64.2 |
| 4 | EPODONIOS | 3/3 | 3216ms | 943ms | - | 63.8 |
| 5 | EPODONIOS | 3/3 | 4189ms | 899ms | - | 63.3 |

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
