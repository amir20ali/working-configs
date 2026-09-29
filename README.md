# Working Configs

## Statistics
- Tested: 9267
- Answered at least one pass: 16
- Passed every pass: 13
- Published (>= 3/3): 13
- Content-verified: 13
- Throughput sampled: 0
- Updated: 2026-09-29 16:45 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 2467ms | 390ms | - | 66.7 |
| 2 | EPODONIOS | 3/3 | 2442ms | 447ms | - | 66.3 |
| 3 | EPODONIOS | 3/3 | 3564ms | 359ms | - | 65.9 |
| 4 | EPODONIOS | 3/3 | 3101ms | 426ms | - | 65.8 |
| 5 | EPODONIOS | 3/3 | 3635ms | 388ms | - | 65.7 |
| 6 | EPODONIOS | 3/3 | 2636ms | 530ms | - | 65.6 |
| 7 | EPODONIOS | 3/3 | 3188ms | 489ms | - | 65.3 |
| 8 | EPODONIOS | 3/3 | 3443ms | 478ms | - | 65.2 |
| 9 | EPODONIOS | 3/3 | 2336ms | 806ms | - | 65.0 |
| 10 | EPODONIOS | 3/3 | 3731ms | 622ms | - | 64.3 |
| 11 | EPODONIOS | 3/3 | 4348ms | 870ms | - | 63.2 |
| 12 | EPODONIOS | 3/3 | 5011ms | 932ms | - | 62.9 |
| 13 | EPODONIOS | 3/3 | 5683ms | 1235ms | - | 62.2 |

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
