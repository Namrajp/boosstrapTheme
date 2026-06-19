# Learning Wordpress Journey

# Steps of Install
1. Installed Xampp from apache and Downloaded Wordpress and extract it.
2. Copied wordpress folder to htdocs on c:\xampp.
3. Opened wpconfig.sample on code editor and visit http://localhost/phpmyadmin in browser.
4. Create Database named wordpress_local and saved.
5. Edit wpconfig.sample file username:root, database:wordpress_local. saved as wpconfig.conf.
6. http://localhost/wordpress visited, follow install. Enter password and email. Finised process and login.

## Xammpp install error:
Apache port error: stopped.

open http.conf and change Listen: 8080 & ServerName localhost:8080
open httpd-ssl.conf and Change it to: Listen 4433 & Change it to: <VirtualHost _default_:4433>

## Copy Theme (My past theme folder)
Copy to folder htdocs/wordpress/wp-content/themes/
Navigate to: htdocs ➔ your-site-folder-name ➔ wp-content ➔ themes
Here, wordpress is default your-site-folder-name.

Wordpress admin dashboard , http://localhost/wp-admin or click "WP Admin" in LocalWP).
 Appearance ➔ Themes click Activate.