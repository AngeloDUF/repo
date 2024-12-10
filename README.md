# REST API
This is a project that was developed with Python in a REST API architecture.

## Description
This project displays a page that will welcome you with a message.
It is a simple program to show how a program works in the programming language with an architectural style.

## Technologies Used
**Contains the Following**
- Python (most recent version)
- Docker
- Flaks

## Development Requirements
- **Docker Desktop** (if you want to run it in a container)
- **Visual Studio Code** (optional, but recommended)
- **Python** (required and recommended)
- **The Python extension for Visual Studio Code** (for improved support and syntax highlighting).
- **GitHub Desktop** (if you want to clone and use the project)

```bash
https://www.docker.com/products/docker-desktop/
```
- **Docker hub** (if you want to clone and use the project)

```bash
https://hub.docker.com/layers/erickjrm/programapi/latest/images/sha256-0dc6b759d09c34f842d583019cd2df517a56ee69cc7db1d50958ea5919f3cfb3?context=repo
```

## Instructions to run the project
## Steps to run
- **Step #1**
**Clone this repository**
If you have not yet cloned the repository, you can do so with the following link:

```bash
https://github.com/JosueRM2001/restapi1.git
```
- **Step #2**
**Build the Docker image**

Run the following command, which will build the image:

```bash
docker pull erickjrm/programapi:latest
```

- **Step #3**
**Run the Docker container:**

Then run the following command, which builds the container and port.

```bash

docker run -d -p 5000:5000 --name apirest erickjrm/programapi:latest
```

- **Step #4**

Open Docker Desktop to see if the image was built correctly and send it to run to view.

- **Step #5**

**Access the application**: If it is running, you can access the application by navigating to the

following url in your web browser:

```bash
http://localhost:5000
```
