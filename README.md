# Notes App Backend

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)
![Node.js](https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

This is the backend for a Notes application built with Node.js, Express, and MongoDB.

## Features

- RESTful API for creating, reading, updating, and deleting notes
- MongoDB database integration using Mongoose
- Serves a frontend (SPA) from the `dist` directory
- Request logging middleware
- Error handling and unknown endpoint handling

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account or local MongoDB

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vinle901/notebackend
   cd notebackend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the project root with the following content:
   ```
   MONGODB_URI=your-mongodb-uri
   PORT=3001
   ```

### Running the Server

```bash
npm start
```

The server will run on `http://localhost:3001` by default.

### API Endpoints

- `GET /api/notes` — Get all notes
- `GET /api/notes/:id` — Get a note by ID
- `POST /api/notes` — Create a new note
- `PUT /api/notes/:id` — Update a note
- `DELETE /api/notes/:id` — Delete a note

### Deployment

The app is deployed at:  
[https://note-oas0.onrender.com/](https://note-oas0.onrender.com/)

---

## License

This project is licensed under the MIT License.