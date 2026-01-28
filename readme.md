# Masterblog

A simple, lightweight CRUD blogging application built with Python and Flask. This project allows you to manage blog posts using a local JSON file for storage.

## Features
- **CRUD Operations**: Create, Read, Update, and Delete blog posts.
- **Persistent Storage**: Posts are stored in `blog_posts.json`.
- **Simple Interface**: Clean HTML templates styled with CSS.

## Setup

1. **Install Dependencies**
   Ensure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Application**
   Start the development server:
   ```bash
   python app.py
   ```

3. **Open the Blog**
   Navigate to [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

## Project Structure
- `app.py`: Main Flask application logic.
- `templates/`: HTML files for `index`, `add`, and `update` views.
- `static/`: CSS and other static assets.
- `blog_posts.json`: JSON file acting as the database.