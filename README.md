# LHL's Shop 建站主机评测：最低 ¥1.99/月，美国三网直连+免费套餐都有

说实话，国内找到一个便宜又靠谱的建站主机还挺难的——要么价格感人，要么线路拉胯，要么跑路风险让人睡不好觉。

最近发现一家叫 **LHL's Shop** 的小店，产品线挺有意思：有美国三网直连的高速建站主机，也有面向轻量用户的超低价甚至免费套餐，另外还卖 VPS 探针、子域名、Telegram Bot、WHMCS 插件这些周边服务。整体走的是"个人开发者/小站长"路线，价格压得很低。

下面把几个主力产品挨个捋一遍。

<img width="2914" height="1592" alt="image" src="https://github.com/user-attachments/assets/72515a5b-7264-48ed-9763-e080b32cadac" />

---

## 建站主机 DC1 US：美国三网直连，最低 ¥1.99/月

DC1 系列是 LHL's Shop 的旗舰产品，机器在美国洛杉矶，线路方面同时走**联通 9929、电信 163、移动 CMI** 三条，对国内访问做了专项优化。官方给的延迟数据是上海方向约 126ms、全国平均约 160ms，算是同价位里相当不错的水平。

硬件层面用的是 E5-2682 v4 处理器，硬盘为 NVMe RAID-10，还有云端备份，稳定性有一定保障。面板是 HestiaCP，IP 为原生 IP。

| 套餐 | 硬盘 | 月流量 | 带宽 | 月付价格 | 购买 |
|------|------|--------|------|----------|------|
| DC1 Mini | 100MB（NVMe RAID-10） | 10G | 1Gbps | ¥1.99 | [ 立即订购](https://shop.lhl.one/store/us-la-host/us-la-mini?aff=2) |
| DC1 Standard | 0.5G（NVMe RAID-10） | 40G | 1Gbps | ¥3.99 | [ 立即订购](https://shop.lhl.one/store/us-la-host/us-host-standard?aff=2) |
| DC1 Large | 1G（NVMe RAID-10） | 100G | 1Gbps | ¥6.99 | [ 立即订购](https://shop.lhl.one/store/us-la-host/us-host-large?aff=2) |

三个套餐全部不限网站数量、不限数据库数量，带宽都是 1Gbps，差别主要在存储和流量上。

Mini 适合挂个静态页或者极轻量的小博客；Standard 是日常建站最常见的选择；Large 流量给到 100G，够大多数内容站用一个月了。

目前 DC1 Mini 还剩 29 个名额，Standard 剩 11 个，Large 只剩 2 个——Large 快卖光了，有需要的早点下手。

👉 [查看 DC1 US 全部套餐](https://shop.lhl.one/store/us-la-host?aff=2)

---

## 建站主机 DC2：最低 ¥0.99/月，还有免费版

DC2 系列走的是极致性价比路线，面板换成了 aaPanel（宝塔国际版），母机是按年付费的 OVH 机器，店主专门说了"不用担心跑路"。代价是**没有大陆访问优化**，套了 Cloudflare CDN 来保证基本可用性，适合对国内访问速度要求不高、主要面向海外或者纯粹练手的场景。

| 套餐 | 硬盘 | 月流量 | 带宽 | 价格 | 购买 |
|------|------|--------|------|------|------|
| DC2 Free A | 0.1G | 5G | 1Gbps | 免费（¥1 初装费） | [ 立即订购](https://shop.lhl.one/store/web-hosting-dc2/free-host-a?aff=2) |
| DC2 Free A+ | 1G | 10G | 1Gbps | 完全免费 | [ 立即订购](https://shop.lhl.one/store/web-hosting-dc2/free-host-a-plus?aff=2) |
| DC2 Tier 1 | 1G | 15G | 1Gbps | ¥0.99/月 | [ 立即订购](https://shop.lhl.one/store/web-hosting-dc2/tier-1?aff=2) |
| DC2 Tier 2 | 2G | 20G | 1Gbps | ¥1.99/月 | [ 立即订购](https://shop.lhl.one/store/web-hosting-dc2/tier-2?aff=2) |
| DC2 Tier 3 | 5G | 50G | 1Gbps | ¥2.99/月 | [ 立即订购](https://shop.lhl.one/store/web-hosting-dc2/tier-3?aff=2) |

全系套餐不限网站、不限数据库，配 CloudFlare CDN。

免费版（Free A+）目前显示 0 个名额，不定时补货；Free A 剩 1 个；Tier 1 还有 28 个，¥0.99 一个月真的很适合拿来跑测试项目或者挂个轻量站。

Tier 2 有个隐藏福利——购买 LHL's Images 图床 Pro 版的用户可以免费领取，发工单附上图床账号邮箱即可申请。

👉 [查看 DC2 全部套餐](https://shop.lhl.one/store/web-hosting-dc2?aff=2)

---

## VPS 探针：¥0.90/月，Beszel 多机监控

如果你手上有一堆 VPS 需要集中监控，LHL's Shop 还提供托管的 Beszel 探针服务，¥0.90/月，不限服务器数量，支持 Telegram 告警推送。

对于同时跑好几台机器的人来说，¥0.90 买个省心还是很划算的。

👉 [订购 Beszel 探针](https://shop.lhl.one/store/applications/beszel?aff=2)

---

## 子域名：¥1.09 起/半年

还有个小众但挺实用的产品——`*.28494020.xyz` 子域名，支持按量付费，DNS 记录可配置 5 到 50 条，用自研面板管理。半年起付，最低 ¥1.09，适合需要几个测试子域名或者给项目起个临时域名的场景。

👉 [查看子域名套餐](https://shop.lhl.one/store/subdomain/28494020-xyz?aff=2)

---

## 适合哪些人？

简单总结一下：

- **需要国内访问速度的站长**：选 DC1 US，三网直连优化，延迟够低
- **预算极有限或者只是练手**：DC2 系列，¥0.99/月甚至免费，不心疼
- **多 VPS 用户**：Beszel 探针，¥0.90 解决监控问题
- **需要临时子域名**：DC2 + 子域名套餐搭配，几块钱搞定

整体来说，LHL's Shop 是个定位明确的小服务商，价格是真的低，产品不多但都很实在。有 Telegram 频道和群组可以跟进最新动态，不定时会放出免费名额。

👉 [进入 LHL's Shop 浏览全部产品](https://shop.lhl.one/aff.php?aff=2)
