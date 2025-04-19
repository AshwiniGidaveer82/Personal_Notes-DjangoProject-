
# Personal Notes Django Project

## Overview

This is a **Django-based Personal Notes application** that allows users to securely store and manage their personal notes. The app provides functionalities for creating, editing, deleting, and viewing notes. It is designed to be simple and user-friendly, with authentication features for secure access.

## Features

- **User Authentication**: Sign up, login, and logout functionalities.
- **CRUD Operations for Notes**: Create, Read, Update, and Delete notes.
- **User Profile**: Users can update their profiles.
- **Responsive Design**: The application is designed to be mobile-friendly and responsive.

## Technologies Used

- **Django**: Backend framework.
- **SQLite**: Database for storing user data and notes.
- **HTML, CSS**: Frontend design for the user interface.
- **Bootstrap**: For responsive web design.

## Setup and Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/AshwiniGidaveer82/Personal_Notes-DjangoProject-
    ```
2. Navigate to the project directory:
    ```bash
    cd Personal_Notes-DjangoProject-
    ```
3. Set up a virtual environment (optional but recommended):
    ```bash
    python -m venv myenv
    ```
4. Activate the virtual environment:
    - On Windows:
        ```bash
        myenv\Scripts\activate
        ```
5. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
6. Apply migrations:
    ```bash
    python manage.py migrate
    ```
7. Run the development server:
    ```bash
    python manage.py runserver
    ```

Now, you can access the application at `http://127.0.0.1:8000/`.

## Output Example

Upon logging in, users will be able to create and manage their personal notes. Below is a screenshot of the homepage showing a list of the notes.

![Homepage Screenshot](https://github.com/AshwiniGidaveer82/Personal_Notes-DjangoProject-/raw/main/path_to_your_screenshot.png)

## Repository

For more details and to explore the source code, visit the project repository on GitHub:

[Personal Notes Django Project Repository](https://github.com/AshwiniGidaveer82/Personal_Notes-DjangoProject-)

---

Feel free to contribute, and if you encounter any issues, open an issue in the repository.
