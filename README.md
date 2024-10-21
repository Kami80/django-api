# Django API

## Overview

This project is a RESTful API built with Django, designed to provide detailed information about various courses offered in a program. It allows users to retrieve course descriptions, credits, prerequisites, and other relevant details in a structured format.

## Features

- **Course Listing**: Access a list of all available courses.
- **Course Details**: Retrieve detailed information about each course.
- **Filtering**: Filter courses by various parameters, such as department or credits.

## Installation

To set up the project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Kami80/django-api.git
   cd django-api
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run database migrations**:
   ```bash
   python manage.py migrate
   ```

5. **Start the Django server**:
   ```bash
   python manage.py runserver
   ```

6. **Access the API**:
   Visit `http://127.0.0.1:8000/api/courses/` to explore the courses API.

## Usage

You can use tools like Postman or curl to interact with the API endpoints. Example requests include:

- **Get all courses**:
   ```
   GET http://127.0.0.1:8000/api/courses/
   ```

- **Get course by ID**:
   ```
   GET http://127.0.0.1:8000/api/courses/{id}/
   ```

## Contributing

Contributions are welcome! If you have suggestions, improvements, or features you'd like to see added, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
