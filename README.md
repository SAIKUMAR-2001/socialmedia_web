# Instgra - Instagram Clone

Instgra is a full-featured social media web application inspired by Instagram. Built with Django, this platform allows users to create accounts, manage friends, share posts, comment, and like content seamlessly.

## Features

- User Authentication: Register, login, and logout functionality using Django's built-in authentication system.
- Profile Management: Users can create and update their profiles.
- Friend Management: Add, remove, and view friends.
- Posts: Create, edit, and delete posts with images and captions.
- Interactions: Like posts and add comments to engage with content.
- Responsive UI: Clean and user-friendly interface built with HTML, CSS, and JavaScript.
- Database: Utilizes Django’s inbuilt SQLite database for efficient data management.

## Technologies Used

- Backend: Django (Python)
- Frontend: HTML5, CSS3, JavaScript
- Database: SQLite (Django’s default inbuilt database)

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/instgra.git
   cd instgra

2.Create and activate a virtual environment:
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

3.Install dependencies:
pip install -r requirements.txt

4.Apply migrations:
python manage.py migrate

5.Run the development server:
python manage.py runserver

6.Open your browser and visit http://127.0.0.1:8000 to access Instgra.

Usage
Sign up for a new account or log in if you already have one.

Add friends to see their posts.

Create new posts with images and captions.

Like and comment on posts to engage with your network.
