## LinkUp 🌐

LinkUp is a full-stack communication platform that enables users to connect with language learners around the world through real-time chat and video calls. Instead of random matching, users can send friend requests to learners of any language and start conversations once the request is accepted.
A real-time communication platform featuring text messaging and video calling, designed to match users based on their preferred languages for effective conversational practice

This project was built as a learning-focused full-stack application to explore modern real-time communication systems and solve real-world communication challenges.

---

Problem Statement:

Language learners often struggle to find reliable, real-time speaking partners.  
Most platforms either rely on random matching or lack seamless communication features.

LinkUp solves this by:
- Allowing users to discover language learners
- Sending and accepting friend requests
- Enabling trusted one-to-one communication via chat and video calls


## Key Features

- Send and receive friend requests  
- One-to-one real-time chat using **Stream Chat**  
- One-to-one video calling using **Stream Video**  
- Real-time online / offline presence  
- User profiles with language learning information  
- Secure backend token generation for Stream APIs  
- Scalable architecture using modern APIs  

---

## Tech Stack

- Frontend: React.js  
- Backend: Node.js + Express.js  
- Real-time Chat: Stream Chat SDK  
- Video Calling: Stream Video SDK  
- Database: MongoDB  
- Authentication: Stream user tokens (JWT-based token flow)  
- Deployment: Render  

---
## Running the Project Locally

# Clone the repository
git clone https://github.com/AayyusH11/LinkUp-Ayush.git
cd LinkUp-Ayush

# Required environment variables (.env)
STREAM_API_KEY=
STREAM_API_SECRET=
MONGO_URI=
JWT_SECRET_KEY=
NODE_ENV=
VITE_STREAM_API_KEY=


# Backend setup
cd backend
npm install
npm start


# Frontend setup (new terminal)
cd frontend
npm install
npm start






