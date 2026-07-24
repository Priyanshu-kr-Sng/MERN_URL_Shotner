# 🔗 MERN URL Shortener

A full-stack URL Shortener application built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. It allows users to shorten long URLs into compact, shareable links and automatically redirects users to the original website when the shortened URL is visited.

---

## 🚀 Features

- 🔗 Shorten long URLs
- ⚡ Instant URL redirection
- 📋 Copy shortened URL with one click
- ✅ URL validation
- 📱 Responsive user interface
- 🗄️ MongoDB database integration
- 🌐 RESTful API architecture

---

## 🛠️ Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript (ES6+)
- Axios

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

---

## 📂 Project Structure

```
MERN_URL_Shotner/
│
├── client/
│   ├── public/
│   ├── src/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── server.js
│   └── package.json
│
├── .gitignore
├── README.md
└── package.json
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Priyanshu-kr-Sng/MERN_URL_Shotner.git
```

### 2. Navigate to the project

```bash
cd MERN_URL_Shotner
```

### 3. Install backend dependencies

```bash
cd server
npm install
```

### 4. Install frontend dependencies

```bash
cd ../client
npm install
```

---

## ▶️ Run the Project

### Start Backend

```bash
cd server
npm start
```

or

```bash
npm run dev
```

### Start Frontend

```bash
cd client
npm start
```

The application will typically run on:

- Frontend: http://localhost:3000
- Backend: http://localhost:5000

---

## 🔐 Environment Variables

Create a `.env` file inside the **server** folder.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
BASE_URL=http://localhost:5000
```

---

## 📷 Screenshots

### Home Page

> Add a screenshot here.

```
screenshots/home.png
```

### Shortened URL

> Add another screenshot here.

```
screenshots/result.png
```

---

## 📡 API Endpoints

### Create Short URL

```
POST /api/url/shorten
```

Request

```json
{
  "url": "https://example.com"
}
```

Response

```json
{
  "shortUrl": "http://localhost:5000/abc123"
}
```

---

## 🎯 Future Improvements

- User authentication
- Custom short URLs
- QR Code generation
- Click analytics
- Expiration date for URLs
- Dashboard for managing links
- Dark mode

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add feature"
```

4. Push your branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Priyanshu Kumar Singh**

- GitHub: https://github.com/Priyanshu-kr-Sng
- LinkedIn: https://www.linkedin.com/in/priyanshu-kumar-singh-b6128524b/

---

⭐ If you found this project useful, please consider giving it a star!
