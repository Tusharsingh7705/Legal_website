<h1 align="center">⚖️ AdvocateHub</h1>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge" alt="License: MIT">
  </a>
  <a href="https://reactjs.org/">
    <img src="https://img.shields.io/badge/React-18+-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React">
  </a>
  <a href="https://www.djangoproject.com/">
    <img src="https://img.shields.io/badge/Django-4.2+-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django">
  </a>
</p>

<p align="center">
  <strong>Bridging the gap between clients and legal professionals through a secure, intuitive platform.</strong>
</p>

<div align="center">
  <img src="https://img.shields.io/badge/Real--Time%20Chat-Enabled-brightgreen" alt="Real-time Chat">
  <img src="https://img.shields.io/badge/Video%20Consultation-Available-blue" alt="Video Consultation">
  <img src="https://img.shields.io/badge/Secure%20Payments-Integrated-success" alt="Secure Payments">
</div>

---

## ✨ Features

<div align="center">
  <table>
    <tr>
      <td width="50%">
        <h3>👥 For Clients</h3>
        <ul>
          <li>🔍 Find & connect with verified legal experts</li>
          <li>📅 Book consultations with ease</li>
          <li>📁 Secure document sharing</li>
          <li>💬 Real-time chat support</li>
          <li>📱 Mobile-responsive interface</li>
        </ul>
      </td>
      <td width="50%">
        <h3>⚖️ For Legal Professionals</h3>
        <ul>
          <li>📝 Profile management with verification</li>
          <li>📅 Calendar & appointment scheduling</li>
          <li>📊 Case management tools</li>
          <li>💼 Document management system</li>
          <li>💳 Secure payment processing</li>
        </ul>
      </td>
    </tr>
  </table>
</div>

## 🛠 Tech Stack

### Frontend
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white" alt="Axios">
</p>

### Backend
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white" alt="Django">
  <img src="https://img.shields.io/badge/Django_REST-ff1709?style=flat&logo=django&logoColor=white" alt="Django REST">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL">
</p>

## 🚀 Quick Start

### Prerequisites
- Node.js 16+
- Python 3.10+
- PostgreSQL
- Git

### Backend Setup
```bash
# Clone the repository
git clone [https://github.com/Tusharsingh7705/Legal_website.git](https://github.com/Tusharsingh7705/Legal_website.git)
cd Legal_website/backend

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Run migrations
python manage.py migrate

# Start development server
python manage.py runserver