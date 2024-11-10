# CSTASK - Aplicación "Hola Mundo" en C#

Este proyecto es una simple aplicación web "Hola Mundo" creada en C# y desplegada en un contenedor Docker. Puedes ejecutarla localmente y acceder a ella en tu navegador.

## Requisitos
- **Docker**: [Instalar Docker](https://www.docker.com/get-started) si aún no lo tienes.

## Instrucciones de Instalación

1. **Clona este repositorio**:
   ```bash
   git clone https://github.com/freddyelgato/CSTASK.git
2. **Ejecuta la aplicación en Docker**:
   ```bash
   docker run -d -p 8080:8080 --name CSTASK 2424833f/cstask
 - **d**: Ejecuta el Contenedor en Segundo Plano.
 - **p8080**: Mapea el puerto 8080 del contenedor al puerto 8080 de tu máquina..

3. **Accede a la aplicación con el Navegador para ver el Mensaje Hola Mundo**:
   ```bash
   http://localhost:8080
   
## Comandos Útiles
- Ver Contenedores: `docker ps`.
- Detener el Contenedor: `docker stop CSTASK`.
- Eliminar el Contenedor: `docker rm CSTASK`.

## Enlaces
- Imagen en Docker Hub: `[docker ps](https://hub.docker.com/repository/docker/2424833f/cstask)`.
- Repositorio de GitHub: `[docker stop CSTASK](https://github.com/freddyelgato/CSTASK)`.
