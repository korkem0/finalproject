# finalproject
finalproject
Description
A simple blog application built with Node.js, Express.js, MongoDB, and EJS templates. It includes an admin panel for managing blog posts with image upload functionality.

Features
Admin Dashboard for managing posts.
CRUD operations for posts.
Image uploads using Multer.
User authentication with JWT.
Responsive design with EJS templates.

Installation
Clone the repository:

git clone <repository-url>
cd <project-folder>


Install dependencies:

npm install


Set up .env file:

MONGODB_URI=<Your MongoDB URI>
JWT_SECRET=<Your JWT Secret>


Create an uploads folder:

mkdir uploads


Start the server:

npm start

Access the app:
Blog: http://localhost:3000
Admin Dashboard: http://localhost:3000/admin

Project Structure
/public: Static assets (CSS, JS)
/uploads: Uploaded images
/views: EJS templates
/server: Routes, models, config
Usage
Admin: Log in, create, edit, delete posts, and upload images.
Public: View blog posts.
