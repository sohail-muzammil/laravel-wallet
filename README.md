# Laravel Wallet

A Laravel with Vue.js authentication starter kit.

## Tech Stack

- Laravel 12
- Vue 3
- Tailwind CSS 4
- Inertia.js
- Laravel Socialite Plus (for social authentication)
- Spatie Laravel Sitemap (for sitemap generation)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/laravel-wallet.git
   cd laravel-wallet
   ```

2. Install PHP dependencies:
   ```bash
   composer install
   ```

3. Install JavaScript dependencies:
   ```bash
   npm install
   ```

4. Create and configure your `.env` file:
   ```bash
   cp .env.example .env
   ```
   Edit the `.env` file with your database credentials and other settings.

5. Generate application key:
   ```bash
   php artisan key:generate
   ```

6. Run database migrations:
   ```bash
   php artisan migrate
   ```

## Included Packages

- **Laravel Socialite Plus**  
  For social authentication:  
  https://github.com/Blaspsoft/socialiteplus

- **Spatie Laravel Sitemap**  
  For sitemap generation:  
  https://github.com/spatie/laravel-sitemap

## Available Commands

- Generate sitemap:
  ```bash
  php artisan app:generate-sitemap
  ```

## Development

1. Start Laravel development server:
   ```bash
   php artisan serve
   ```

2. Build frontend assets (for development):
   ```bash
   npm run dev
   ```

3. For production build:
   ```bash
   npm run build
   ```

## License

This project is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
