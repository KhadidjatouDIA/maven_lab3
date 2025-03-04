# 📦 Commandes - Projet Maven Multi-modules

Ce projet est un projet **Maven multi-modules** qui se compose des modules suivants :

- **commandes (projet parent)** : Contient la configuration globale et la gestion des dépendances.
- **services** : Module backend qui gère la logique métier avec Spring Boot.
- **web** : Application frontend développée en Angular.

-----
![img_1.png](img_1.png)
## 🚀 Installation et Exécution

### 1️⃣ Prérequis
Avant de commencer, assure-toi d'avoir installé :
```plaintext
- Java 17+
- Maven 3.9
- Node.js 16+ et npm (pour Angular)
```

---

### 2️⃣ Cloner le projet
```sh
git clone https://github.com/KhadidjatouDIA/maven_lab3.git
```

### 3️⃣ Build le projet <br>
💡 Compiler tout le projet :
```sh
mvn clean install
```
Cela construira tous les modules (services et web).

💡 Compiler un module spécifique :
```sh
mvn clean install -pl services -am
```
![img.png](img.png)

### Lancer le projet:
➤ Installer les dépendances:
```sh 
cd web
npm install
```
➤ Lancer l'application Angular:
```sh 
npm start
```
➤ Accès à l'application : **http://localhost:4200/**
![img_2.png](img_2.png)

## 👤 Khadidiatou DIA
📧 sokhnakhadidjah@gmail.com