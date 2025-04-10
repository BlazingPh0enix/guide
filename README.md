# Interview Preparation Chatbot

A SaaS application that helps job seekers prepare for interviews by simulating interview scenarios using OpenAI's language models and analyzing their resumes.

## Features

- **Resume Analysis**: Upload your resume to get personalized interview questions based on your experience and skills
- **Mock Interviews**: Participate in text or voice-based simulated interviews for specific job roles
- **Realistic Feedback**: Receive constructive feedback on your responses
- **Voice Interaction**: Practice speaking with voice-based interviews that simulate real conversations
- **Customizable Experience**: Focus on specific skills, job roles, or interview types
- **Progress Tracking**: Monitor your improvement over time with detailed analytics

## Tech Stack

### Frontend
- React.js with Tailwind CSS
- Redux Toolkit for state management
- Framer Motion for animations
- WebRTC for real-time voice communication

### Backend
- Python with FastAPI
- PostgreSQL for data storage
- OpenAI API for interview simulation
- Speech-to-Text and Text-to-Speech services

### Deployment
- Frontend: Vercel/Netlify
- Backend: Render
- Database: ElephantSQL
- CI/CD: GitHub Actions

## Getting Started

### Prerequisites
- Node.js v16+
- Python 3.9+
- PostgreSQL
- OpenAI API key

### Installation

#### Backend Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/interview-prep-chatbot.git
cd interview-prep-chatbot/backend

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env with your OpenAI API key and database credentials

# Run migrations
alembic upgrade head

# Start the backend server
uvicorn app.main:app --reload
```

#### Frontend Setup
```bash
# Navigate to the frontend directory
cd ../frontend

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your backend API URL

# Start the development server
npm run dev
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Your Name - your.email@example.com

Project Link: [https://github.com/yourusername/interview-prep-chatbot](https://github.com/yourusername/interview-prep-chatbot)
