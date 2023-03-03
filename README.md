# ENTR-451 Homework #4

Full instructions at https://entr451.com/homework-4/

Rubric (20 points)
Implement all user stories

(6 points) User Authentication
<!-- When creating new users, save a 1-way encrypted hash of the password using Bcrypt. -->
<!-- Complete the login form -->
<!-- Secure data in transit - use the appropriate form input types when dealing with any password data. -->
<!-- In the sessions controller, authenticate the user by email and password. If successful, "log them in" (i.e. assign the user's id to the session hash) and redirect to the places index. If unsuccessful, redirect back to login. -->
<!-- Use @current_user to conditionally show the login/signup links or a logout link. You will first need to assign @current_user in the global application controller. -->
<!-- In the sessions controller, "logout" a logged-in user (i.e. remove the user's id from the session hash) and redirect to login. -->

(3 points) User Authorization
<!-- Only show the new post form to logged-in users (i.e. if there is a @current_user). -->
<!-- Assign new posts to the logged-in user (aka @current_user). -->
<!-- Only show posts created by the logged-in user (aka @current_user). Hide all other users' posts. (Note: logged-out users should also not be able to see other users' posts). -->

(6 points) Frontend with Bootstrap
<!-- Install Bootstrap including both the <link> (in the <head> before any custom stylesheets) and the <script> (just before the closing </body>). -->
<!-- Add Bootstrap's navbar component (any version). Move the relevant links (e.g. "Home", "Login", "Signup", "Logout") into the navbar. -->
<!-- Wrap all relevant content including <%= yield %> in a Bootstrap .container (navbar is commonly excluded from the .container). -->
<!-- Using the Bootstrap button component, style all links to forms and all form submit buttons. -->
Use the Bootstrap grid for posts (3 posts per row on larger screens, stacking on smaller screens). See wireframe.
Use the bootstrap spacing (margin or padding) as needed, but at least twice (not counting the navbar).

(5 points) TBA