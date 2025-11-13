🚀 Tech Stack
Frontend

React + Vite

Axios

React Router DOM

Backend

Node.js

Express.js

MongoDB

Mongoose

CORS

📌 Features

➕ Add new movie (Title + Description)

🏠 View all movies on Home page

🔌 Add movies using REST API (Thunder Client/Postman)

⚙ MERN folder structure (frontend + backend)

📦 MongoDB database integration

🎨 Clean UI with Navbar & Footer

📁 Project Structure
Jay Mern Test/
│
├── backend/
│   ├── server.js
│   ├── models/
│   │   └── Movie.js
│   └── routes/
│       └── movieRoutes.js
│
└── frontend/
    ├── src/
    │   ├── pages/
    │   │   ├── AddMovie.jsx
    │   │   └── Home.jsx
    │   ├── components/
    │   │   └── Navbar.jsx
    │   ├── App.jsx
    │   └── main.jsx

⚙ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/yourusername/Jay-Mern-Test.git
cd Jay-Mern-Test

🖥 Backend Setup
cd backend
npm install

Create .env file inside backend:
MONGO_URI=your_mongodb_url
PORT=5000

Start Backend
npm start


Backend runs at:

http://localhost:5000/

🌐 Frontend Setup
cd frontend
npm install
npm run dev


Frontend runs at:

http://localhost:5173/

📡 API Endpoints
🔹 Add Movie

POST:

http://localhost:5000/api/movies


Body (JSON):

{
  "title": "Inception",
  "description": "A mind-bending thriller"
}

🔹 Get All Movies

GET:

http://localhost:5000/api/movies

🧪 Testing With Thunder Client / Postman

Open Thunder Client

Select POST → JSON

URL:

http://localhost:5000/api/movies


Add JSON body:

{
  "title": "Avatar",
  "description": "A sci-fi masterpiece"
}


Click Send

Movie will appear on the frontend Home page

🛠 Future Enhancements

🗑 Delete Movie

✏ Update Movie

🖼 Upload Movie Poster

🔍 Search & Filter Movies

🔐 Authentication (Login/Register)

📱 Make UI fully responsive

🏁 Conclusion

This MERN app is perfect for beginners learning full-stack development.
It shows how to connect a frontend React UI with a backend Express API and a MongoDB database.


Screenshots:

<img width="1311" height="843" alt="image" src="https://github.com/user-attachments/assets/e98090ce-71a7-4008-865c-2974ccdf4cff" />
<img width="1303" height="839" alt="image" src="https://github.com/user-attachments/assets/c58aeac4-cadd-4640-9bac-ef7e886a1455" />

