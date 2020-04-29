# Practica 3 de IRAC - DASH - equipo 9

## Como trabajar con el repositorio
- Descargar/clonar proyecto en tu carpeta local:
``` shell
git clone https://github.com/irenegl3/DASH_irac_9.git
```
- añadir ficheros y subirlos (PRIMERO ACTUALIZAR PARA TENER EL MISMO CONTENIDO QUE EN GITHUB)
``` shell
git add fichero.js 
git commit -m "mensajito de commit"
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