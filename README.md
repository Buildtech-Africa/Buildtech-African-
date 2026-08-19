BUILDTECH AFRICA WORKABLE MVP

WHAT IT DOES:
- Public homepage
- User registration
- Password hashing
- Login/logout
- Individual user dashboard
- Construction cost calculator
- Saved estimates in SQLite database
- Health endpoint

RUN ON A COMPUTER:
1. Install Python 3.11 or newer.
2. Open a terminal in this folder.
3. Run: python -m venv .venv
4. Activate the environment.
5. Run: pip install -r requirements.txt
6. Set a strong SECRET_KEY.
7. Run: python app.py
8. Open: http://127.0.0.1:5000

PUBLIC WEBSITE:
This package is the application source code. To let customers use it on the internet,
deploy it to a server/cloud host. A domain name must then point to that server.

IMPORTANT:
This is an MVP, not a finished regulated production platform. Before accepting real
payments or sensitive information, add HTTPS, production database, backups, CSRF/rate
limiting, email/phone verification, password reset, monitoring, privacy/terms and
appropriate Kenyan legal/data-protection review.

NEXT FEATURES:
- Professional/supplier registration
- Admin verification
- PostgreSQL
- BuildTech AI
- M-Pesa/Daraja
- Materials marketplace
- Notifications
- Project management
- Mobile app
