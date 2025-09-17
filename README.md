# Blog App

**English**

A blogging web application built with **Flask (Python)**, **SQLite**, and **Bootstrap 5**.  

**Español**

Una aplicación web de blogging construida con **Flask (Python)**, **SQLite** y **Bootstrap 5**.

---

## 🌍 Overview / Descripción

**English**  
Blog App is a simple but functional blogging platform. Users can register, log in, create blog posts using a rich-text editor (CKEditor), and manage their content by editing or deleting their posts. Visitors can also leave comments on individual posts.  

**Español**  
Blog App es una plataforma de blogging sencilla pero funcional. Los usuarios pueden registrarse, iniciar sesión, crear publicaciones usando un editor de texto enriquecido (CKEditor) y gestionar su contenido editando o eliminando sus posts. Los visitantes también pueden dejar comentarios en las publicaciones.  

---

## ✨ Features / Características

**English**
- 👤 User authentication (register/login/logout)  
- 📝 Create, edit, and delete blog posts  
- 💬 Comment system for posts  
- 🎨 Responsive UI with **Bootstrap 5**  
- 🖊️ Rich-text editor integration with **CKEditor**  
- 💾 Lightweight database with **SQLite**  

**Spanish**
- 👤 Autenticacion de usuarios (registro/Iniciar Sesion/Cerrar Sesion)  
- 📝 Crear, editar, y elimina publicaciones del blog  
- 💬 Sistema de comentarios por publicacion
- 🎨 Interfaz de usuario responsiva con **Bootstrap 5**  
- 🖊️ Editor de texto enriquecido con **CKEditor**  
- 💾 Base de datos ligera con **SQLite**  

---

## 🛠️ Tech Stack / Tecnologías

- **Backend:** Flask (Python)  
- **Frontend:** Bootstrap 5, HTML, CSS, JS  
- **Database:** SQLite  
- **Libraries:** Flask-WTF, Flask-Login, Flask-SQLAlchemy, Flask-CKEditor  

---

## 📂 Project Structure / Estructura del Proyecto

```text
Blog/
│
├── main.py
├── forms.py
|── 
│
├── static/
│ ├── assets/
│ │ ├── img/
│ │ └── favicon.ico
│ ├── css/
│ │ └── styles.css
│ └── js/
│ └── scripts.js
│
├── templates/
│ ├── about.html
│ ├── contact.html
│ ├── footer.html
│ ├── header.html
│ ├── index.html
│ ├── login.html
│ ├── make-post.html
│ ├── post.html
│ └── register.html
│
└── README.md
```
---

## ⚙️ Installation & Setup / Instalación y Configuración

### 1. Clone repo / Clonar repositorio
```bash
git clone https://github.com/fockus26/BlogApp.git
cd BlogApp
```

### 2. Create virtual environment / Crear entorno virtual
```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```
### 3. Install dependencies / Instalar dependencias
```bash
pip install -r requirements.txt
```

### 4. Run app / Ejecutar aplicación
```bash
flask run
```

---

## 🚀 Usage / Uso

1. Register a new account / Regístrate con una nueva cuenta

2. Log in to access the editor / Inicia sesión para acceder al editor

3. Create, edit or delete blog posts / Crea, edita o elimina publicaciones

4. Comment on posts / Escribe comentarios en los posts

5. Explore blog content / Explora el contenido del blog

---

## 📖 Case Study / Estudio de Caso

**English**

This project was developed as part of a Python course to practice web development concepts with Flask. It focuses on user authentication, CRUD operations, and template rendering with Bootstrap for responsive UI.

**Español**

Este proyecto fue desarrollado como parte de un curso de Python para practicar conceptos de desarrollo web con Flask. Se centra en autenticación de usuarios, operaciones CRUD y renderizado de plantillas con Bootstrap para una interfaz responsive.

---

## 📈 Future Improvements / Mejoras Futuras

**English**

- 🔐 Password reset functionality

- 🖼️ Image upload for blog posts

- 🗄️ Migration to PostgreSQL or MySQL

- 📊 Admin panel for user and content management

- 🌍 Deployment to Heroku or Render


**Español**

- 🔐 Funcionalidad de reiniciar contraseña

- 🖼️ Subida de imagen para la publicaciones del blog

- 🗄️ Migrar a PostgreSQL o MySQL

- 📊 Panel de administrador para usuario y manejo de contenido

- 🌍 Despliegue a Heroku o Render

---

## 📜 License / Licencia

This project is licensed under the MIT License.
Este proyecto está licenciado bajo la Licencia MIT.

---
