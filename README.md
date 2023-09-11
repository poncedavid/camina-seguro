# Camina Seguro

**Una aplicación desarrollada por CLKTEAM para CITT de DuocUC.**

## Tabla de contenidos

* [Introducción](#introducción)
* [Requisitos](#requisitos)
* [Características](#características)
* [Instalación y ejecución](#instalación-y-ejecución)
* [Tecnologías utilizadas](#tecnologias-utilizadas)
* [Agradecimientos](#agradecimientos)

## Introducción

Camina Seguro es una aplicación para ayudar a las personas a caminar de manera segura. La aplicación tiene dos principales requisitos:

* Generar reportes de incidentes de seguridad.
* Enviar la ubicación geográfica del usuario.

## Requisitos

Para utilizar y desarrollar este proyecto, necesitas tener las siguientes herramientas instaladas:

- Node.js y npm (Node Package Manager)
- Ionic CLI
- Angular CLI
- Capacitor

## Características

* **Generar reportes de incidentes de seguridad:**
    * El usuario puede generar un reporte de incidente de seguridad tocando el botón "Reportar incidente".
    * El reporte incluirá la ubicación del incidente, una descripción del incidente y una foto, si está disponible.
    * El reporte se enviará al servidor para su posterior procesamiento.
* **Enviar la ubicación geográfica del usuario:**
    * La aplicación envía la ubicación geográfica del usuario al servidor cada minuto.
    * Esta información se puede utilizar para rastrear el movimiento del usuario y para enviar notificaciones de seguridad en caso de emergencia.

## Instalación y ejecución

Para instalar y ejecutar el proyecto, sigue estos pasos:

1. Clona el repositorio de GitHub:
```bash
   git clone https://github.com/tuusuario/camina-seguro.git
```
2. Entra en el directorio del proyecto:
```bash
   cd camina-seguro
```
3. Instala las dependencias:
```bash
   npm install
```
4. Agrega las plataformas móviles a través de Capacitor. Por ejemplo, para Android o Ios:
```bash
   npx cap add android
```
ó 
```bash
   npx cap add ios
```
5. Ejecuta la aplicación:
```bash
   ionic cordova run ios
```

## Tecnologías utilizadas

Camina Seguro está desarrollada con las siguientes tecnologías:

* Ionic: un framework para crear aplicaciones móviles híbridas.
* Angular: un framework para crear aplicaciones web SPA.
* Capacitor: un puente que permite a las aplicaciones Ionic ejecutarse en dispositivos móviles.

## Agradecimientos

Este proyecto es el resultado del trabajo de un equipo de desarrolladores de CLKTEAM. Agradecemos el apoyo del CITT de DuocUC, que nos proporcionó los recursos necesarios para llevar a cabo este proyecto.

