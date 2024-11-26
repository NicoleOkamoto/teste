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
```

For development, we are using the `dev` branch instead of the `main` branch. Make sure to switch to the `dev` branch after cloning the repository:
```bash
git checkout dev
```

### 2. Install Dependencies
Navigate to the project folder and run:
```bash
npm install
```

### 3. Run the Development Server
Start the development server by running:
```bash
npm run dev
```

To assign a specific port, use:
```bash
npm run dev -- --port [port number]
```
Open your browser and navigate to http://localhost:3000 to see the application.

---

## Backend API Setup

### 1. Navigate to the backend folder:
   ```bash
   cd backend
```

### 2. Build the backend Docker image:
   ```bash
   docker build -t backend_image .
```

### 3. Run the backend container:
   ```bash
$ docker run -itd --name mysql-server -p 3316:3306 -e MYSQL_ROOT_PASSWORD=123456 MySQL
```

### 4. MySQL Setup - Config database server

Refer to the Technical Manual for detailed instructions. 

### Database Connection Indicator
The homepage includes a database connection status indicator. It displays:

- **🟢 Connected: If the backend is successfully connected to the MySQL database.**
- **🔴 Not Connected: If there is an issue with the database connection.**

### Preview

Below is an example of how the project will look when hosted locally:

![Homepage Preview](./assets/homepage-preview.png)

### You are all set and ready to dev, Happy coding 🥳
