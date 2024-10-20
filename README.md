# Rule Engine with AST

## Overview
This project implements a simple 3-tier rule engine application with a user interface, API, and backend. It determines user eligibility based on attributes like age, department, income, and spend. The system uses an Abstract Syntax Tree (AST) to represent conditional rules and allows for dynamic creation and evaluation of these rules.

## Features
- Check user eligibility based on defined rules
- Responsive web interface
- Error handling for invalid rule strings and data formats
- Simple and intuitive UI with a focus on eligibility checking

## Technology Stack
- Frontend: HTML, CSS, JavaScript
- Backend: Python with Flask
- Database: SQLite

## Setup and Installation
1. Clone the repository:
   ```
   git clone https://github.com/your-username/rule-engine-ast.git
   cd rule-engine-ast
   ```

2. Set up a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Initialize the database:
   ```
   flask db init
   flask db migrate
   flask db upgrade
   ```

5. Start the backend server:
   ```
   flask run
   ```

6. Open `index.html` in a web browser to access the application.

## Usage
### Checking Eligibility
1. Enter a rule string in the format: `(condition) AND/OR (condition)`.
   Example: `(age > 30 AND department = 'Sales') OR (income > 50000)`
2. Fill in the user attributes (Age, Department, Income, Spend).
3. Click "Check Eligibility" to evaluate the rule.

## Project Structure
- `index.html`: Main HTML file for the user interface
- `app.py`: Backend implementation for rule processing and API endpoints
- `models.py`: Database models
- `requirements.txt`: List of Python dependencies

## API Endpoints
- `/check_eligibility`: POST request to evaluate a rule against user data

## Future Enhancements
- Implement user management functionality (add, edit, delete users)
- Add support for more complex rule structures
- Enhance the user interface for rule creation
- Implement rule combination functionality
- Add unit tests for backend logic

## Dependencies
The project relies on the following main dependencies:
- Flask
- Flask-SQLAlchemy
- SQLAlchemy
- python-dotenv

For a complete list of dependencies, refer to the `requirements.txt` file.

## Contributing
Contributions to improve the Rule Engine are welcome. Please follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes and commit (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

## License
MIT License

## Contact
Your Name - your.email@example.com

Project Link: https://github.com/your-username/rule-engine-ast
