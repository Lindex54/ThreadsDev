# ThreadsDev 🧵💻

ThreadsDev is a developer-focused discussion platform built with Django. It provides a collaborative space where developers can create topic-based rooms, share ideas, ask questions, and engage in meaningful technical discussions.

The platform is designed to encourage knowledge sharing, community learning, and collaboration among developers of all skill levels.

---

## 🚀 Features

- 🔐 User authentication (sign up, login, logout)
- 👤 Custom user profiles with avatars and bios
- 🧵 Topic-based discussion rooms
- 💬 Threaded conversations
- 👥 Room participants list
- 🏷️ Topic categorization
- ✏️ Edit and delete messages (owner only)
- 🔍 Search rooms by topic or name
- 📱 Responsive user interface

---

## 🛠️ Tech Stack

- **Backend:** Django
- **Frontend:** Django Templates (HTML, CSS)
- **Database:** SQLite (development)
- **Authentication:** Custom Django User Model
- **Media Handling:** Django Media Files
- **Styling:** Custom CSS

---

## 📂 Project Structure

threadsdev/
│
├── base/ # Core application
│ ├── models.py # User, Room, Message, Topic models
│ ├── views.py # Application logic
│ ├── urls.py # App routes
│ └── templates/ # HTML templates
│
├── static/ # Static files (CSS, JS, images)
├── media/ # Uploaded avatars
├── templates/ # Base templates
├── db.sqlite3
<<<<<<< HEAD
---
└── manage.py

=======
└── manage.py


---

>>>>>>> 87d6060d54f4bf7bd5a731e60e716705e6a58609
## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
<<<<<<< HEAD
git clone https://github.com/Lindex/Learning_Hub.git
cd threadsdev

python -m venv env
source env/bin/activate   # Windows: env\Scripts\activate

#install Dependencies
pip install -r requirements.txt

#Run migration
python manage.py migrate

# create super user
python manage.py createsuperuser
```
🧠 How ThreadsDev Works

Developers create accounts and customize their profiles.

Users can create or join discussion rooms based on specific topics.

Each room supports threaded conversations for idea sharing.

Messages are linked to users and timestamps for clear discussion flow.

Only message owners can edit or delete their content.

---

🔒 Permissions & Security

Only authenticated users can post messages.

Users can only edit or delete their own messages.

Profile editing is restricted to account owners.
=======
git clone https://github.com/your-username/ThreadsDev.git
cd threadsdev

# Create Virtual Environment
python -m venv env
source env/bin/activate   # Windows: env\Scripts\activate

#install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py makemigrations
python manage.py migrate

# Create Superuser
python manage.py createsuperuser

# Run Server
python manage.py runserver

```

🧠 How ThreadsDev Works

  Developers create accounts and customize their profiles.
  
  Users can create or join discussion rooms based on specific topics.
  
  Each room supports threaded conversations for idea sharing.
  
  Messages are linked to users and timestamps for clear discussion flow.
  
  Only message owners can edit or delete their content.

--=

🔒 Permissions & Security
  
  Only authenticated users can post messages.
  
  Users can only edit or delete their own messages.
  
  Profile editing is restricted to account owners.

🌱 Future Improvements

---

🔔 Notifications for replies

  ⚡ Real-time messaging with WebSockets
  
  ⭐ Room bookmarking
  
  👍 Message reactions (likes)
  
  🧑‍🤝‍🧑 Follow developers
  
  📊 User activity analytics
  
  🐳 Docker support
>>>>>>> 87d6060d54f4bf7bd5a731e60e716705e6a58609

---

🤝 Contributing

<<<<<<< HEAD
Contributions are welcome!

Fork the repository

Create a new feature branch

Commit your changes

Open a pull request


=======
  Contributions are welcome!
  
  Fork the repository
  
  Create a new feature branch
  
  Commit your changes
  
  Open a pull request
>>>>>>> 87d6060d54f4bf7bd5a731e60e716705e6a58609
