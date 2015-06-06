# Drupal Portfolio Assessment for Epicodus
## by Daniel Toader
### Date: June 5, 2015
#### Description
Drupal 7 site as a showcase for custom modules and my sub-subtheme.

#### Setup instructions
1. Clone this git repository
2. Import the database that exists in sites/db-backups/testportfolio.sql to your mysql server
3. add db user "admin" with password "password" and all privileges to the db
3. Ensure Apache server is running with PHP server and pointed to the root folder for this site
4. Start the web app by pointing your browser to the root (http://localhost:8888/)

#### Drupal admin login instructions
This is a portfolio site that doesn't have user login. To login as the admin, go to (http://localhost:8888/user).
Admins created are:
1. "admin" with password "password"

#### Copyright © 2015, Daniel Toader

#### License: [MIT](https://github.com/twbs/bootstrap/blob/master/LICENSE)

#### Technologies used
- Drupal 7.37
  - Themes:
    - nucleus
    - tb_sirate
    - biscuit (custom sub-subtheme)
  - Modules:
    - ckeditor_insert
    - diff
    - jquery_update
    - views
    - admin_menu
    - ctools
    - dna (custom module)
    - module_filter
    - backup_migrate
    - date
    - reviews_display (custom module)
    - ckeditor
    - devel
    - insert
    - sweaver
- php
