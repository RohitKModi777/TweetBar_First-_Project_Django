# 🐍 My First Django Project — TweetBar🐦

A simple Twitter-like app built while learning Django for the very first time!  
This project helped me understand the core concepts of Django — from models and views to templates and CRUD operations.  
It’s my first step into the world of backend web development with Python 🐍.

---
demo
<img width="1885" height="895" alt="image" src="https://github.com/user-attachments/assets/e315e35c-023d-4d67-acbd-5f9ac5af7c74" />
when we search
<img width="1884" height="862" alt="image" src="https://github.com/user-attachments/assets/17ae7bba-94f7-415e-b073-dad1f9486553" />
creating tweet
<img width="1916" height="750" alt="image" src="https://github.com/user-attachments/assets/1e8a5c78-0165-4f58-b66e-a6aa087f18c8" />
editing tweet
<img width="1588" height="691" alt="image" src="https://github.com/user-attachments/assets/40929ec2-5820-406a-babd-d54e69765215" />
deleting tweet
<img width="1627" height="339" alt="image" src="https://github.com/user-attachments/assets/532056d0-f84a-482e-911d-39a21062cea4" />
login
<img width="1902" height="471" alt="image" src="https://github.com/user-attachments/assets/e9f2eb5e-f25b-4c5c-9717-0e69c5389e09" />
Register
<img width="1800" height="665" alt="image" src="https://github.com/user-attachments/assets/2890b252-c4c7-47d2-a854-8effaf640c15" />
Home page when no tweet found
<img width="1913" height="406" alt="image" src="https://github.com/user-attachments/assets/e04c929a-40b9-41d5-96e1-60928e4ea5ec" />




## 🌱 What I Learned

While building **ChaiTweet**, I learned:

- How Django follows the **MVT (Model-View-Template)** architecture  
- How to set up a **Django project and app**
- How to create and use **models**, **forms**, and **views**
- How to connect **templates** with backend data
- Handling **image uploads** using `ImageField`
- Using **Bootstrap** for frontend styling
- Implementing **CRUD operations**:
  - 📝 Create Tweet  
  - ✏️ Edit Tweet  
  - ❌ Delete Tweet  
  - 👀 Display Tweets  
- Implementing a simple **search bar** using `Q` filters in views
- Basic authentication and user-based access (only tweet owners can edit/delete)
- How Django ORM interacts with the database
- Using the **admin panel** to view and manage data

---

## ⚙️ Tech Stack

| Layer | Technology |
|-------|-------------|
| Backend | Django (Python) |
| Frontend | HTML, CSS, Bootstrap |
| Database | SQLite3 |
| Tools | VS Code, Git, GitHub |

---

## 🚀 Features

✅ Create, edit, and delete tweets  
✅ Upload an image with each tweet  
✅ Search tweets by text or username  
✅ Responsive Bootstrap UI  
✅ User-specific access control (only owner can edit/delete)  
✅ Clean and simple layout for easy learning  

---

## 🖥️ How to Run Locally

```bash
# Clone this repository
git clone https://github.com/yourusername/chaitweet.git
cd chaitweet

# Create virtual environment (optional but recommended)
python -m venv venv
venv\Scripts\activate  # On Windows
source venv/bin/activate  # On Mac/Linux

# Install dependencies
pip install django pillow

# Run migrations
python manage.py makemigrations
python manage.py migrate

# Start development server
python manage.py runserver
