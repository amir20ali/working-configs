# Working Configs

## Statistics
- Tested: 8865
- Answered at least one pass: 11
- Passed every pass: 3
- Published (>= 3/3): 3
- Content-verified: 3
- Throughput sampled: 0
- Updated: 2026-10-13 07:22 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 2481ms | 364ms | - | 66.9 |
| 2 | EPODONIOS | 3/3 | 2420ms | 807ms | - | 64.9 |
| 3 | EPODONIOS | 3/3 | 2813ms | 1393ms | - | 63.5 |

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
