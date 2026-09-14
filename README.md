**中文** · [English](https://github.com/winstinwang/winstinwang/blob/main/README.en.md)

# Wang Minyi

**嵌入式软件工程师 · Android / Linux 内核**

`Qualcomm` · `MediaTek` · `Rockchip` · **15 年以上开发经验**

> Embedded software engineer — Android / Linux kernel. 15+ years of driver porting,
> kernel debugging and system stability work across Qualcomm, MediaTek and Rockchip
> platforms. Long-form write-ups at **[diyallai.com](https://diyallai.com)**.

---

## 核心能力

| 方向 | 内容 |
|---|---|
| **芯片平台** | Qualcomm · MediaTek · Rockchip |
| **内核调试** | Android Kernel / Linux Kernel；Oops、Panic、崩溃转储定位；ftrace、kgdb、kdump、eBPF |
| **驱动移植** | 设备树、I2C/SPI/UART、pinctrl/GPIO、PCIe/DMA、电源管理（Runtime PM、Regulator） |
| **系统稳定性** | 死机重启定位、内存与并发问题（竞态、死锁、缓存一致性）、压测与回归 |
| **AI × 嵌入式** | 把 AI 接进真实项目流程：代码与日志分析、驱动模板生成、文档与测试自动化 |

---

## ★ AI 融入嵌入式开发

不是「用 AI 聊聊天」，而是把 AI 放进**可验证的工程约束**里 —— 下面三条都在线上跑着：

- **AI 只生成数据，不生成代码。** 关卡引擎唯一的数据契约是一份 JSON 规格，
  AI 的产出必须过 schema 校验层才能生效 —— 从机制上排除「AI 写出不可控代码」。
- **密钥永不进前端。** AI 接口是独立的 Cloudflare Worker，API Key 只存在服务端环境变量里；
  Worker 与主站解耦，它挂了网站照常运行。
- **主备双线路自动降级。** 接口配了主地址 + 兜底地址，应对国内网络对 `workers.dev` 的不稳定。
- **真实项目里的速度。** 基于 **RK3568 + Android 12** 的医疗设备平台，含外设驱动在内
  **2 个月内完成落地** —— 这是 AI 辅助在真实项目中最直接的体现。

🔗 线上可玩：[贪吃蛇 · AI 一句话生成关卡](https://diyallai.com/games/snake/editor.html)

---

## 技术输出

把项目里真实踩过的坑写成长文，长期更新 · 免费 · 中英双语 → **[diyallai.com](https://diyallai.com)**

- [从零写一个能跑的字符设备驱动](https://diyallai.com/blog/linux-char-device-driver.html)
- [Linux 内核调试手段全览：从 printk 到 eBPF](https://diyallai.com/blog/kernel-debugging.html)
- [RTL8125 网卡驱动在 RK3568 Android 12 上的移植调试](https://diyallai.com/blog/rtl8125-nic-driver-porting.html)
- [Linux 内存管理与 DMA 映射：驱动开发者必须搞懂的缓存一致性](https://diyallai.com/blog/memory-dma.html)

其余 15 篇见 [博客目录](https://diyallai.com/blog/)

**顺手写的网页小游戏**
- [3D 赛车竞速](https://diyallai.com/games/racing.html) —— 跨局自适应难度的 AI 对手
- [可客制化贪吃蛇](https://diyallai.com/games/snake/) —— 带关卡编辑器

---

## 求职意向

**嵌入式软件工程师 / Android 系统工程师 / Linux 内核开发** —— 内核调试、驱动移植、系统稳定性方向。
**15 年以上经验**，欢迎内推与交流。

📮 [联系方式](https://diyallai.com/contact.html)

