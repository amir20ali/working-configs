# Working Configs

## Statistics
- Tested: 8876
- Answered at least one pass: 10
- Passed every pass: 5
- Published (>= 3/3): 5
- Content-verified: 5
- Throughput sampled: 0
- Updated: 2026-10-10 18:54 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | SG 🇸🇬 | @Raydikalx | 4CC338 | 3/3 | 896ms | 13ms | - | 80.9 |
| 2 | Reality, VK [V.O.I.D] | 3/3 | 652ms | 1520ms | - | 70.0 |
| 3 | ⚡ b2n.ir/v2ray-configs | 527 | 3/3 | 1206ms | 1125ms | - | 67.1 |
| 4 | Reality, VK [V.O.I.D] | 3/3 | 1225ms | 1366ms | - | 66.7 |
| 5 | EPODONIOS | 3/3 | 3821ms | 710ms | - | 64.0 |

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
