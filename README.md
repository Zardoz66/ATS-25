# Si4732 ATS-25 All Band Radio Receiver
files and info on ATS-25/ATS25/ATS25+


https://github.com/Zardoz66/ATS-25/blob/bc22cdae2abf06848d40267293facccd16021898/ats25.png


---


ATS-25 sketch battery fix for BINNS MOD 4.0 or 5.3a

Change line in sketch #define BAT_INFO 25 → #define BAT_INFO 35

also look for float vsupply and chage to float vsupply = 3.724 * analogRead(BAT_INFO) / 2047; //3.324v
This string occurs three times in the firmware.

---
