# Linux-Privilege-Escalation
Este repositorio cuenta con un script de configuracion que se utilizara en el curso de Escalacion de Privilegios en Ambientes Linux.

## Tecnicas para la Escalada de Privilegios

1. Recopilar Información de privilegios del usuario que hemos obtenido posterior a la explotación.
2. Identificar versión del sistema operativo.
3. Recolectar información sobre las variables del entorno, esto lo podremos realizar con herramientas automatizadas como "LinEnum.sh" y "lse.sh".
4. Busqueda de Exploits relacionados con Procesos, Kernel y Aplicaciones.
5. Explotación mediante exploits adaptados a nuestro sistema utilizando repositorios de exploits como exploit-db.
6. Si en este punto no hemos logrado la explotación para escalar a root, podemos utilizar otras técnicas como: tareas programadas, permisos de archivos debiles, SUID/SGID y Contraseñas en archivos dentro del sistema.

## Estrategia
1. Administre adecuadamente su tiempo y lea los resultados de su enumeración.
2. Si con la herramienta lse.sh/linenum.sh u otra herramienta encuentra algo interesante, haga una nota de ello para no repetir algún paso dentro de la enumeración.
3. Cree una lista de verificación de las cosas que necesita para que el método de escalada de privilegios funcione de esta manera evitará entrar en un ciclo que solo le consumirá tiempo.
