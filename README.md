# Django Learning App

A powerful learning platform built with Django that leverages AI to generate personalized quiz questions, implements spaced repetition algorithms for effective learning, and offers premium features through a paywall system.

## 🚀 Features

- **AI-Powered Question Generation**: Uses AI models to automatically create relevant quiz questions from course content
- **Course Management**: Create and organize courses with concepts, practical exercises, syllabus, and units
- **Spaced Repetition Algorithm**: Optimizes learning retention by intelligently scheduling review sessions
- **Authentication System**: Secure user registration and login flow
- **Quiz Generation**: Create quizzes from notes with questions, multiple-choice answers, and explanations
- **PDF Upload with RAG**: Upload PDFs and generate questions using Retrieval-Augmented Generation
- **Stripe Integration**: Payment processing for premium features
- **Learning Science Based**: Implementation inspired by "Make It Stick" learning principles

## 📋 Prerequisites

- Python 3.12+
- Django 5.2+
- Node.js and npm/Bun (for Tailwind CSS)
- Stripe account for payment processing

## 🛠️ Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/django-learningapp.git
cd django-learningapp
```

2. Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
npm install  # or bun install
```

4. Set up environment variables
```bash
cp .env.example .env
# Edit .env with your settings (API keys, database credentials, etc.)
```

5. Run migrations
```bash
python manage.py migrate
```

6. Start the development server
```bash
python manage.py runserver
```

7. In a separate terminal, compile Tailwind CSS
```bash
npm run watch # or bun run watch
```

<!-- ## 🔄 API Endpoints

- `/api/auth/` - Authentication endpoints
- `/api/courses/` - Course management
- `/api/quizzes/` - Quiz operations
- `/api/payments/` - Stripe payment processing

## 💳 Payment Integration

This project uses Stripe for payment processing. You'll need to:
1. Create a Stripe account
2. Add your API keys to the `.env` file
3. Configure webhook endpoints for payment events

## 🤖 AI Integration

The system uses AI models to generate questions from course content. To set up:
1. Obtain API keys for your chosen AI provider
2. Configure the keys in the `.env` file
3. Adjust generation parameters in `core/services/ai/config.py`

## 📚 Learning Algorithm

The spaced repetition system is based on proven learning science from "Make It Stick" and implements:
- Variable practice intervals
- Interleaved content review
- Active recall testing
- Difficulty-based scheduling -->

## 🚀 Deployment

Instructions for deploying to common platforms:

### Docker
```bash
docker-compose build
docker-compose up -d
```

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.