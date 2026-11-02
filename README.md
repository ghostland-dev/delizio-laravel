# Delizio

Recipe sharing website built with Laravel: browse recipes, follow each step and leave comments and ratings.

## Features

- Recipes with categories, ingredients, utensils and step-by-step instructions
- Image uploads for recipes
- Comments, ratings and contact messages
- User accounts and authentication

## Tech Stack

- Laravel (PHP), Blade
- MySQL
- Bootstrap

## Getting Started

```bash
git clone https://github.com/ghostland-dev/delizio-laravel.git
cd delizio-laravel/Delizio
composer install
npm install && npm run dev
cp .env.example .env && php artisan key:generate
php artisan migrate --seed
php artisan serve
```

## Author

**Ismail.M**, Software Engineer & DevOps

- GitHub: [@ghostland-dev](https://github.com/ghostland-dev)
- Website: [ismail-mouyahada.com](https://www.ismail-mouyahada.com)
