# Hypervisor
Viskas apie Virtualias sistemas.

## XCP_ng konfiguravimas

Papildomos ISO failų saugyklos sukurimas naudojant konsolę:

  __$ mkdir -p /var/opt/iso_offline__ (sukuriame saugyklos direktoriją)
  
  __$ xe sr-create name-label=LocalISO type=iso device-config:location=/var/opt/iso_offline device-config:legacy_mode=true content-type=iso__ (sukuriame reikiamas nuorodas)
