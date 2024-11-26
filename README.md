# NurseX Technologies

This project is built with **Next.js** using the App Router, styled with **TailwindCSS**, and utilizes **shadcn components**. It includes a backend API integrated with a **MySQL database**. The frontend fetches data from this API, and components are written in **TypeScript** with `.tsx` files.

---

## Prerequisites

Before starting, ensure the following are installed on your machine:
- **Node.js** (including npm)
- **Git**
- **VS Code** or another code editor
- **Docker**

Make sure to set up a local Git repository to manage the project files.

---

## Features

- Database connection indicator: Displays if the database backend is connected or not.
- Clean and responsive UI.
- Backend API using **Express.js** to connect to a MySQL database.

---

## Getting Started

### 1. Clone the GitHub Repository
Use Git Bash and run the following command to download the repository:
```bash
git clone [SSH link]

### 2. Install Dependencies
Navigate to the project folder and run:
```bash
npm install

### 3. Set Up MySQL Server
Use Docker to create a MySQL server container:
```bash
docker run -itd --name mysql-server -p 3316:3306 -e MYSQL_ROOT_PASSWORD=123456 MySQL

### 4. Run the Development Server
Start the development server by running:
```bash
npm run dev

To assign a specific port, use:
```bash
npm run dev -- --port [port number]

Open your browser and navigate to http://localhost:3000 to see the application.

---

## Backend API Setup

1. Navigate to the backend folder:
   ```bash
   cd backend

2. Build the backend Docker image:
   ```bash
   docker build -t backend_image .

3. Run the backend container:
   ```bash
$ docker run -itd --name mysql-server -p 3316:3306 -e MYSQL_ROOT_PASSWORD=123456 mysql


# NurseX Technologies

This project is based on Next.JS. Using App Router, styling with tailwindcss.
Under the project folder, you'll need to make sure:
1. You have Node.js including npm installed on your machine.
2. Dependencies are installed, which is included in the package.json file.
3. You'll need a code editor installed such as VS code, and a local git repo set up.
4. Backend API is designed for MySQL Database, and the frontend fetches data from the API.
5. Components are created using TypeScript with JSX syntax, therefore documents are .tsx files.

Detailed installation and setup guide is included in the technical manual.

## Getting Started
To download from GitHub repo, use Git Bash and run:
`$ git clone [SSH link]`

To set a MySQL server docker container use the following command in CMD:
`$ docker run -itd --name mysql-server -p 3316:3306 -e MYSQL_ROOT_PASSWORD=123456 mysql`

To ensure all packages are installed, open the project folder and run `npm install` in CMD:

Host project in develop mode, run command in CMD/Terminal:
`npm run dev`

## You are all set and ready to dev, Happy coding 🥳
