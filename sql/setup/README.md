# MariaDB Setup on webdev VMs
1. Configure MariaDB using

    ```
    mysql_secure_installation
    ```

2. Create your webdev database. (Enter your root password when prompted)

    ```
    mysql -u root -p < create-webdev-db.sql
    ```

3. Create your webdev database user. (Enter your root password when prompted)

    ```
    mysql -u root -p < create-webdev-db.sql
    ```

4. Create your first table. (Enter your csstudent password when prompted)
   
    ```
    mysql -u csstudent -p < create-table.sql
    ```