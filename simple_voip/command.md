```
Switch(config)#vlan 10
Switch(config-vlan)#name data
Switch(config-vlan)#vlan 100
Switch(config-vlan)#name voi
Switch(config-vlan)#name voice

###

Switch(config)#int f0/1
Switch(config-if)#switchport mode access
Switch(config-if)#switchport access vlan 10
Switch(config-if)#switchport voice vlan 100
Switch(config-if)#exit
```
