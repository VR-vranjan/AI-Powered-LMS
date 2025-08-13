# AI-Powered Learning Management System (LMS)

An advanced **AI-powered Learning Management System** built using the **MERN stack**.  
This platform enables seamless online learning with AI-driven smart search, secure authentication, integrated payments, and dedicated dashboards for students and instructors.

---

## 🚀 Features

- **🧠 AI-Powered Smart Search** – Find courses instantly with Gemini/OpenAI integration.
- **🔐 Google Authentication** – Secure login with OAuth 2.0.
- **💳 Razorpay Payment Gateway** – Smooth and secure payment processing.
- **📚 Role-Based Dashboards** – Separate views for Students and Instructors.
- **⚛️ State Management** – Redux Toolkit for scalable state handling.
- **📱 Fully Responsive UI** – Optimized for all devices.

---

## 🛠 Tech Stack

- **Frontend:** React.js, Tailwind CSS, Redux Toolkit  
- **Backend:** Node.js, Express.js, MongoDB  
- **Auth:** Google OAuth 2.0  
- **Payments:** Razorpay  
- **AI Integration:** Gemini/OpenAI API  

---

## 📦 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ai-powered-lms.git
   cd ai-powered-lms
2 **Install backend dependencies**
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

3. **Set up environment variables**
MONGO_URI=your_mongodb_connection_string
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
GEMINI_API_KEY=your_gemini_api_key

4. **Run the application**
# Run backend
cd backend
npm start

# Run frontend
cd ../frontend
npm start

