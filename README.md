# php_laravel_challenge
A code test to assess developer skils, during the recruitment process for nayojobs.com

Create a project to manage companies and their employees. Mini-CRM.

##Basic Laravel Auth: 
ability to log in as administrator

##Database:
Use database seeds to create first user with email admin@admin.com and password “password”
We would like to be able to get up and running with data via your migrations and seeds

##CRUD functionality (Create / Read / Update / Delete) for two menu items: 
###Companies and Employees.
Companies DB table consists of these fields: Name (required), email, logo (minimum 100×100), website
Employees DB table consists of these fields: First name (required), last name (required), Company (foreign key to Companies), email, phone
Use database migrations to create those schemas above
Store companies logos in storage/app/public folder and make them accessible from public
Use basic Laravel resource controllers with default methods – index, create, store etc.
Use Laravel’s validation function, using Request classes
Use Laravel’s pagination for showing Companies/Employees list, 10 entries per page
Use Laravel make:auth as default Bootstrap-based design theme, but remove ability to register
company-crud






