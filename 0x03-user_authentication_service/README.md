# User authentication service; The ALX Project
--------------
This project implements a __user authentication service__ using `Flask`, 
`SQLAlchemy`, and `bcrypt` for __password hashing__. 
The authentication service includes functionality for 
__user registration__, __login__,__logout__,__profile access__,__password reset__,and __password update__.


__The project is organized into multiple modules__:

- `main.py`: Contains functions to test various functionalities of the authentication service.
- `auth.py`: Implements the Auth class, which interacts with the authentication database.
- `db.py`: Defines the DB class responsible for database operations.
- `user.py`: Declares the __SQLAlchemy model__ User representing the users table.
