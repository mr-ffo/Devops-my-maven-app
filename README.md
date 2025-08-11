# 🚀 My Maven App

A simple yet powerful Java application built with **Maven**, running on an **AWS EC2 instance**, and tracked with **Git & GitHub**.  
Created with ❤️ by **Folarin Favour Olaoluwapo**.

---

## 📖 Table of Contents
1. [About the Project](#-about-the-project)
2. [Features](#-features)
3. [Prerequisites](#-prerequisites)
4. [Installation & Setup](#-installation--setup)
5. [Build & Run](#-build--run)
6. [Project Structure](#-project-structure)
7. [Version Control Workflow](#-version-control-workflow)
8. [Tech Stack](#-tech-stack)
9. [Author](#-author)

---

## 📜 About the Project
This project is a **Java Maven application** designed to demonstrate:
- How to set up a Java Maven project
- How to compile and package it
- How to run it inside an **AWS EC2 environment**
- How to track changes using **Git** and push to **GitHub**

This application currently prints **"Hello World!"** to the console, but can be expanded into a more complex system.

---

## ✨ Features
- 🛠 **Maven Build Automation**
- ☁ **Runs on AWS EC2**
- 📦 **Easily Packaged into a `.jar`**
- 🔗 **Git & GitHub Version Control**
- 🚀 **Lightweight & Ready for Deployment**

---

## ✅ Prerequisites
Before you begin, make sure you have:
- **Java 8+** installed
- **Maven** installed
- **Git** installed
- An **AWS EC2 instance** running
- A **GitHub repository** linked to your EC2 instance

---

## �� Installation & Setup
Clone this repository to your EC2 instance:
```bash
git clone https://github.com/mr-ffo/Devops-my-maven-app.git
cd Devops-my-maven-app
🔨 Build & Run

Build the project:mvn package
Run the project:
java -cp target/my-maven-app-1.0-SNAPSHOT.jar com.mycompany.app.App
You should see:

Hello World!
📂 Project Structure
my-maven-app/
│── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/mycompany/app/App.java
│   └── test/
│       └── java/
│           └── com/mycompany/app/AppTest.java
│── pom.xml
│── README.md

🔄 Version Control Workflow

    Make changes to your code

    Stage changes:

git add .

Commit changes:

git commit -m "Describe your changes"

Push changes to GitHub:

    git push origin main

🛠 Tech Stack

    Java (v8+)

    Maven

    AWS EC2

    Git & GitHub

✍ Author

👨‍💻 Folarin Favour Olaoluwapo
📧 Email: folarinfavourolaoluwapo@gmail.com
🔗 GitHub: mr-ffo

