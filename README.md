# 🚀 Project Setup Guide (Frontend + Backend)

This project consists of:

* Backend: Spring Boot (Java + Maven)
* Frontend: Next.js (React)

---

# 📦 Prerequisites (MANDATORY)

Make sure these are installed before running the project:

## 1. Install Java (JDK 17 or higher)

Download from: https://adoptium.net/

Verify:

```bash
java -version
```

---

## 2. Install Maven

Download from: https://maven.apache.org/download.cgi

Verify:

```bash
mvn -version
```

---

## 3. Install Node.js (v18+ recommended)

Download from: https://nodejs.org/

Verify:

```bash
node -v
npm -v
```

---

## 4. Install Git

Download from: https://git-scm.com/

Verify:

```bash
git --version
```

---

# 📥 Clone Repository

```bash
git clone https://github.com/AshitoshAmbilwade/DRC.git
cd DRC
```

---

# ⚙️ Backend Setup (Spring Boot)

## Navigate to backend folder

```bash
cd AiJobAssistantBackEnd1
```

## Install dependencies

```bash
mvn clean install
```

## Run backend server

```bash
mvn spring-boot:run
```

👉 Backend will start on:

```
http://localhost:8080
```

---

# 🎨 Frontend Setup (Next.js)

## Open new terminal and navigate:

```bash
cd AiJobAssistantFrontEnd
```

## Install dependencies

```bash
npm install
```

## Run development server

```bash
npm run dev
```

👉 Frontend will run on:

```
http://localhost:3000
```

---

# 🔑 Environment Variables (IMPORTANT)

Create `.env` file inside frontend/backend if required.

Example:

```
NEXT_PUBLIC_API_URL=http://localhost:8080
```

---

# 🧪 Common Issues & Fixes

## 1. Port already in use

Kill process or change port in config.

---

## 2. Maven not recognized

Add Maven to system PATH.

---

## 3. Node modules error

```bash
rm -rf node_modules package-lock.json
npm install
```

---

## 4. Java version mismatch

Ensure JDK 17+ is installed and configured.

---

# 🧠 Development Workflow

1. Start backend first
2. Then start frontend
3. Make changes → auto reload enabled

---

# 📌 Notes

* Backend and frontend must run simultaneously
* Ensure API URL is correctly configured
* Use proper branch while working

---

# 👨‍💻 Author

Ashitosh Ambilwade
