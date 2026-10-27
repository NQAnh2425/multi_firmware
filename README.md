# multi_firmware
Store space for multiple firmware
Supported SoC/MCU:
 - ST: stm32f103c8t6 / stm32f405rgt6
 - ESP: esp32s3 (dev module N16R8) / esp32 wroom (Xtensa dual-core dev kit)
 - 
===========================================================================
Step for updating firmware:
- compile & get new binary or hex file
- replace old binary/hex file by the new one
- update version in firmware_infor.json file
