# Fuente: 
### **[Station x](http://https://www.stationx.net/nmap-cheat-sheet/ "Station x")**

### Especificación de target:

|  Switch | Ejemplo  | Descripción  |
| ------------ | ------------ | ------------ |
|   | nmap 192.168.1.1  | Escaneo de una ip sola  |
|   |  nmap 192.168.1.1 192.168.1.2 | Escaneo de varias IPs  |
|   | nmap 192.168.1.1-254  | Escaneo de un rango de Ips en una red  |
|   | nmap scanme.nmap.org  | Escaneo de un dominio  |
|  -iL  | nmap -iL targets.txt | Escaneo de targets desde un archivo  |
|  -iR  |  nmap -iR 100 | Escaneo de 100 hosts random  |
|  -- exclude  | nmap -- exclude 192.168.1.1  |  Excluir un host específico   |
