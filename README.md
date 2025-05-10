# EduNexus

EduNexus is an educational platform designed to streamline content management and delivery for educational institutions. The platform centralizes four key content types (YouTube videos, books, question sets, and doubt solving) into a unified system.

## Development Setup

1. Clone the repository
2. Create a virtual environment: `python -m venv venv`
3. Activate the virtual environment:
   - Windows: `venv\Scripts\activate`
   - macOS/Linux: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements/development.txt`
5. Create a `.env` file from the example: `cp .env.example .env`
6. Run migrations: `python manage.py migrate`
7. Create a superuser: `python manage.py createsuperuser`
8. Run the development server: `python manage.py runserver`

## Project Structure

- `apps/` - Django applications
- `config/` - Project configuration
- `api/` - API endpoints and versioning
- `templates/` - HTML templates
- `static/` - Static assets
- `media/` - User uploaded content
- `docs/` - Project documentation

## Documentation

See the `docs/` directory for more detailed documentation.