# Intel 11th Generation Opencore EFI for MSI MEG Z490i Unify

EFI to boot macOS on 11th Generation Intel Hackintosh for MSI MEG Z490i Unify.  
For my own use.  
You can take and re-use it, but I may not be able to provide support.

## My System Specifications:

1. Processor: Intel® Core™ i7-11700K
2. GPU: Saphire Pulse AMD RX580 4GB (Ellesmere)
3. RAM: 16GB
4. SSD: (2nd Slot M.2) ADATA SX8200PNP Media 256GB
5. Motherboard: MSI MEG Z490i Unify

## F.A.Q.
1. On board WiFi and Ethernet<sup>1</sup> works.
2. On board Bluetooth works (Some device is not stable though).

## Reference
<sup>1</sup> On board internet need to enter the command below in the terminal.
```
sudo ifconfig en0 media 1000baseT mediaopt full-duplex
```

## Update on 10<sup>th</sup> October 2021
1. Successfully update to Opencore 0.7.4.
2. Succefully update the kernel extensions to their latest version.
3. No problematic problems found.

## About Me
Pangeran Wiguan  
My Blog: [pangeranWiguan.com](https://pangeranwiguan.com "Pangeran Wiguan's Blog")
