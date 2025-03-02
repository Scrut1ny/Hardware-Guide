# Hardware Guide 🔧

## Table of Contents
- [General Information](#general-information)
- [Computer Components](#computer-components)
- [Peripherals](#peripherals)
- [Networking](#networking)
- [Internet Service Providers (ISP)](#internet-service-providers-isp)
- [Troubleshooting](#troubleshooting)
- [Software Tools](#software-tools)
- [Personal Preference Table](#personal-preference-table)

---

## General Information

### Electronics Store Websites
<details>
<summary>🔗 Popular Retailers</summary>

- [Newegg](https://www.newegg.com/)  
- [Amazon Electronics](https://www.amazon.com/gp/browse.html?node=172282)  
- [Micro Center](https://www.microcenter.com/)
</details>

---

## Computer Components

### CPU (Processor)
<details>
<summary>📚 Breakdown & Reference Tables</summary>

#### Example Processors
- **Intel Core i7-11800H**  
  `i7` = High-Performance Tier | `11` = 11th Gen | `800` = Model # | `H` = High-Performance  
- **AMD Ryzen 7 5800X**  
  `7` = Series | `5800` = Model # | `X` = High-Performance Desktop  

#### Processor Tiers
| Tier        | Intel      | AMD        | Description                          | Price Range       | Power Consumption   |
|-------------|------------|------------|--------------------------------------|-------------------|---------------------|
| Entry       | Core i3    | Ryzen 3    | Budget-Friendly                      | $100 - $200       | Low-Moderate        |
| Mid-Range   | Core i5    | Ryzen 5    | Mainstream Performance               | $200 - $300       | Moderate-High       |
| High-Perf   | Core i7    | Ryzen 7    | High-Performance                     | $300 - $500       | Moderate-High       |
| Enthusiast  | Core i9    | Ryzen 9    | Extreme Performance                  | $500 - $1000+     | High                |

#### Suffix Guide
| Suffix | Intel Use Case                  | AMD Use Case                     |
|--------|----------------------------------|----------------------------------|
| U      | Ultra-Low Power (Laptops)       | Ultra-Low Power                 |
| H/HK   | High-Performance (Mobile)       | High-Performance (HS = Efficient)|
| X      | Extreme Performance             | High-Performance/Extended Freq. |
| G      | Integrated Iris Graphics        | Radeon Vega Graphics            |
| F      | No Integrated Graphics          | -                                |
| T      | Power-Optimized                 | Power-Optimized                 |
</details>

---

### Motherboard
<details>
<summary>🛠️ BIOS/UEFI & CMOS Management</summary>

#### BIOS/UEFI Flashback (USB Recovery)
1. **Prepare USB**:  
   - Format to FAT32.  
   - Download latest BIOS to root directory.  
2. **Flash Process**:  
   - Power off → Insert USB → Hold Flashback button.  
   - Wait for completion → Power on.  

#### CMOS Battery & Reset
- **Recommended Batteries**:  
  [LiCB CR2032](https://www.amazon.com/dp/B071D4DKTZ) | [Energizer CR2032](https://www.amazon.com/dp/B0002RID4G)  
- **Reset Methods**:  
  - Jumper Shorting  
  - Battery Removal (5-10 min)  
  - Power Drain (Hold power button 15-20 sec)  

#### EZ Debug LEDs
- 🔴 **CPU**: Not detected/failed  
- 🟡 **DRAM**: RAM issue  
- ⚪ **VGA**: GPU issue  
- 🟢 **BOOT**: Storage device issue  
</details>

---

### Disc Drive Components
<details>
<summary>💿 Ripping & Hardware Recommendations</summary>

#### Tools & Software
- **MakeMKV** ([v1.17.6](https://makemkv.com/download/Setup_MakeMKV_v1.17.6.exe))  
  - Beta Key: `T-nG89YZ0OKvZx4umZwYcU0bh2M5DwF7hcp3JeoMn0zzbQG@zgvLRURcxMSN6ldZzF72`  
- **HandBrake** ([Latest](https://github.com/HandBrake/HandBrake/releases/latest))  
- **Firmware Tools**:  
  [SDFtool Flasher](https://www.mediafire.com/file/rak1mk0p0qlqa0t/SDFtool+Flasher+%28v1.3.5%29.zip/file) | [Firmware Pack](https://www.mediafire.com/file/ph1ap2egi441epk/All+You+Need+Firmware+Pack+%28MartyMcNuts%29.zip/file)

#### Recommended Hardware
- **Optical Drives**:  
  [LG WH16NS40](https://www.amazon.com/dp/B00E7B08MS) | [ASUS BW-16D1HT](https://www.amazon.com/dp/B00DWFPDJI)  
- **Enclosures**:  
  [NexStar DX2](https://www.amazon.com/dp/B09SS74KCN) | [OWC Mercury Pro](https://www.amazon.com/dp/B06XRCCV44)  
</details>

---

## Peripherals

### Key Recommendations
<details>
<summary>🖱️ Mouse | ⌨️ Keyboard | 🎤 Mic | 🎧 Headphones</summary>

- **Mouse**: [Logitech G502 HERO](https://www.amazon.com/dp/B07GBZ4Q68)  
- **Microphones**:  
  [Blue Yeti](https://www.amazon.com/dp/B00N1YPXW2) | [Shure SM7B](https://www.amazon.com/dp/B0002E4Z8M)  
- **Headphones**:  
  - Music: [Sennheiser HD 660S2](https://www.amazon.com/dp/B0BRT1ZN7Q)  
  - Bass: [Skullcandy Crusher ANC 2](https://www.amazon.com/dp/B0CD1DZ6RD)  
</details>

---

## Networking

### Routers & Modems
<details>
<summary>📶 ISP Setup & Tools</summary>

- **Router OS**:  
  [pfSense](https://www.pfsense.org/) | [OpenWrt](https://openwrt.org/) | [Pi-hole](https://pi-hole.net/) (Ad Blocking)  
- **Modems**:  
  [Motorola MB8600](https://www.amazon.com/dp/B0723599RQ) (DOCSIS 3.1) | [NETGEAR CM1000](https://www.amazon.com/dp/B01I5TJGSE)  
- **ISP Guides**:  
  [Bypass AT&T Fiber BGW320](https://youtu.be/3rIsq8tW8js) | [ISP Scams Explained](#common-scams)  
</details>

---

## Internet Service Providers (ISP)

### Key Providers Compared
<details>
<summary>📊 ISP Features & Scams</summary>

| Provider          | Pricing       | Coverage      | Key Features                          |
|-------------------|---------------|---------------|---------------------------------------|
| **AT&T**          | Competitive   | Nationwide    | No data caps, included gateway        |
| **Verizon Fios**  | Fiber-Optics  | Northeast US  | 24-month price guarantee              |
| **Xfinity**       | Regional      | Wide Coverage | Bundles (TV/Internet)                 |

#### Common Scams
- **Mbps vs MBps**:  
  ![Speed Conversion Table](https://github.com/Scrut1ny/Hardware-Guide/assets/53458032/91969929-b5a8-403f-ba4c-2059b9f2138f)  
- **Hidden Fees**: Equipment rentals, data caps, throttling.  
</details>

---

## Troubleshooting

### VGA LED/No Display Fixes
<details>
<summary>🛠️ Step-by-Step Solutions</summary>

1. Check GPU/motherboard connections.  
2. Test integrated graphics (if CPU supports iGPU).  
3. Clear CMOS → Reseat RAM/GPU.  
4. Update GPU firmware:  
   [NVIDIA Firmware Tool](https://us.download.nvidia.com/Windows/uefi/firmware/1.1/NVIDIA_DisplayID_Firmware_Updater_1.1-x64.exe)  
5. Test GPU in another system.  
</details>

---

## Software Tools
<details>
<summary>💻 Essential Utilities</summary>

- **WizTree**: [Disk Analyzer](https://www.diskanalyzer.com/)  
- **ValiDrive**: [Drive Validator](https://www.grc.com/validrive.htm)  
- **OpenRGB**: [RGB Control](https://openrgb.org/index.html)  
</details>

---

## Personal Preference Table

| GAMING 🎮          | PROFESSIONAL 💼     | ULTRABOOK 💻         |
|--------------------|---------------------|----------------------|
| 🪫 Short Battery   | 🪫 Short Battery    | 🔋 Long Battery      |
| High Performance   | Balanced Performance| Balanced Performance |
| H Series CPU       | H/X Series CPU      | U Series CPU         |
