# Blog Post Website Application

This Python application is a blog post website built using Flask, a lightweight web framework. It allows users to register, log in, create, edit, and delete blog posts, as well as comment on posts. The application includes features such as user authentication, database integration, and dynamic content rendering.

## Features

- **User Authentication**: Users can register, log in, and log out securely.
- **Database Integration**: Utilizes SQLAlchemy for database management, enabling storage of users, blog posts, and comments.
- **Content Management**: Users can create, edit, and delete blog posts, with support for rich text formatting.
- **Commenting System**: Provides a commenting system for users to engage with blog posts.
- **Profile Images**: Integrates Gravatar for adding profile images to the comment section.
- **Responsive Design**: Utilizes Flask Bootstrap for responsive design elements.

## Setup and Installation

1. Clone the repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file using `pip install -r requirements.txt`.
3. Set up environment variables:
    - `FLASK_KEY`: Secret key for Flask app.
    - `DB_URI`: URI for the database (optional, defaults to SQLite).
4. Run the application using `python app.py`.
5. Access the application in your web browser at `http://localhost:5001`.

## Usage

- Navigate to `http://localhost:5001` in your web browser to access the application.
- Register an account or log in if you already have an account.
- Explore the available features, such as creating, editing, and deleting blog posts, and commenting on posts.
- Log out when finished using the application.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This application was built using Flask, a micro web framework for Python.
- Bootstrap5 was used for frontend styling.
- CKEditor was used for rich text editing capabilities.
- Gravatar was used for profile image integration.
- SQLAlchemy was used for database management.
- Flask Login was used for user authentication.
