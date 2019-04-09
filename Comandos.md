# Comandos <h5>

> información sobre comandos basico y avanzados en linea de comandos de linux

__# id__ = Información del usuario

__# tail__ = se visualizan las ultimas 10 lineas de un archivo o puede modificarse por las necesarioas con el argumento -1,2,3...n

__# head__ = se muestra las primeras 10 lineas de un archivo o se puede modificar por las necesarias con el argumento -1,2,3...n

__# useradd "Nombre"__ = agregar un usuario nuevo
  * -c = agregar un nombre completo para el campo gecos
  
  * -g = cambiar el grupo principal
  
  * -aG = conservar varios grupos
  
 __# passwd "usuario"__ = cambiar o colocar contraseña para un usuario
  
 __# usermod "nombre"__ = modificar usuario
  
  * -L = bloquear usuario
  
  * -U = desbloquear usuario
  
  * Podemos agregar los campos anteriosres que son: cambiar grupo, conservar ambos grupos
  
  __# userdel -r "usuario"__ = elimina usuario y su directorio
