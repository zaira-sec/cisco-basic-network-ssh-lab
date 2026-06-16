# cisco-basic-network-ssh-lab
Configuración completa de una red en Cisco Packet Tracer: PCs, router, switches, conectividad end-to-end y acceso remoto seguro mediante SSH.

🖥️ Cisco Packet Tracer – Basic Network + Secure SSH Access
Este proyecto demuestra la configuración completa de una red en Cisco Packet Tracer, incluyendo:

Conexión física de dispositivos

Configuración de PCs

Configuración de un router (R1)

Configuración de switches (S1, S2)

Verificación de conectividad extremo a extremo

Implementación de seguridad básica

Acceso remoto seguro mediante SSH

🔧 Tecnologías utilizadas
Cisco Packet Tracer

IOS CLI (Router & Switch)

SSH v2

IPv4

VLAN 1 (SVI)

🛠️ Configuraciones realizadas
✔️ PCs configuradas
Dirección IP

Máscara

Gateway

Pruebas de conectividad (ping)

✔️ Router configurado
Interfaces IP

Default gateway

SSH habilitado

Usuario local seguro

enable secret

Guardado de configuración

✔️ Switches configurados
Hostname

VLAN 1 con IP

Contraseñas de consola y enable

Banner MOTD

SSH habilitado

Líneas VTY seguras

🔐 Seguridad implementada
service password-encryption

enable secret

Acceso remoto solo SSH

Usuario local con contraseña cifrada

Telnet deshabilitado

🧪 Verificación
Ping entre PC1 ↔ S1 ↔ S2 ↔ PC2

Ping al router

Acceso SSH desde PC

Telnet bloqueado correctamente

📁 Archivos incluidos
.pkt del proyecto

Capturas de pantalla de los pings

Capturas de SSH funcionando

Configuración completa (show run)

🎯 Resultado final
Red completamente funcional, segura y administrable de forma remota mediante SSH.
