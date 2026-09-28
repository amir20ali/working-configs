# Working Configs

## Statistics
- Tested: 9069
- Answered at least one pass: 29
- Passed every pass: 18
- Published (>= 3/3): 18
- Content-verified: 18
- Throughput sampled: 0
- Updated: 2026-09-28 06:55 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 888ms | 439ms | - | 70.8 |
| 2 | EPODONIOS | 3/3 | 3033ms | 113ms | - | 70.6 |
| 3 | EPODONIOS | 3/3 | 2728ms | 137ms | - | 70.1 |
| 4 | EPODONIOS | 3/3 | 1982ms | 519ms | - | 66.6 |
| 5 | EPODONIOS | 3/3 | 4237ms | 298ms | - | 66.2 |
| 6 | EPODONIOS | 3/3 | 1994ms | 625ms | - | 66.1 |
| 7 | EPODONIOS | 3/3 | 2406ms | 550ms | - | 65.8 |
| 8 | EPODONIOS | 3/3 | 1945ms | 823ms | - | 65.6 |
| 9 | EPODONIOS | 3/3 | 1983ms | 883ms | - | 65.4 |
| 10 | EPODONIOS | 3/3 | 2017ms | 1194ms | - | 64.8 |
| 11 | EPODONIOS | 3/3 | 3025ms | 623ms | - | 64.8 |
| 12 | EPODONIOS | 3/3 | 2487ms | 869ms | - | 64.7 |
| 13 | EPODONIOS | 3/3 | 3566ms | 656ms | - | 64.3 |
| 14 | EPODONIOS | 3/3 | 3778ms | 652ms | - | 64.2 |
| 15 | EPODONIOS | 3/3 | 3308ms | 818ms | - | 64.0 |

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
