## Demomios en Linux:
1) Servicio FTP -> Dependientes del superdemonio de red (inetd)
2) Servicio Telnet -> Dependientes del superdemonio de red (inetd)
3) Servicio SSH -> Independientes (stand alone)

## SERVICIO FTP

Instalamos lo necesario para el superdemonio de red inetd -> `sudo apt install openbsd-inetd`

Maneras -> Arrancar / Parar / Reiniciar Demonios:
1. `sudo /etc/init.d/nombre_demonio restart/start/stop` (Prefiblemente usar esta)
2. `sudo service nombre_demonio restart/start/stop`
3. `sudo systemctl restart`
