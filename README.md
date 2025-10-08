(For other languages, please use Traslate button icon above in navigation bar like "github.com" to traslating into your mother language)

# Gestor de Políticas de Contraseñas v2.3

## 📋 Descripción

El **Gestor de Políticas de Contraseñas** es una aplicación de línea de comandos diseñada para administrar y configurar políticas de seguridad de contraseñas en sistemas Linux. Desarrollado con soporte multi-distribución y multi-idioma, ofrece una interfaz intuitiva para la gestión completa de políticas de seguridad.

## 🚀 Características Principales

### Gestión de Políticas
- Configuración de políticas por defecto para nuevos usuarios
- Políticas específicas por usuario
- Visualización del estado actual de configuración
- Aplicación de políticas a todos los usuarios

### Gestión de Contraseñas
- Cambio de contraseñas de usuario
- Cambio seguro de contraseña de root
- Verificación de complejidad de contraseñas
- Monitoreo de vencimiento de contraseñas

### Funciones de Seguridad
- Creación de backups de configuración
- Restauración de backups
- Log de actividades del sistema
- Verificación de políticas de seguridad

## 🆕 Novedades v2.3

### Soporte Multi-Idioma
- **+45 idiomas** incluidos
- Soporte para variantes regionales
- Incluye el idioma **Latín** del Vaticano (la_VA) y **Latín** de los romanos (la_IT)
- Incluye soporte para caracteres runicas tipo Futhark: alemán, sueco, noruego y islandés (ejm: "ᛁᚾᚠᛟᚱᛗᚨᛏᛁᛟᚾ" en alemán rúnico) de los vikingos.
- Traducciones completas de la interfaz
- Configuración manual para cambios de idiomas a traves de la variable `CURRENT_LANG="es_ES"` usando **nano**, **pluma**, **gedit**, **vim**, **emacs**, etc., con facilidad.

### Distribuciones Soportadas
- **Modernas**: Ubuntu, Debian, Canaima, Devuan, Fedora, CentOS, Slackware (Moderno) Arch, Manjaro, openSUSE, Gentoo (Moderno)
- **Históricas**: Mandriva, Mandrake, Slackware (antigua), Gentoo (antigua)
- **Especializadas**: Alpine, Void, OpenMandriva, Mageia

### Mejoras Técnicas
- Detección automática de distribución
- Instalación automática de dependencias
- Soporte para instalación offline
- Interfaz optimizada para TUI

## USO
- Versión simple: sudo password-policy-manager
- Versión extendida: sudo password-policy-manager-all

## 🌍 Cambio de Idioma

### Configuración Manual

Clonar a traves del comando "git clone"

# Una vez descargados:

cd passwordman2

activar para los ejecutables:

```bash
sudo chmod a+x *.sh
```
luego a...

1) Ejecute el instalador **sudo ./install-password-manager-universal**
2) Ejecute el instalador de idiomas: **sudo ./install-languages**
3) Ejecuten:

```bash
sudo ./password-policy-manager 
```
(version simple para distribuciones más actuales) 

o
```bash
sudo ./password-policy-manager-all 
```
(soporte multidistribuciones, versiones antiguas de linux como Mandrake Linux o Mandriva, Slackware antiguo, etc.)

# Cambio de idiomas | Change Language

Busque y edite con nano de la variable `CURRENT_LANG="es_ES"` en los archivos principales:

```bash
nano /usr/local/bin/password-policy-manager
```
y
```bash
nano /usr/local/bin/password-policy-manager-all
```

**Español**
CURRENT_LANG="es_ES" 

**Para inglés americano**
CURRENT_LANG="en_US"

**Para inglés británico**
CURRENT_LANG="en_GB"

**Para francés**
CURRENT_LANG="fr_FR"

**Para alemán**
CURRENT_LANG="de_DE"

  variantes: de_VE, de_DE_runes (**NUEVO:** alemán rúnico)

**Para italiano**
CURRENT_LANG="it_IT"

   variantes: it_VE, it_AR, it_US, it_LA (**NUEVO:** Italiano latinoamericano y de EUA)

**Para ucraniano (Slava Ukraini)**
CURRENT_LANG="uk_UA"

## LICENCIA

GPL v2.0 License - Ver archivo LICENSE para detalles completos.

Se concede permiso para usar, copiar, modificar y distribuir este software
sin restricciones, siempre que se incluya el aviso de copyright.

## COPYRIGHT

Copyright (c) 2024 Gestor de Políticas de Contraseñas
Todos los derechos reservados según los términos de la GPL v2.0.

### CONTACTO Y SOPORTE

Para reportar issues o solicitar características, crear un issue en el
repositorio del proyecto incluyendo información de la distribución y
versión del sistema.

### Versión: 2.3
Actualización: Octubre del 2025

Soporte: Sistemas Linux Multi-Distribución
