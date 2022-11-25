# alpha-silicon

## Para desarrollar local
- Descargar el repositorio
```sh
$ git clone git@github.com:FacundoRauber/alpha-silicon.git
```
- Restaurar la copia de la base de datos
- Dentro de l carpeta /alpha-silicon instalar los paquetes necesarios:
```sh
$ npm init
$ npm install express mysql morgan rootpath
```
- Ejecutar:
```sh
$ node index.js
```

## Coinsideraciones
- En el archivo config.json se encuentran las configuraciones para que el sistema se conecte al motor de la base de datos y para configurar los puertos de escucha del servidor web.
- Tener en cuenta que al restaurar la base de datos el nombre de la base de datos puede ser distinto, revisar el archivo de configuración.
- Tener en cuenta que al restaurar la base de datos la clave y el usuario del motor de base de datos puede ser distinto, revisar el archivo de configuración.
- Es posible modificar el puerto de escucha del servidor web, por defecto esta en el 8080.