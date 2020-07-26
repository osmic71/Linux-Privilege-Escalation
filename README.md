# Linux-Privilege-Escalation
Este repositorio cuenta con un script de configuracion que se utilizara en el curso de Escalacion de Privilegios en Ambientes Linux.

## Tecnicas para la Escalada de Privilegios

1. Recopilar Información de privilegios del usuario que hemos obtenido posterior a la explotación.
2. Identificar versión del sistema operativo.
3. Recolectar información sobre las variables del entorno, esto lo podremos realizar con herramientas automatizadas como "LinEnum.sh" y "lse.sh".
4. Busqueda de Exploits relacionados con Procesos, Kernel y Aplicaciones.
5. Explotación mediante exploits adaptados a nuestro sistema utilizando repositorios de exploits como exploit-db.
6. Si en este punto no hemos logrado la explotación para escalar a root, podemos utilizar otras técnicas como: tareas programadas, permisos de archivos debiles, SUID/SGID, programas corriendo como SUDO  y contraseñas en archivos dentro del sistema.

## Estrategia
1. Administre adecuadamente su tiempo y lea los resultados de su enumeración.
2. Si con la herramienta lse.sh/linenum.sh u otra herramienta encuentra algo interesante, haga una nota de ello para no repetir algún paso dentro de la enumeración.
3. Cree una lista de verificación de las cosas que necesita para que el método de escalada de privilegios funcione de esta manera evitará entrar en un ciclo que solo le consumirá tiempo.
4. Realice pruebas con cosas que no tienen muchos pasos primero, por ejemplo: sudo, cronjobs, archivos SUID/SGID.
5. Revise los procesos root, enumere sus versiones y busque exploits relacionados con estas aplicaciones.
6. Verifique los puertos internos que se encuentran abiertos a los que podría crear tunneles SSH hacia su máquina de ataque.
7. Si aún no tiene root, vuelva a leer sus volcados de enumeración completa y resalte todo lo que parezca extraño. Este podría ser un proceso o un nombre de archivo con el que no está familiarizado, un sistema de archivos "inusual" configurado (en Linux, cualquier cosa que no sea ext, swap o tmpfs), o incluso un nombre de usuario.
En esta etapa, también puede comenzar a realizar pruebas con exploits relacionados con el Kernel.
8. Mantenga la calma, el proceso de escalada de privilegios puede ser complejo y difícil de detectar a simple vista.
Recuerde que en un examen, laboratorio o en un CTF existen métodos específicos para la escalada de privilegios a su vez como un tiempo limitado, repase los puntos que ha realizado y continúe buscando.


