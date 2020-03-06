# proyectoSL
Trabajo del diseño de redes y creación de vlans
Ingresar al switch en configuracion global
no ip domain-lookup
service password-encryption
enable secret class
banner motd #
Unauthorized access is strictly prohibited. #
line con 0
password cisco
login
logging synchronous
line vty 0 15
password cisco
logging synchronous
login
exit

Creacion de VLANS para la Urbanizacion Vista del Sol tomando de referencia el SWITCH2
S1(config)# vlan 2
S1(config-vlan)# name Manzana1
S1(config-vlan)# vlan 3
S1(config-vlan)# name Manzana2
S1(config-vlan)# vlan 4
S1(config-vlan)# name Manzana3
S1(config-vlan)# vlan 5
S1(config-vlan)# name Manzana6
S1(config-vlan)# vlan 6
S1(config-vlan)# name Manzana7
S1(config-vlan)# end

Creacion de VLANS para la Urbanizacion Vista del Sol tomando de referencia el SWITCH2
S2(config)# vlan 7
S2(config-vlan)# name Manzana4
S2(config-vlan)# vlan 8
S2(config-vlan)# name Manzana5
S2(config-vlan)# vlan 9
S2(config-vlan)# name Manzana8
S2(config)# vlan 10
S2(config-vlan)# name MAnzana9
S2(config-vlan)# vlan 11
S2(config-vlan)# name Manzana10
S2(config-vlan)# end
