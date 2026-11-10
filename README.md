
# 🌊 SETU – AI-Powered Disaster Management & Rescue Coordination Platform

SETU is an AI-powered disaster management platform designed to connect citizens, rescue teams, NGOs, shelters, and authorities through a unified system.

> 🌉 **Connecting People. Coordinating Rescue. Saving Lives.**

## 📌 Problem Statement

During floods and other disasters, victims struggle to communicate their exact location and receive updates about their emergency requests. Rescue teams, NGOs, shelters, and authorities often lack real-time information and coordination.

Existing platforms like SACHET provide early disaster warnings, but coordinating the actual rescue process remains a major challenge.

**⚠️ Warnings exist. Coordination doesn't.**

## 💡 Our Solution

SETU bridges this coordination gap through an integrated disaster management platform covering prediction, preparation, emergency response, and recovery.

Key capabilities:

- 🌧️ AI-powered flood risk prediction and early warning alerts.
- 🆘 SOS reporting with real-time victim location sharing.
- ✅ SOS verification and rescue status tracking.
- 🚨 Rescue team coordination.
- 🗺️ Nearby shelter discovery and safe navigation.
- 📦 Smart shelter and resource management.
- 📊 Live disaster monitoring dashboard.

## ⭐ USP – Real-Time Rescue Tracking

Inspired by the live-tracking experience of Uber and Ola, SETU brings transparency to disaster rescue operations.

1. 📍 Victims press a single SOS button.
2. 📡 Their real-time location is shared with the response system.
3. ✅ SOS requests are received and verified.
4. 🚑 Rescue teams coordinate using the shared location.
5. 🔔 Victims can track available rescue-status updates.

Unlike traditional emergency reporting systems, SETU focuses on ensuring victims know that their SOS has been received and that the rescue process has started.

> ❤️ **Not just sending an SOS, but knowing that help is on its way!**

## 🚀 Key Features

### 🌧️ 1. Flood Risk Prediction
AI-supported disaster risk assessment and early warning alerts.

### 🆘 2. SOS & Live Location Tracking
Share emergency requests and real-time location with rescue teams.

### ✅ 3. SOS Verification Engine
Verify incoming emergency requests and improve response coordination.

### 🗺️ 4. Safe Navigation
Identify nearby shelters and safer routes using mapping services.

### 🚨 5. Rescue Coordination
Connect citizens, rescue teams, NGOs, and government authorities.

### 📦 6. Resource Allocation
Improve coordination and distribution of essential relief supplies.

### 📊 7. Live Dashboard
Monitor disaster situations and rescue operations through a unified interface.

## ⚙️ How It Works

1. 🔍 Risk Detection – Identify potential disaster risks.
2. 🤖 AI Risk Prediction – Analyze available information.
3. 📡 Ground Data Integration – Combine predictions with real-time information.
4. 🔔 Early Warnings – Notify relevant users and stakeholders.
5. 🆘 SOS Reporting – Victims submit emergency requests.
6. ✅ SOS Verification – Verify requests and coordinate response.
7. 🚑 Rescue & Recovery – Support rescue teams, shelters, and relief operations.

## 📈 Expected Impact

- ⚡ Faster emergency response through real-time coordination.
- 🤝 Better communication between victims and rescue teams.
- 📦 Improved resource allocation.
- ♻️ Reduced duplication and wastage of relief supplies.
- 🛡️ Better disaster preparedness and public safety.

Our project presentation identifies aspirational targets of up to 70% faster SOS verification and rescue coordination and 30% reduction in resource wastage and duplication. These targets require real-world validation.

## 🔮 Future Scope

- 🚁 Drone-based disaster assessment.
- 📡 IoT sensor integration.
- 🌪️ Multi-disaster support, including cyclones.
- 👁️ Computer vision-based damage assessment.
- 🤖 AI-powered decision support.
- 📊 Disaster impact forecasting.
- 🇮🇳 Expansion across disaster-prone districts and states.
- 🌍 Nationwide disaster intelligence network.

