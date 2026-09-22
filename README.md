# Working Configs

## Statistics
- Tested: 4267
- Answered at least one pass: 12
- Passed every pass: 4
- Published (>= 3/3): 4
- Content-verified: 4
- Throughput sampled: 0
- Updated: 2026-09-22 19:11 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 2009ms | 232ms | - | 69.1 |
| 2 | EPODONIOS | 3/3 | 1773ms | 495ms | - | 67.1 |
| 3 | EPODONIOS | 3/3 | 2472ms | 822ms | - | 64.8 |
| 4 | EPODONIOS | 3/3 | 2315ms | 1407ms | - | 64.1 |

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
