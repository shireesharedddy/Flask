# Project Structure Overview

![project structure](https://github.com/user-attachments/assets/967fb1db-9509-4e9e-9083-359706938925)


**`hello_world_app/`**: This is the main directory of the Flask application.

- **`__init__.py`**: This file is used to initialize the Python package. It can also contain application setup code, such as creating the Flask app instance and configuring it.
  
- **`auth.py`**: This module handles authentication-related routes. It typically includes functions for user signup, login, and logout.
  
- **`main.py`**: This file often serves as the entry point for your application. It might include the main application logic and route definitions.
  
- **`venv/`**: This is a virtual environment directory that contains the dependencies of this project. It isolates the project’s packages from the global Python environment.
  
- **`__pycache__/`**: This directory stores the compiled bytecode of your Python files. It is automatically created by Python and can be ignored in most cases.

---

## Key Files in `auth.py`

- **`signup()`**: This function is meant to handle user registration.

- **`login()`**: This function manages user login requests.

- **`logout()`**: This function handles user logout requests.

---

### Additional Notes

- **Routing**: The `@auth.route()` decorator is used to define the URL endpoints for each function, making it easy to manage different parts of your application.

- **Terminal Output**: The terminal shows logs of requests made to your application, including status codes (like `200` for success and `404` for not found).

- 1. Hello World Page
![main page content](https://github.com/user-attachments/assets/68047b54-84e1-4d61-8790-feae99757148)

The image shows a web browser displaying the text **"Hello, World!"** on a blank white page. The URL in the address bar indicates it's running on a local server (`127.0.0.1`) at port `5000`.

- 2. Profile Page
![profile page](https://github.com/user-attachments/assets/be9fd41d-c421-4437-9ad1-6e9efe2e36a9)

The image shows a web browser displaying a simple webpage at the address `127.0.0.1:5000/profile`. The page contains the text **"Profile Here!"**.

- 3. Signup Page
![signup page](https://github.com/user-attachments/assets/3bef80c5-1d6d-4749-ab50-75c65f0e659e)

The image shows a web browser displaying a simple webpage with the text: **"This page will be used to sign up users."**

- 4. Login Page
![login page](https://github.com/user-attachments/assets/56c48ea3-6519-41d0-aeaa-81eab1aa5023)

The image shows a web page with the URL `127.0.0.1:5000/login`. The content of the page displays the text: **"This page will be used to login users."**

- 5. Logout Page
![logout page](https://github.com/user-attachments/assets/f350b0e6-c859-4a50-9363-5647b174424d)

The image shows a web browser displaying a blank page with the address `127.0.0.1:5000/logout` in the URL bar. There is a simple message that reads, **"Use this to log out."**

### Conclusion

The images presented depict the basic structure and functionality of the web application. Each page serves a specific purpose:

- **Hello World Page**: A simple "Hello, World!" message is displayed to confirm the server is running correctly.
- **Profile Page**: Displays a placeholder for the user profile.
- **Signup Page**: A page for user registration with the message, "This page will be used to sign up users."
- **Login Page**: A page for user authentication with the message, "This page will be used to login users."
- **Logout Page**: A simple page with a message indicating that users can log out, stating, "Use this to log out."

These screenshots represent the basic routing functionality of the Flask web application, ensuring to navigate through essential authentication-related tasks.




