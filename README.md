# CompileVerse ✨ - Compile, Analyze, and Optimize with AI

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue.svg?logo=react)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-20.x-green.svg?logo=node.js)](https://nodejs.org/)
[![Docker](https://img.shields.io/badge/Docker-blue.svg?logo=docker)](https://www.docker.com/)
[![AWS](https://img.shields.io/badge/AWS-orange.svg?logo=amazon-aws)](https://aws.amazon.com/)

An advanced online code compiler that not only executes your code but also provides instant Time & Space Complexity analysis and an AI-powered review for code optimization.

---

## 🚀 Live Demo

**[Link to your deployed CompileVerse frontend]**

*(Add a GIF or screenshot of CompileVerse in action here!)*

![CompileVerse Demo GIF](https://your-link-to-a-demo-gif-or-screenshot.com/demo.gif)

## 🤔 What is CompileVerse?

In a world full of online code compilers, CompileVerse stands out by focusing on what matters most after getting the correct output: **code efficiency**. It's designed for students, developers, and interview preppers who want to write not just working code, but *optimal* code.

## ✨ Key Features

* **💻 Modern Code Editor**: A beautiful and responsive code editor powered by `@monaco-editor/react`.
* **🌗 Dark & Light Modes**: Seamlessly switch between themes for your comfort.
* **📊 Instant Complexity Analysis**: Run your code and instantly get its **Time and Space Complexity**.
* **🤖 AI Code Review**: Get an **optimized version** of your code and its improved complexity with a single click.
* **🐳 Dockerized Backend**: The backend is containerized with Docker for consistent and scalable deployment.

## 🚧 Deployment Status & Call for Help

* **Frontend**: ✅ The React frontend is successfully deployed and live!
* **Backend**: ⚠️ The Node.js backend has been secured and containerized using **Docker**. The image is ready for cloud deployment.

I am currently facing a challenge with the final step of deploying the backend Docker container to **AWS**. If you have experience with Docker on AWS (using services like **ECR, ECS, or Elastic Beanstalk**) and are willing to help, your guidance would be immensely appreciated! Please open an issue or a pull request.

## 🛠️ Tech Stack

* **Frontend**: React.jsx, Tailwind CSS, @monaco-editor/react
* **Backend**: Node.js, Express.js
* **DevOps**: Docker, AWS
* **AI Integration**: [Mention the AI model/API you used]

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Node.js (v18 or higher)
* Docker
* npm / yarn

### Installation

1.  **Clone the repo**
    ```sh
    git clone [https://github.com/your-username/compileverse.git](https://github.com/your-username/compileverse.git)
    ```
2.  **Set up Environment Variables** in the `/server` directory.
3.  **(Option A) Run Locally with Node**
    * Install dependencies and run the server and client in separate terminals.
4.  **(Option B) Run Locally with Docker**
    * Build the Docker image: `docker build -t compileverse-backend .` in the `/server` directory.
    * Run the container: `docker run -p 8080:8080 compileverse-backend`

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

We are **particularly looking for help with deploying our Dockerized backend to AWS**. If you have expertise in this area, please see the "Deployment Status" section above and feel free to reach out.

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📬 Contact

Your Name - [@YourLinkedIn](https://www.linkedin.com/in/your-linkedin-profile/) - your.email@example.com

Project Link: [https://github.com/your-username/compileverse](https://github.com/your-username/compileverse)
