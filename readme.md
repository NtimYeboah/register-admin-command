## register-admin-command

Simple project to demonstrate how to register a super admin with artisan command

## Install

- Clone this repository

`git clone https://github.com/NtimYeboah/register-admin-command.git`

- Run composer to install packages

`composer install`

- Create env file

`cp .env.example .env`

- Generate key

`php artisan key:generate`

- Set the database connections in the `.env` file

- Run migration

`php artisan db:migrate`

## Run artisan command

`$ php artisan register:admin`
