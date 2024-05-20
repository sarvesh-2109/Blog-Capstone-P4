# Blog Capstone Project

Welcome to the Blog Capstone Project! This is a full-featured blog web application built using Flask. The application supports user registration, login, creating, editing, deleting posts, and commenting on posts. It also includes features for user authentication, admin-only access, and email notifications.

## Output


https://github.com/sarvesh-2109/Blog-Capstone-P4/assets/113255836/fd53611f-b378-4acb-b6d7-0da3ec5cb128




## Features

- 📝 **User Authentication**: Register, login, and logout functionalities.
- ✍️ **Create/Edit Posts**: Authenticated users can create and edit their own blog posts.
- 🗑️ **Delete Posts**: Admin users can delete any posts.
- 💬 **Comment on Posts**: Users can comment on posts.
- 🌟 **Admin-Only Features**: Some functionalities are restricted to admin users only.
- 📅 **Post Date**: Posts automatically include the date they were created.
- 🖼️ **Image Support**: Blog posts can include images.
- 📧 **Email Notifications**: Contact form that sends email notifications.

## Technologies Used

- **Flask**: A micro web framework for Python.
- **Flask-Bootstrap**: Integrates Bootstrap with Flask.
- **Flask-CKEditor**: Integrates CKEditor (a rich text editor) with Flask.
- **Flask-Login**: Manages user sessions and authentication.
- **Flask-SQLAlchemy**: Adds SQLAlchemy support to Flask.
- **Flask-WTF**: Simplifies form handling in Flask.
- **Flask-Gravatar**: Generates Gravatar URLs.
- **SQLite**: Database for storing user and post data.

## Setup and Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/sarvesh-2109/Blog-Capstone-P4.git
    cd Blog-Capstone-P4
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application**:
    ```bash
    flask run
    ```

## Usage

- **Register**: Create a new account by providing your email, name, and password.
- **Login**: Access your account by entering your email and password.
- **Create Post**: Once logged in, you can create a new blog post.
- **Edit/Delete Post**: Admin users can edit or delete any post.
- **Comment**: Logged-in users can comment on posts.



## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. 


Happy coding! 🧑‍💻🚀
