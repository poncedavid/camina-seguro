# Camina Seguro

**Una aplicación desarrollada por CLKTEAM para CITT de DuocUC.**
[![Imagen de la aplicación](https://example.com/imagen.png)](https://example.com/imagen.png)
## Tabla de contenidos

* [Introducción](#introducción)
* [Requisitos](#requisitos)
* [Características](#características)
* [Instalación y ejecución](#instalación-y-ejecución)
* [Tecnologías utilizadas](#tecnologias-utilizadas)
* [Documentacion](#documentación)
* [Agradecimientos](#agradecimientos)
* [Licencia](#licencia)

## Introducción

Camina Seguro es una aplicación para ayudar a las personas a caminar de manera segura. La aplicación tiene dos principales requisitos:

* Generar reportes de incidentes de seguridad.
* Enviar la ubicación geográfica del usuario.

## Requisitos

Antes de comenzar a utilizar y desarrollar este proyecto, asegúrate de tener las siguientes herramientas instaladas:

- [Node.js y npm](https://nodejs.org/): Utilizados para gestionar las dependencias del proyecto.
  - Puedes instalar Node.js y npm desde [aquí](https://nodejs.org/).

- [Ionic CLI](https://ionicframework.com/docs/cli): Necesario para la interfaz de usuario.
  - Instala Ionic CLI globalmente con el comando: `npm install -g @ionic/cli`.

- [Angular CLI](https://angular.io/cli): Requerido para el desarrollo de la aplicación.
  - Instala Angular CLI globalmente con el comando: `npm install -g @angular/cli`.

- [Capacitor](https://capacitorjs.com/): Esencial para el despliegue en dispositivos móviles.
  - Agrega Capacitor a tu proyecto con el comando: `npm install @capacitor/core`.

Asegúrate de tener estas herramientas configuradas antes de empezar a trabajar en el proyecto.

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

## Documentación

Para obtener más información sobre cómo usar la aplicación, consulta la [documentación](https://example.com/documentacion.html).


## Agradecimientos

Este proyecto ha sido posible gracias al esfuerzo conjunto de nuestro equipo en [CLK Team](https://www.cloverluck.cl). También agradecemos al CITT de DuocUC por proporcionarnos los recursos necesarios para llevar a cabo este proyecto con éxito.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para obtener más detalles.