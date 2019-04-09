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

__#chage -d 0 "usuario"__ = solicitar el cambio de contraseña al iniciar sesion
  
    * -l = informacion sobre el usuario y su estatus, con respecto a la contraseña y su caducidad
  
    * -I # = la cuenta queda on la opcion de recuperar despues de los dias establecidos
  
    * -W # = alerta sobre cambios necesarios o caducidad de la cuenta dias antes
  
    * -E 2019-03-21 = establece la fecha de caducidad de la cuenta
  
    * -M # = dias maximos para cambiar de contraseña
  
__# date -d "+90 day"__ = contar dias para establecer el cambio o cualquier otro uso

__# groupadd "nombre"__ = agrega un nuevo grupo
  
    * -g # = crea un grupo con gid que sea neceario o solicitado o en su defecto cambiarlo
  
    * -n "nombre" "nombrenuevo" = cambia el nombre a un grupo
  
    * -o = permite usar un GID duplicado (no unico)
  
__#groupmod "nombre"__ = modificar un grupo despues de aver creado o en su defecto cambiarlo
  
    * -g # = crea un grupo con gid que sea neceario o solicitado
  
    * -n "nombre" "nombrenuevo" = cambia el nombre a un grupo
  
    * -o = permite usar un GID duplicado (no unico)
  
__groupdel "nombre"__ = eliminar un grupo 
  
__#timedatectl__ = informacion del reloj y se puede agregar varias configuraciones
  
    * set-ntp yes|no = activar el servicio de ntp
    
    * set-time 3:15 = establecer una hora
    
    * list-timezones = muestra una lista de las zonas horarias del planeta
    
    * set-timezone = establece la zona horaria selecionada
    
    * status  = muestra es estatus del reloj

__# ping 8.8.8.8__ = informacion si es que exite conexion o es alcanzable el host

__# traceroute 8.8.8.8__ = estable la ruta que toma para llegar a la direccion solicitada

__# mtr 8.8.8.8__ = combinacion de ping y traceroute para obtener mas informacion



  
  
