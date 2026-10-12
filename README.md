# Working Configs

## Statistics
- Tested: 8910
- Answered at least one pass: 18
- Passed every pass: 9
- Published (>= 3/3): 9
- Content-verified: 9
- Throughput sampled: 0
- Updated: 2026-10-12 13:01 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 2050ms | 743ms | - | 65.6 |
| 2 | EPODONIOS | 3/3 | 2118ms | 963ms | - | 65.0 |
| 3 | EPODONIOS | 3/3 | 2077ms | 1065ms | - | 64.9 |
| 4 | EPODONIOS | 3/3 | 2932ms | 659ms | - | 64.8 |
| 5 | EPODONIOS | 3/3 | 2164ms | 1120ms | - | 64.7 |
| 6 | EPODONIOS | 3/3 | 2513ms | 1126ms | - | 64.2 |
| 7 | EPODONIOS | 3/3 | 3690ms | 711ms | - | 64.0 |
| 8 | EPODONIOS | 3/3 | 3695ms | 768ms | - | 63.9 |
| 9 | EPODONIOS | 3/3 | 5103ms | 796ms | - | 63.1 |

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
