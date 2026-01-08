# AdvocateHub

A legal consultation platform that connects clients with qualified advocates.

## Features

- **Role-based Registration**: Separate registration for lawyers and clients
- **Booking System**: Slot management and appointment scheduling
- **Real-time Chat**: In-app communication after confirmed bookings
- **Admin Approval**: Secure verification for legal professionals

## Quick Start

### Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

## Access URLs
- **Frontend**: http://localhost:5173
- **Backend API**: http://127.0.0.1:8000
- **Admin Panel**: http://127.0.0.1:8000/admin

## Tech Stack
- **Frontend**: React.js, Vite, Tailwind CSS
- **Backend**: Django, Django REST Framework
- **Database**: SQLite (development) / PostgreSQL (production)

## Project Structure
```
AdvocateHub-main/
├── backend/          # Django application
├── frontend/         # React application
└── README.md         # This file
```

## Contributing
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

**Note**: This platform facilitates legal consultations but does not provide legal advice directly.
