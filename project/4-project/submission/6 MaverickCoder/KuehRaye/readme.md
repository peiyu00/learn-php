This website has to be run on a web server, either using a MAMP/LAMP/WAMP etc.

You can put this whole folder, KuehRaye in your htdocs file and access it via localhost/KuehRaye and it will take you to the index.php page.

The users will be seeded automatically upon the first visit of the website, on page index.php where it will then redirect to the login page.

If there is an error with your phpmyadmin settings, where you cannot set your root user to using no password, please visit the db_config.php and db_connection.php to include a password of your choice that matches what you have set in your own phpmyadmin under account root.

For an ADMIN, the account username is admin with the password admin123.

For a USER account, the usernames and password are
1. janesmith - password123
2. mikejohnson - password123

As an admin you are able to view an extra tab, stocks to manage inventory.