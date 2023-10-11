# Django REST + React Image Uploading

This project demonstrates how to create a full-stack web application for uploading images to a Django REST API backend using a React frontend.

### Usman Ghias - Follow me in GitHub

## Project Overview

This project is divided into two main components:

1. **Backend (Django REST API):** This is responsible for handling image uploads, serving images, and managing the REST API endpoints.

2. **Frontend (React):** This is responsible for providing a user-friendly interface to upload images to the backend, view uploaded images, and interact with the API.

## Getting Started

To set up and run this project, follow these steps:

### Backend (Django REST API)

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/UsmanGhias/DjangoRest_React_ImageUploading.git
   ```

2. Navigate to the backend directory:

   ```shell
   cd DjangoRest_React_ImageUploading/backend
   ```

3. Create and activate a virtual environment (recommended):

   ```shell
   python -m venv env
   source env/bin/activate  # On Windows, use: env\Scripts\activate
   ```

4. Install the required Python packages:

   ```shell
   pip install -r requirements.txt
   ```

5. Run database migrations:

   ```shell
   python manage.py makemigrations
   python manage.py migrate
   ```

6. Start the Django development server:

   ```shell
   python manage.py runserver
   ```

### Frontend (React)

1. Navigate to the frontend directory:

   ```shell
   cd DjangoRest_React_ImageUploading/frontend
   ```

2. Install the required Node.js packages:

   ```shell
   npm install
   ```

3. Start the React development server:

   ```shell
   npm start
   ```

The project should now be running, and you can access the React app at `http://localhost:3000`.

## Using the Application

- Open your web browser and go to `http://localhost:3000`.
- Use the provided interface to upload images. The uploaded images will be sent to the Django REST API.
- To view the uploaded images, you can access the API endpoints, e.g., `http://localhost:8000/api/images/`.

## Sample Images

To test image uploads and API functionality, you can use the following sample image URLs:

- Image 1: [Backend](/backend.png)
- Image 2: [FrontEnd](/frontend.png)

## License

This project is open-source and available under the [MIT License](LICENSE).

