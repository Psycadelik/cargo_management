#easy install
1. git clone
2. update .env  with your database info
3. run composer update
4. run php artisan key:generate
5. run php artisan migrate
6. login into mysql shell (mysql -u root)
7. INSERT INTO roles(slug,name) values('admin,'Admin')
8. INSERT INTO roles(slug,name) values('customer', 'Customer')
9. run php artisan serve
