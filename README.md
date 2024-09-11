## FlaskPost

Welcome to FlaskBlog, a mini-project designed as part of my learning journey with Flask. This repository contains a simple yet functional blog platform where users can sign up, create posts, and manage content efficiently.

## Features

- **User Authentication:** Allows users to sign up and log in to access their personalized dashboard.
- **Blog Post Management:** Users can create, edit, and delete their posts.
- **Responsive Design:** Ensures a smooth user experience across various devices and screen sizes.

## Technologies Used

- **Flask:** A micro web framework written in Python.
- **SQLAlchemy:** ORM (Object Relational Mapping) library for database operations.
- **HTML/CSS:** For crafting a responsive and intuitive interface.

## Setup and Run

Follow these steps to get the blog running on your local machine:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/mhmp98/Flask-Blog.git
   ```
2. **Navigate to the Directory**
   ```bash
   cd Flask-Blog
   ```
3. **Create a Virtual Environment**
   ```bash
   python3 -m virtualenv venv
   # Or on Windows
   py -3 -m virtualenv venv
   ```
4. **Activate the Virtual Environment**
   ```bash
   ./venv/bin/activate
   # Or on Windows
   .\venv\Scripts\activate.bat
   ```
5. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
6. **Set up the Environment Variables**
   - Copy the `.env.example` file to `.env` and fill in the necessary details.
   ```bash
   cp .env.example .env
   ```
7. **Run Database Migrations**
   ```bash
   flask db upgrade
   ```
8. **Start the Server**
   ```bash
   flask run
   ```
