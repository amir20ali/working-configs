# Working Configs

## Statistics
- Tested: 8827
- Answered at least one pass: 12
- Passed every pass: 8
- Published (>= 3/3): 8
- Content-verified: 8
- Throughput sampled: 0
- Updated: 2026-10-25 07:12 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | CA 🇨🇦 | @Raydikalx | 0AD519 | 3/3 | 780ms | 4ms | - | 82.5 |
| 2 | US 🇺🇸 | @Raydikalx | 25DD23 | 3/3 | 1191ms | 49ms | - | 76.9 |
| 3 | HK 🇭🇰 | @Raydikalx | A36995 | 3/3 | 1255ms | 296ms | - | 70.2 |
| 4 | EPODONIOS | 3/3 | 2365ms | 987ms | - | 64.6 |
| 5 | EPODONIOS | 3/3 | 3613ms | 915ms | - | 63.6 |
| 6 | EPODONIOS | 3/3 | 2933ms | 1644ms | - | 63.2 |
| 7 | EPODONIOS | 3/3 | 3428ms | 1266ms | - | 63.1 |
| 8 | EPODONIOS | 3/3 | 5032ms | 1137ms | - | 62.5 |

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
