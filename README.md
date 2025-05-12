
# Simple Social Network 🌐

A user-friendly Django-based social networking site built using Django Template views. Users can register, create and manage posts, interact with others, and manage their profiles — all through a clean and responsive HTML interface.

---

## ✨ Features

- 🧑‍🤝‍🧑 User Registration & Authentication (Login/Logout)
- 📝 Create, Edit, and Delete Posts
- 💬 Comment on Posts
- 👍 Like & 👎 Dislike Posts
- 🛠️ Edit Personal Profile
- 📧 Email support via Gmail SMTP
- 🧭 Django Admin Panel

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Nima-Mollaei/simple_social_network.git
cd simple_social_network
````

### 2. Create & Activate Virtual Environment

#### On Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

#### On macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Set your Gmail SMTP settings in `.env` or directly in `settings.py`:

```env
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=587
EMAIL_HOST_USER=your_email@gmail.com
EMAIL_HOST_PASSWORD=your_app_password
EMAIL_USE_TLS=True
```

### 5. Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6. Create Superuser (Optional)

```bash
python manage.py createsuperuser
```

### 7. Run the Server

```bash
python manage.py runserver
```

Visit the app at: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo, open issues, or submit pull requests.




