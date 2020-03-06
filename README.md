# proyectoSL
Trabajo del diseño de redes y creación de vlans
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

S1(config)# vlan 10
S1(config-vlan)# name Estudiantes
S1(config-vlan)# vlan 20
S1(config-vlan)# name Docentes
S1(config-vlan)# vlan 99
S1(config-vlan)# name Administración
S1(config-vlan)# end

Creacion de VLANS para la Urbanizacion Vista del Sol tomando de referencia el SWITCH2
S2(config)# vlan 10
S2(config-vlan)# name Estudiantes
S2(config-vlan)# vlan 20
S2(config-vlan)# name Docentes
S2(config-vlan)# vlan 99
S2(config-vlan)# name Administración
S2(config-vlan)# end

