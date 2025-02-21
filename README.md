# Real-Time Chat Application

## Overview

This is a **Real-Time Chat Application** built using **Django Channels**, **WebSockets**, **HTMX**, and **Tailwind CSS**. The application allows users to engage in both **public chat rooms** and **private chat groups**, with support for **image and file sharing**.

## Features

- **Real-Time Messaging**: Powered by Django Channels and WebSockets.
- **Public Chat**: Users can join and participate in an open chatroom.
- **Private Chat Groups**: Users can create and manage private chat groups.
- **Media Sharing**: Supports sending images and files in both public and private chats.
- **HTMX for Dynamic Updates**: Enables smooth UI updates without full-page reloads.
- **Tailwind CSS for Styling**: Provides a modern, responsive design.

## Technologies Used

### Backend

- Django
- Django Channels
- WebSockets
- Django HTMX

### Frontend

- HTMX
- Tailwind CSS

### Database

- PostgreSQL / SQLite (depending on the environment)


## Installation & Setup

### Prerequisites

Make sure you have **Python 3.8+** and **pip** installed.

### Clone the Repository

```sh
git clone https://github.com/yourusername/realtime-chat.git
cd realtime-chat
```

### Create a Virtual Environment

```sh
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Install Dependencies

```sh
pip install -r requirements.txt
```

### Apply Migrations

```sh
python manage.py migrate
```

### Create a Superuser (For Admin Access)

```sh
python manage.py createsuperuser
```

### Run the Development Server

```sh
python manage.py runserver
```



## Usage

- **Sign up and log in** to access the chat system.
- **Join public chat** to communicate with everyone.
- **Create private chat groups** and invite friends.
- **Send text, images, and files** in conversations.


## License

This project is licensed under the **MIT License**.

## Contributing

Contributions are welcome! Feel free to submit a pull request or report issues.



