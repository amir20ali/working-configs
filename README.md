# Working Configs

## Statistics
- Tested: 9238
- Answered at least one pass: 15
- Passed every pass: 6
- Published (>= 3/3): 6
- Content-verified: 6
- Throughput sampled: 0
- Updated: 2026-09-29 06:05 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 1936ms | 87ms | - | 72.9 |
| 2 | EPODONIOS | 3/3 | 2073ms | 101ms | - | 72.2 |
| 3 | EPODONIOS | 3/3 | 2172ms | 303ms | - | 67.9 |
| 4 | EPODONIOS | 3/3 | 1804ms | 398ms | - | 67.7 |
| 5 | EPODONIOS | 3/3 | 1836ms | 483ms | - | 67.1 |
| 6 | EPODONIOS | 3/3 | 3131ms | 992ms | - | 63.8 |

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
