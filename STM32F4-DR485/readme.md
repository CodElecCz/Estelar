# 1. Description:

### GR-DH1_{hi}{low}_PRG.bin 
* version for flash via ST-LINK

### GR-DH1_{hi}{low}_PRG_nohttps.bin
* version for flash via ST-LINK
* no https web interface, no SRAM use

### GR-DH1_{hi}{low}.bin 
* version for flash via web interface

### GR-DH1_{hi}{low}_nohttps.bin
* version for flash via web interface
* no https web interface, no SRAM use

# 2. Versions change log:

### v01.15 (14.09.2021)
* FW update (upg.estelar.cz) 
* PowerSupply ADC from DMA, 600ms moving avg

### v01.14 (13.07.2021)
* DHCP default off 

### v01.13 (24.05.2021)
* Initialize LWIP with Ethernet disconnected 

### v01.12 (09.04.2021)
* SSDP/uPnP: block if socket 13000/13001
* LWPI timer 250ms to 40ms - Delayed ACK  

### v01.11 (19.02.2021)
* dhcp + web lan update
* auto ip (dhcp failed 4x) 169.254.x.x
* netbios (ip <> device name)
* SSDP/uPnP: response to broadcast MSEARCH (windows>network>refresh)
* SSDP/uPnP: first advertise in 2s after device start, next 60s 
* web fix: error if no access to internet (local js/jquery-3.5.1.min.js) 

### v01.10 (03.02.2021)
* web page fileupload password
* web minor updates
  
### v01.09 (29.01.2021)
* web user login session id authentication
* SSDP/uPnP 

### v01.08 (22.01.2021)
* mbedtls 2.25.0
* https

### v01.07 (21.12.2020)
* IAP flash via web interface
* UART data 9-bit