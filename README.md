# box-o-ai BOM

| Item               | Part Number / Model             | Description                                       | Qty   | Vendor / Link                                                                 | Unit Price (USD) |
|--------------------|---------------------------------|---------------------------------------------------|-------|--------------------------------------------------------------------------------|------------------|
| **SoC**            | RK3588S                         | Rockchip 8‑core SoC with 6 TOPS NPU               | 1     | LCSC [C2940552](https://lcsc.com/product-detail/Rockchip-RK3588S_C2940552.html) | $88.27 :contentReference[oaicite:0]{index=0}   |
| **RAM**            | K4F6E3S4HM‑MGCJ                 | Samsung 16 Gbit LPDDR4‑3733 Mbps FBGA‑200 (2 GB)   | 2     | YIC International Co. Ltd.                                                     | $17.12 :contentReference[oaicite:1]{index=1}   |
| **eMMC Storage**   | EMMC16G‑MW28‑01E10              | Kingston 16 GB eMMC 5.1 HS400, 153‑FBGA            | 1     | DigiKey (5297-EMMC16G-TB29-90F01-ND)                                           | $12.87 :contentReference[oaicite:2]{index=2}   |
| **NVMe Connector** | 123A‑40M00                      | ATTEND 67‑pos M.2 NGFF socket, Key M               | 1     | Mouser (123A‑40M00)                                                           | $2.12  :contentReference[oaicite:3]{index=3}   |
| **PMIC**           | RK809‑2                         | Rockchip power‑management IC, QFN‑68               | 1     | LCSC (C2940552)                                                               | $3.05  :contentReference[oaicite:4]{index=4}   |
| **Power Input**    | USB4220‑03‑0930‑C               | GCT USB‑C Receptacle 16 pos, 5 A / 48 V SMD        | 1     | Mouser (640‑USB4220030930C)                                                   | $0.92  :contentReference[oaicite:5]{index=5}   |
| **Buck Regulator** | MP2315GJ‑P                      | Monolithic Power Systems 3 A buck, TSOT‑23‑8      | 3     | DigiKey (1589-1103-2-ND)                                                      | $1.31  :contentReference[oaicite:6]{index=6}   |
| **WiFi + BT Module**| AP6256                          | AMPAK dual‑band Wi‑Fi 802.11ac + BT 5.0 SIP        | 1     | LCSC (C5248079)                                                               | $8.64  :contentReference[oaicite:7]{index=7}   |
| **Ethernet PHY**   | RTL8211F‑CG                     | Realtek Gigabit Ethernet PHY, RGMII, QFN‑40       | 1     | LCSC                                                                         | $0.72  :contentReference[oaicite:8]{index=8}  |
| **USB Hub/Port**   | FE1.1S‑BQFN24B                  | Terminus 4‑port USB 2.0 hub controller, WQFN‑24   | 1     | LCSC (C6776948)                                                               | $0.73  :contentReference[oaicite:9]{index=9}  |
| **Debug UART**     | CP2102N‑A02‑GQFN28              | Silicon Labs USB 2.0‑to‑UART bridge, QFN‑28       | 1     | DigiKey (336-5889-ND)                                                         | $4.32  :contentReference[oaicite:10]{index=10} |
| **NPU (optional)** | Coral USB Accelerator           | Google Edge TPU USB ML accelerator                | 1     | Coral.ai                                                                     | $59.99 :contentReference[oaicite:11]{index=11} |
| **Heatsink/Fan**   | —                               | Aluminum passive heatsink + 5 V cooling fan       | 1     | MakerFocus (2‑pack)                                                          | $3.45  :contentReference[oaicite:12]{index=12} |
| **Misc**           | —                               | Crystals, passives, ESD diodes, resistors, caps   | many  | LCSC / JLCPCB                                                                | $0.50 (est.)    |

*Notes:*
- Qty for buck regulators assumes 3 rails; adjust as needed.
- “Misc” is an estimated placeholder; final BOM should break out per net.
