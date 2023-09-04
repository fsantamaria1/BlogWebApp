
# BlogWebApp

This is a Django web application. The project allows users to create, edit, and delete blog posts.

You can access the live demo of this project [here](https://fsantamaria14.pythonanywhere.com/).

## Features

- User authentication: Register and log in to manage your blog posts.
- Create, edit, and delete blog posts.
- View a list of all blog posts on the home page.
- View individual blog posts with details.

## Prerequisites

Before running this project locally or deploying it, make sure you have the following dependencies installed:

- Python (3.6 or higher)
- Django (3.0 or higher)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/fsantamaria1/BlogWebApp.git
   ```

2. Navigate to the project directory:

   ```bash
   cd BlogWebApp
   ```

3. Install the project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Apply the database migrations:

   ```bash
   python manage.py migrate
   ```

5. Create a superuser to access the admin panel:

   ```bash
   python manage.py createsuperuser
   ```

6. Start the development server:

   ```bash
   python manage.py runserver
   ```

7. Open your web browser and go to [http://localhost:8000](http://localhost:8000) to view the application.

## Usage

- Visit the live demo [here](https://fsantamaria14.pythonanywhere.com/) to interact with the deployed project.
- To access the admin panel, go to [http://localhost:8000/admin/](http://localhost:8000/admin/) and log in with your superuser credentials.

## Deployment

This project is currently deployed on [PythonAnywhere](https://fsantamaria14.pythonanywhere.com/).

If you want to deploy it on your own server or hosting service, make sure to configure the necessary settings for your deployment platform.

## Acknowledgments

- [Django Girls](https://tutorial.djangogirls.org/en/) for the excellent tutorial that helped create this project.
- The Django community for creating a powerful web framework.
