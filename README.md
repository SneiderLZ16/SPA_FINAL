# Prueba

# 🗓️ Project: SPA Event Management

This project is a single-page web application (SPA) for event management, developed with HTML, CSS, and JavaScript. It allows users to register, log in, create, join, and cancel events. It includes user roles (admin and visitor) and a responsive interface.

---

## 👨‍💻 Developer

- **Name:** Kevin Londoño
- **Clan:** Linux
- **Email:** sneiderlondono0216@gmail.com
- **ID:** 1025641044

---

## 🚀 Requirements

- Modern web browser (Chrome, Firefox, Edge)
- Node.js (optional, to set up the backend with json-server)

---

## 📁 Estructura del Proyecto

/
|
|----PRUEBA
|
|-----Assets
|    |-----Style.css
|----db.json
|----Index.html
|----README.md
|----Scripts.js
|----package.json
|----package-lock.json


##🛠 Personalization In db.json, I defined at least one admin user: Json "id": "034a",
      "username": "Kevin",
      "password": "0520",
      "role": "admin"

---

## Technologies used

JavaScript: SPA main logic
HTML and CSS: Interface structure and styles

---

## How does localStorage work in this project?

This app uses localStorage to temporarily save the logged-in user. This allows the user to navigate between pages without having to log in again each time.

The saved value (loggedUser) contains data such as id, name, email and role. Then, anywhere in the app, you can get it with:

---

##  Roles: Admin vs User Users

in this app can have a role field that defines their permissions: admin: You have full access. Can: Create new events. Edit and delete events from the list. customer: You have limited access. Can only: See the list of events, sign up for events and create events. You cannot edit, delete.


---
## How to run 

Option #1: You must stop at the index.html file, then right click and click on the option (Open with live server)

Option #2 (Recommended): You must enter the terminal and execute the command npm run dev, Following this, the terminal will create a local server, you must enter the server URL (e.g.: http://localhost:5173) and once you enter the project will be loaded.

Option #3: Just like in step #2, you should open console (command ctrl + j) and execute the following command (json-server --watch db.json), the terminal will create a local server with the port (http://localhost:3000)
