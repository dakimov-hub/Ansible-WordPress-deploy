# Ansible WordPress Capstone

This is the starting point for the Ansible Capstone project in the Mastering Ansible Automation course

## Variable

- **wordpress_db** and **wordpress_user** specify the name of the MySQL database and user, respectively, that will be created for WordPress
- **wordpress_password** specifies the password for the MySQL user
- the variables **mysql_databases** and **mysql_users** are used by the my_sql role

## Installing Dependencies for playbook

    ansible-galaxy install -r sible-WordPress-deploy/requirements.yml 



