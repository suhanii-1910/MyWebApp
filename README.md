# MyWebApp – WAD Experiment 12

This repository was created as part of my **Web Application Development (WAD)** college assignment.

## Assignment Title

**Experiment 12: To understand the basic use of Git, Jenkins, and Apache Tomcat for managing and running a web application.**

## Objective

The main objective of this assignment was to understand the complete basic workflow of:

**Git → GitHub → Jenkins → Apache Tomcat → Web Application**

This experiment helped in understanding how source code is managed using Git, stored on GitHub, fetched using Jenkins, and finally deployed on Apache Tomcat.

## Technologies Used

- **HTML** – for creating the simple web application
- **Git** – for version control
- **GitHub** – for hosting the repository
- **Jenkins** – for fetching and checking the latest project code
- **Apache Tomcat 9** – for hosting and running the web application
- **Homebrew** – for installing Jenkins and Tomcat on macOS
- **VS Code** – for writing and editing the project files
- **macOS Terminal** – for executing Git and deployment commands

## Project Structure

```text
MyWebApp/
└── index.html

Features
- Simple HTML web application
- Git repository initialization
- Initial Git commit
- Project uploaded to GitHub
- Application updated and pushed again using Git
- Jenkins configured with the GitHub repository
- Jenkins build completed successfully
- Apache Tomcat configured on port 8081
- Web application deployed successfully on Tomcat

Git Commands Used
git init
git add .
git commit -m "Initial web application"

git remote add origin <repository-url>
git branch -M main
git push -u origin main

After updating the application:
git add .
git commit -m "Updated application title"
git push

Jenkins Configuration
A Jenkins Freestyle Project named MyWebApp was created.
The GitHub repository was configured under:
Source Code Management → Git

The branch used was:
*/main

The successful Jenkins build confirmed that Jenkins was able to fetch the latest version of the application from GitHub.
Apache Tomcat Configuration
Jenkins was running on:
http://localhost:8080

Therefore, Apache Tomcat was configured to run on:
http://localhost:8081

The application was deployed inside Tomcat using the following structure:
webapps/
└── MyWebApp/
    └── index.html

The final application was accessed through:
http://localhost:8081/MyWebApp/

Workflow
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

Learning Outcome
Through this assignment, I learned:
- how to initialize and manage a project using Git
- how to push and update code on GitHub
- how Jenkins can fetch code from a GitHub repository
- how to configure and run Apache Tomcat
- how to deploy a web application on Tomcat
- how basic source control, automation, and deployment tools work together
Author
Suhani Garg
B.Tech Computer Science and Engineering
Symbiosis Institute of Technology, Pune
This repository was created for academic and learning purposes as part of a college Web Application Development assignment.


You can also make the top of the README a little more polished by using this title instead:

```markdown
# 🚀 MyWebApp
### WAD Experiment 12 – Git, GitHub, Jenkins & Apache Tomcat
