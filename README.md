1.Run git clone https://github.com/truongnm-0205/Ecommerce_Graduation_Thesi
2.Run cd Ecommerce_Graduation_Thesi
2.Run composer install
3.Run cp .env.example .env
4.Run php artisan key:generate
5.Run php artisan migrate
6.Run php artisan serve
7.Go to link localhost:8000
# Laravel Sample

> Laravel sample website with content retrieving from [prismic.io](https://prismic.io)

This project runs with Laravel version 8.x.

## Getting started
git clone https://github.com/truongnm-0205/Ecommerce_Graduation_Thesi
cd Ecommerce_Graduation_Thesi
``` bash
# install dependencies
composer install
npm install

# create .env file and generate the application key
cp .env.example .env
php artisan key:generate
Run php artisan migrate

Then launch the server:

``` bash
php artisan serve
```

The Laravel sample project is now up and running! Access it at http://localhost:8000.

## Licence

This software is licensed under the Apache 2 license, quoted below.

Copyright 2018 Prismic.io (https://prismic.io).

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
