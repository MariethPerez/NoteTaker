# NoteTaker - A Modern Note-Taking Web Application

NoteTaker is a simple yet powerful web application for managing different types of notes. It features a clean, modern interface and supports three types of notes: long notes, short notes, and sticky notes.

## Features

- User authentication (login/register)
- Three types of notes:
  - Long notes: For detailed content
  - Short notes: For quick reminders
  - Sticky notes: For important highlights
- Responsive design that works on all devices
- Clean and intuitive user interface
- Secure password storage
- SQLite database for data persistence

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd notetaker
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the root directory and add your secret key:
```
SECRET_KEY=your-secret-key-here
```

5. Run the application:
```bash
python app.py
```

The application will be available at `http://localhost:5000`

## Usage

1. Register a new account or login with existing credentials
2. Create new notes by clicking the "New Note" button
3. Choose the appropriate note type for your content
4. Edit or delete notes as needed
5. All notes are automatically saved and organized by type

## Security Features

- Password hashing using bcrypt
- SQL injection prevention through SQLAlchemy
- CSRF protection
- Secure session management

## Technologies Used

- Python
- Flask
- SQLAlchemy
- SQLite
- Bootstrap 5
- JavaScript (ES6)

## Contributing

Feel free to submit issues and enhancement requests! 