# Book Reading Habit Analyzer

A web-based application that helps users track, monitor, and analyze their reading habits. Built with Django, this application provides detailed insights into reading patterns, goal tracking, and reading session management.

## Features

- **User Management**
  - Secure registration and login
  - Customizable user profiles
  - Privacy settings for reading activity

- **Book Library**
  - Add, update, and delete books
  - Track reading status (Currently Reading, Completed, Abandoned)
  - Book cover image upload
  - ISBN lookup

- **Reading Goals**
  - Set daily, weekly, monthly, or yearly targets
  - Track progress towards goals
  - Visual progress indicators

- **Reading Tracker**
  - Log reading sessions with pages read
  - Track reading time
  - Add notes and reflections

- **Analytics Dashboard**
  - Total books and pages read
  - Reading progress charts
  - Genre distribution analysis
  - Reading streaks and patterns

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd book-analyzer
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply database migrations:
   ```bash
   python manage.py migrate
   ```

5. Create a superuser (admin):
   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```bash
   python manage.py runserver
   ```

7. Visit http://127.0.0.1:8000 in your web browser

## Environment Setup

Create a `.env` file in the project root with the following variables:
```
DEBUG=True
SECRET_KEY=your-secret-key
DATABASE_URL=sqlite:///db.sqlite3
```

## Technology Stack

- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (default) / PostgreSQL
- **Charts**: Chart.js
- **Styling**: Bootstrap 5
- **Forms**: django-crispy-forms

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. #   b a p p  
 "# final_bookapp" 
"# final_bookapp" 
