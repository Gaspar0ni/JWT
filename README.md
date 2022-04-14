




Instalação pode ser feita por:

composer require tymon/jwt-auth

ou

composer require tymon/jwt-auth:dev-develop --prefer-source

------------------------------------------------

Publish config

php artisan vendor:publish --provider="Tymon\JWTAuth\Providers\LaravelServiceProvider"

____________________________--------------------

Generate secret key

php artisan jwt:secret

---------------------------------------------------

