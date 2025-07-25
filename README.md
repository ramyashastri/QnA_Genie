Q&A Genie is an intelligent question management system that leverages AI to streamline Q&A sessions in conferences and presentations. It helps speakers manage audience questions efficiently by filtering out redundant questions and prioritizing relevant ones.

## Features

- **AI-Powered Question Analysis**
  - Automatic relevance checking
  - Redundancy detection
  - Question similarity grouping
  - Smart question prioritization

- **User Management**
  - Role-based authentication (Admin/Speaker/Audience)
  - Secure JWT-based authentication
  - User-specific dashboards

- **Real-time Question Management**
  - Live question submission
  - Topic-based categorization
  - Dynamic question filtering
  - Interactive speaker dashboard

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Axios for API calls
- JWT for authentication

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication

### AI Model
- PyTorch
- Transformers
- Sentence-Transformers
- Streamlit
- Scikit-learn

## Prerequisites

- Node.js (v14 or higher)
- Python 3.8+
- MongoDB (v4.4 or higher)
- npm or yarn
- Git

## Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/qa-genie.git
cd qa-genie
```

2. **Install Frontend Dependencies**
```bash
cd frontend
npm install
```

3. **Install Backend Dependencies**
```bash
cd ../backend
npm install
```

4. **Install AI Model Dependencies**
```bash
cd ../AI\ model
pip install -r requirements.txt
```

5. **Environment Setup**

Create `.env` files in both backend and frontend directories:

Backend `.env`:
```env
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=5001
```

Frontend `.env`:
```env
REACT_APP_API_URL=http://localhost:5001/api
```

## Running the Application

1. **Start the Backend Server**
```bash
cd backend
npm run dev
```

2. **Start the Frontend Development Server**
```bash
cd frontend
npm start
```

3. **Start the AI Model Server**
```bash
cd AI\ model
python app.py
```





