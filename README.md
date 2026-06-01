# Take-Home-Assignment
# 🎬 Movie Listing App

A full-stack Movie Listing Application built using React.js for the frontend and Express.js for the backend. The application displays movie information fetched from a backend API.

## 🚀 Features

- View a list of movies
- Backend REST API using Express.js
- React frontend with dynamic rendering
- JSON-based movie data storage
- Responsive and easy-to-use interface

## 🛠️ Technologies Used

### Frontend
- React.js
- JavaScript
- CSS

### Backend
- Node.js
- Express.js
- CORS

### Data Source
- movies_metadata.json

---

## 📂 Project Structure

```text
movie-listing-app/
│
├── public/
│   └── index.html
│
├── src/
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── ...
│
├── server/
│   ├── server.js
│   └── movies_metadata.json
│
├── package.json
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone <repository-url>
cd movie-listing-app
```

### 2. Install frontend dependencies

```bash
npm install
```

### 3. Install backend dependencies

```bash
npm install express cors
```

## ▶️ Running the Application

### Start Backend Server

```bash
node server/server.js
```

Server runs on:

```text
http://localhost:5000
```

### Start React Frontend

```bash
npm start
```

Application runs on:

```text
http://localhost:3000
```

## 📡 API Endpoint

### Get All Movies

```http
GET /api/movies
```

### Sample Response

```json
[
  {
    "id": 1,
    "title": "Inception",
    "year": 2010
  },
  {
    "id": 2,
    "title": "Interstellar",
    "year": 2014
  }
]
```

## 🔄 Future Enhancements

- Movie search functionality
- Genre filtering
- Pagination
- Movie details page
- User authentication
- Database integration (MongoDB/MySQL)

## 👨‍💻 Author

Developed as part of a Full Stack Web Development project using React and Express.

## 📄 License

This project is intended for educational purposes.
