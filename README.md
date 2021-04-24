```bash
php artisan migrate --path=database/migrations/landlord --database=landlord
php artisan tenants:artisan "migrate --database=tenant"
php artisan tenants:artisan "migrate --database=tenant --seed"
```
