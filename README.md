# box-o-ai

Parts
--

| Item               | Part Number / Model         | Description                                      | Qty | Vendor / Link                          |
|--------------------|-----------------------------|--------------------------------------------------|-----|----------------------------------------|
| **SoC**            | RK3588S                     | Rockchip 8-core SoC with 6 TOPS NPU              | 1   | [OKdo](https://www.okdo.com) / Allnet |
| **RAM**            | K4F6E304HB-MGCH             | 8GB LPDDR4X BGA DRAM (Samsung)                   | 2   | DigiKey / Mouser                       |
| **eMMC Storage**   | BGA153 16GB (Kingston/Micron)| 16GB onboard flash                               | 1   | Arrow / LCSC                           |
| **NVMe Connector** | M.2 Key M Socket            | PCIe NVMe SSD support (2242/2280)                | 1   | LCSC / Mouser                          |
| **PMIC**           | RK809                       | Power Mgmt IC matched to RK3588S                 | 1   | Rockchip distributor                   |
| **Power Input**    | USB-C PD or DC Barrel Jack  | 5V–12V power connector                           | 1   | SparkFun / DigiKey                     |
| **Buck Regulator** | MP2315 / TPS62147           | 3A/5A buck converters for core voltage rails     | 2–3 | Mouser / DigiKey                       |
| **WiFi+BT Module** | AP6256 (Broadcom)           | Dual-band WiFi + BT 5.0 (via SDIO/UART)          | 1   | AliExpress / Seeed Studio             |
| **Ethernet PHY**   | RTL8211F                    | Gigabit Ethernet PHY (RGMII)                     | 1   | LCSC / DigiKey                         |
| **USB Hub/Port**   | FE1.1s / USB 3.0 sockets    | USB hub/controller for peripherals               | 1–2 | LCSC / SparkFun                        |
| **Debug UART**     | 3-pin header / CP2102N      | Serial console/debug interface                   | 1   | Adafruit / SparkFun                    |
| **NPU (optional)** | Google Coral TPU USB        | 4 TOPS USB TPU accelerator (if extra needed)     | 1   | [Coral.ai](https://coral.ai)           |
| **Heatsink/Fan**   | Passive aluminum + 5V fan   | RK3588S gets hot under load                      | 1   | Any electronics vendor                 |
| **Misc**           | Crystals, passives, ESD     | Supporting caps/resistors, protection diodes     | many| LCSC / JLCPCB                          |
