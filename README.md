# Comandos de Linux Más Utilizados

Este repositorio contiene una recopilación de comandos de Linux comunes junto con una breve descripción de cada uno. Es una guía rápida para aquellos que trabajan con sistemas basados en Linux y buscan un resumen práctico de comandos importantes.

## Tabla de Contenidos

- [Comandos Básicos](#comandos-básicos)
- [Comandos de Archivo y Directorio](#comandos-de-archivo-y-directorio)
- [Comandos de Sistema](#comandos-de-sistema)
- [Comandos de Red](#comandos-de-red)
- [Comandos de Gestión de Paquetes](#comandos-de-gestión-de-paquetes)
- [Comandos de Permisos](#comandos-de-permisos)

## Comandos Básicos

- `pwd`: Muestra el directorio actual de trabajo.
- `ls`: Lista los archivos y directorios en el directorio actual.
- `cd [directorio]`: Cambia al directorio especificado.
- `cp [origen] [destino]`: Copia archivos o directorios.
- `mv [origen] [destino]`: Mueve o renombra archivos o directorios.
- `rm [archivo]`: Elimina archivos o directorios.

## Comandos de Archivo y Directorio

- `touch [archivo]`: Crea un archivo vacío o actualiza la fecha de acceso/modificación de un archivo existente.
- `mkdir [directorio]`: Crea un nuevo directorio.
- `rmdir [directorio]`: Elimina un directorio vacío.
- `find [directorio] -name [nombre]`: Busca archivos y directorios en un directorio específico.
- `grep [patrón] [archivo]`: Busca un patrón en un archivo.

## Comandos de Sistema

- `top`: Muestra una vista dinámica de los procesos en ejecución.
- `ps aux`: Muestra una lista de procesos en ejecución.
- `kill [PID]`: Envía una señal a un proceso, generalmente para terminarlo.
- `df -h`: Muestra el uso del espacio en disco en un formato legible.
- `du -sh [directorio]`: Muestra el tamaño total de un directorio.

## Comandos de Red

- `ping [host]`: Envía paquetes ICMP a un host para verificar la conectividad de red.
- `ifconfig`: Muestra o configura interfaces de red (generalmente reemplazado por `ip`).
- `ip addr`: Muestra las direcciones IP asignadas a las interfaces de red.
- `netstat -tuln`: Muestra conexiones de red, tablas de enrutamiento, y más.
- `curl [URL]`: Obtiene o envía datos a una URL.

## Comandos de Gestión de Paquetes

- `apt-get update`: Actualiza la lista de paquetes disponibles (para distribuciones basadas en Debian).
- `apt-get install [paquete]`: Instala un nuevo paquete (para distribuciones basadas en Debian).
- `yum install [paquete]`: Instala un nuevo paquete (para distribuciones basadas en Red Hat).
- `dnf update`: Actualiza los paquetes del sistema (para Fedora).
- `rpm -qa`: Lista todos los paquetes instalados (para distribuciones basadas en RPM).

## Comandos de Permisos

- `chmod [opciones] [archivo]`: Cambia los permisos de acceso de un archivo o directorio.
- `chown [usuario]:[grupo] [archivo]`: Cambia el propietario y el grupo de un archivo o directorio.
- `sudo [comando]`: Ejecuta un comando con privilegios de superusuario.

## Contribuciones

Si tienes algún comando útil que te gustaría agregar o mejorar la descripción de los comandos existentes, siéntete libre de hacer un pull request. Para más detalles sobre cómo contribuir, consulta el archivo `CONTRIBUTING.md`.
