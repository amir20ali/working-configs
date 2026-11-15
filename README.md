# Working Configs

## Statistics
- Tested: 4785
- Answered at least one pass: 80
- Passed every pass: 27
- Published (>= 3/3): 27
- Content-verified: 27
- Throughput sampled: 0
- Updated: 2026-11-15 08:16 UTC

## Top configs

| # | Name | Passes | Delay | Spread | Throughput | Score |
|---|------|--------|-------|--------|------------|-------|
| 1 | ⚡ b2n.ir/v2ray-configs | 156 | 3/3 | 495ms | 160ms | - | 77.8 |
| 2 | US 🇺🇸 | @Raydikalx | CA0DCB | 3/3 | 784ms | 165ms | - | 74.8 |
| 3 | 🇧🇪 Misha Lan VPN | 3/3 | 1232ms | 141ms | - | 73.0 |
| 4 | ⚡ b2n.ir/v2ray-configs | 887 | 3/3 | 1232ms | 218ms | - | 71.4 |
| 5 | US 🇺🇸 | @Raydikalx | 1B8231 | 3/3 | 2027ms | 261ms | - | 68.7 |
| 6 | 🇺🇸 Misha Lan VPN | 3/3 | 2221ms | 239ms | - | 68.7 |
| 7 | FI 🇫🇮 | @Raydikalx | 3FAF16 | 3/3 | 1715ms | 383ms | - | 68.0 |
| 8 | ⚡ b2n.ir/v2ray-configs | 627 | 3/3 | 2162ms | 350ms | - | 67.5 |
| 9 | ⚡ b2n.ir/v2ray-configs | 601 | 3/3 | 1319ms | 756ms | - | 67.4 |
| 10 | US 🇺🇸 | @Raydikalx | 9B4F83 | 3/3 | 1976ms | 428ms | - | 67.2 |
| 11 | US 🇺🇸 | @Raydikalx | DE08A7 | 3/3 | 1222ms | 1226ms | - | 66.9 |
| 12 | ⚡ b2n.ir/v2ray-configs | 462 | 3/3 | 2117ms | 537ms | - | 66.3 |
| 13 | ⚡ b2n.ir/v2ray-configs | 484 | 3/3 | 1579ms | 1151ms | - | 65.8 |
| 14 | ⚡ b2n.ir/v2ray-configs | 246 | 3/3 | 2703ms | 513ms | - | 65.6 |
| 15 | CA 🇨🇦 | @Raydikalx | A9BDF3 | 3/3 | 2603ms | 541ms | - | 65.6 |

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
