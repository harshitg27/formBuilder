# FormBot - Create Your Own Bot

## 🚀 Project Overview
FormBot is a **Fullstack MERN** application that enables users to create and share customizable bots for efficient data collection. Users can design bots with various elements, apply themes, and analyze collected data effectively.

## 🌟 Features
- **User Authentication**: Secure login and signup using JSON Web Token (JWT).
- **Customizable Bot Elements**: Supports text, images, videos, GIFs, input fields, and themes.
- **CRUD Functionality**: Users can create, update, and delete bot templates.
- **Easy Sharing**: Share bots with others for streamlined data collection.
- **Data Analysis**: Gather and analyze collected responses efficiently.

## 🛠 Tech Stack
- **Frontend**: React.js (with Modular CSS for styling)
- **Backend**: Node.js & Express.js (REST API)
- **Database**: MongoDB
- **Frontend Library**: Axios , moment , react Icons
- **Backend Library**: bcrypt , express , jsonwebtoken , mongoose , dotenv ,   cors

## 🔗 Live Demo
[FormBot Deployment](https://harshit-gupta-form-builder.netlify.app/)
```
Demo User
Email - demo@gmail.com
Password - 12345
```


## 📂 Project Structure
```
formBot/
│-- client/      # React Frontend
│-- server/      # Express Backend
│-- models/      # Database Models
│-- routes/      # API Routes
│-- controllers/ # Business Logic
│-- middleware/      # Authentication and Autherization
```

## 🛠 Setup & Installation
1. **Clone the repository**
   ```sh
   git clone https://github.com/harshitg27/formBuilder.git
   cd formBuilder
   ```
2. **Install dependencies**
   ```sh
   cd client && npm install
   cd ../server && npm install
   ```
3. **Setup Environment Variables**
   - Create a `.env` file inside the `server/` directory and add:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   ```
4. **Run the application**
   ```sh
   # Start Backend
   cd server && nodemon index.js
   # Start Frontend
   cd client && npm run dev
   ```

## 🤝 Contributing
Contributions are welcome! Feel free to fork, create issues, and submit pull requests.

### **Author:**
**Harshit Gupta**  
📧 Email: Harshitg1710@gmail.com
🔗 GitHub: [Harshitg27](https://github.com/harshitg27)

## 📧 Contact
- **GitHub**: [harshitg27](https://github.com/harshitg27)
- **Live Demo**: [FormBot](https://harshit-gupta-form-builder.netlify.app/)

