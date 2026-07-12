# Node.js Continuous Integration using Jenkins and GitHub

## Project Description

This project demonstrates Continuous Integration (CI) using Node.js, Jenkins, and GitHub. The main objective is to automate the build process whenever code is pushed to the GitHub repository.

GitHub is connected to Jenkins using a webhook. Whenever a developer pushes new code, Jenkins automatically starts the pipeline, downloads the latest project, installs the required dependencies, runs the test stage, and completes the build process.

---

## Project Objectives

- Learn the concept of Continuous Integration.
- Connect GitHub with Jenkins.
- Automate the build process.
- Execute the pipeline automatically using GitHub Webhooks.
- Reduce manual work during software development.

---

## Tools Used

- Node.js
- Jenkins
- Git
- GitHub
- GitHub Webhooks
- ngrok
- Visual Studio Code

---

## Project Files

```
node-ci-project/
│── Jenkinsfile
│── index.js
│── package.json
│── package-lock.json
└── README.md
```

---

## Pipeline Workflow

Developer
↓
Push Code to GitHub
↓
GitHub Webhook
↓
Jenkins Pipeline
↓
Clone Repository
↓
npm install
↓
npm test
↓
npm run build
↓
Build Successful

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/Sharan358/node-ci-project.git
```

Go to the project folder:

```bash
cd node-ci-project
```

Install dependencies:

```bash
npm install
```

Run the project:

```bash
npm start
```

---

## Expected Output

Whenever code is pushed to GitHub:

- GitHub sends a webhook to Jenkins.
- Jenkins starts the pipeline automatically.
- The project is cloned.
- Dependencies are installed.
- Tests are executed.
- The build completes successfully.

---

## Author

**Sharan Sai**

Mini Project - Node.js Continuous Integration using Jenkins and GitHub
