# AdvocateHub

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A comprehensive legal consultation platform that bridges the gap between clients and qualified legal professionals through an intuitive and secure interface.

## 🚀 Features

- **Role-based Authentication**
  - Separate registration flows for lawyers and clients
  - Email verification for all users
  - Secure password reset functionality

- **Legal Professional Features**
  - Profile management with specialization details
  - Availability calendar
  - Case management system
  - Document sharing capabilities

- **Client Features**
  - Search and filter legal professionals
  - Book consultations
  - Secure document upload
  - Appointment history

- **Core Functionality**
  - Real-time chat with WebSocket support
  - Video consultation integration
  - Secure payment processing
  - Admin dashboard for user management

## 🛠️ Tech Stack

### Frontend
- React.js 18+ with Hooks
- Vite 4+ for fast development
- Tailwind CSS 3+ for styling
- Axios for API requests
- Socket.IO for real-time features

### Backend
- Python 3.10+
- Django 4.2+
- Django REST Framework
- Django Channels for WebSockets
- PostgreSQL (production) / SQLite (development)

## 🚀 Quick Start

### Prerequisites
- Node.js 16+
- Python 3.10+
- PostgreSQL (for production)
- Git

### Backend Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/AdvocateHub.git
   cd AdvocateHub/backend
   ```

2. **Set up virtual environment**
   ```bash
   # Windows
   python -m venv venv
   .\venv\Scripts\activate
   
   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   Create a `.env` file in the backend directory:
   ```env
   DEBUG=True
   SECRET_KEY=your-secret-key
   DATABASE_URL=sqlite:///db.sqlite3
   ALLOWED_HOSTS=localhost,127.0.0.1
   ```

5. **Run migrations**
   ```bash
   python manage.py migrate
   ```

6. **Create superuser**
   ```bash
   python manage.py createsuperuser
   ```

7. **Run the server**
   ```bash
   python manage.py runserver
   ```

### Frontend Setup

1. **Navigate to frontend directory**
   ```bash
   cd ../frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

## 🔗 Access URLs

- **Frontend**: http://localhost:5173
- **Backend API**: http://127.0.0.1:8000/api/
- **Admin Panel**: http://127.0.0.1:8000/admin
- **API Documentation**: http://127.0.0.1:8000/api/docs/

## 🏗 Project Structure

```
AdvocateHub/
├── backend/                  # Django backend
│   ├── core/                # Main app with core functionality
│   ├── website_feedback/    # User feedback system
│   ├── videosession/        # Video chat functionality
│   ├── manage.py            # Django management script
│   └── requirements.txt     # Python dependencies
│
├── frontend/                # React frontend
│   ├── public/              # Static files
│   ├── src/                 # Source code
│   │   ├── components/      # Reusable components
│   │   ├── pages/           # Page components
│   │   ├── utils/           # Utility functions
│   │   └── App.jsx          # Main App component
│   └── package.json         # Node.js dependencies
│
├── .gitignore               # Git ignore file
├── LICENSE                  # MIT License
└── README.md                # This file
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

For any inquiries, please open an issue in the repository.

---

**Note**: This platform facilitates legal consultations but does not provide legal advice directly.
