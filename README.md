````md
# DevOps Python CI/CD

A simple Python application demonstrating a basic CI/CD pipeline using GitHub Actions.

## Project Structure

devops-python-app/
│
├── .github/
│   └── workflows/
│       └── python-ci.yml
│
├── app.py
├── test_app.py
└── README.md
````

## Application

The application performs a simple addition operation.

## Test

The project uses `pytest` to test the application.

Run tests locally:

```bash
pip install pytest
pytest
```

## CI/CD Pipeline

GitHub Actions automatically:

* Checks out the code
* Sets up Python
* Installs pytest
* Runs tests
* Runs the application

The pipeline runs automatically whenever code is pushed to the `main` branch.

## Author

Bhagyashri Joshi, Tanvi Jagade, Neha Karkhanis

```
```
