# CI/CD Pipeline: WebApp Deployment using Jenkins, GitHub, Tomcat, and AWS

This project demonstrates a complete CI/CD pipeline setup for deploying a **Registration Page Web Application** using Jenkins (Freestyle Job), GitHub, Apache Tomcat, and AWS EC2 

## 🔧 Tools & Technologies Used
- Jenkins (Freestyle Job)
- GitHub
- Maven
- Apache Tomcat
- AWS EC2 (Windows Server 2022)
- HTML, CSS, Java (for registration web app)

## 🛠️ CI/CD Workflow

1. ✅ Code pushed to GitHub repository [`webapps`](https://github.com/shravan-12345/webapps)
2. ✅ Jenkins is triggered manually or via webhook
3. ✅ Jenkins pulls the code, builds it using Maven (generates `.war` file)
4. ✅ `.war` file is deployed to Apache Tomcat server on AWS EC2 (Windows)
5. ✅ Web application is live on a public IP

## 🌐 Project Description

This project includes a basic **registration form web application** which is deployed using a CI/CD pipeline. It helps in understanding:

- Source code management with GitHub
- Automating builds and deployments with Jenkins
- Hosting applications on AWS Windows Server
- Real-time DevOps practices

## 📌 Repository

🔗 GitHub Repo: [https://github.com/shravan-12345/webapps](https://github.com/shravan-12345/webapps)

---

Thanks for visiting this project! Feel free to fork or star ⭐ the repo.
