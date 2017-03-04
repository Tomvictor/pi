# pi
raspberry pi codes and useful commands


#BLE commands
* type " hcicongig "  for listing the avilable ble device
* type "sudo hciconfig hci0 up"  where hci0 is my device
* to find mac id of required device type " sudo hcitool lescan "

* for opening gatttool type " sudo gatttool - B0:B4:48:D0:B4:03 -I " replace the mac id
