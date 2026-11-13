# Inventario de dispositivos

Este proyecto es una API realizada con FastAPI.

La función que me tocó realizar fue el alta de dispositivos mediante POST.

La API permite registrar dispositivos con nombre, tipo y dirección IP.

## Prueba

Se utiliza la ruta POST /dispositivos para agregar nuevos equipos.

---

*(Lo que sigue lo agregaste tú)*

## Baja de dispositivos

Mi aportación al equipo fue la operación de baja (DELETE). 
La API permite eliminar un dispositivo del inventario utilizando su nombre como identificador en la ruta.

## Prueba
Se utiliza la ruta DELETE /dispositivos/{nombre} para dar de baja un equipo. Si el equipo existe, responde con un código 204 (sin contenido). Si no existe, responde con un 404.
