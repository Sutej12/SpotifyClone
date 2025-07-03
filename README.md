# 🎵 Spotify Clone – Django Application

A full-stack Django web application that emulates core functionalities of Spotify, allowing users to manage music content such as artists and tracks through an admin panel.

## 🚀 Features

- Admin interface for managing music content.
- Modular Django architecture with reusable apps.
- Artist management (via `admin/artist/`).
- URL routing and views structured for scalability.

## 🛠 Tech Stack

- Python 3.7+
- Django Web Framework
- SQLite (default DB)

## 📁 Project Structure

SpotifyClone-Django-master/
│
├── manage.py
├── requirements.txt
├── db.sqlite3
│
├── SpotifyClone/ # Project settings & routing
├── admin/ # Main app
│ └── artist/ # Artist management sub-app
