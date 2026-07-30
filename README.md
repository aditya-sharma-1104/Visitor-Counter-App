# 👥 Visitor Counter App

A modern, lightweight web application that tracks and displays the total number of visitors to your website in real time. The application automatically increments the visitor count whenever someone visits the page and stores the count using Redis, ensuring fast and reliable performance.

---

## 🌐 Live Demo

🔗 **Website:** https://your-netlify-link.netlify.app

> Replace the above URL with your deployed application link.

---

## 📖 Overview

The Visitor Counter App is designed to demonstrate the fundamentals of full-stack web development. It combines a responsive frontend with a Flask backend and Redis database to create a real-time visitor tracking system.

Whether you're learning web development or looking for a simple analytics project, this application provides a clean implementation of backend APIs, database integration, Docker, and CI/CD workflows.

---

## ✨ Features

- 📈 Real-time visitor counting
- ⚡ Automatic count increment on every visit
- 💾 Redis database for fast storage
- 🎨 Responsive and modern UI
- 🐳 Docker support
- 🔄 Docker Compose configuration
- 🚀 GitHub Actions CI/CD workflow
- 🛠️ Easy deployment and setup

---

## 🏗️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Flask (Python)

### Database
- Redis

### DevOps
- Docker
- Docker Compose
- GitHub Actions

---

## 📂 Project Structure

```
Visitor-Counter-App/
│
├── .github/
│   └── workflows/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── docker-compose.yml
├── README.md
│
└── static/
    ├── css/
    ├── js/
    └── images/
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/aditya-sharma-1104/Visitor-Counter-App.git
```

### 2. Navigate into the project

```bash
cd Visitor-Counter-App
```

### 3. Create a virtual environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### macOS/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Start Redis

Make sure Redis is installed and running.

Or start it using Docker:

```bash
docker run -d -p 6379:6379 redis
```

### 6. Run the application

```bash
python app.py
```

Open your browser and visit:

```
http://localhost:5000
```

---

# 🐳 Running with Docker

Build the Docker image

```bash
docker build -t visitor-counter .
```

Run the container

```bash
docker run -p 5000:5000 visitor-counter
```

Or simply use Docker Compose

```bash
docker-compose up --build
```

---

## 📸 Screenshots

### Home Page

> Add your application screenshot here.

```
images/home.png
```

---

## 🔄 How It Works

1. A visitor opens the website.
2. Flask receives the request.
3. The backend connects to Redis.
4. The visitor count is incremented.
5. The updated count is returned to the frontend.
6. The latest visitor count is displayed instantly.

---

## 🚀 Future Improvements

- Unique visitor tracking
- IP-based analytics
- Visitor history
- Daily and monthly reports
- Admin dashboard
- Charts and graphs
- Dark mode
- Visitor location tracking
- Authentication
- REST API support

---

## 🤝 Contributing

Contributions are always welcome.

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push to GitHub.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Aditya Kumar Sharma**

- GitHub: https://github.com/aditya-sharma-1104

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.

It motivates me to build more open-source projects.
