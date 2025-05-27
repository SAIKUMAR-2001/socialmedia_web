## 📸 Instagram Clone (Django)

Instagram is a full-featured social media web application inspired by Instagram. Built with Django, this platform allows users to create accounts, manage friends, share posts, comment, and like content seamlessly. 🌐💬📷
---

## ✨ Features

- 🔐 User Authentication: Register, login, logout, and forgot password functionality using Django's built-in authentication system.

- 👤 Profile Management: Users can create and update their profiles.

- 🤝 Friend Management: Add, remove, and view friends.

- 🖼️ Posts: Create, edit, and delete posts with images and captions.

- ❤️💬 Interactions: Like posts and add comments to engage with content.

- 🖥️📱 Responsive UI: Clean and user-friendly interface built with HTML, CSS, and JavaScript.

- 🗄️ Database: Utilizes Django’s inbuilt SQLite database for efficient data management.

---

## 🖼️ Screenshots

### 🔐 Login Page
![Image](https://github.com/user-attachments/assets/3ed07674-3c3d-4575-b4cd-0faf7402ced9)

### 📝 Sign Up Page
![Image](https://github.com/user-attachments/assets/ed831dc4-f302-4621-96ec-6607677fc5d6)

### ❓ Forgot Password Page
![Image](https://github.com/user-attachments/assets/26d8c9fb-3187-4017-963c-f7ee1e940bb6)

### 👤 Profile Page
![Image](https://github.com/user-attachments/assets/347687e1-84e8-48bc-9f74-1e0e64dec91c)

---

## 🛠️ Technologies Used

- 🔙 Backend: Django (Python)

- 🎨 Frontend: HTML5, CSS3, JavaScript

- 🧩 Database: SQLite (Django’s default inbuilt database)

---

## 🔐 Forgot Password Feature

Users can now reset their password using the "Forgot Password" option available on the login page.

- An email with a reset link will be sent to the registered address. 📧

- The link allows users to securely create a new password and regain access to their account. 🔁🔒

- ✅ Make sure to configure Django’s email backend (EMAIL_BACKEND, EMAIL_HOST, etc.) in settings.py for this to work correctly.

---

## ⚙️ Installation and Setup

1. 📥 Clone the repository:
git clone https://github.com/SAIKUAMR-2001/instgra.git
cd instgra

2. 🐍 Create and activate a virtual environment:
python -m venv env
source env/bin/activate  # On Windows use env\Scripts\activate

3. 📦 Install dependencies:
pip install -r requirements.txt

4. 🔄 Apply migrations:
python manage.py migrate

5. 🚀 Run the development server:
python manage.py runserver

6. 🌐 Open your browser and visit http://127.0.0.1:8000 to access Instgra.

---

## 📲 Usage

- 📝 Sign up for a new account or log in if you already have one.

- ❓ Forgot your password? Use the password reset link to regain access.

- 👥 Add friends to see their posts.

- ➕ Create new posts with images and captions.

- ❤️ Like and 💬 comment on posts to engage with your network.
