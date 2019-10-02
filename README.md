
![](/pkg/logo/L-LITEOS.png)
---

L-LITE OS Installer es un script escrito en Bash que ayudara a la instalacion de L-LITE OS. 
Es provisional mientras se crea la iso.

**Pasos**:
* Descarga la ISO de instalador por red de Devuan:https://devuan.org/get-devuan
* Instala devuan base(tty).
* Al iniciar sesion tendras que instalar git(`sudo apt install git git-core`) para poder clonar el repositorio.
* Actualizar Devuan(en caso no lo este) `sudo apt dist-upgrade`
* Luego de Actualizar Reinicia el sistema `sudo reboot`
* En la segunda encendida del sistema entonces procedemos a la instalacion del script con los siguentes comandos:

`git clone https://github.com/d33vliter/lliteos`

`cd lliteos`

`chmod +x ./installer`

`./installer`
