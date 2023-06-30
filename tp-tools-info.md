![TP Tools](./tp-tools.png)

# TP-Tools (beta)
**FREE for commercial use**


A small collection of tools that simplify the commissioning and programming of Fanuc robots.

The programs are licensed under the

*CC BY-ND 4.0 Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)*


https://creativecommons.org/licenses/by-nd/4.0/

- The distribution is allowed.
- Modification of the binary file is not allowed.
- The naming of the author is given, because the binary file contains information

Even if the Creative Commons license was not made for software, it serves its purpose for us here.

A license file does NOT have to be copied to the robot controller.

**Thereby nothing stands in the way of commercial use.**

---
### Controller and Version

- R-30iA (< V7.50)
- R-30iB (< V8.10)
- R-30iBPlus (<> V9.10)
- R-30iBPlus/CRX (< V9.40/42)

If there is no corresponding subfolder, the version is (currently) not available.

If the Arg-Wizard can be used or there is a CRX plug-in this is described or explained.

---


## RANDOM


Generates a (pseudo) random number and writes the value into the corresponding register.

Uses $FAST_CLOCK to initialize, but can also be configured.

---

## TP_WRITE


TP_WRITE can be used to write single-line (dynamic) messages to various "screens".

Among others, the following are available for selection:

  - Console
  - UserScreen
  - TPError

The usage with the Arg-Wizard is in development.
The CRX_PlugIn is under development

---



## set_invisib(le)


Make programs temporarily invisible or hide them
  
 ---

## PING


A simple program for "pinging" network participants


---


## CRC-Tools


Enables the calculation of different checksums:
  
  - MODBUS
  - CCITT
  - MCRF4XX

---

## ~~MESSAGE~~


Replaces the internal command

    MESSAGE[string].


***TP_WRITE*** is the more powerful alternative :-)

---

Copyright (c) 2023 Backdate Software/Andreas Wissing

---

