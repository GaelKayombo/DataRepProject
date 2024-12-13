# DataRepProject

What It Does
Lets you view a list of perfumes.
You can add new perfumes to the list.
Edit details of existing perfumes.
Delete perfumes if needed.
Uses a backend API with Express and Mongoose.
React is used for the frontend to make it interactive.


Tech Stack
Frontend: React, Axios, React Router
Backend: Node.js, Express.js, Mongoose
Database: MongoDB (hosted on MongoDB Atlas)

How to Run This
Backend
Open the terminal and go to the backend folder:
bash
Copy code
cd backend
Install the backend dependencies:
bash
Copy code
npm install
Create a .env file and add this:
makefile
Copy code
MONGO_URI=your_mongo_connection_string
Start the server:
bash
Copy code
npx nodemon server.js
Frontend
Go to the frontend folder:
bash
Copy code
cd ../frontend
Install the frontend dependencies:
bash
Copy code
npm install
Start the React app:
bash
Copy code
npm start


Where to See It
Open http://localhost:3000 in your browser for the frontend.
Backend API is at http://localhost:4000/api.
API Endpoints


Method	Endpoint	What It Does
GET	/api/perfumes	Gets all perfumes.
POST	/api/perfumes	Adds a new perfume.
PUT	/api/perfumes/:id	Updates a perfume by ID.
DELETE	/api/perfumes/:id	Deletes a perfume by ID.
What’s Next
Add a search bar to find perfumes easily.
Clean up the design with better styling (maybe use Bootstrap or Tailwind).
Maybe add user accounts in the future.


Why I Made This
This is my project for the Data Representation and Querying module. It shows how to build a full-stack app using modern tools. Hope you like it!

