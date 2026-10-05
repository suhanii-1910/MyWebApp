# 🚀 MyWebApp

### WAD Experiment 12 – Git, GitHub, Jenkins & Apache Tomcat

This repository was created as part of my **Web Application Development (WAD)** college assignment.

## Assignment Title

**Experiment 12: To understand the basic use of Git, Jenkins, and Apache Tomcat for managing and running a web application.**

## Objective

The objective of this experiment was to understand the basic development and deployment workflow:

**Git → GitHub → Jenkins → Apache Tomcat → Web Application**

This experiment demonstrates how source code can be managed using Git, stored on GitHub, fetched using Jenkins, and finally deployed using Apache Tomcat.

## Technologies Used

- **HTML** – for creating the web application
- **Git** – for version control
- **GitHub** – for hosting the source-code repository
- **Jenkins** – for fetching and checking the latest project code
- **Apache Tomcat 9** – for hosting and running the web application
- **Homebrew** – for installing Jenkins and Tomcat on macOS
- **Visual Studio Code** – for writing and editing the application
- **macOS Terminal** – for executing Git and deployment commands

## Project Structure

```text
MyWebApp/
└── index.html
```

## Features

- Simple HTML web application
- Git repository initialization
- Initial Git commit
- Project uploaded to GitHub
- Application updated and pushed again using Git
- Jenkins connected to the GitHub repository
- Jenkins build completed successfully
- Apache Tomcat configured on port `8081`
- Web application deployed successfully on Tomcat

## Git Commands Used

### Initial Commit

```bash
git init
git add .
git commit -m "Initial web application"
```

### Connect Repository to GitHub

```bash
git remote add origin <repository-url>
git branch -M main
git push -u origin main
```

### Update the Application

```bash
git add .
git commit -m "Updated application title"
git push
```

## Jenkins Configuration

A Jenkins **Freestyle Project** named `MyWebApp` was created.

The GitHub repository was configured under:

`Source Code Management → Git`

The branch used was:

`*/main`

The Jenkins build completed successfully and displayed:

`Finished: SUCCESS`

This confirmed that Jenkins was able to fetch the latest version of the application from GitHub.

## Apache Tomcat Configuration

Jenkins was running on:

`http://localhost:8080`

Since Jenkins was already using port `8080`, Apache Tomcat was configured to run on:

`http://localhost:8081`

The application was deployed inside Tomcat using the following structure:

```text
webapps/
└── MyWebApp/
    └── index.html
```

The final web application was accessed through:

`http://localhost:8081/MyWebApp/`

## Workflow

```text
Developer
   ↓
Git
   ↓
GitHub
   ↓
Jenkins
   ↓
Apache Tomcat
   ↓
Web Browser
```

## Learning Outcomes

Through this experiment, I learned:

- How to initialize and manage a project using Git
- How to commit and push code to GitHub
- How to update and maintain different versions of a project
- How to configure Jenkins with a GitHub repository
- How Jenkins fetches the latest source code
- How to install and configure Apache Tomcat
- How to deploy a web application on Tomcat
- How Git, GitHub, Jenkins, and Tomcat work together in a basic development and deployment workflow

## Author

**Suhani Garg**  
B.Tech Computer Science and Engineering  
Symbiosis Institute of Technology, Pune

---

> This repository was created for academic and learning purposes as part of a Web Application Development college assignment.
