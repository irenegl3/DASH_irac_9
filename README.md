# Practica 3 de IRAC - DASH - equipo 9
Desarrollo de una aplicación web que proporciona un servicio de streaming básico mediante el protocolo DASH. Para ello, por un lado, se ha creado un servidor que organiza el acceso a los recursos que el cliente navegador utiliza, y, por otro lado, se ha implementado un entorno de visualización cliente para que el usuario pueda acceder a dicho servicio.

## Como trabajar con el repositorio
- Descargar/clonar proyecto en tu carpeta local:
``` shell
git clone https://github.com/irenegl3/DASH_irac_9.git
```
- añadir ficheros y subirlos (PRIMERO ACTUALIZAR PARA TENER EL MISMO CONTENIDO QUE EN GITHUB)
``` shell
git add fichero.js 
git commit -m "mensaje"
git push 
```
- actualizar mi codigo con el que esta en github:
``` shell
git pull
```

- estado de git:
``` shell
git status
```

## Arrancar el servidor
En el directorio en el que se encuentran todos los ficheros (importante que esté el `index.html`):

``` shell
pyhton -m SimpleHTTPServer 8080
```