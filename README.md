# Working Configs

## Statistics
- Tested: 8873
- Answered at least one pass: 25
- Passed every pass: 12
- Published (>= 3/3): 12
- Content-verified: 12
- Throughput sampled: 0
- Updated: 2026-10-15 09:07 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | EPODONIOS | 3/3 | 353ms | 916ms | - | 74.7 |
| 2 | EPODONIOS | 3/3 | 619ms | 978ms | - | 71.0 |
| 3 | EPODONIOS | 3/3 | 835ms | 1428ms | - | 68.7 |
| 4 | TCP, Тинькофф [V.O.I.D] | 3/3 | 1365ms | 1522ms | - | 66.1 |
| 5 | EPODONIOS | 3/3 | 2824ms | 425ms | - | 66.0 |
| 6 | EPODONIOS | 3/3 | 3125ms | 626ms | - | 64.7 |
| 7 | EPODONIOS | 3/3 | 2706ms | 963ms | - | 64.2 |
| 8 | EPODONIOS | 3/3 | 4100ms | 841ms | - | 63.4 |
| 9 | EPODONIOS | 3/3 | 4922ms | 888ms | - | 63.0 |
| 10 | EPODONIOS | 3/3 | 5503ms | 1243ms | - | 62.2 |
| 11 | EPODONIOS | 3/3 | 4628ms | 1610ms | - | 62.2 |
| 12 | EPODONIOS | 3/3 | 5340ms | 1607ms | - | 61.9 |

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
