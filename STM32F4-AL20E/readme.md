# 1. Description:

### AL20E_{hi}{low}_PRG.bin 
* version for flash via ST-LINK

### AL20E_{hi}{low}_PRG_nohttps.bin
* version for flash via ST-LINK
* no https web interface, no SRAM use

### AL20E_{hi}{low}.bin 
* version for flash via web interface

### EL20E_{hi}{low}_nohttps.bin
* version for flash via web interface
* no https web interface, no SRAM use

# 2. Versions change log:

### in progress
* RestApi http://192.168.1.100:8080/acsline/v2/
- GET/POST config

### v01.06 (15.09.2021)
* RestApi http://192.168.1.100:8080/acsline/v2/
- POST DataEdit
* IO ACS Store (IN1,IN2,TL1,TL2,TMP,PowerSupply) + Debounce

### v01.05 (03.09.2021)
* RestApi http://192.168.1.100:8080/acsline/v2/
- POST/GET RelayPlan

### v01.04 (18.08.2021)
* ACS personal/access/plan/action/store
* RestApi http://192.168.1.100:8080/acsline/v2/
- POST memory
- POST/GET personal
- POST/GET access
- POST/GET plan
- POST/GET action
- GET/POST datetime
- GET commit
- GET store
- POST login - authorization Apikey

### v01.03 (16.07.2021)
* AL20E configuration for HW: 
- READER-1, READER-2 (wiegand)
- Dip switch 1 ON - wiegand, OFF - rs232
* web "Nastaveni ctecek" - read/save/last barcode
* web "Nastaveni rele" - read/save
* SNTP service "pool.ntp.org"

### v01.02 (21.06.2021)
* AL20E configuration for HW: 
- READER-1, READER-2 (rs232)
- DIP switch
- CRYPTO
- TAMPER
- PGM1, PGM2
  
### v01.01 (04.06.2021)
* AL20E created configuration for HW:
- ETH
- U-INPUT
- RS485
- SRAM + controller
- FLASH
- WATCHDOG
- GPIO - LEDs, DEF
- INPUTS - IN1, IN2, TL1, TL2
- OUTPUTS - REL1, REL2 ?nefuncni rele?