# Flask Web Application

This is a Flask-based web application that provides a modern and interactive user interface.

## Project Structure

- `main.py` - Main application file
- `forms.py` - Form definitions
- `templates/` - HTML templates
- `static/` - Static files (CSS, JavaScript, images)
- `requirements.txt` - Python dependencies
- `.env` - Environment variables (create this file)

## Environment Variables

The application requires the following environment variables to be set. Create a `.env` file in the project root with the following content:

```
# Flask Configuration
FLASK_KEY=your_secret_key_here

# Database Configuration
DB_URI=sqlite:///posts.db

# Email Configuration (uncomment if using email functionality)
# EMAIL_KEY=your_email@gmail.com
# PASSWORD_KEY=your_app_password
```

Make sure to:
1. Replace `your_secret_key_here` with a secure random string
2. Add `.env` to your `.gitignore` file to keep sensitive information secure
3. If using email functionality, uncomment and fill in the email configuration

## Setup Instructions

1. Create a virtual environment:
```bash
python -m venv env
```

2. Activate the virtual environment:
- Windows:
```bash
env\Scripts\activate
```
- Unix/MacOS:
```bash
source env/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create and configure the `.env` file (see Environment Variables section above)

5. Run the application:
```bash
python main.py
```

## Features

- Modern web interface
- Form handling
- Static file serving
- Template rendering
- Secure configuration using environment variables

## Requirements

See `requirements.txt` for a complete list of dependencies.

## License

This project is open source and available under the MIT License. 