# How to Use GeneratorCode

Welcome! This guide will help you get started quickly with **GeneratorCode**, your AI-powered tool for generating complete .NET backends.

---

## 1. Two Ways to Generate Your Backend

You have two options to generate your backend:

### Option 1: Using AI with a Prompt

- Enter a natural language prompt describing the backend you want.
- For example:
'Medical Clinic Appointment Booking System. Create a platform where patients can book appointments with doctors from various specialties. Include doctors, specialties, available schedules, medical history, prescriptions, and reminders.'


- The AI will interpret your prompt and generate the backend accordingly.

### Option 2: Using Your Database Connection

- Go to the **Front Database** option.
- Enter a valid connection string to your SQL Server database.
- Click **Generate Schema**.
- The application will analyze your database schema and generate backend code.

---

## 2. Schema Generation Process

- The schema generation process may take around 20 seconds.
- Once completed, review the generated schema carefully.
- If you want to modify anything (e.g., table names, field names, schemas), do so before proceeding.
- If everything looks good, click **Generate App**.
- You will be prompted to provide a name for your application.

---

## 3. Downloading and Exploring the Generated Solution

- After generation, a compressed file with your .NET solution will be downloaded.
- Extract the compressed file.
- Inside, you will find:
- The full .NET backend solution.
- A SQL script you can run on your own database.
- A Postman collection for testing your API endpoints.

---

## 4. Running Your Application Locally

You have two options to run your app locally:

### Option 1: Using Docker Desktop

- Make sure you have [Docker Desktop](https://www.docker.com/products/docker-desktop) installed.
- Open a terminal in the project folder.
- Run:

```bash
docker-compose up --build


