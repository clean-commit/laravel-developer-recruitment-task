# Laravel Recruitment Task

Hi!

Thank you for joining our recruitment process @ Clean Commit! This task will test how you can work with front end project.

![laravel](https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg)

## Task

We need to create a simple CRM application with auth!

## Requirements

- Use Laravel 7.x
- **Basic Laravel Auth**: ability to log in as administrator
- Use database seeds to create first user with email admin@admin.com and password “password”
- Implement CRUD functionality (Create / Read / Update / Delete) for two menu items: Companies and Employees.
- Companies DB table consists of these fields: Name (required), email, logo (minimum 100×100), website
- Employees DB table consists of these fields: First name (required), last name (required), Company (foreign key to Companies), email, phone
- Use database migrations to create those schemas above
- Store companies logos in storage/app/public folder and make them accessible from public
- Use basic Laravel resource controllers with default methods – index, create, store etc.
- Use Laravel’s validation function, using Request classes
- Use Laravel’s pagination for showing Companies/Employees list, 10 entries per page
- Use Laravel make:auth as default Bootstrap-based design theme, but remove ability to register

Additional options (big plus):

- Add API routes to view and add companies
- Add authorization token to API
- Add Seeding to fill the db with initial data (companies and employees)
- Use Tailwind instead of Bootstrap

## Rules & Hints

1. Pay attention to code quality, formatting, conventions etc. (Your code is your business card)
2. Try to optimize images :)
3. Send us access to your repo to check out your work!
4. Don't worry about the front end, just make it look 'ok' with Tailwind or Bootstrap
