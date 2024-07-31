# Proyecto de Chat con Node.js

Este repositorio contiene un proyecto de chat en tiempo real desarrollado con Node.js, utilizando websockets a través de Socket.io, junto con tecnologías de frontend como HTML y CSS. El objetivo de este proyecto es aprender y practicar la implementación de websockets en un entorno de servidor y cliente, así como la integración con una base de datos SQL para manejar el almacenamiento de datos.

## Tecnologías y Dependencias Utilizadas

### Backend

#### Express

[Express](https://expressjs.com/) es un framework minimalista para Node.js que facilita la creación de aplicaciones web y APIs robustas. Se utiliza en este proyecto para gestionar rutas, middleware y la lógica del servidor.

#### Socket.io

[Socket.io](https://socket.io/) es una biblioteca que permite la comunicación bidireccional y en tiempo real entre clientes y servidores. En este proyecto, Socket.io se utiliza para implementar la funcionalidad de chat en tiempo real, permitiendo a los usuarios enviar y recibir mensajes instantáneamente.

#### Morgan

[Morgan](https://github.com/expressjs/morgan) es un middleware de logging para Node.js que se integra con Express. Se utiliza para registrar las solicitudes HTTP recibidas por el servidor, lo cual es útil para depuración y análisis de tráfico.

#### SQL

Se utiliza una base de datos SQL para almacenar datos persistentes como usuarios, mensajes, y cualquier otra información relevante para el chat. La elección del motor SQL puede variar (MySQL, PostgreSQL, etc.), y se puede manejar a través de ORM o consultas SQL directas.

### Frontend

#### HTML y CSS

Se utilizan [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) y [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) para construir y estilizar la interfaz de usuario. HTML estructura el contenido y CSS proporciona el diseño visual, asegurando una experiencia de usuario atractiva y fácil de usar.

#### Todos los créditos al [Curso de NODEJS de midudev](https://github.com/midudev/curso-node-js)
