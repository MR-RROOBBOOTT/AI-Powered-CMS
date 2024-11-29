# AI-Powered-CMS
An AI-powered content management system using Django and OpenAI GPT models. Created by Ravi Teja for a cloud computing project.
# AI-Powered CMS: Content Management with AI Integration

Author: Ravi Teja Koneru 
Project Type: Cloud Computing Project (Django-Based)  
Status: Active  

## Project Description

AI-Powered CMS is an innovative content management system built with Django and enhanced with OpenAI's GPT models. 
This project leverages cutting-edge AI to help users create, manage, and optimize content efficiently. It includes 
modern features such as AI-generated content creation, full-text search, and REST APIs, making it ideal for individuals 
and organizations managing large-scale content needs.

---

## Features
- AI-Powered Content Generation: Automatically generate high-quality blog posts, product descriptions, and more.
- REST API Integration: Seamlessly interact with the system via APIs.
- Full-Text Search: Search for content by title, keywords, or other metadata.
- Responsive UI: Modern, user-friendly design with Bootstrap integration.
- Secure and Optimized:** Enhanced with CSRF protection, input sanitization, and caching.

---

## Tech Stack
- Backend: Django 5.1, Python 3.12
- AI Integration: OpenAI GPT models
- Database: PostgreSQL
- Caching: Redis
- Deployment: Docker, GitHub Actions, Heroku

---

## Setup Instructions

### Prerequisites
- Python 3.12 or later
- PostgreSQL
- Docker (optional, for containerized deployment)

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/<your-username>/AI-Powered-CMS.git
    cd AI-Powered-CMS
    ```

2. Set up a virtual environment and install dependencies:
    ```bash
    python3 -m venv env
    source env/bin/activate
    pip install -r requirements.txt
    ```

3. Update the database configuration in `settings.py`:
    ```python
    DATABASES = {
        'default': {
            'ENGINE': 'django.db.backends.postgresql',
            'NAME': 'your_db_name',
            'USER': 'your_user',
            'PASSWORD': 'your_password',
            'HOST': 'localhost',
            'PORT': '5432',
        }
    }
    ```

4. Run migrations and start the server:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver
    ```

5. Access the app in your browser:
    - URL: `http://127.0.0.1:8000/`

---

## Deployment
- **Local Deployment:** Follow the setup instructions.
- **Dockerized Deployment:**
    ```bash
    docker-compose up --build
    ```
- **CI/CD Pipeline:** Automated with GitHub Actions for testing and deployment.

---

## Contribution Guidelines
1. Fork the repository and clone your fork locally.
2. Create a new branch for your feature or bug fix:
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes and push to your fork:
    ```bash
    git push origin feature-name
    ```
4. Submit a pull request describing your changes.

---

## License
This project is licensed under the Apache.

---

## Upcoming Features
- AI-powered suggestions for SEO optimization.
- Integration with popular content platforms (WordPress, Medium).
- Multi-user support with role-based access control.

---

## Contact
For any inquiries, feel free to reach out via GitHub or email at raviteja.koneru@uofsa.edu.

---

