# Java AWT Login Form

A simple **Java AWT** login form for practicing GUI components and event
handling.

## Features

-   Checks that the username and password are not empty.
-   Checks the username and password against hard-coded users.
-   Checks that the selected role matches the user's role.
-   Shows a simple message when the entered information is incorrect.
-   Disables the Login button after **3 incorrect passwords** for a
    known username.
-   Opens a welcome window after a successful login.

## Screenshots

### Login form

![Login form](screenshots/login-form.png)

### Empty fields validation

![Empty fields validation](screenshots/empty-fields-validation.png)

### Invalid username or password

![Invalid username or
password](screenshots/invalid-username-or-password.png)

### Incorrect password attempts

![Incorrect password attempts](screenshots/wrong-password-attempts.png)

### Incorrect role

![Incorrect role](screenshots/incorrect-role.png)

### Login disabled after three incorrect passwords

![Login disabled after three incorrect
passwords](screenshots/login-disabled-after-three-attempts.png)

### Successful login

![Successful login](screenshots/successful-login.png)

## Test Accounts

  Username      Password   Role
  ------------- ---------- -----------
  `shady`       `1234`     Student
  `ahmed`       `5678`     TA
  `professor`   `9999`     Professor

These are demo credentials stored directly in the code.

## Run

1.  Open the project in your Java IDE.
2.  Make sure `LoginFormTask.java` is in the project.
3.  Run `LoginFormTask`.

## Technologies

-   Java
-   AWT (`Frame`, `Panel`, `Label`, `TextField`, `Choice`, `Button`,
    `Dialog`)
-   Event handling (`ActionListener`, `WindowAdapter`)

## Note

This is a small educational example. The users and passwords are
hard-coded for practice, not for production use.
