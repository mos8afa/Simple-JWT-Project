# 🌟 Django JWT Authentication API

![Django](https://img.shields.io/badge/Django-4.x-green?style=flat&logo=django)  
![DRF](https://img.shields.io/badge/DRF-REST%20Framework-red?style=flat&logo=django)  
![License](https://img.shields.io/badge/License-MIT-blue.svg)  
![Python](https://img.shields.io/badge/Python-3.x-yellow?style=flat&logo=python)  

> A simple Django project that implements **JWT-based authentication** using djangorestframework-simplejwt. This project allows users to obtain access and refresh tokens, and access a protected login endpoint using JWT authentication.  

---

## ✨ Features

- **JWT Authentication with access and refresh tokens**
- **Protected endpoint /api/login/ that returns the authenticated user's information**
- **Token rotation and blacklist support**
- **Simple project structure using Django REST Framework**
- **Easy to test with Postman**

## 🔐 Notes

- **Access tokens expire in 5 minutes by default.**
- **Refresh tokens expire in 1 day.**
_ **Tokens are rotated and blacklisted after use.**

## 📡 API Documentation

- **API endpoints are available through a Postman collection:**
👉 [![Postman](https://img.shields.io/badge/API%20Docs-Postman-orange?logo=postman)](https://documenter.getpostman.com/view/47987371/2sBXc8oNdP)
