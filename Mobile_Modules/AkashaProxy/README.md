# 📂 AkashaProxy

[🔙 返回主页 (Return to Home)](../../README.md)

> 🤖 **自动分析报告** | Auto-generated Report

## ⚔️ 配置横向对比 (Comparison)

| 特性 / 文件 | `akasha_config.yaml` | `config.yaml` |
| :--- | :--- | :--- |
| **文件大小** | 8.2 KB | 32.6 KB |
| **混合端口** | 7890 | 7890 |
| **控制面板** | 127.0.0.1:9090 | 127.0.0.1:9090 |
| **运行模式** | rule | rule |
| **TUN 模式** | ✅ 开启 | ✅ 开启 |
| **策略组数** | **20** | **51** |
| **规则条数** | **14** | **60** |


## 📄 配置文件详解 (Details)

### 📝 akasha_config.yaml
- **大小**: 8.2 KB
- **链接**: [查看源码](https://github.com/chenlong622/mihomo_yamls/blob/main/Mobile_Modules/AkashaProxy/akasha_config.yaml)

#### 📶 网络端口配置 (Ports)
| 类型 | 端口/地址 | 说明 |
| :--- | :--- | :--- |
| Mixed (混合) | 7890 | HTTP/SOCKS |
| TProxy | 7893 | 透明代理 (UDP) |
| Redirect | 7892 | 透明代理 (TCP) |
| Controller | 127.0.0.1:9090 | 控制面板 |


<details>
<summary><b>🔎 点击查看策略组架构 (20个)</b></summary>

| 策略组 (Group) | 类型 (Type) |
| :--- | :--- |
| 👆 代理设置 | `select` |
| 👆 国内分流 | `select` |
| 👆 屏蔽 | `select` |
| 👆 AI分流 | `select` |
| 👆 中国 | `select` |
| 👆 香港 | `select` |
| 👆 台湾 | `select` |
| 👆 日本 | `select` |
| 👆 美国 | `select` |
| 👆 英国 | `select` |
| 👆 新加坡 | `select` |
| 👆 全部节点 | `select` |
| ♻️ 中国自动选择 | `url-test` |
| ♻️ 香港自动选择 | `url-test` |
| ♻️ 台湾自动选择 | `url-test` |
| ... | 还有 5 个 |

</details>

<details>
<summary><b>🌐 点击查看 DNS 配置</b></summary>

| 类型 | 服务器 |
| :--- | :--- |
| DoH | `https://dns.alidns.com/dns-query` |
| DoH | `https://xxxxxxxxxx.cloudflare-gateway.com/dns-query` |

</details>


---

### 📝 config.yaml
- **大小**: 32.6 KB
- **链接**: [查看源码](https://github.com/chenlong622/mihomo_yamls/blob/main/Mobile_Modules/AkashaProxy/config.yaml)

#### 📶 网络端口配置 (Ports)
| 类型 | 端口/地址 | 说明 |
| :--- | :--- | :--- |
| Mixed (混合) | 7890 | HTTP/SOCKS |
| TProxy | 7893 | 透明代理 (UDP) |
| Redirect | 7892 | 透明代理 (TCP) |
| Controller | 127.0.0.1:9090 | 控制面板 |


<details>
<summary><b>🔎 点击查看策略组架构 (51个)</b></summary>

| 策略组 (Group) | 类型 (Type) |
| :--- | :--- |
| 👆 全局代理 | `select` |
| 👆 兜底流量 | `select` |
| 👆 国内直连 | `select` |
| 🔧 故障转移 | `fallback` |
| 👆 手动选择 | `select` |
| 👆 广告拦截 | `select` |
| 👆 直接连接 | `select` |
| 👆 人工智能 | `select` |
| 👆 海外社交 | `select` |
| 👆 国内社交 | `select` |
| 👆 国际媒体 | `select` |
| 👆 谷歌服务 | `select` |
| 👆 微软服务 | `select` |
| 👆 金融平台 | `select` |
| 👆 游戏平台 | `select` |
| ... | 还有 36 个 |

</details>

<details>
<summary><b>🌐 点击查看 DNS 配置</b></summary>

| 类型 | 服务器 |
| :--- | :--- |
| DoH | `https://dns.google/dns-query` |
| DoH | `https://cloudflare-dns.com/dns-query` |

</details>


---

## 📦 所有文件列表 (File List)

| 文件名 | 大小 | 链接 |
| :--- | :--- | :--- |
| `akasha_config.yaml` | 8.2 KB | [查看](https://github.com/chenlong622/mihomo_yamls/blob/main/Mobile_Modules/AkashaProxy/akasha_config.yaml) |
| `config.yaml` | 32.6 KB | [查看](https://github.com/chenlong622/mihomo_yamls/blob/main/Mobile_Modules/AkashaProxy/config.yaml) |