
# WebX_Security 🔐
 
**WebX_Security** is a Django-based project focused on strengthening user authentication through Two-Factor Authentication (2FA). This app demonstrates secure login practices, token-based verification, and best practices in securing Django applications.

## 🚀 Key Features

- 🔐 Two-Factor Authentication (TOTP/Twilio-based)
- 🧾 Secure token generation and backup tokens
- 🧱 Modular views and utilities for clean 2FA logic
- 🖥️ Django template integration for 2FA flows
- 🧰 Custom template tags for frontend control

## 🛠️ Tech Stack

- **Python 3**
- **Django**
- **Django-Two-Factor-Auth**
- **SQLite** (can be swapped with PostgreSQL)
- **Twilio (optional for SMS-based 2FA)**

## 🧪 Setup Instructions

```bash
git clone https://github.com/AnishPasupuleti/WebX_Security.git
cd WebX_Security
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Then visit: `http://localhost:8000/`

## 📁 Project Highlights

```
two_factor/
├── views/            # Core 2FA logic
├── utils.py          # Helper functions
├── templates/        # Token and login templates
├── templatetags/     # Custom tags for frontend logic
├── urls.py           # Routing for 2FA
```

## 🔍 What You’ll Learn

- Implementing secure 2FA in Django
- Token generation and validation workflows
- Creating secure, modular, and reusable views

## 📌 Future Scope

- Integrate with social logins (Google/GitHub)
- Rate limiting and brute-force detection
- Session-based device trust and history

## 📜 License

MIT License. Feel free to modify and use with credit.
