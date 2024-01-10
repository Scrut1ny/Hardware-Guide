## Electronics Store Websites
* [newegg](https://www.newegg.com/)
* [Amazon](https://www.amazon.com/gp/browse.html?node=172282)
* [Micro Center](https://www.microcenter.com/)

# ===== CPU (Processor) =====
* [Intel® Core™ Processor Suffixes](https://www.intel.com/content/www/us/en/support/articles/000058567/processors/intel-core-processors.html)
* [Intel® Processor Names and Numbers](https://www.intel.com/content/www/us/en/processors/processor-numbers.html)
* [AMD Ryzen CPU Names](https://www.howtogeek.com/all-the-letters-in-amd-ryzen-cpu-names-explained/)

## Processor Breakdown (Example)
* Core i7-11800H
  * i7 = High-Performance Series/Tier
  * 11 = 11th Generaton
  * 800 = Specific Model #
  * H = High Performance
* Ryzen 7 5800X
  * 7 = 7th Generation (Note: AMD Ryzen processors don't strictly follow a numeric generation naming convention like Intel)
  * 5800 = Specific Model #
  * X = High-Performance Desktop Processor

## Processor Overview
| Tier     | Intel          | AMD             | Description                               | Average Price Range      | Power Consumption Range  |
|----------|----------------|-----------------|-------------------------------------------|--------------------------|--------------------------|
| Entry    | Core i3         | Ryzen 3         | Budget-Friendly                           | $100 - $200              | Low to Moderate          |
| Mid-Range| Core i5         | Ryzen 5         | Mainstream Performance                    | $200 - $300              | Moderate to Moderate-High|
| High-Perf| Core i7         | Ryzen 7         | High-Performance                          | $300 - $500              | Moderate-High            |
| Enthusiast| Core i9        | Ryzen 9         | Enthusiast and High-End Performance       | $500 - $1000+            | High                     |

## Processor Suffixes Reference
| Suffix  | Intel Description                                     | AMD Description                                      |
|---------|-------------------------------------------------------|-------------------------------------------------------|
| U       | Ultra-Low Power                                       | Ultra-Low Power                                       |
| Y       | Extremely Low Power                                   | -                                                     |
| H       | High Performance Graphics                             | -                                                     |
| HQ/HK   | High-Performance, Unlocked (Mobile)                   | High-Performance (HS may be efficient)                 |
| G       | Iris Xe Graphics                                      | Radeon Vega Graphics                                  |
| C/K     | Unlocked Multiplier                                   | -                                                     |
| F       | No Integrated Graphics                                | -                                                     |
| T       | Power-Optimized                                       | Power-Optimized                                       |
| X       | Extreme Performance                                   | High Performance                                      |
| E       | Embedded                                              | -                                                     |
| XT      | -                                                     | eXtended Frequency Range, High Performance            |
| GE      | -                                                     | Graphics Edition (Integrated Graphics)                |
| PRO     | -                                                     | Professional Series                                   |
| +       | Enhanced or Advanced version                          | -                                                     |
| S       | Special Edition                                       | -                                                     |
| -       | -                                                     | Special Edition                                       |

# ===== Motherboard =====

## Form Factors
|  | Mini-ITX | MicroATX | ATX |
|-|-|-|-|
| Size | 9.0 x 7.5 inches | 9.6 x 9.6 inches | 12 x 9.6 inches |
| Expansion Slots | 1 | 4 | 7 |
| RAM | DIMM | DIMM | DIMM |
| RAM Slots | 2 | Up to 4 | Up to 8 |
| GPUs | Up to 1 | Up to 3 | Up to 4 |
| SATA ports | Up to 6 | Up to 8 | Up to 12 |

## BIOS/UEFI Flashback (USB)
* Brick Recovery: Utilize BIOS/UEFI Flashback with a formatted USB containing a compatible BIOS/UEFI to revive a bricked motherboard.
* Steps
  * USB Setup:
    * Format USB to FAT32.
    * Download latest BIOS.
    * Save to USB root.
  * Flashback:
    * Power off.
    * Insert USB.
    * Press & hold Flashback button.
  * Wait & Power On:
    * Wait for process.
    * Power on; check updated BIOS.

## CMOS Battery (CR2032 3V Lithium Battery)
* [LiCB](https://www.amazon.com/dp/B071D4DKTZ)
* [Energizer](https://www.amazon.com/dp/B0002RID4G)

## Clear/Reset CMOS Methods
* CMOS Reset Button (if available):
  * Some motherboards have a dedicated CMOS reset button.
  * Locate the button on the motherboard.
  * Power off the computer and press the button for a few seconds.
* Jumper Method:
  * Locate the CMOS jumper on the motherboard.
  * Power off the computer.
  * Move the jumper from its default position to the clear position.
  * Wait for a few seconds, then move the jumper back to its original position.
* Battery Removal:
  * Power off the computer and disconnect it from the power source.
  * Locate the CMOS battery on the motherboard.
  * Remove the CMOS battery carefully.
  * Wait for about 5-10 minutes, then reinsert the battery.
* Power Drain Method:
  * Power off the computer and unplug it.
  * Press and hold the power button for 15-20 seconds.
  * Reconnect the power and turn on the computer.
* BIOS/UEFI Settings:
  * Enter the BIOS/UEFI settings during system boot (usually by pressing DEL, F2, or another key).
  * Navigate to the "Reset to default" or "Load optimized defaults" option.
  * Save changes and exit.

## EZ Debug LED
* 🟥 CPU
  * indicates CPU is not detected or fail.
* 🟨 DRAM
  * indicates DRAM is not detected or fail.
* ⬜ VGA
  * indicates GPU is not detected or fail.
* 🟩 BOOT
  * indicates the booting device is not detected or fail.

# ===== GPU (Graphics Processing Unit) =====

# ===== Router =====

## Firmware
* [pfsense](https://www.pfsense.org/)
  * Addon: pfBlocker-NG
* [OpenWrt](https://openwrt.org/)

## Software
* [Pi-hole](https://pi-hole.net/)

## Physical Connections
* ISP (Coax) --> MoCA Converter/Adapter --> Router
* ISP (SFP/Fiber) --> SFP/Fiber to RJ45/Ethernet Converter/Adapter --> Router

* Converter/Adapters
  * [ScreenBeam Bonded MoCA 2.0 Network Adapter](https://www.amazon.com/dp/B013J7OBUU)

# ===== Storage =====

## Adapters
* M.2 SATA SSD to 2.5" SATA
  * [M.2 SATA SSD to 2.5" SATA](https://www.amazon.com/dp/B00ITJ7U20)
  * [M.2 SATA SSD to 2.5" SATA](https://www.amazon.com/dp/B01N6PMZLW)
* M.2 NVMe SSD to 2.5" SATA

# ===== Troubleshooting =====

* Issue: "EZ Debug LED" shows/displays the "VGA" LED light - No display and "failure to boot into UEFI/BIOS."
  * Solutions:
    * Check if your CPU supports iGPU (Integrated Graphics); attempt to get output from the motherboard instead of the GPU.
    * Verify cable connections; ensure all are securely in place.
    * Attempt taking out the GPU, cleaning the pins, and blowing out all dust etc then reinserting the GPU.
    * Troubleshoot RAM issues; try booting with 1 or 2 RAM sticks, testing different sticks as one may be faulty.
    * Clear the CMOS.
    * If the motherboard is potentially bricked, update the UEFI/BIOS by placing a fresh image on a flash drive. Connect it to the Flash BIOS port in the I/O port area and use the Flash BIOS Button if available. If you don't have this option, you will have to aquire a new motherboard.
    * If possible, check how the GPU acts in another currently working system.
    * [NVIDIA GPU Firmware Update Tool for DisplayID](https://nvidia.custhelp.com/app/answers/detail/a_id/5233/~/nvidia-gpu-firmware-update-tool-for-displayid) - [Download Link](https://us.download.nvidia.com/Windows/uefi/firmware/1.1/NVIDIA_DisplayID_Firmware_Updater_1.1-x64.exe)


## Personal Preference
| GAMING | PROFESSIONAL | ULTRABOOK |
|-|-|-|
| 🪫 Short Battery Life | 🪫 Short Battery Life | 🔋 Long Battery Life |
| High Performance | Balanced Performance | Balanced Performance |
| H Series | H, X Series | U Series |
