# How to Use GeneratorCode

Welcome! This guide will help you get started quickly with **GeneratorCode**, your AI-powered tool for generating complete .NET backends.

---

## 1. Get Started Online

You don’t need to install anything to try GeneratorCode. Just:

- Go to [https://generatorcode.net](https://generatorcode.net)
- Enter a natural language prompt describing your backend or provide your database connection string
- Click **Generate**
- Download or clone the generated .NET backend ready to run

---

## 2. Run Locally with Docker

If you want to test GeneratorCode on your machine:

1. Make sure you have [Docker](https://www.docker.com/get-started) installed

2. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USER/YOUR-REPO.git
   cd YOUR-REPO
Build and run the app using Docker Compose:

    docker-compose up --build

3. Access the app at http://localhost:5000/swagger/index.html
4. Using Prompts

You can provide natural language prompts like:

    “Create a backend for a blog with users, posts, and comments.”

    “Generate a .NET API with clean architecture and CQRS for an e-commerce database.”

The AI will interpret your request and generate the backend code accordingly.
4. Using Connection Strings

If you have an existing database, just enter your connection string (e.g., for SQL Server) and GeneratorCode will:

    Analyze your database schema

    Generate backend code with models, repositories, commands, and queries following clean architecture and CQRS patterns

5. Next Steps

    Download the generated code

    Open it in your favorite IDE (Visual Studio, VS Code)

    Build and run your new backend

    Customize or extend as needed

6. Need Help or Want to Give Feedback?

    Open an issue or discussion in this repo here 

