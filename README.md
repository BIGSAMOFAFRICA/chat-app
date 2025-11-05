## BIGSAM chat app

Clean Laravel chat demo. No credentials are included in this repository.

### Setup

- `composer install`
- Create a database
- Copy your environment file and configure it locally: `cp .env.example .env`
- Update `.env` with your own values (APP_NAME, DB_*, PUSHER_*)
- `php artisan key:generate`
- `php artisan migrate --seed`
- `npm install && npm run dev`
- `php artisan storage:link`
- `php artisan serve`

### Notes

- Replace any placeholder environment values with your own in `.env`.
- This project includes a messaging package for chat UI and APIs.

© 2025 OLABISI SAMUEL. All rights reserved.
