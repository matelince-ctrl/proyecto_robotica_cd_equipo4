proyecto_robotica_cd_equipo4
Estación 4 

Este repositorio contiene el desarrollo de la estación 4 de una línea automatizada para ensamblaje de PCB. La estación utiliza un manipulador SCARA de configuración PRR para transportar una PCB hacia una cama caliente, realizar el proceso térmico y enviarla a la siguiente estación.

Tecnologías utilizadas

- ROS 2
- MoveIt 2
- ros2_control
- ESP32
- C/C++
- Comunicación Serial/USB

Arquitectura general

El sistema se divide en dos niveles principales:
Alto nivel: ejecutado en ROS 2, encargado de la coordinación de la estación, planificación de movimiento, supervisión y comunicación.
Bajo nivel: ejecutado en la ESP32, encargado del control de posición de los motores, lectura de sensores, control de temperatura y manejo de la herramienta.

