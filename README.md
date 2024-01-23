# Hypervisor
Viskas apie Virtualias sistemas.

## XCP_ng konfiguravimas

Papildomos ISO failų saugyklos sukurimas naudojant konsolę:

  __$ mkdir -p /var/opt/iso_offline__ 
  
_(sukuriame saugyklos direktoriją)_
  
  __$ xe sr-create name-label=LocalISO type=iso device-config:location=/var/opt/iso_offline device-config:legacy_mode=true content-type=iso__ 
  
_(sukuriame reikiamas nuorodas)_

  __wget https://releases.ubuntu.com/23.10/ubuntu-23.10.1-desktop-amd64.iso__

_(atsisiunčiam reikiamą distributyvą)_
