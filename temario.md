# Temario

## Introducción a Linux y a la shell

- Introducción a los SO's

  - Qué es un SO
    - Tipos de SO's
  - Qué es un kernel
    - Tipos de kernel
    - Modo kernel y modo usuario

- Introducción de Linux

  - Orígenes de Linux
    - El Proyecto Unix
      - Innovaciones de Unix
    - El proyecto GNU
    - El proyecto Linux (kernel)
    - Proyecto GNU/Linux
  - Por qué usar Linux
  - Por qué no usar Linux
  - Distribuciones de Linux
  - Tipos de instalación

- Introducción a interfaces

  - GUI
  - CLI
  - De texto (e.g., BIOS)

- Introducción a la terminal

  - Qué es una terminal
  - Qué es una shell
    - Shells comunes de Linux
  - Qué es un comando
    - Comandos básicos
      - Tú primer comando: "Hello, world!"
      - Comandos de manejo de archivos
        - Navegación
          - Rutas relativas y absolutas
        - Consulta
        - Manipulación
      - Comandos de utilidad
      - Comandos de ayuda
  - Tipos de comandos
    - Comando type
  - Estructura de un comando

- CLI shortcuts (atajos)

- Jerarquía de archivos de Linux

- Wildcards

- Archivos

  - Tipos de archivos
    - Binario
    - Texto plano
    - Directorio
    - Link simbólico y fuerte

- Usuarios

  - Tipos de usuarios

- Comandos:

- Gestión de archivos

  - Permisos de archivos
  - Gestión de permisos de archivos

    - Simbólico
    - Octal Permisos por defecto (umasks)

  - Gestión de usuarios

- Estándar input (stdin), output (stout) y error (stderr)

  - Redireccionamientos
  - Pipe operator
  - Exit codes

- Administración de servicios

## Configuración de Entorno

- Variables de entorno
  - Qué es una variable de entorno
  - Consultar variables de entorno
  - Crear variables de entorno (temporales)
  - Archivos de configuración (usuario)
    - .profile
    - .bash_profile (i.e., startup file)
    - .bashrc
      - Alias
      - PATH
      - Funciones
      - Umask
  - Archivos de configuración (global)

## Editores de Texto

- Editores de terminal

  - Nano
  - Vi
  - Vim
  - Neovim
  - Emacs

- Editores GUI

  - Gedit
  - Kwrite

## Herramientas Esenciales

- Gestores de paquetes

  > [!TODO]
  >
  > Describir cómo hacer las siguientes acciones en los package manager más
  > populares:
  >
  > - Install
  > - Uninstall
  > - Update
  > - List installed
  > - Search packages

  - Binary-based (local)
    - Debian (dpkg)
    - RedHat (rpm)
    - Arch Linux (pacman -U)
  - Repository-based (online)
    - Debian (apt)
    - RedHat (yum)
    - Fedora (dnf)
    - Arch Linux (pacman -S)

- Dispositivos de almacenamiento

- Redes

- Búsqueda de archivos

  - Find
    - Exec
  - Locate
    - Updatedb

- Archivado y respaldos

  - Archivado vs compresión (diferencias)

  - Archivado
    - tar
  - Compresión
    - gzip
    - bzip
  - Sincronización de archivos y directorios
    - rsync

- Conversión de archivos

  - pandoc

- Reducción de tamaño de archivos (compresión)

  - ps2pdf
  - imagemagick

- Gestión de metadata

  - exiftool

- Expresiones regulares (RegEx)

- Procesamiento de texto

- Formateado de output

- Impresión

- Compilación de programas

  - Qué es un compilador
    - Compilación en C/C++
    - Construcción de un programa
      - configure
      - Make
    - Instalación de un programa

- Ejecución de scripts

  - Qué es un intérprete
    - Ejecución de código Python

## Bash Scripting
