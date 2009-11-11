Steps:

1. Download your favorite Apache + MYSQL package (e.g. XAMPP and make sure it's PHP 5.2.x)
2. Extract mediawiki-plus-extensions.zip to htdocs
3. Extract mysql-backup-script.zip somewhere
4. Run mysql -u root < localhost.sql to create the wiki datababase
5. Hit http://localhost:[port]/w/ 
- If there's an error, remember to check C:\xampp\htdocs\w\LocalSettings.php for username/password issues
- feel free to contact joebogner [at] gmail for help