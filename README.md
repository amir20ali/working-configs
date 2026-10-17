# Working Configs

## Statistics
- Tested: 8803
- Answered at least one pass: 13
- Passed every pass: 10
- Published (>= 3/3): 10
- Content-verified: 10
- Throughput sampled: 0
- Updated: 2026-10-17 06:23 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 4182ms | 64ms | - | 71.8 |
| 2 | TCP, Яндекс [V.O.I.D] | 3/3 | 1591ms | 311ms | - | 69.0 |
| 3 | Reality, Яндекс [V.O.I.D] | 3/3 | 1283ms | 503ms | - | 68.5 |
| 4 | US 🇺🇸 | @Raydikalx | AA9499 | 3/3 | 1563ms | 511ms | - | 67.6 |
| 5 | Reality, Яндекс [V.O.I.D] | 3/3 | 1213ms | 1146ms | - | 67.0 |
| 6 | EPODONIOS | 3/3 | 3808ms | 365ms | - | 65.7 |
| 7 | EPODONIOS | 3/3 | 2619ms | 674ms | - | 65.0 |
| 8 | EPODONIOS | 3/3 | 3720ms | 506ms | - | 64.8 |
| 9 | TCP, Яндекс [V.O.I.D] | 3/3 | 2190ms | 1435ms | - | 64.3 |
| 10 | EPODONIOS | 3/3 | 3995ms | 671ms | - | 64.0 |

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
