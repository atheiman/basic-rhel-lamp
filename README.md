# Basic RHEL LAMP Cookbook

Following the Chef tutorial at [learn.chef.io](https://learn.chef.io/manage-a-web-app/rhel/).

- Installs `apache2` webserver, `mysql` database, and `mod_php5` apache module
- opens up firewall restrictions
- creates web user, MySQL user, encrypts passwords
- configures Apache webserver
- creates MySQL tables
- puts a basic PHP index page that queries MySQL

Using this cookbook will required you to create passwords in your data bag as described [in the tutorial](https://learn.chef.io/manage-a-web-app/rhel/create-a-password-store/).
