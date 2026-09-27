# Working Configs

## Statistics
- Tested: 9073
- Answered at least one pass: 27
- Passed every pass: 15
- Published (>= 3/3): 15
- Content-verified: 15
- Throughput sampled: 0
- Updated: 2026-09-27 06:26 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 1183ms | 218ms | - | 71.6 |
| 2 | EPODONIOS | 3/3 | 1253ms | 304ms | - | 70.1 |
| 3 | EPODONIOS | 3/3 | 1154ms | 355ms | - | 70.0 |
| 4 | EPODONIOS | 3/3 | 1306ms | 356ms | - | 69.4 |
| 5 | EPODONIOS | 3/3 | 2596ms | 273ms | - | 67.7 |
| 6 | EPODONIOS | 3/3 | 1878ms | 384ms | - | 67.7 |
| 7 | EPODONIOS | 3/3 | 1567ms | 493ms | - | 67.7 |
| 8 | EPODONIOS | 3/3 | 1587ms | 488ms | - | 67.6 |
| 9 | EPODONIOS | 3/3 | 1542ms | 516ms | - | 67.6 |
| 10 | EPODONIOS | 3/3 | 1539ms | 520ms | - | 67.6 |
| 11 | EPODONIOS | 3/3 | 1549ms | 551ms | - | 67.4 |
| 12 | EPODONIOS | 3/3 | 2049ms | 713ms | - | 65.7 |
| 13 | EPODONIOS | 3/3 | 2139ms | 1280ms | - | 64.5 |
| 14 | EPODONIOS | 3/3 | 2189ms | 1302ms | - | 64.4 |
| 15 | EPODONIOS | 3/3 | 3008ms | 1262ms | - | 63.5 |

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
