# Entorno-Virtual
Aprender sobre la decodificación de entornos virtuales en python para windows

****
****
- Paso1: entrar al cmd y escribir el comando pip3 list 
- Paso2: verificar que esten las librerías como **virtualenv** 
- Paso3: instalar la libería con pip install virtualenv 
- Paso4: Entrar a la carpeta donde se creó el repositorio y digitar el comando **virtualenv -p python3 myenv** este crea el entorno virtual 



### *Ahora para activarlo 
Nos adentramos al archivo con activate de la siguiente manera 
**.\myenv\Scripts\activate**

### *requirements.txt 
Si quieres mantener un estandar en la descarga de paquetes de un entorno encontes ejecutar mientras está activado el siguiente comando 
**pip freeze > requirements.txt**

### *Ahora para desactivarlo
Utilizamos el siguiente comando en la terminal 
**deactivate** 

### *Usando Otro entorno
Bueno para usar los mismo paquetes solo hay que copiar la carpeta Scripts y el texto requirements.txt y activar el entorno nuevo posterior a ello darle al siguiente comando 
**pip install -r .\requirements.txt**

------
**"Listo ya tienes tu entorno virtual, espero que te haya servido"**
---
