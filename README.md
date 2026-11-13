# Back-End Development – Pictures Microservice

## Project Description

This project is a Flask-based RESTful API microservice for managing picture records.

It supports creating, retrieving, updating, deleting, and counting picture records using HTTP methods and JSON responses.

## Technologies Used

- Python
- Flask
- REST API
- JSON
- Pytest
- Git and GitHub

## API Endpoints

| HTTP Method | Endpoint | Description |
|---|---|---|
| GET | `/health` | Check application health |
| GET | `/count` | Get the total number of pictures |
| GET | `/picture` | Retrieve all pictures |
| GET | `/picture/<id>` | Retrieve a picture by ID |
| POST | `/picture` | Create a new picture |
| PUT | `/picture/<id>` | Update an existing picture |
| DELETE | `/picture/<id>` | Delete a picture by ID |

## Running the Application

Run the following command:

```bash
python app.py
```

The Flask application runs on port `8080`.

## Running Tests

Execute the test suite using:

```bash
pytest
```

## Test Results

All 11 tests passed successfully.

```text
============================== 11 passed in 0.08s ==============================
```

The tests cover:

- Application health and picture count
- Retrieving all pictures
- Retrieving pictures by ID
- Creating pictures
- Handling duplicate picture records
- Updating picture records
- Deleting picture records

## Repository

GitHub: [Back-End-Development-Pictures](https://github.com/tvasavi2007-beep/Back-End-Development-Pictures)

## Author

Snigdha Veera Naga Vasavi Tadi
