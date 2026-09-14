# Winstin Wang

**Embedded Software Engineer · Android / Linux Kernel**

`Qualcomm` · `MediaTek` · `Rockchip` · **15+ years**

> 15+ years of driver porting, kernel debugging and system stability work across Qualcomm,
> MediaTek and Rockchip platforms. Long-form write-ups at **[diyallai.com](https://diyallai.com)**.

---

## Core Skills

| Area | Details |
|---|---|
| **SoC platforms** | Qualcomm · MediaTek · Rockchip |
| **Kernel debugging** | Android / Linux kernel; Oops, panic and crash-dump triage; ftrace, kgdb, kdump, eBPF |
| **Driver porting** | Device tree, I2C/SPI/UART, pinctrl/GPIO, PCIe/DMA, power management (Runtime PM, regulators) |
| **System stability** | Boot-loop and random-reboot triage; memory and concurrency issues (races, deadlocks, cache coherency); stress testing and regression |
| **AI × embedded** | Bringing AI into real project workflows: code and log analysis, driver template generation, documentation and test automation |

---

## ★ AI in Embedded Development

Not "chatting with AI" — AI placed inside **verifiable engineering constraints**. All three
of the following are running in production:

- **AI generates data, never code.** The level engine's single data contract is a JSON spec;
  anything AI produces must pass a schema validation layer before it takes effect — ruling out
  "AI writing uncontrollable code" by construction.
- **Keys never reach the frontend.** The AI endpoint is a separate Cloudflare Worker; the API key
  lives only in server-side environment variables. The Worker is decoupled from the main site —
  if it goes down, the site keeps running.
- **Primary / fallback endpoints.** The API auto-degrades across two addresses, because
  `workers.dev` is unreliable on some networks.
- **Real-project velocity.** An **RK3568 + Android 12 medical device platform** — peripheral
  drivers included — was brought up and delivered in **2 months**. That timeline is the most
  direct evidence of what AI-assisted development looks like on a real project.

🔗 Live demo: [Snake — generate a level from one sentence](https://diyallai.com/en/games/snake/editor.html)

---

## Writing

Long-form posts on problems actually hit in real projects · free · bilingual → **[diyallai.com](https://diyallai.com)**

- [Linux Char Device Drivers: Writing a Working Driver from Scratch](https://diyallai.com/en/blog/linux-char-device-driver.html)
- [A Complete Survey of Linux Kernel Debugging: From printk to eBPF](https://diyallai.com/en/blog/kernel-debugging.html)
- [Porting and Debugging the RTL8125 NIC Driver on RK3568 Android 12](https://diyallai.com/en/blog/rtl8125-nic-driver-porting.html)
- [Linux Memory Management and DMA Mapping: Cache Coherency Every Driver Developer Must Understand](https://diyallai.com/en/blog/memory-dma.html)

The other 15 are in the [blog index](https://diyallai.com/en/blog/)

**Browser games built on the side**
- [3D Racing](https://diyallai.com/en/games/racing.html) — AI opponents with cross-race adaptive difficulty
- [Customizable Snake](https://diyallai.com/en/games/snake/) — with a level editor

---

## Open to

**Embedded Software Engineer / Android System Engineer / Linux Kernel Developer** —
kernel debugging, driver porting and system stability. Open to referrals and inquiries.

📮 [Get in touch](https://diyallai.com/en/contact.html)
