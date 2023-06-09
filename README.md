Sliding Login Page - README

This project consists of a sliding login page implemented in HTML, CSS, and JavaScript. It allows users to sign up and log in to access a profile page.


Files:
1. index.html: The main HTML file that contains the structure and content of the sliding login page. It includes the necessary CSS and JavaScript files.

2. style.css: The CSS file that defines the styles for the sliding login page.

3. index.js: The JavaScript file that handles the login functionality, user authentication, and redirection to the profile page.

4. index2.js: The JavaScript file that handles the sign-up functionality, form validation, and user data storage.

5. profiles.js: The JavaScript file that checks if a user is logged in and provides a logout feature on the profile page.


Functionality:
- Sliding Login: The login form slides in from the right when the "Login" label is clicked.

- Password Visibility: Clicking on the checkbox in the login form toggles the visibility of the password field.

- Login Validation: The login form validates the email and password fields. If they are empty or do not match the stored user records, an error message is displayed.

- Sign Up: Clicking on the "Sign Up" label reveals the sign-up form.

- Sign Up Validation: The sign-up form validates the name, email, and password fields. It checks for required fields, email format, and password length.

- User Data Storage: When a user signs up, their information is stored in the local storage using the HTML5 Web Storage API.

- Profile Page: The profile page (`last.html`) displays a welcome message and provides a logout option. It checks if a user is logged in by checking the presence of the user's name in the local storage.


Usage:
1. Clone or download the project files to your local machine.

2. Open the `index.html` file in a web browser.

3. The sliding login page will be displayed. You can log in using existing credentials or sign up as a new user.

4. Upon successful login or signup, you will be redirected to the profile page (`last.html`), where you will see a welcome message and have the option to log out.

Note: Make sure to have an internet connection to load the required external libraries (jQuery and jQuery Ripples) used for the ripple effect on the login page.
