# Working Configs

## Statistics
- Tested: 8832
- Answered at least one pass: 12
- Passed every pass: 3
- Published (>= 3/3): 3
- Content-verified: 3
- Throughput sampled: 0
- Updated: 2026-10-07 06:55 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 769ms | 258ms | - | 73.3 |
| 2 | EPODONIOS | 3/3 | 1295ms | 168ms | - | 72.1 |
| 3 | EPODONIOS | 3/3 | 1465ms | 171ms | - | 71.5 |

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
