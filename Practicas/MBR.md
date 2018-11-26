**Que contiene el MBR?**

El sitema de particiones MBR contiene:  

  **-La tabla de particiones:**  es donde se encuentran las particiones primarias.

  **-Gestor de arranque:** Sirve para:

    -busca la particion activa 
    
    -busca el sector de arranque de la particion activa  

    -encontrar el gestor de arranque en la particion  

    -copiar el sector de arranque en la RAM  

    -pasa el control al sector de arranque de la RAM

  **-La signature:** Sirve para marcar la posición del sector de arranque
