# PHP-Auth
Simple PHP authentication system 

Use the user 'admin' and password 'admin'.

To authenticate a page using an HTML login page, include the 'auth.php' file, and call the function authHTML().

To authenticate an API script using the BASIC Authentication method, include the 'auth.php' file, and call the function authAPI(), test the API login

NOTE: There is a lot more to be done for security in real life, this code was done for testing purposes.

The user validation is done by the function isValidUser($user, $pass) in the file auth.php, reimplement it to use a custom validation or to just change the default user and password.
