# Laravel Socialite Social Login

This projects demostrates how to authenticate with OAuth providers using Laravel Socialite

## Installation

- Clone the repository
```bash
git clone https://github.com/phi-rakib/laravel-socialite-social-login.git
```

- Change directory to laravel-socialite-social-login
```bash
cd laravel-socialite-social-login
```

- Install the dependencies
```bash
composer install
```
- Create database
- Copy the environment file
```bash
cp .env.example .env
```
- Change client id & secrets for each of the providers in the .env file
```bash
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret

FACEBOOK_CLIENT_ID=your-facebook-client-id
FACEBOOK_CLIENT_SECRET=your-facebook-client-secret

GITHUB_CLIENT_ID=your-github-client-id
GITHUB_CLIENT_SECRET=your-github-client-secret
```
- Also change database configuration values in the .env file
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your-database-name
DB_USERNAME=your-db-user-name
DB_PASSWORD=your-db-password
```
- Run migration
```bash
php artisan migrate
```
- Start local development server
```bash
php artisan serve
```