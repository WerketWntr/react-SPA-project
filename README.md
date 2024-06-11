
Clone the project
Navigate to the project's root directory using terminal
Create .env file - cp .env.example .env
Execute composer install
Execute npm install
Set application key - php artisan key:generate --ansi
Execute migrations and seed data - php artisan migrate --seed
Start vite server - npm run dev
Start Artisan server - php artisan serve


'email' => 'test@example.com',
'password' => bcrypt('123.123A'),
