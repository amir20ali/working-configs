# Working Configs

## Statistics
- Tested: 4913
- Answered at least one pass: 109
- Passed every pass: 87
- Published (>= 3/3): 40
- Content-verified: 40
- Throughput sampled: 0
- Updated: 2026-10-30 10:27 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | ⚡ b2n.ir/v2ray-configs | 285 | 3/3 | 938ms | 20ms | - | 80.1 |
| 2 | ⚡ b2n.ir/v2ray-configs | 61 | 3/3 | 1026ms | 25ms | - | 79.2 |
| 3 | US 🇺🇸 | @Raydikalx | 3A610C | 3/3 | 1169ms | 18ms | - | 79.0 |
| 4 | ⚡ b2n.ir/v2ray-configs | 957 | 3/3 | 720ms | 73ms | - | 78.4 |
| 5 | ⚡ b2n.ir/v2ray-configs | 438 | 3/3 | 863ms | 61ms | - | 77.9 |
| 6 | ⚡ b2n.ir/v2ray-configs | 217 | 3/3 | 812ms | 73ms | - | 77.6 |
| 7 | CA 🇨🇦 | @Raydikalx | 874860 | 3/3 | 993ms | 55ms | - | 77.5 |
| 8 | CA 🇨🇦 | @Raydikalx | A7D452 | 3/3 | 1145ms | 60ms | - | 76.5 |
| 9 | ⚡ b2n.ir/v2ray-configs | 151 | 3/3 | 1088ms | 71ms | - | 76.2 |
| 10 | ⚡ b2n.ir/v2ray-configs | 939 | 3/3 | 905ms | 102ms | - | 75.9 |
| 11 | ⚡ b2n.ir/v2ray-configs | 40 | 3/3 | 747ms | 140ms | - | 75.8 |
| 12 | SG 🇸🇬 | @Raydikalx | 481627 | 3/3 | 1327ms | 61ms | - | 75.7 |
| 13 | CA 🇨🇦 | @Raydikalx | 0940F6 | 3/3 | 731ms | 164ms | - | 75.3 |
| 14 | ⚡ b2n.ir/v2ray-configs | 301 | 3/3 | 1464ms | 61ms | - | 75.2 |
| 15 | ⚡ b2n.ir/v2ray-configs | 429 | 3/3 | 1188ms | 84ms | - | 75.2 |

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
