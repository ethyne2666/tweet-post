# 🐦 Tweet Post Website (Beginner Django Project)

This is a simple **Tweet Post Web Application** built using the **Django** framework. It allows registered users to create an account, log in, and share posts that include an image, a title, and a description. 

This project is ideal for Django beginners looking to practice user authentication, forms, media upload, and template inheritance.

---

## 🔧 Features

- 🔐 User Registration and Login
- 🖼️ Post Creation with Image, Title, and Description
- ✍️ Only Logged-In Users Can Post
- 📄 Clean UI with Bootstrap 5
- 🌑 Dark Mode Styling
- 📦 Image Upload via Pillow

---

## 📁 Project Structure

```
tweet_project/
├── templates/
│   ├── layout.html        # Base layout with navbar and Bootstrap
│   ├── login.html         # Login page
│   └── register.html      # User registration form
├── static/                # (Optional) For static files
├── media/                 # For uploaded images
├── tweets/                # Your Django app for posts
│   ├── models.py          # Tweet post model
│   ├── views.py           # Post creation, edit, delete logic
│   └── urls.py            # App-level URL configuration
├── manage.py
├── db.sqlite3             # SQLite database (default)
└── requirements.txt       # Python dependencies
```

---

## ⚙️ Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/tweet-post-django.git
   cd tweet-post-django
   ```

2. **Create a Virtual Environment**
   ```bash
   python -m venv env
   source env/bin/activate    # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Migrations**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Run the Development Server**
   ```bash
   python manage.py runserver
   ```

6. **Access the App**
   Open your browser and go to: `http://127.0.0.1:8000/`

---

## 🧪 Test Credentials (Optional)

You can register a new user from the registration page or create a superuser:

```bash
python manage.py createsuperuser
```

---

## 📦 Requirements

See `requirements.txt`:

```
asgiref==3.9.0
Django==5.2.4
pillow==11.3.0
sqlparse==0.5.3
tzdata==2025.2
```

---

## 📸 Screenshot

![Tweet Post Screenshot](twitter/media/photos/screenshot.png)

---

## 🚀 Future Enhancements

- 🗂️ User profiles
- ❤️ Like or comment system
- 🧵 Pagination and filtering

---

## 📜 License

This project is open-source and free to use for learning and development.

---

## 🙋‍♂️ Author

**Charan Kumar** – [YouTube Channel: Bits and Facts](https://youtube.com/@charankumar_2666?si=XiHa8gBYvjqDgsW2)
