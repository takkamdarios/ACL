# Laravel 9 Hospital Stock Management System

Manage the assets and their stock in hospitals: view for one hospital, with superadmin overseeing all hospitals and get notified of low amounts left, also seeing transactions history.

- - - - -

## Screenshots 

![Laravel Stock Management 01](https://quickadminpanel.com/blog/wp-content/uploads/2020/04/Screen-Shot-2020-04-07-at-12.24.57-PM.png)

- - - - -

![Laravel Stock Management 02](https://quickadminpanel.com/blog/wp-content/uploads/2020/04/Screen-Shot-2020-04-07-at-12.24.04-PM.png)

- - - - -

![Laravel Stock Management 03](https://quickadminpanel.com/blog/wp-content/uploads/2020/04/Screen-Shot-2020-04-07-at-12.24.18-PM.png)

- - - - -

![Laravel Stock Management 04](https://quickadminpanel.com/blog/wp-content/uploads/2020/04/Screen-Shot-2020-04-07-at-12.25.12-PM.png)

- - - - -

## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL. 
- You can login to adminpanel by going go `/login` URL and login with credentials __admin@admin.com__ - __password__
- For other users, doctors/directors, their email is in `users.email` field, and password is __password__

