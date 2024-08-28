# API Testing & Documentation

This repository contains the Postman for testing and Swagger for Documentation of the Django REST API.

## Project Overview

This project showcases how to use Postman to test API and Swagger to document API for a Django-based sample Library Management System project. 

It includes:

  - Testing GET, POST, PUT, DELETE requests.
    
    The Postman collection is available in the repository.
    
    Import the collection into Postman to test the API endpoints.
    
    - [Postman Collection](https://github.com/Sudham4444/api_tools/blob/main/Library%20Management%20API.postman_collection.json)
    
  - Documentation.
    
    The API documentation is available at the following URL:
    
    - [Swagger UI Documentation](http://127.0.0.1:8000/api/swagger/) 
    
    - [Swagger JSON Documentation](https://github.com/Sudham4444/api_tools/blob/main/swagger.json)

    - [Swagger PDF Documentation](https://github.com/Sudham4444/api_tools/blob/main/Documentation%20-%20Library%20Management%20API%20-Swagger.pdf)
   
    - [OpenAPI YAML Documentation](https://github.com/Sudham4444/api_tools/blob/main/openapi.yaml)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sudham4444/api_tools.git
   
2. **Navigate to the project directory:**
    ```bash
    cd api_tools/

3. **Install the dependencies:**
    ```bash
    pip install -r requirements.txt

4. **Run the development server:**
    ```bash
    python manage.py runserver

5. **Import the Postman Collection:**
    - Open Postman.
    - Go to the "Collections" tab and click "Import".
    - Upload the `Library Management API.postman_collection.json` file from this repository.
    - Alternatively
      - Choose the "Collection" file from your system.
      - Click "Import" to add the collection to Postman.

6. **Access Swagger UI Documentation**
   
   http://127.0.0.1:8000/api/swagger/

## How to Use
- Environment Setup:

  - Set up your environments in Postman (e.g., Development, Production).

  - Use the environment variables to manage different stages of API testing.

- Running Tests:

  - Use the Postman Collection Runner to execute the tests.
    
  - Review the results to ensure all API endpoints are functioning correctly.

## License

This collection is licensed under the MIT License.

## Contact
For any questions or issues, please contact at sudhamsingh2412@gmail.com.
