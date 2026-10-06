# Working Configs

## Statistics
- Tested: 8817
- Answered at least one pass: 3
- Passed every pass: 2
- Published (>= 3/3): 2
- Content-verified: 2
- Throughput sampled: 0
- Updated: 2026-10-06 17:23 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 1339ms | 419ms | - | 68.8 |
| 2 | EPODONIOS | 3/3 | 1315ms | 680ms | - | 67.6 |

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
