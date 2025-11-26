MagicLens AI — Text to Image Generator (MERN + ClipDrop API)
🚀 Generate Stunning AI Images Instantly

MagicLens AI is a Full-Stack Text to Image Generator Website built with MERN Stack integrated with ClipDrop AI API.
Users can register, log in, generate images using prompts, and manage credits (without payment gateway).

🌟 Features

✔️ Full-Stack MERN project
✔️ Login / Signup authentication with JWT
✔️ AI Image generation using ClipDrop API
✔️ User credits system (credits reduce per generation)
✔️ View, download, and regenerate images
✔️ Responsive UI (React + Tailwind UI)
✔️ Backend secured with environment variables
✔️ MongoDB database connection


🛠️ Tech Stack
Area	Technology
Frontend	React.js, Tailwind CSS, Axios
Backend	Node.js, Express.js
Database	MongoDB + Mongoose
Authentication	JWT + Bcrypt
AI API	ClipDrop Text-to-Image
Tools	Vite, Postman, Git, GitHub


MagicLens-AI/
│── client/        # React Frontend
│── server/        # Node/Express Backend
│── .env           # API keys (not shared publicly)
│── package.json
│── README.md




MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLIPDROP_API=your_clipdrop_api_key
PORT=4000

git clone https://github.com/YOUR_USERNAME/MagicLens-AI.git
cd MagicLens-AI

cd client
npm install
npm run dev

cd server
npm install
npm start


🔮 Future Updates

🚀 In upcoming versions of MagicLens AI, we will integrate Razorpay Payment Gateway so users can:

Buy credits securely using UPI/Card/NetBanking 💳

Upgrade to premium credit packs

View transaction history

Auto credit recharge after payment

📌 Planned modules:
| Feature                            | Status        |
| ---------------------------------- | ------------- |
| Razorpay Payment                   | ⏳ Coming Soon |
| Credit Purchase Page               | ⏳ Coming Soon |
| Transaction History Model          | ⏳ Coming Soon |
| Premium Plans (Basic/Advanced/Pro) | ⏳ Coming Soon |
