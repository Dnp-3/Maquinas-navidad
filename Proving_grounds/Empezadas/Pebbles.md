SQL injection 
Nmap
![[Pasted image 20260105190331.png]]
3305: apache default
8080: tomcat
Gobuster:
![[Pasted image 20260114174443.png]]
:3305/zm
![[Pasted image 20260116133929.png]]

Searchsploit:
![[Pasted image 20260116133808.png]]

Miramos las interesantes como puede ser la que es justo de nuestra version 1.29.0 
Zoneminder 1.29/1.30 - Cross-Site Scripting / SQL Injection / Session F | php/webapps/41239.txt

Vamos al burp y cambiamos el post como nos indican en la explotacion:
![[Pasted image 20260116141307.png]]

Despues nos vamos al Target para buscar el response a este post:
![[Pasted image 20260116141346.png]]

![[Pasted image 20260116135538.png]]


