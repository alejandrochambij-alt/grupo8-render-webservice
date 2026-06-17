# Grupo 8 – Render Web Service

## Descripción del proyecto

Este proyecto fue desarrollado como parte de la asignatura y tiene como objetivo demostrar el proceso completo de despliegue de una aplicación web utilizando **Render Web Service**.

Inicialmente el proyecto consistía en una página web estática desarrollada con HTML y CSS. Para hacerla compatible con Render Web Service se implementó un pequeño servidor utilizando **Node.js** y **Express**, permitiendo ejecutar la aplicación como un servicio web.

---

## Tecnologías utilizadas

* HTML5
* CSS3
* Node.js
* Express.js
* Git
* GitHub
* Render Web Service

---

## Estructura del proyecto

```text
Proyecto/
│
├── index.html
├── estilos.css
├── img/
│   ├── imagen1.png
│   └── ...
│
├── server.js
├── package.json
├── package-lock.json
└── README.md
```

---

## Instalación y ejecución local

### 1. Clonar el repositorio

```bash
git clone https://github.com/alejandrochambij-alt/grupo8-render-webservice.git
```

### 2. Entrar a la carpeta del proyecto

```bash
cd grupo8-render-webservice
```

### 3. Instalar dependencias

```bash
npm install
```

### 4. Ejecutar el servidor

```bash
node server.js
```

---

## Acceso local

Abrir en el navegador:

```text
http://localhost:3000
```

---

## Despliegue en Render

Configuración utilizada:

**Build Command**

```bash
npm install
```

**Start Command**

```bash
node server.js
```

---

## Repositorio GitHub

Repositorio público:

 https://github.com/alejandrochambij-alt/grupo8-render-webservice 

---

## Sitio desplegado

URL del proyecto:

https://grupo8-render-webservice.onrender.com/ 

---

## Integrantes del grupo

Alejandro José Chambi Quispe
Beymar Ismael Chuquimia Lima
José Alberto Mamani Murga
Fabricio Álvaro Tambo Alcón


---

## Problemas encontrados y soluciones

### Problema

PowerShell bloqueó la ejecución de npm:

```text
No se puede cargar npm.ps1 porque el archivo no está firmado digitalmente
```

### Solución aplicada

```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
```

---

## Conclusión

Se logró convertir una página web estática en una aplicación compatible con Render Web Service mediante Node.js y Express. Posteriormente se realizó el despliegue exitoso utilizando GitHub y Render, obteniendo una aplicación funcional disponible en internet.
