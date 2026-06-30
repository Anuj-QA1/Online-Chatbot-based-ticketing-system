# Chatbot-Based Ticketing System

> AI-powered chatbot-based ticketing system for automating museum ticket booking, customer support, and visitor management.

## Overview
This project was proposed for Smart India Hackathon 2024. It uses AI/NLP to automate ticket booking, answer visitor queries, manage bookings, and improve customer experience.

## Features
- AI chatbot
- Ticket booking
- Multilingual support
- Secure payment integration
- Booking confirmation
- Admin dashboard
- Analytics
- Conversation history

## Tech Stack
**Frontend:** React, HTML, CSS, JavaScript

**Backend:** Node.js, Express.js, Python

**Database:** MySQL, MongoDB

**AI/NLP:** spaCy, TensorFlow, Hugging Face

**DevOps:** Docker, GitHub Actions

## Architecture
```text
User
 │
 ▼
Frontend
 │
 ▼
REST API
 │
 ├── Chatbot Engine
 ├── Booking Service
 ├── Payment Service
 └── Database
```

## REST APIs

| Method | Endpoint | Description |
|---|---|---|
| POST | /api/auth/login | Login |
| POST | /api/auth/register | Register |
| POST | /api/chatbot/message | Chat |
| POST | /api/tickets/book | Book Ticket |
| GET | /api/tickets | Get Tickets |

## Security
- JWT Authentication
- Password Hashing
- HTTPS
- RBAC
- Input Validation

## Testing
- Unit Testing
- Integration Testing
- API Testing
- Manual Testing
- Performance Testing

## Future Scope
- Voice chatbot
- QR ticket validation
- Mobile app
- AI recommendations

## License
MIT
