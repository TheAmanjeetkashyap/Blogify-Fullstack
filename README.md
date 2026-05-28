📝 Blogify - Full Stack Blogging Platform
Blogify is a full-stack blogging web application built using Node.js, Express.js, MongoDB, and EJS templating. It features user authentication, CRUD operations for blog posts, and a simple admin panel for managing content. LIVE LINK: https://blogify-fullstack.onrender.com/
🚀 Features
✍️ User Signup/Login with authentication (JWT or sessions)
📰 Create, edit, delete, and view blog posts
🧑 Admin-only delete feature for any blog
🗃️ MongoDB for blog and user data storage
🎨 Clean and responsive UI using Bootstrap
🔐 Cookie-based or token-based authentication
📚 EJS-powered server-side rendering
🛠️ Tech Stack
Frontend: HTML, CSS, Bootstrap, EJS
Backend: Node.js, Express.js
Database: MongoDB + Mongoose
Authentication: Sessions / JWT + Cookies
Templating: EJS
⚙️ Installation
# 1. Clone the repository
git clone https://github.com/TheAmanjeetkashyap/Blogify-Fullstack.git
cd blogify-fullstack

# 2. Install dependencies
npm install

# 3. Set up environment variables
# Create a .env file and add the following:
# PORT=3000
# MONGODB_URI=mongodb://127.0.0.1:27017/blogify
# JWT_SECRET=your_secret_key (if using JWT)

# 4. Run the app
npm start

blogify/
├── models/
│   └── Blog.js
│   └── User.js
├── routes/
│   └── auth.js
│   └── blog.js
├── views/
│   └── home.ejs
│   └── login.ejs
│   └── dashboard.ejs
├── public/
│   └── css/
│   └── js/
├── app.js / index.js
├── .env
