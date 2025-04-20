# Apnagram - Instagram Clone (MERN Stack)

![Apnagram Screenshot](https://github.com/vaibhav-afk/project-demo/blob/main/ss.png?raw=true)

A full-stack social media application inspired by Instagram, built with modern web technologies. Implements core features like authentication, image sharing, and user interactions.

🔗 [Live Demo](https://apnagram.netlify.app/) <!---|🎥 [Video Walkthrough](https://loom.com/share/...) -->

## 🛠 Tech Stack & Architecture

### **Frontend**
- **React** (Functional Components, Hooks)
- **Context API** (State Management)
- **CSS Modules** (Scoped Styling)
- **Axios** (API Calls)

### **Backend**
- **Node.js** (Runtime)
- **Express** (REST API)
- **MongoDB** (Database)
- **Mongoose** (ODM)
- **JWT** (Authentication)

### **Services**
- **Cloudinary** (Image Storage - Free Tier)
- **MongoDB Atlas** (Database Hosting)
- **Render** (Backend Hosting)
- **Netlify** (Frontend Hosting)

## ✨ Key Features & Optimizations

### **Authentication System**
- JWT-based login/logout with refresh tokens
- Password reset flow using SendGrid
- Protected routes using token verification middleware .

### **Performance**
- Image uploads with Cloudinary's free-tier API  
- Component optimization through modular design  
- Efficient state management using React Context 

### **UI/UX**
- Responsive design for mobile/desktop
- Interactive modals for likes/comments
- Intuitive navigation

### Planned Enhancements  
- **Role-Based Access Control**: Implement admin/user permissions  
- **Advanced Caching**: Add Redis for frequently accessed posts  
- **Performance**:  
  - Implement lazy loading for images  
  - Adopt React.memo for post rendering optimization  
- **State Management**: Migrate to Zustand for better scalability  

## 🚀 Technical Highlights

### **Backend Architecture**
```plaintext
backend/
├── middleware/   # Auth guards and validators
├── models/       # MongoDB schemas
├── routes/       # API endpoints
│   ├── auth.js   # Authentication logic
│   ├── posts.js  # Post CRUD operations
│   └── users.js  # User profile management
