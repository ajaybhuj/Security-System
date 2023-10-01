# Security-System
**Project Title:** User Authentication System

**Description:**

The User Authentication System is a simple command-line based authentication program implemented in C++. It provides users with the ability to register, log in, and change passwords. The program stores user credentials (username and password) and additional information (age) in a text file called `file.txt`.

**Features:**

1. **Registration:** Users can register by providing a username, password, and age. The credentials are stored in the `file.txt` file.

2. **Login:** Registered users can log in by entering their username and password. If the credentials match, the program displays the user's details (username, password, and age).

3. **Password Change:** Users can change their passwords after logging in. They need to provide the old password, and if it matches the stored password, they can set a new password.

**How to Use:**

1. **Registration:**
   - Choose option 1 to register.
   - Enter a unique username, password, and age.

2. **Login:**
   - Choose option 2 to log in.
   - Enter the registered username and password.

3. **Password Change:**
   - Choose option 3 to change the password.
   - Enter the old password for verification.
   - Set a new password and confirm it.

4. **Exiting the Program:**
   - Choose option 4 to exit the program.

**Note:** 
- The user credentials and details are stored in a file called `file.txt`.
- The program checks the entered username and password against the stored credentials for authentication.

**Files:**
- `main.cpp`: Contains the C++ code for the User Authentication System.
- `file.txt`: Text file where user credentials and details are stored.

**How to Run:**
1. Compile and run the `main.cpp` file using a C++ compiler.
2. Follow the on-screen instructions to register, log in, change the password, and exit the program.

Feel free to customize and modify the program according to your requirements!
