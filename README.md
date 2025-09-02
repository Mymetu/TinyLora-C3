# TinyLora-C3
The cheapest Meshtastic terminal, compatible with various LoRa modules.


## Files

- **SCH_Schematic1_2025-09-02.pdf** → Circuit schematic  
- **TinyLora-C3.zip** → PCB manufacturing files  

## Supported Modules

| Module Name | Chip | Price (CNY) | BOM Cost (excluding PCB & antenna, USD) | Purchase Source | Notes |
| ----------- | ---- | ----------- | -------------------------------------- | --------------- | ----- |
| 255MN-L03   | LLCC68 | 9.9   | ~19.9 | Taobao (255mesh shop) | LLCC68 does not support Meshtastic long mode, mediumslow recommended |
| RA-01SC     | LLCC68 | 11.9  | ~21.9 | Taobao (Youxin, IPEX version) | LLCC68 does not support Meshtastic long mode, mediumslow recommended |
| HT-RA62     | SX1262 | 21.9  | ~31.9 | Taobao (Huite Automation shop) | Full Meshtastic LoRa mode support |
| RA-01SC-P   | LLCC68 | 16.5  | ~26.5 | Taobao (Youxin, IPEX version) | LLCC68 does not support Meshtastic long mode, mediumslow recommended<br>High power, default LDO not sufficient; add an extra LDO or use a higher-power LDO/DCDC<br>External amplifier, software setting 22 actually gives 29 |
| RA-01S-P    | SX1268 | 21.2  | ~31.2 | Taobao (Youxin, IPEX version) | Full Meshtastic LoRa mode support<br>High power, default LDO not sufficient; add an extra LDO or use a higher-power LDO/DCDC<br>External amplifier, software setting 22 actually gives 29 |

## Photos





Custom License

This project is free for personal and educational use only.
Commercial use is strictly prohibited.
