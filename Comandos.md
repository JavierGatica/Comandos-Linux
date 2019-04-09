# Comandos <h5>

> información sobre comandos basico y avanzados en linea de comandos de linux

_# id = Información del usuario_

_# tail = se visualizan las ultimas 10 lineas de un archivo o puede modificarse por las necesarioas con el argumento -1,2,3...n_

_# head = se muestra las primeras 10 lineas de un archivo o se puede modificar por las necesarias con el argumento -1,2,3...n_

_# useradd "Nombre" = agregar un usuario nuevo_
  * -c = agregar un nombre completo para el campo gecos
  
  * -g = cambiar el grupo principal
  
  * -aG = conservar varios grupos
  
  _# passwd "usuario" = cambiar o colocar contraseña para un usuario_
  
 _# usermod "nombre" = modificar usuario_
  
  * -L = bloquear usuario
  
  * -U = desbloquear usuario
  
  * Podemos agregar los campos anteriosres que son: cambiar grupo, conservar ambos grupos
  
  _# userdel -r "usuario"_ = elimina usuario y su directorio
