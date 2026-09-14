# 🎁 Zyvora

**AI Powered Personalized Gifting Platform with WebAR**

Zyvora is a full stack AI powered gifting platform that helps users discover, customize, and visualize personalized gift hampers. Instead of browsing hundreds of products manually, users simply describe the occasion, recipient, or preferences, and the AI generates intelligent gift recommendations. The platform also provides an immersive WebAR experience, allowing users to preview products in their real environment before purchasing.

---

## ✨ Features

* 🤖 AI powered gift recommendations using Groq LLM
* 🎁 Personalized gift hamper creation
* 🛍 Smart product recommendation engine
* 📦 Custom hamper management
* 🔐 Secure JWT Authentication
* 👤 User Profile Management
* 📱 Responsive and modern UI
* ⚡ Fast performance with Next.js
* 🌐 WebAR product visualization
* 📊 Real time data synchronization

---

## 🛠 Tech Stack

### Frontend

* Next.js
* React
* TypeScript
* Tailwind CSS
* Framer Motion
* React Context API

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Bcrypt

### AI

* Groq API
* LLM Based Recommendation System

### AR & 3D

* Three.js
* React Three Fiber
* WebXR

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/zyvora.git
cd zyvora
```

---

### Install dependencies

Frontend

```bash
cd client
npm install
```

Backend

```bash
cd server
npm install
```

---

### Environment Variables

Create a `.env` file inside the server directory.

```env
PORT=5000

MONGODB_URI=your_mongodb_connection

JWT_SECRET=your_secret_key

GROQ_API_KEY=your_groq_api_key
```

---

### Run the application

Backend

```bash
npm run dev
```

Frontend

```bash
npm run dev
```

---

## 📁 Project Structure

```text
zyvora
│
├── client
│   ├── components
│   ├── pages
│   ├── context
│   ├── hooks
│   ├── utils
│   └── assets
│
├── server
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   ├── config
│   ├── services
│   └── utils
│
└── README.md
```

---

## 🧠 How It Works

1. User signs in to the platform.
2. User enters details about the recipient, occasion, budget, and preferences.
3. Groq AI analyzes the prompt and generates personalized gift recommendations.
4. Users can customize and build their own gift hamper.
5. Products can be previewed using WebAR before purchase.
6. Final selections are saved and managed through the user's account.

---

## 🔒 Authentication

* User Registration
* User Login
* JWT Based Authentication
* Protected Routes
* Password Encryption using Bcrypt

---

## 🎯 Future Improvements

* Payment Gateway Integration
* Wishlist
* Order Tracking
* Voice Based Gift Search
* Multi Language Support
* Admin Dashboard
* AI Generated Greeting Cards
* Social Gift Sharing
* Recommendation Learning from User Behavior

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create your feature branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Developer

Built with ❤️ by **Divyanshu, Ayesha and Astha**

If you found this project helpful, consider giving it a ⭐ on GitHub.
