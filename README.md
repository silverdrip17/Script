# Scripts de Bash con Zenity

Este repositorio contiene varios scripts de bash que utilizan Zenity para la interacción con el usuario.

## Scripts

1. **Menú Principal**
   Este script muestra un menú con varias opciones. El usuario puede elegir entre consultar las tareas del sistema, crear usuarios, buscar archivos o directorios en el sistema, o salir del menú. Dependiendo de la opción seleccionada, se ejecuta un script diferente.

2. **Consultar Tareas del Sistema**
   Este script muestra un menú con varias opciones. El usuario puede elegir entre consultar todas las tareas del sistema, buscar una tarea específica del sistema, o volver al menú principal. Si el usuario elige consultar todas las tareas del sistema, se ejecuta el comando htop. Si el usuario elige buscar una tarea específica del sistema, se solicita al usuario que introduzca un valor y luego se busca ese valor en htop.

3. **Buscar Archivo o Directorio**
   Este script solicita al usuario que introduzca una ruta de archivo o directorio. Luego, verifica si la ruta existe en el sistema. Si la ruta existe, se muestra un mensaje de confirmación. Si no existe, se muestra un mensaje de error.

4. **Crear Usuario**
   Este script solicita al usuario que introduzca un nombre de usuario. Luego, crea un nuevo usuario con ese nombre y establece una contraseña para el usuario. Si el proceso se completa correctamente, se muestra un mensaje de confirmación. Si ocurre un error, se muestra un mensaje de error y los detalles del error se guardan en un archivo llamado error.txt.

## Instalación

Para ejecutar estos scripts, debes tener instalado Zenity en tu sistema. Si no lo tienes, puedes instalarlo con el siguiente comando en sistemas basados en Debian, como Ubuntu:

```bash
sudo apt install zenity
