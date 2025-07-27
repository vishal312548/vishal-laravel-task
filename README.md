# vishal-laravel-task
Laravel 10 Assignment

1) Features

->User Registration (with Slack notification)
->Employee create and Editing (with Slack notification)
->Slack Integration using Laravel Notification System
->Bootstrap 5 Frontend (Home, About Us, Features)
->using laravel service layer for bussiness logivs.


->Setup Instructions


```bash
1) git clone https://github.com/your-name/your-project.git
2) cd your-project

3) composer install
4) npm install && npm run dev

5)setup database

DB_DATABASE=your_db
DB_USERNAME=root
DB_PASSWORD=

6) create a channel of slack and on the income webhook then add a url in the env.
=>SLACK_WEBHOOK_URL=https://hooks.slack.com/services/XXXX/YYYY/ZZZZ

7)php artisan migrate
8) php artisan serve

9) php artisan optimize:clear 
10) http://127.0.0.1:8000
click on the link and clik on register.
open the channel you got a :- New User Registered: test (test@gmail.com) this is exp.
->User Registration (with Slack notification) step done

11)after show the employee navigation in the navbar click on the tab then show the employee list.
12) click on the add new button then show the form and enter the ('Full Name , Email , Phone ,Designation)
then employee created and show the channel message you show. New Employee Created: test (test@gmail.com),,123

13) click the button edit on table, then you can edit the empoloyee details after get a message.
New Employee updated: test133434 (test@gmail.com), 123456, 123

14) after created a 3 page of Bootstrap 5 Frontend (Home, About Us, Features);
this is page is non authenticated.

15) /home for home page; 
16) /aboutUs for aboutus page;
17) /features for features page

when you open a home page then you can easily change the page using the navigation bar.


thankyou....
