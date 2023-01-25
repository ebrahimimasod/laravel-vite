# laravel-vite
A simple example of combining Laravel and Vite, where the admin panel and client sections are separated.


## npm commands


 for admin panel (dev , build and build for ssr) :
```bash
npm run dev:admin 
npm run build:admin 
npm run build:admin-ssr 
```

build and build ssr (for production) :
```bash
 npm run admin:serve 
```


 for client (dev , build and build for ssr) :
```bash
npm run dev:client 
npm run build:client 
npm run build:client-ssr 
```

build and build ssr (for production) :
```bash
 npm run client:serve 
```


serve ssr file (useful for SEO) :
```bash
php artisan inertia:start-ssr 
```












