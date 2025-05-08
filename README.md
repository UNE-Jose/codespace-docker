# Docker-codespace

Este repositorio contiene una configuración básica para desplegar una base de datos **MariaDB** utilizando **Docker**. El objetivo es proporcionar un entorno de desarrollo portátil y fácil de usar para pruebas o desarrollo local.

## 📦 Requisitos

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- Opcional: [Visual Studio Code](https://code.visualstudio.com/) con la extensión **Dev Containers** o **Codespaces** para integraciones más fáciles.

## 🐬 ¿Qué incluye?

- Contenedor MariaDB configurado con:
  - Usuario y contraseña personalizados
  - Nombre de base de datos especificado
  - Persistencia de datos mediante volúmenes
- Archivo `docker-compose.yml` para levantar la base de datos con un solo comando.

## 🚀 Cómo usar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/Docker-codespace.git
   cd Docker-codespace