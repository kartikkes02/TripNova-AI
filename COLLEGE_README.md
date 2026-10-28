# AI TRIP PLANNER

> **Minor Project Report & Documentation**  
> **Course:** Bachelor Minor Project  
> **Project Title:** AI Trip Planner (TripNova)  
> **Author:** Binod Kapadi  

---

## 1. Abstract of Project

Traditional travel planning is often a fragmented, tedious, and time-consuming process. Travelers spend hours navigating multiple platforms to search for destinations, calculate budgets, estimate daily schedules, evaluate local weather conditions, and discover popular attractions. This manual approach frequently leads to inefficient itineraries, budget overruns, and decision fatigue due to information overload.

To address these challenges, the **AI Trip Planner** (TripNova) is proposed as an intelligent, full-stack web application designed to automate and streamline the end-to-end travel planning experience. Utilizing state-of-the-art Artificial Intelligence (Google Gemini and Groq LLMs), the system processes user parameters—such as target destination, travel duration, budget constraints, and personal interests—to instantly generate comprehensive, personalized daily travel itineraries.

The application features a modern React and Vite frontend integrated with a Python FastAPI RESTful backend and MongoDB database. To ensure real-time accuracy, the platform incorporates external APIs including OpenWeather API for dynamic weather forecasting and SerpAPI/Tavily for live location recommendations. Additionally, an interactive AI travel assistant chatbot offers real-time recommendations, while secure multi-provider OAuth (Google, GitHub, LinkedIn) and OTP email verification protect user data. Users can save, modify, share, and receive detailed itineraries directly via email notification services.

The key objectives of this minor project are to minimize travel preparation effort, eliminate manual itinerary synthesis, provide data-driven destination insights, and offer a seamless, responsive user interface. The expected outcome is a fully deployed, high-performance web platform that reduces itinerary generation time from hours to seconds, delivering personalized, actionable, and reliable travel plans to enhance user experience. *(Word count: ~245 words)*

---

## 2. Project Breakdown & Objectives

### Problem Being Addressed
- **Information Fragmentation:** Planning a trip requires visiting multiple websites for weather, attractions, maps, and schedules.
- **Time Consumption:** Manually creating a balanced travel schedule takes several hours or days.
- **Lack of Personalization:** Generic travel guides do not accommodate individual budgets, constraints, or unique preferences.

### Proposed Solution
- An integrated AI-powered web platform that gathers user parameters and dynamically creates day-by-day itineraries.
- AI travel chatbot for live Q&A and destination queries.
- Integration of dynamic weather forecasts and Google Places search fallback.
- Direct email export and link sharing for itineraries.

### Key Objectives
1. **Automated Itinerary Generation:** Leverage LLM models (Gemini / Groq) to curate optimized travel plans instantly.
2. **Real-time Data Integration:** Connect OpenWeather API and SerpAPI for accurate environmental and location updates.
3. **Secure Authentication:** Implement OAuth 2.0 (Google, GitHub, LinkedIn) alongside OTP-based email verification.
4. **Responsive UI/UX:** Build a modern, interactive single-page application using React and Vite.
5. **Full-Stack Architecture:** Structure scalable FastAPI backend microservices with MongoDB database persistence.

### Expected Outcome
- A functional, end-to-end deployed AI travel planning system accessible via web browsers.
- Reduction of travel itinerary creation time from hours to seconds.
- High user satisfaction through tailored travel recommendations, live assistance, and email sharing.

---

## 3. Technology Stack

### Frontend
- **Framework / Library:** React.js (built with Vite)
- **Routing & State:** React Router DOM, Axios
- **Markup & Styling:** HTML5, CSS3, JavaScript (ES6+)

### Backend
- **Language / Framework:** Python 3.x, FastAPI, Uvicorn
- **Database:** MongoDB (MongoDB Atlas / PyMongo / Motor)
- **AI Models:** Google Gemini API, Groq LLM API
- **Third-Party APIs:** OpenWeather API, SerpAPI, Tavily, Serper API
- **Services:** SMTP / Brevo API (Email Notifications & OTP)

### Deployment & Hosting
- **Frontend Hosting:** Netlify / Vercel
- **Backend Hosting:** Render

---

## 4. Key Features

- 🤖 **AI-Powered Itinerary Generation:** Tailored day-by-day travel schedules based on budget, length, and interests.
- 🌤️ **Live Weather Integration:** Real-time destination weather forecasting.
- 💬 **AI Travel Assistant:** Interactive chatbot for travel tips, recommendations, and local insights.
- 🔐 **Multi-Provider Authentication:** Google, GitHub, LinkedIn OAuth, and OTP Email Verification.
- 📧 **Itinerary Export:** Direct email dispatch of travel plans to users.
- 📱 **Responsive UI:** Dynamic navigation and modern design built for mobile and desktop devices.

---

## 5. Deployment Links

- **Frontend Deployment (Netlify):** [https://tripwithbinod.netlify.app](https://tripwithbinod.netlify.app)
- **Frontend Deployment (Vercel):** [https://tripwithbinod.vercel.app](https://tripwithbinod.vercel.app)
- **Backend Deployment (Render):** [https://tripadvisor-binodkapadi.onrender.com](https://tripadvisor-binodkapadi.onrender.com)
