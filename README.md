# pfsense-patches

Pfsense patches

Creating patches
login as root user on pfsense appliance

copy original template file

cp /etc/inc/interfaces.inc /etc/inc/interfaces.inc.org

edit /etc/inc/interfaces.inc and test changes

create patch diff -u /etc/inc/interfaces.inc.org /etc/inc/interfaces.inc > interfaces.inc.add-vlan-trunk-to-vm.patch

upload patch to this repo