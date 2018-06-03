# SwitchBlade

**DO NOT UPDATE FOR THIS!**

Instantly loads up Horizon with homebrew enabled for 2.x/4.x/5.x Switches with all the other functions of Hekate removed. It is recommended to only use this for development, anyone else should wait for Atmosphere.

* Starting the payload while holding Vol+ will power off the device.
* Starting the payload while holding Vol- will start Horizon without homebrew enabled.
* Starting it normally will start Horizon with homebrew enabled.

## switchblade.ini File

* The `[stock]` section is when you startup SwitchBlade holding down the Vol- buttons.
* The `[hen]` section is when you startup SwitchBlade without holding any buttons.

| Config option      | Description                                                |
| ------------------ | ---------------------------------------------------------- |
| warmboot={SD path} | Replaces the warmboot binary.                              |
| secmon={SD path}   | Replaces the security monitor binary.                      |
| kernel={SD path}   | Replaces the kernel binary.                                |
| kip1={SD path}     | Replaces/Adds kernel initial process. Multiple can be set. |
| fullsvcperm=1      | Disables SVC verification.                                 |
| debugmode=1        | Enables Debug mode.                                        |

## Credits

**Based on the awesome work of:** naehrwert, and st4rk  
**Thanks to:** derrek, nedwill, plutoo, shuffle2, smea, thexyz, and yellows8  
**Greetings to:** fincs, hexkyz, SciresM, Shiny Quagsire, and WinterMute  
**Open source and free packages used:**
* FatFs R0.13a (Copyright (C) 2017, ChaN)
* bcl-1.2.0 (Copyright (c) 2003-2006 Marcus Geelnard)
