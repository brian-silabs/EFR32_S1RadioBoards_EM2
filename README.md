# EFR32_S1RadioBoards_EM2 (BLE & GPD DMP)

## Description
This projects aims to be a simple source holder to achieve datasheet low power numbers of Silicon Labs EFR32 Series 1 chipsets on Radio Boards
It initializes :
* DCDC to Low Power Mode
* Voltage Scaling to Low Power Mode
* LFXO as LF Clock Source
* Powers down the MX25 SPI Flash (import configuration header from <Gecko SDK suite location>/hardware/kit/<Your kit>)

## Disclaimer ##
Unless otherwise specified in the specific directory, all examples are considered to be EXPERIMENTAL QUALITY which implies that the code provided in the repos has not been formally tested and is provided as-is.  It is not suitable for production environments.  In addition, this code will not be maintained and there may be no bug maintenance planned for these resources.