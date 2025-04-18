# BailReckoner


A legal tech web application designed to streamline bail eligibility assessment in India's judicial system.

## Features

- User Authentication & Role-based Access
- Bail Assessment Interface
- Legal Resource Center
- Analytics Dashboard
- Document Management with Blockchain Integration
- Multilingual Support

## Tech Stack

- Backend: Django (primary) with Flask microservices
- Frontend: HTML, TailwindCSS
- Database: PostgreSQL
- Blockchain: Hyperledger Fabric
- AI/ML: Custom models for eligibility assessment
- Authentication: Aadhaar Integration

## Setup Instructions

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
```bash
cp .env.example .env
# Edit .env with your configuration
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Start the development server:
```bash
python manage.py runserver
```

## Project Structure

```
bail_reckoner/
├── manage.py
├── requirements.txt
├── .env.example
├── bail_reckoner/          # Main Django project
├── authentication/         # User auth app
├── assessment/            # Bail assessment app
├── resources/            # Legal resources app
├── analytics/           # Analytics dashboard app
├── blockchain/         # Blockchain integration
├── api/               # API endpoints
└── templates/        # HTML templates
```

## Contributing

Please read CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Security

For security concerns, please email security@bailreckoner.org 

