# Proyecto de ROS con Turtle Sim
Este README proporciona instrucciones sobre cómo ejecutar un proyecto de ROS que utiliza TurtleSim. Este proyecto es una introducción básica al funcionamiento de ROS y cómo interactuar con un robot simulado.

# Requisitos previos
Antes de ejecutar el proyecto, asegúrate de tener instalado:
ROS (Robot Operating System): Asegúrate de tener ROS instalado en tu sistema. Puedes seguir las instrucciones de instalación en el sitio web oficial de ROS. https://wiki.ros.org/Installation/Windows

# Ejecución del proyecto
Para ejecutar el proyecto hay que:
1. Ejecutar como administrador el acceso directo de ROS
2. Ejecutar el comando ```roscore``` en una terminal de ROS
3. Abrir otra ventana de ROS
4. Posicionarse en la carpeta adolfo_saucedo, utilizando el comando ```cd..``` y ```cd adolfo_saucedo```
5. Ejecutar el comando ```devel\setup.bat```
6. Ejecutar el comando ```rosrun turtlesim turtlesim_node```
7. Abrir otra terminal de ROS y repetir el paso 4 y 5
8. Ejecutar el comando ```rosrun turtle_unida src/mover.py```.

Obs: las mismas deben ser ejecutadas en otra terminal de ROS, una seguida de otra, sin cerrar la anterior.
