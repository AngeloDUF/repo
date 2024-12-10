# API REST
Este es un proyecto que fue desarrollado con Python en una arquitectura REST API.

## Descripción
Este proyecto muestra una página en la cual dará la bienvenida con un mensaje. 
Es un programa sencillo para mostrar cómo funciona un programa en el lenguaje de programación con un estilo de arquitectura.

## Tecnologías Utilizadas
**Contiene lo Siguiente**
- Python(version mas actual)
- Docker
- Flaks

## Requerimientos para el Desarrollo
- **Docker Desktop** (si lo quieres correr en un contenedor)
- **Visual Studio Code** (opcional, pero recomendado)
- **Python**(requerido y recomendado)
- **La extensión Python para Visual Studio Code** (para mejorar el soporte y el resaltado de sintaxis).
- **GitHub Desktop** (si quieres clonar y usar el proyecto)
  
  ```bash
  https://www.docker.com/products/docker-desktop/
  ```
- **Docker hub** (si quieres clonar y usar el proyecto)
  
  ```bash
  https://hub.docker.com/layers/erickjrm/programapi/latest/images/sha256-0dc6b759d09c34f842d583019cd2df517a56ee69cc7db1d50958ea5919f3cfb3?context=repo
  ```

## Intruciciones para ejecutar el proyecto
## Pasos para ejecutar
- **Paso #1**
  **Clonar este repositorio**
Si aún no ha clonado el repositorio, puede hacerlo con el siguiente link:

 ```bash
https://github.com/JosueRM2001/restapi1.git
 ```
- **Paso #2**
  **Construya la imagen de Docker**

Ejecuta el siguiente comando, que generará la imagen:

```bash
docker pull erickjrm/programapi:latest
```

- **Paso #3**
**Ejecute el contenedor Docker:**

Luego ejecuta el siguiente comando, que genera el contenedor y el puerto.

```bash

docker run -d -p 5000:5000 --name apirest erickjrm/programapi:latest
```

- **Paso #4**

Abre Docker Desktop para ver si la imagen se creó correctamente y envíala a ejecutar para verla.

- **Paso #5**

**Accede a la aplicación**: Si está ejecutándose, puedes acceder a la aplicación navegando a la

siguiente url en tu navegador web:

```bash
http://localhost:500
```

