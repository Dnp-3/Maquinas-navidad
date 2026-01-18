Nmap
![[Pasted image 20260102114159.png]]
Gobuster inicial (ip)
![[Pasted image 20260102115304.png]]
Gobuster final(IP)
![[Pasted image 20260102122231.png]]
Gobuster (DNS)
![[Pasted image 20260102132720.png]]
![[Pasted image 20260102135746.png]]
Robots.txt
![[Pasted image 20260102115400.png]]
Panel.php
![[Pasted image 20260102122341.png]]
Se ve la version del admin panel y se buscaran vulnerabilidades
Se prueban credenciales tipicas como root, admin...
Se da con que es user(admin) contraseña (admin)

Vulnerabilidades de Subrion CMS
![[Pasted image 20260116124216.png]]
Nos fijamos en este despues de leer varios y entrar en este se ve que se hace un rce: Subrion CMS 4.2.1 - Arbitrary File Upload | php/webapps/49876.py
Ejecutando la sell y expecificando en el panel el user (-l) y la password (-p) generamos un acceso a una shell
![[Pasted image 20260116124912.png]]
