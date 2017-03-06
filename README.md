# pi
raspberry pi codes and useful commands


#BLE commands
* type " hcicongig "  for listing the avilable ble device
* type "sudo hciconfig hci0 up"  where hci0 is my device
* to find mac id of required device type " sudo hcitool lescan "

* for opening gatttool type " sudo gatttool - B0:B4:48:D0:B4:03 -I " replace the mac id

#gatttool commands

* type " connect " form making a ble connection
* type " characteristics " for listing all charactristics on the GATT table, note down the uuuid and handle for read and write operations
* For writing to a perticular characteristics, type " char-write-req 0x001e 11 " this will write value "11" to the specified handle
* for reading a charactersistics value type "char-read-uuid 00001111-xxxx-xxx-xxx-xxxx"


#SSH configs

hostname -I
ssh -Y pi@192.168.1.5
