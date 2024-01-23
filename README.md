# Hypervisor
Viskas apie Virtualias sistemas.

**XCP_ng

Papildomos ISO failų saugyklos sukurimas naudojant konsolę:

  __$ mkdir -p /var/opt/iso_offline__
  
  __$ xe sr-create name-label=LocalISO type=iso device-config:location=/var/opt/iso_offline device-config:legacy_mode=true content-type=iso__
