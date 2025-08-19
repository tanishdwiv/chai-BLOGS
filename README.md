

# chai-BLOGS ☕📖

*A Modern Full-Stack Blogging Platform*

chai-BLOGS is a **full-stack web application** designed for creating, managing, and sharing technical blogs. It allows authenticated users to write and publish blogs, while others can explore, read, and engage with the content. The platform is built with a focus on **performance, responsiveness, and a clean user experience**.

---

## 🚀 Features

* ✍️ **Create & Manage Blogs** – Write, edit, and delete your blogs with ease.
* 🔒 **Authentication** – Secure login & signup functionality for users.
* 🌗 **Dark & Light Mode** – Toggle between light and dark themes for better reading experience.
* 🖼️ **Image Support** – Upload and manage blog thumbnails/images.
* 📱 **Responsive Design** – Works seamlessly across desktops, tablets, and mobiles.
* 🔎 **Explore Blogs** – Users can read and engage with published blogs.

---

## 🛠️ Tech Stack

**Frontend**

* [Next.js](https://nextjs.org/)
* [React.js](https://reactjs.org/)
* [Tailwind CSS](https://tailwindcss.com/)

**Backend**

* [Node.js](https://nodejs.org/)
* [Express.js](https://expressjs.com/)

**Database & Storage**

* [MongoDB](https://www.mongodb.com/) – Blog data storage
* [Firebase](https://firebase.google.com/) – Thumbnail image storage

**Authentication**

* JWT-based Authentication / Clerk / Firebase Auth (depending on final implementation)

---

## 📂 Project Structure

```
chai-BLOGS/
│── prisma/          # Database schema & configurations  
│── public/          # Static files (icons, images, etc.)  
│── src/             # Application source code  
│   ├── components/  # Reusable UI components  
│   ├── pages/       # Next.js pages  
│   ├── styles/      # Global styles  
│   └── utils/       # Helper functions  
│── package.json     # Dependencies & scripts  
│── next.config.js   # Next.js configuration  
│── README.md        # Project documentation  
```

---

## ⚡ Getting Started

Follow these steps to set up the project locally:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/tanishdwiv/chai-BLOGS.git
cd chai-BLOGS
```

### 2️⃣ Install Dependencies

```bash
npm install
# or
yarn install
```

### 3️⃣ Configure Environment Variables

Create a `.env.local` file in the root directory and add the following:

.env
MONGODB_URI=your_mongodb_connection_string
FIREBASE_API_KEY=your_firebase_api_key
FIREBASE_PROJECT_ID=your_firebase_project_id
JWT_SECRET=your_jwt_secret


### 4️⃣ Run the Development Server

```bash
npm run dev
# or
yarn dev


Now visit **[http://localhost:3000](http://localhost:3000)** in your browser 🚀

---

## 📸 Screenshots

> *(Add screenshots/gifs of your app here – home page, blog editor, dark/light mode, etc.)*

---

## 🔮 Future Enhancements

* 💬 Comments section for blogs
* ❤️ Like/Bookmark functionality
* 👥 User profiles with bio and blog history
* 🧵 Categories & Tags for better content discovery
* 📊 Analytics for blog views and engagement

---

## 🤝 Contributing

Contributions are welcome! If you’d like to improve chai-BLOGS:

1. Fork the repo
2. Create a new branch (`feature/your-feature-name`)
3. Commit your changes
4. Push the branch and open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.
You’re free to use, modify, and distribute it with proper attribution.

---

## 👨‍💻 Author

**Tanish Dwivedi**

* 💼 [LinkedIn](https://www.linkedin.com/in/tanishdwiv)
* 🐙 [GitHub](https://github.com/tanishdwiv)

---

⭐ If you like this project, don’t forget to **star the repo** on GitHub!


