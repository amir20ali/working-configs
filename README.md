# Working Configs

## Statistics
- Tested: 4677
- Answered at least one pass: 79
- Passed every pass: 37
- Published (>= 3/3): 37
- Content-verified: 37
- Throughput sampled: 0
- Updated: 2026-11-19 18:44 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | ⚡ b2n.ir/v2ray-configs | 787 | 3/3 | 408ms | 52ms | - | 83.0 |
| 2 | 🇬🇧GB-57.129.132.223-1048 | 3/3 | 565ms | 212ms | - | 75.9 |
| 3 | GB 🇬🇧 | @Raydikalx | 360227 | 3/3 | 836ms | 143ms | - | 75.0 |
| 4 | ⚡ b2n.ir/v2ray-configs | 375 | 3/3 | 588ms | 259ms | - | 74.9 |
| 5 | ⚡ b2n.ir/v2ray-configs | 42 | 3/3 | 737ms | 229ms | - | 74.0 |
| 6 | ⚡ b2n.ir/v2ray-configs | 797 | 3/3 | 844ms | 207ms | - | 73.6 |
| 7 | ⚡ b2n.ir/v2ray-configs | 177 | 3/3 | 552ms | 491ms | - | 73.3 |
| 8 | ⚡ b2n.ir/v2ray-configs | 81 | 3/3 | 615ms | 437ms | - | 72.9 |
| 9 | CA 🇨🇦 | @Raydikalx | F0DDD9 | 3/3 | 1261ms | 242ms | - | 70.9 |
| 10 | CA 🇨🇦 | @Raydikalx | 1CA799 | 3/3 | 1651ms | 190ms | - | 70.6 |
| 11 | ⚡ b2n.ir/v2ray-configs | 575 | 3/3 | 1024ms | 359ms | - | 70.6 |
| 12 | ⚡ b2n.ir/v2ray-configs | 850 | 3/3 | 1240ms | 281ms | - | 70.5 |
| 13 | ⚡ b2n.ir/v2ray-configs | 598 | 3/3 | 994ms | 423ms | - | 70.3 |
| 14 | GB 🇬🇧 | @Raydikalx | 4B9793 | 3/3 | 1223ms | 369ms | - | 69.6 |
| 15 | ⚡ b2n.ir/v2ray-configs | 780 | 3/3 | 1497ms | 419ms | - | 68.3 |

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
