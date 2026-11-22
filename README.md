# Online Bus Pass Application System

A web-based application developed using Python Flask that simplifies the process of applying for, managing, renewing, and verifying bus passes. It provides a user-friendly interface for passengers and an administrative interface for managing applications.

## Features

- **User Registration and Login:** Users can create accounts and securely authenticate themselves.
- **Bus Pass Application:** Users can apply for bus passes through the online application.
- **Application Management:** Administrators can view and manage submitted applications.
- **Application Verification:** Admins can verify applications and manage approval status.
- **Payment Management:** Payment functionality for bus pass applications.
- **Digital Bus Pass:** Generation and management of bus passes.
- **Pass Renewal:** Users can renew their bus passes.
- **Password Security:** Passwords are secured using hashing.
- **Database Management:** SQLite database for storing application and user information.

## Technologies Used

| Technology | Purpose                                 |
|------------|-----------------------------------------|
| Python     | Backend programming                     |
| Flask      | Web framework                           |
| SQLite     | Database                                |
| HTML5      | Web page structure                      |
| CSS3       | Styling                                 |
| JavaScript | Frontend functionality                  |
| Jinja2     | Template rendering                      |
| Werkzeug   | Password hashing and security utilities |
| Git& GitHub| Version control                         |

## Project Structure

```text
OnlineBus-Pass-System/
│
├── static/              # CSS, JavaScript and images
├── templates/            # HTML templates
├── .github/              # GitHub configuration
├── app.py                # Main Flask application
├── requirements.txt       # Python dependencies
├── .gitignore            # Files excluded from Git
└── README.md              # Project documentation
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the project directory

```bash
cd OnlineBus-Pass-System
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
python app.py
```

### 7. Open the application

Visit the following URL in your browser:

http://127.0.0.1:5000/

## Database

The application uses SQLite for database management.

SQLite databases are used to store user registration details, application information, administrative data, and payment-related information.

The database is managed through Python's built-in `sqlite3` module.

## Security

- Password hashing using Werkzeug security utilities.
- Flask session-based authentication.
- Parameterized SQL queries for database operations.
- Sensitive database and environment files excluded from version control.

## Future Enhancements

- Online payment gateway integration.
- QR code-based digital bus pass verification.
- Email and SMS notifications.
- Responsive user interface improvements.
- Deployment to a cloud hosting platform.

## Author

Developed as a web application project using Python Flask, SQLite, HTML, CSS, and JavaScript.

## Application Screenshots

### Home Page
![Home Page](screenshots/home.png)

### User Login
![User Login](screenshots/login.png)

### User Registration
![User Registration](screenshots/registration.png)

### Admin Login
![Admin Login](screenshots/admin-login.png)

### Admin Registration
![Admin Registration](screenshots/admin-registration.png)

### Bus Pass Application
![Application Form](screenshots/application-form.png)

### Pass Renewal
![Renewal](screenshots/renewal.png)

### Contact Page
![Contact Page](screenshots/contacts.png)