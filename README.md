
# Notes App

A full-stack web application built using Python, Django, and React that allows users to create, view, and delete their own notes. The application supports user authentication, allowing users to log in and log out securely. The app is deployed on Choreo. It will be reformatted in the future to scrape certain websites for prices of products and allow users to save those prices.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Features

- User registration and authentication
- Create, view, and delete notes
- User-specific note management
- Secure JWT-based authentication
- Responsive UI built with React

## Installation

### Prerequisites

- Python 3.x
- Node.js
- PostgreSQL

### Backend Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/notes-app.git
    cd notes-app
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up environment variables:
    - Create a `.env` file in the root directory and add your environment variables (e.g., database credentials, secret key).

5. Apply migrations:
    ```bash
    python manage.py migrate
    ```

6. Create a superuser:
    ```bash
    python manage.py createsuperuser
    ```

7. Run the development server:
    ```bash
    python manage.py runserver
    ```

### Frontend Setup

1. Navigate to the frontend directory:
    ```bash
    cd frontend
    ```

2. Install the required packages:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm start
    ```

## Usage

1. Open your web browser and go to `http://localhost:3000`.
2. Register for a new account or log in with your credentials.
3. Create, view, and delete your notes.

## Deployment

The application is deployed on Choreo. Follow the documentation on [Choreo](https://wso2.com/choreo/) to deploy your own instance of the application.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b my-feature-branch
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Add my feature"
    ```
4. Push to the branch:
    ```bash
    git push origin my-feature-branch
    ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README file further to suit your project's needs.
