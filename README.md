# Awesome-Compact-Tablet-Hardware

# Awesome-Compact-Tablet-Hardware

**Curated List of Commercial Hardware & Open-Source Software Projects**
*Focused on Compact Tablets (8–9"), Linux/Android Compatibility & Stylus Productivity*
**Last updated: October 2026**

This repository tracks notable **compact tablet hardware** and **open-source software projects** that maximize their potential. These tools help users choose the right sub-9-inch device and unlock its capabilities with free, open-source operating systems and stylus-optimized applications.

**Examples** include Apple iPad mini, Lenovo Legion Y700, Xiaomi Pad Mini, HUAWEI MatePad Mini OLED, Redmagic Astra OLED, Microsoft Surface Go, Samsung Galaxy Tab A9, Amazon Fire HD 8, and Alldocube iPlay 50 Mini (the category leaders).

**Open-source emphasis**: The compact tablet hardware market is **dominated by commercial vendors** with locked bootloaders, but a **vibrant open-source ecosystem** exists to extend these devices. **GrapheneOS** provides hardened Android for Pixel devices (including Pixel Tablet) , **postmarketOS** supports 200+ devices including older tablets , and **LineageOS** officially supports Galaxy Tab models . For stylus work, **Linwood Butterfly** and **NexaNote** offer open-source note-taking alternatives to Samsung Notes . This section documents the hardware landscape and the open-source software that extends these devices' lives.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📖 Table of Contents

- [🔓 Commercial Hardware](#-commercial-hardware)
- [🔓 Open-Source Software Projects](#-open-source-software-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## 🔓 Commercial Hardware

> **📊 Market Context**: The compact tablet segment (8–9 inches) is experiencing a **renaissance in 2026**, with flagship-class hardware now available in sub-9-inch form factors. **Xiaomi Pad Mini** leads on thinness at 6.5mm with Dimensity 9400+, **Lenovo Legion Y700** dominates gaming with Snapdragon 8 Elite Gen 5 and 165Hz displays , and **Apple iPad mini** remains the predictable standard at 8.3 inches and 297g . The market is **highly fragmented** — no single vendor dominates, and Linux support varies wildly by model. For open-source enthusiasts, **Pixel Tablet with GrapheneOS** is the only officially supported privacy-hardened option , while older Galaxy Tab models have LineageOS support .

| Hardware | Description | Pricing (Starting Tier) | Linux/Open-Source Support | Company Size |
|----------|-------------|------------------------|--------------------------|--------------|
| **[Apple iPad mini (7th Gen)](https://www.apple.com/ipad-mini/)** | **The benchmark compact tablet.** 8.3" Liquid Retina, A17 Pro, 297g, 6.3mm. Supports Apple Pencil Pro and Apple Intelligence (US) . | **$499** (128GB Wi-Fi); **$649** (256GB); **$849** (512GB)  | **None** — locked bootloader. No Linux installation possible. | **~$400B revenue (Apple FY2025 est.)** |
| **[Lenovo Legion Y700 (Gen 5)](https://www.lenovo.com/)** | **Best compact tablet for gaming.** 8.8" 3K 165Hz, Snapdragon 8 Elite Gen 5, 9000mAh, dual USB-C, microSD, JBL stereo . | **~48,000 ₽** (~$550) in Russia (parallel import); China pricing lower  | **None** — Android 16 with Chinese firmware. No official Linux support. | **~$60B revenue (Lenovo FY2025 est.)** |
| **[Xiaomi Pad Mini](https://www.mi.com/)** | **Thinnest flagship compact tablet.** 6.5mm thickness, Dimensity 9400+, 3K 165Hz display, dual USB-C, 67W charging with bypass power . | **~$500–$600** (est., China market) | **None** — Android with MIUI/HyperOS. No Linux support. | **~$40B revenue (Xiaomi FY2025 est.)** |
| **[HUAWEI MatePad Mini OLED](https://consumer.huawei.com/)** | **Lightest OLED compact tablet.** 260g, ~5mm thickness, Kirin 9020, HarmonyOS 5.1, stylus support, satellite connectivity . | **~$600–$800** (est., China market) | **None** — HarmonyOS with no bootloader unlock. No Linux support. | **~$100B revenue (Huawei FY2025 est.)** |
| **[Pixel Tablet](https://store.google.com/)** | **The only GrapheneOS-supported tablet.** 11" (larger than typical compact), Tensor G2, Android 16. **GrapheneOS 17** in development . | **$499** (128GB); **$599** (256GB) | **GrapheneOS**: Fully supported. **LineageOS**: Officially supported . **Linux**: No direct support. | **~$350B revenue (Alphabet FY2025)** |
| **[Microsoft Surface Go](https://www.microsoft.com/surface/)** | **The most Linux-friendly compact Windows tablet.** 10.5" (borderline compact), Intel Pentium/Core, kickstand. **linux-surface** project provides kernel/drivers . | **$399** (Go 3 base); **$549** (Go 4) | **Linux**: Community-supported via **linux-surface** kernel . Touchscreen, pen, keyboard work with patches. | **~$281B revenue (Microsoft FY2025)** |
| **[Samsung Galaxy Tab A9](https://www.samsung.com/)** | Budget compact Android tablet. 8.7" LCD, Helio G99, expandable storage. **LineageOS**: Galaxy Tab A 8.0 2019 officially supported . | **~$150–$200** | **LineageOS**: Older Galaxy Tab A 8.0 (2019) officially supported . A9 support may vary. | **~$250B revenue (Samsung FY2025 est.)** |
| **[Amazon Fire HD 8](https://www.amazon.com/)** | Budget Amazon tablet with Fire OS (Android fork). 8" HD, expandable storage. **Open-source support**: Limited; Fire Toolbox for debloating. | **$99** (32GB); **$139** (64GB) | **None** — locked bootloader. No LineageOS/GrapheneOS support. | **~$638B revenue (Amazon FY2025)** |
| **[Alldocube iPlay 50 Mini](https://www.alldocube.com/)** | **Budget 8.4" tablet with near-stock Android.** Unisoc T606, 4GB RAM, 64GB storage. Popular for LineageOS/GSI experiments. | **~$100–$150** | **GSI/LineageOS**: Often compatible via Project Treble GSI images. Check XDA forums for model-specific builds. | **Private (Chinese OEM)** |

## 🔓 Open-Source Software Projects

Sorted by star count (descending). Star badge links to each repo's stargazers page.

| Repo | Description | Stars |
|---|---|---|
| **[Readest](https://github.com/bilingify/readest)** — **Modern, open-source ebook reader for people who read a lot.** Open EPUB, PDF, MOBI, AZW3, FB2, CBZ, TXT, Markdown. Paginated/scrolling modes, e-ink optimized, up to 4 books side-by-side, TTS with offline voices, translations, sync via Readest Cloud or bring-your-own (Google Drive, OneDrive, WebDAV, S3). **Android, iOS, macOS, Windows, Linux, Web** . **MIT/AGPL**. | [![Stars](https://img.shields.io/github/stars/bilingify/readest?style=social&color=white)](https://github.com/bilingify/readest/stargazers) | ~5,000 |
| **[Linwood Butterfly](https://github.com/LinwoodCloud/Butterfly)** — **Powerful, minimalistic, cross-platform open-source note-taking app.** Infinite canvas, stylus support, import/export PDF/SVG/images, WebDAV sync, offline use, FOSS. **Android, Windows, Linux, Web** . | [![Stars](https://img.shields.io/github/stars/LinwoodCloud/Butterfly?style=social&color=white)](https://github.com/LinwoodCloud/Butterfly/stargazers) | ~2,000 |
| **[Episteme Reader](https://github.com/Aryan-Raj3112/episteme)** — **Offline-first, privacy-focused document and ebook reader.** Kotlin Multiplatform. Supports PDF, EPUB, MOBI/AZW3, FB2, DOCX, ODT, TXT, Markdown, HTML, comics (CBZ/CBR/CB7). PDF ink annotations, highlighting, reflow mode, text-to-speech, themes. **OSS Offline edition** has network permissions stripped . | [![Stars](https://img.shields.io/github/stars/Aryan-Raj3112/episteme?style=social&color=white)](https://github.com/Aryan-Raj3112/episteme/stargazers) | ~500 |
| **[NexaNote](https://github.com/TheZupZup/NexaNote)** — **Self-hosted note-taking built for handwriting, stylus input, and privacy.** Docker support, local-first SQLite, optional sync via REST API/WebDAV. **Android APK** via GitHub Releases, Obtainium-compatible. MPL-2.0 . | [![Stars](https://img.shields.io/github/stars/TheZupZup/NexaNote?style=social&color=white)](https://github.com/TheZupZup/NexaNote/stargazers) | ~200 |
| **[GrapheneOS](https://grapheneos.org/)** — **The most secure Android distribution.** Hardened AOSP with verified boot, sandboxed Play Services, and privacy protections. **Pixel Tablet** is the only officially supported tablet . | [![GrapheneOS](https://img.shields.io/badge/GrapheneOS-Project-blue)](https://grapheneos.org/) | N/A |
| **[LineageOS](https://lineageos.org/)** — **The leading alternative Android distribution.** Officially supports **Galaxy Tab A 8.0 2019, Tab A7 10.4, Tab S5e, Tab S6 Lite, Tab S7**, and others . Gives new life to older tablets. | [![LineageOS](https://img.shields.io/badge/LineageOS-Project-blue)](https://lineageos.org/) | N/A |
| **[postmarketOS](https://postmarketos.org/)** — **Independent Linux OS for smartphones and tablets.** Supports **200+ devices** including **Samsung Galaxy Tab A 8.0/9.7, ASUS MeMo Pad 7, Google Nexus 10, Lenovo A6000** . Extends life of older devices with security updates. | [![postmarketOS](https://img.shields.io/badge/postmarketOS-Project-blue)](https://postmarketos.org/) | N/A |
| **[Mobian](https://github.com/tabletseeker/mobian)** — **Android-like OS using 100% Debian FOSS and 0% Google services.** For touch devices including **Surface Pro, Zenbook, ThinkPad, Pinephone**. On-screen keyboard support, kernel packages for Surface Pro 3-10 via **linux-surface** . | [![Stars](https://img.shields.io/github/stars/tabletseeker/mobian?style=social&color=white)](https://github.com/tabletseeker/mobian/stargazers) | ~100 |

**Additional open-source options worth exploring:**

| Repo | Description |
|---|---|
| **[linux-surface](https://github.com/linux-surface/linux-surface)** — Kernel and drivers for Microsoft Surface devices including Surface Go. Touchscreen, pen, keyboard support via patched kernel . | [![Stars](https://img.shields.io/github/stars/linux-surface/linux-surface?style=social&color=white)](https://github.com/linux-surface/linux-surface/stargazers) |
| **[openKylin](https://docs.openkylin.top/)** — Chinese open-source OS with **deep tablet mode optimization**, virtual keyboard, multi-terminal collaboration (Android interconnection), and KMRE Android compatibility environment. Supports X86, ARM, and RISC-V . | [![openKylin](https://img.shields.io/badge/openKylin-OS-blue)](https://docs.openkylin.top/) |
| **[Ubuntu-Tiny](https://github.com/ghostplant/ubuntu-tiny)** — **Tiny, faster, power-saving Ubuntu MATE LTS** for x64 and ARM64. 570MB full desktop or 140MB no-desktop version. Supports tablet use cases on compatible hardware . | [![Stars](https://img.shields.io/github/stars/ghostplant/ubuntu-tiny?style=social&color=white)](https://github.com/ghostplant/ubuntu-tiny/stargazers) |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's commercial hardware or open-source software.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Compact tablet hardware is **commercial proprietary technology**; open-source software can extend functionality but cannot bypass locked bootloaders. **Most modern tablets (iPad mini, Legion Y700, Xiaomi Pad Mini, Huawei MatePad Mini) have no Linux or alternative OS support** .
- **Open-source reality**: The open-source ecosystem for compact tablets is **fragmented by device**. **Pixel Tablet with GrapheneOS** is the only officially supported privacy-hardened option , while **older Galaxy Tab models** have LineageOS support  and **Surface Go** has community Linux support via linux-surface . **postmarketOS** extends life to 200+ older devices . For stylus productivity, **Linwood Butterfly** and **NexaNote** provide open-source alternatives to proprietary note apps . The open-source path is **genuinely viable** for specific devices, but **not universally available** across the compact tablet market.

---

**Made for tablet enthusiasts, Linux users, digital note-takers, and open-source advocates.**
Let's make compact tablets more open, capable, and long-lasting.
