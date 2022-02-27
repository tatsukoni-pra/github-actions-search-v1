# github-actions-search-v1
GitHub Actions検証用

# set up(初回)

```
cp .env.example .env
docker-compose up -d
docker exec -it app sh
composer clear-cache
composer install
php artisan key:generate --force
php artisan cache:clear
php artisan config:clear
```
