### Proyecto Final Docker
## Autor: Samuel Parra Cadavid
## 📌 Descripción

Este proyecto consiste en una aplicación web ligera y escalable desarrollada con Python y Flask, empaquetada en un contenedor Docker. La aplicación sirve como una demostración práctica de los conocimientos adquiridos en el curso de Telemática, destacando el uso de contenedores para el despliegue de servicios web.
## 🛰️ Tecnologías Utilizadas

- **Lenguaje:** Python 3.10
- **Framework:** Flask
- **Contenerización:** Docker
- **Frontend:** HTML5, CSS3 (estilizado incluido en index.html)
- **Sistema Operativo Base:** Ubuntu 22.04
- **Infraestructura:** Aws Ec2
- **Repositorio:** Git Hub

## 💡Requisitos

Tener -**docker** instalado
Tener -**git**  instalado

## 🗃️ Estructura del Proyecto
<div style="display: flex; gap: 10px;">
    <img src="https://i.imgur.com/Gu0Wiyj.png" alt="Captura de la app" width="300"/>
    <img src="https://i.imgur.com/liisb4c.png" alt="Captura de la app 2" width="300"/>
    <img src="https://i.imgur.com/j72Zbx2.png" alt="Captura de la app 3" width="300"/>
</div>


## 🔧instrucciones de despliegue:
## Instalación

## Clona este repositorio en tu maquina local:

git clone https://github.com/samuel2524/Proyecto-final.git

## Entramos a Proyecto-final/
```bash
cd Proyecto-final/
```

Construye la imagen Docker con el siguiente comando:

sudo docker build . -t proyectofinal:v01.

Ejecutar el Contenedor

sudo docker run -d -p 80:80 proyectofinal:v01

Verificamos si se creo

sudo docker ps

Acceder a la Aplicación con la ip publica

http://ip publica

🛠️ ¿Cómo modificar?

Modifica el contenido o diseño fácilmente editando los siguientes archivos:

    app/templates/index.html: Cambia el contenido HTML de la página.
    app/static/style.css: Ajusta el diseño visual (colores, fuentes, etc.).

Como Reconstruir la imagen:

sudo docker build . -t proyectofinal:v01

Volvemos A Ejecutar El Contenedor:

sudo docker run -d -p 80:80 proyectofinal:v01
