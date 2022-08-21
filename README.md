# Si4732 ATS-25 All Band Radio Receiver
files and info on ATS-25/ATS25/ATS25+


![ats25](https://user-images.githubusercontent.com/44716085/185809159-f8e3d3a2-1067-4bdf-9d19-2dcd61e50f11.png)


---

Firmwares

pe0mgb / SI4735-Radio-ESP32-Touchscreen-Arduino
https://github.com/pe0mgb/SI4735-Radio-ESP32-Touchscreen-Arduino


IU4ALH / IU4ALH - Mod. V. 5.2a made by me IU4ALH Antonin and Mod. V. 4.0 ( original) made by Bernard Binns
https://github.com/IU4ALH/IU4ALH

---

ATS-25 sketch battery fix for BINNS MOD 4.0 or 5.3a

Change line in sketch #define BAT_INFO 25 → #define BAT_INFO 35

also look for float vsupply and chage to float vsupply = 3.724 * analogRead(BAT_INFO) / 2047; //3.324v
This string occurs three times in the firmware.

---
