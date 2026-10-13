# Working Configs

## Statistics
- Tested: 8843
- Answered at least one pass: 10
- Passed every pass: 2
- Published (>= 3/3): 2
- Content-verified: 2
- Throughput sampled: 0
- Updated: 2026-10-13 15:40 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | @V2ray_Alpha💍 1 | 3/3 | 2051ms | 990ms | - | 65.1 |
| 2 | EPODONIOS | 3/3 | 4392ms | 1172ms | - | 62.7 |

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
