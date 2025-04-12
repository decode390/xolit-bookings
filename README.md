Prueba técnica Xolit Espacios Compartidos

Para ejecutar el projecto:
- `git clone --recurse-submodules https://github.com/decode390/xolit-bookings`
- `cd xolit-bookings`
- `docker compose up -d`

Requerimientos para poder ejecutar:
- Docker compose
- Puertos disponibles en la máquina:
  - 5000
  - 4201
  - 1433
 
Una vez levandado el projecto se puede acceder por la URL `http://localhost:4201/login` en el navegador.

En el puerto 5000 se puede consumir la API.

En el puerto 1433 se puede acceder desde cualquier gestor de base de datos.
