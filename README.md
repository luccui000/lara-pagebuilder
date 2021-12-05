## Công nghệ sử dụng

- [Larvel 8](https://laravel.com/)
- [React](https://laravel-livewire.com/)
- [TailwindCSS](https://tailwindcss.com/)
- [Docker Container](http://dockerhub.com/)
## Cài đặt
**Cách 1:**

Bước 1: Tải source code
>git clone https://github.dev/luccui000/lara-pagebuilder

Bước 2: Đi đến thư mục source code vừa tải về
> cd lara-pagebuilder

Bước 3: Tiến hành cài đặt

Cài đặt các thư viện liên quan
> composer install

Copy file .env mẫu
>cp .env.example .env

Generate key
> php artisan key:generate

**Cách 2: Cài đặt qua docker**
>docker-compose up -d
## React src
```
.
├── assets
│   ├── images
│   └── styles
├── components
│   ├── Example.js
│   └── index.js
├── features
│   ├── Page
│   └── index.js
├── app.js
└── bootstrap.js
```

