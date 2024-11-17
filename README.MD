Django Portfolio Project
This is a personal portfolio website built using Django. It showcases my skills, projects, and contact information. The project includes a contact form where visitors can send messages directly to my email.

Features
Homepage: Displays an introduction and highlights of my work.
Portfolio Section: Showcases various projects with descriptions, images, and links.
Contact Form: Allows users to send messages with their name, email, phone, subject, and message.
Responsive Design: The website is fully responsive and works on various screen sizes.
Technologies Used
Django: Web framework used to build the application.
HTML/CSS: For structuring and styling the web pages.
JavaScript: For interactive elements and form validation.
SQLite: Default database used by Django (can be switched to PostgreSQL or MySQL).
Setup and Installation
Prerequisites
Ensure you have the following installed on your machine:

Python 3.x
pip (Python package installer)
Installation Steps
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/your-portfolio.git
cd your-portfolio
Create a virtual environment (optional but recommended):

bash
Copy code
python -m venv venv
Activate the virtual environment:

For Windows:
bash
Copy code
venv\Scripts\activate
For Mac/Linux:
bash
Copy code
source venv/bin/activate
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the migrations to set up the database:

bash
Copy code
python manage.py migrate
Create a superuser to access the Django admin (optional):

bash
Copy code
python manage.py createsuperuser
Run the development server:

bash
Copy code
python manage.py runserver
Access the website in your browser at http://127.0.0.1:8000/.

Usage
Navigate through the portfolio sections to view projects, skills, and details about me.
Use the contact form to send a message. The form collects the user's name, email, phone, subject, and message, and stores it in the database.
Deployment
To deploy this project on a live server, follow these steps:

Set up a production environment (e.g., using Gunicorn and nginx on a VPS).
Configure the database to use PostgreSQL or MySQL for better scalability.
Set DEBUG = False in settings.py for production use.
Configure a mail backend to send contact form messages to your email.