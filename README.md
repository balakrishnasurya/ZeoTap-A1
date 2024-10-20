# Rule Engine with AST

## Overview
This project implements a simple 3-tier rule engine application with a user interface, API, and backend. It determines user eligibility based on attributes like age, department, income, and spend. The system uses an Abstract Syntax Tree (AST) to represent conditional rules and allows for dynamic creation, combination, and modification of these rules.

## Features
- Create and add new users
- Define and evaluate eligibility rules
- Check user eligibility based on defined rules
- Responsive web interface
- Error handling for invalid rule strings and data formats

## Technology Stack
- Frontend: HTML, CSS, JavaScript
- Backend: [Your backend technology, e.g., Python with Flask]
- Database: [Your database choice, e.g., SQLite, PostgreSQL]

## Setup and Installation
1. Clone the repository:
   ```
   git clone https://github.com/your-username/rule-engine-ast.git
   cd rule-engine-ast
   ```

2. [Include steps to set up the backend environment, e.g., installing Python dependencies]

3. [Include steps to set up the database]

4. Start the backend server:
   ```
   [Command to start your backend server]
   ```

5. Open `index.html` in a web browser to access the application.

## Usage
### Adding a New User
1. Click on the "Add New User" button.
2. Fill in the user details (Name, Age, Department, Income, Spend).
3. Click "Add User" to save the new user.

### Checking Eligibility
1. Enter a rule string in the format: `(condition) AND/OR (condition)`.
   Example: `(age > 30 AND department = 'Sales') OR (income > 50000)`
2. Fill in the user attributes (Age, Department, Income, Spend).
3. Click "Check Eligibility" to evaluate the rule.

## Project Structure
- `index.html`: Main HTML file for the user interface
- `[backend_file]`: Backend implementation for rule processing and user management
- `[database_file]`: Database for storing user information and rules

## API Endpoints
- `/add_user`: POST request to add a new user
- `/check_eligibility`: POST request to evaluate a rule against user data

## Future Enhancements
- Implement rule combination functionality
- Add support for more complex rule structures
- Enhance the user interface for rule creation
- Implement user authentication and authorization

## Contributing
Contributions to improve the Rule Engine are welcome. Please follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes and commit (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

## License
[Your chosen license, e.g., MIT License]

## Contact
[Your Name] - [Your Email]

Project Link: https://github.com/your-username/rule-engine-ast