## 🛠️ Technology Stack

| Layer | Technologies |
|---|---|
| 🎨 Frontend | React.js, Tailwind CSS, Axios |
| ⚙️ Backend | Python, FastAPI |
| 🗄️ Database | MongoDB |
| 🔌 Database Access | Motor, PyMongo |
| 🤖 AI Integration | OpenAI API |
| 🗺️ Maps | Mapbox, OpenStreetMap, OpenTopoMap |
| 📍 Geolocation | Browser Geolocation API |
| 🧮 Algorithms | Dijkstra's Algorithm, A*, Point-in-Polygon |

## 🏗️ System Architecture

- 🎨 Frontend: React.js application for user interaction.
- ⚙️ Backend: FastAPI services for application logic and APIs.
- 🗄️ Database: MongoDB for application data.
- 🤖 AI Services: OpenAI API integration.
- 🗺️ Mapping Services: Mapbox and OpenStreetMap.
- 🚦 Routing Engine: Dijkstra's Algorithm and A*.
- 📍 Geospatial Processing: Point-in-Polygon algorithm.

## 💻 Getting Started

### 📋 Prerequisites

- Node.js and npm
- Python 3.10+
- MongoDB
- Git
- OpenAI API key (if using AI features)
- Mapbox access token (if using Mapbox services)

### 1️⃣ Clone Repository

    git clone YOUR_GITHUB_REPOSITORY_URL
    cd YOUR_REPOSITORY_FOLDER

### 2️⃣ Backend Setup

    cd backend
    python -m venv .venv

**Windows:**

    .venv\Scripts\Activate.ps1

**Linux/macOS:**

    source .venv/bin/activate

**Install dependencies:**

    pip install -r requirements.txt

**Start backend (adjust the entry point to match your project):**

    uvicorn main:app --reload

**API documentation:**

    http://127.0.0.1:8000/docs

### 3️⃣ Frontend Setup

    cd frontend
    npm install
    npm run dev

Open the local development URL displayed in the terminal.

## 🔐 Environment Configuration

Configure the required environment variables according to your source code.

Typical configuration requirements:

- 🗄️ MongoDB connection string.
- 🤖 OpenAI API key.
- 🗺️ Mapbox access token.
- 🔗 Frontend API base URL.

⚠️ Never commit API keys, passwords, or other secrets to GitHub.

## 📁 Project Structure

    SETU/
    ├── frontend/
    │   ├── src/
    │   ├── public/
    │   └── package.json
    ├── backend/
    │   ├── main.py
    │   ├── requirements.txt
    │   └── app/
    ├── README.md
    └── .gitignore

📝 Note: Adjust this example structure to match the actual repository.

## 🎯 Target Users

- 👥 Citizens affected by disasters.
- 🏛️ Disaster response authorities.
- 🚑 Rescue teams.
- 🤝 NGOs and relief organizations.
- 🏠 Emergency shelters.
- 🏢 Government departments and local administration.

## ⚠️ Limitations & Responsible Use

- Location accuracy depends on GPS permissions and network connectivity.
- AI predictions require reliable data and validation.
- Rescue operations depend on authorized response stakeholders.
- SETU is a coordination platform, not a replacement for official emergency services.
- Real-world deployment requires security testing, privacy safeguards, and partnerships with disaster response agencies.

## 🤝 Contributing

Contributions and suggestions are welcome.

1. 🍴 Fork the repository.
2. 🌿 Create a new feature branch.
3. 💻 Make your changes.
4. 🧪 Test your implementation.
5. 📩 Submit a pull request.

## 🏆 Project Information

- **Project:** SETU
- **Team:** PRIME
- **Competition:** SBI Youth Ideathon 2026
- **Domain:** Artificial Intelligence | Disaster Management | Emergency Response

---

<p align="center">
  🌊 <b>SETU – Connecting People. Coordinating Rescue. Saving Lives.</b> ❤️
</p>
