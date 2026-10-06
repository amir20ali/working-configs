# Working Configs

## Statistics
- Tested: 8855
- Answered at least one pass: 9
- Passed every pass: 3
- Published (>= 3/3): 3
- Content-verified: 3
- Throughput sampled: 0
- Updated: 2026-10-06 07:14 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 2046ms | 379ms | - | 67.4 |
| 2 | EPODONIOS | 3/3 | 1849ms | 801ms | - | 65.8 |
| 3 | EPODONIOS | 3/3 | 2488ms | 830ms | - | 64.8 |

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
