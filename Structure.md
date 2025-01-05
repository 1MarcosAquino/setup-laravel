# Structure
````
project/
├── README.md
├── Structure.md
├── app
│   ├── README.md
│   ├── app
│   │   ├── Http
│   │   │   └── Controllers
│   │   │       └── Controller.php
│   │   ├── Models
│   │   │   └── User.php
│   │   └── Providers
│   │       └── AppServiceProvider.php
│   ├── artisan
│   ├── bootstrap
│   │   ├── app.php
│   │   ├── cache
│   │   │   ├── packages.php
│   │   │   └── services.php
│   │   └── providers.php
│   ├── composer.json
│   ├── composer.lock
│   ├── config
│   │   ├── app.php
│   │   ├── auth.php
│   │   ├── cache.php
│   │   ├── database.php
│   │   ├── filesystems.php
│   │   ├── logging.php
│   │   ├── mail.php
│   │   ├── queue.php
│   │   ├── services.php
│   │   └── session.php
│   ├── database
│   │   ├── database.sqlite
│   │   ├── factories
│   │   │   └── UserFactory.php
│   │   ├── migrations
│   │   │   ├── 0001_01_01_000000_create_users_table.php
│   │   │   ├── 0001_01_01_000001_create_cache_table.php
│   │   │   └── 0001_01_01_000002_create_jobs_table.php
│   │   └── seeders
│   │       └── DatabaseSeeder.php
│   ├── package.json
│   ├── phpunit.xml
│   ├── postcss.config.js
│   ├── public
│   │   ├── favicon.ico
│   │   ├── index.php
│   │   └── robots.txt
│   ├── resources
│   │   ├── css
│   │   │   └── app.css
│   │   ├── js
│   │   │   ├── app.js
│   │   │   └── bootstrap.js
│   │   └── views
│   │       └── welcome.blade.php
│   ├── routes
│   │   ├── console.php
│   │   └── web.php
│   ├── storage
│   │   ├── app
│   │   │   ├── private
│   │   │   │   └── *
│   │   │   └── public
│   │   │       └── *
│   │   ├── framework
│   │   │   ├── cache
│   │   │   │   └── data
│   │   │   │       └── *
│   │   │   ├── sessions
│   │   │   │   └── *
│   │   │   ├── testing
│   │   │   │   └── *
│   │   │   └── views
│   │   │       └── *
│   │   └── logs
│   │       └── laravel.log
│   ├── tailwind.config.js
│   ├── tests
│   │   ├── Feature
│   │   │   └── ExampleTest.php
│   │   ├── TestCase.php
│   │   └── Unit
│   │       └── ExampleTest.php
│   └── vite.config.js
├── docker
│   ├── nginx
│   │   └── default.conf
│   └── php
│       ├── Dockerfile
│       └── custom.ini
└── docker-compose.yml
````
