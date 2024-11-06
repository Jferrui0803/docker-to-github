# Dockerized Apache Site

Este proyecto utiliza Docker y GitHub Actions para automatizar la creación de una imagen de Docker que sirve una página web simple con Apache.

## Contenido

- **index.html**: Página web que se muestra en el navegador.
- **Dockerfile**: Configuración para la imagen Docker, que usa la imagen base de Apache.
- **GitHub Actions Workflow**: Flujo de trabajo que construye y sube la imagen a Docker Hub cuando se realizan cambios en la rama `main`.

## Configuración

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Jferrui0803/docker-to-github.git
   cd tu-repositorio
