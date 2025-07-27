# flask_Asg2
This Flask program is a basic login system using sessions.

🔹 Main Features:
Login Page (/):

Accepts username and password via a form.

Valid credentials: username = "admin", password = "123".

On success, stores user in session and redirects to /welcome.

On failure, shows: "In-valid credentials. Try again".

Welcome Page (/welcome):

Accessible only if the user is logged in (session exists).

Displays a welcome message and a logout link.

Logout Page (/logout):

Removes user from session.

Redirects back to the login page.
