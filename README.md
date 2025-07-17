# 💼 Full Stack Portfolio – Deepak Raikwar

🔴 **Live Demo:** [https://rai-deepak-07.github.io/raideepak07/](https://rai-deepak-07.github.io/raideepak07/)  

🟢 **Backend API:** [https://raideepak07.pythonanywhere.com/api/portfolio/](https://raideepak07.pythonanywhere.com/api/portfolio/))

---

## 🔍 Description

This is a full-stack **developer portfolio website** built with:

- 🧩 **React.js** (frontend)

- 🐍 **Django REST Framework** (backend)

- 🗄️ **MySQL** database

It showcases your **skills**, **projects**, **resume**, and includes a **contact form** that connects directly to the backend via **REST APIs**.

---

## 🚀 Features

- ⚛️ Clean, modern React UI using Bootstrap

- 🔁 Backend API powered by Django REST Framework

- 📡 Live API connected via Axios (PythonAnywhere)

- 🗃️ Contact form integrated with MySQL database

- 🧠 Uses React Hooks: `useEffect`, `useState`

- 📱 Fully responsive design

- 🌍 Frontend hosted on GitHub Pages

- 🔐 CORS-secured REST API

---

## 📁 Folder Structure

raideepak07/  
├── client/ # React Frontend  
│ ├── src/  
│ │ ├── components/  
│ │ │ ├── Navbar.js  
│ │ │ ├── Projects.js  
│ │ │ ├── Contact.js  
│ │ │ └── Footer.js  
│ │ ├── App.js  
│ │ └── index.js  
│ ├── public/  
│ └── package.json  

├── server/ # Django Backend (PythonAnywhere)  
│ ├── manage.py  
│ ├── portfolio/ # Django project settings  
│ └── api/ # Django app (models, serializers, views, urls)  
│ ├── models.py  
│ ├── views.py  
│ ├── urls.py  
│ └── serializers.py  
├── requirements.txt  
└── README.md  


---

## 🔌 API Endpoints (Live)

📍 Base URL: [https://raideepak07.pythonanywhere.com/api/portfolio/](https://raideepak07.pythonanywhere.com/api/portfolio/)

| Method | Endpoint             | Description                  |
|--------|----------------------|------------------------------|
| GET    | `/about/`         | To get all the data of about table |
| GET    | `/category/`         | To get all the data of category table |
| GET    | `/category/{id}/`         | To get specific id data of category table |
| GET    | `/services/`         | To get all the data of services table |
| GET    | `/services/{id}/`         | To get specific id data of services table |
| GET    | `/project/`         | To get all the data of project table |
| GET    | `/project/?Project_Id={id}/`         | To get specific project id data in project table |
| GET    | `/project/?Prj_Tech={id}/`         | To get specific Project Category id data in project table |
| GET    | `/project/?Project_Id={id}&Prj_Tech={id}/`         | To get specific project id with specific project category id data in project table |
| GET    | `/prjimage/`         | To get all the projects images data in ProjectImage table |
| GET    | `/project/?Img_Id={id}/`         | To get specific project image id data in projectimage table |
| GET    | `/project/?Prj_Img_Name={id}/`         | To get specific Project_Image_Name id data in project table |
| POST   | `/contact+ {data}/`          | To Send Contact Form Data in to table          |

---

## 🛠 Tech Stack

### 🎯 Frontend

- React.js

- Bootstrap 5

- Axios

- GitHub Pages

- React Router (HashRouter)

### ⚙️ Backend

- Python 3

- Django 4+

- Django REST Framework

- CORS Headers

- MySQL

- PythonAnywhere (hosting)

---

## 🖼️ Preview

![Portfolio Screenshot](https://rai123.pythonanywhere.com/media/portfolio/project/Portfolio/Screenshot_543.png.png) <!-- Optional image -->

---

## 🙋‍♂️ Author

Made with ❤️ by [Deepak Raikwar](https://www.linkedin.com/in/raideepak07)

---

## 🌐 Connect With Me

- 🔗 [Portfolio Website](https://rai-deepak-07.github.io/raideepak07/)

- 💼 [LinkedIn](https://www.linkedin.com/in/raideepak07)

- 📸 [Instagram](https://www.instagram.com/rai_deepak_07)

- 🐙 [GitHub Profile](https://github.com/rai-deepak-07)

---
