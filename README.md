# First_Flask_Site_V.1

# First Flask Site

This is a basic web application built using Flask, titled "First Flask Site." 

## Project Structure

```
First-Flask-Site
├── app
│   ├── __init__.py
│   ├── routes.py
│   ├── static
│   │   └── styles.css
│   └── templates
│       └── index.html
├── tests
│   └── test_app.py
├── requirements.txt
├── config.py
└── README.md
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd First-Flask-Site
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Running the Application

To run the application, use the following command:
```
flask run
```

Make sure to set the `FLASK_APP` environment variable to `app` before running the command.

## Testing

To run the tests, use:
```
pytest tests/test_app.py
```

## License

This project is licensed under the MIT License.
