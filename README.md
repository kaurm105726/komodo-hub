# Komodo Hub - Digital Platform for Community-Supported Animal Conservation

## Overview
Komodo Hub is a Flask-based web application designed to support animal conservation efforts through community engagement. The platform provides role-based access for teachers, students, and community members to participate in wildlife conservation activities.

## Features

### Core Functionality
- Multi-role authentication system
- Species database and sighting reports
- Educational resource management
- Interactive community forum
- Progress tracking and analytics

### Role-Specific Features

#### Teacher Dashboard
- Content management
- Student progress tracking
- Sighting verification
- Analytics dashboard

#### Student Interface
- Interactive learning materials
- Species identification
- Progress tracking
- Sighting reports

#### Community Member Access
- Conservation program participation
- Species sighting reports
- Resource library access
- Forum engagement

## Quick Start

### Prerequisites
- Python 3.11+
- PostgreSQL database
- Required Python packages (see pyproject.toml)

### Installation
1. Clone the repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Set up environment variables:
```bash
DATABASE_URL=postgresql://...
SESSION_SECRET=your_secret_key
```

### Running the Application
```bash
python main.py
```
The application will be available at `http://localhost:5000`

## Technical Stack

### Backend
- Flask web framework
- PostgreSQL database
- SQLAlchemy ORM
- Flask-Login authentication

### Frontend
- Bootstrap 5
- Custom CSS/JS
- Chart.js
- Leaflet.js maps

## Documentation
For detailed documentation, including:
- Complete feature list
- API endpoints
- Database schema
- Development guidelines

Please refer to [MANUAL.md](MANUAL.md)

## Contributing
1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## License
This project is proprietary and confidential.

## Support
For support and inquiries, please contact the development team.