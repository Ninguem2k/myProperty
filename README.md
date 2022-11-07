<center>
<h1>My Property</h1>

<h3>Criar o projeto Laravel:</h3>

    Laravel new Mypropries

<h3>Gerar as migrations:</h3>

    php artisan make:migration create_table_real_state --create=real_state
    php artisan make:migration create_table_categories --create=categories
    php artisan make:migration create_table_real_state_photos --create=real_state_photos
    php artisan make:migration create_table_user_profile --create=user_profile
    php artisan make:migration create_table_real_state_categories --create=real_state_categories

<h3>Gerar os Models:</h3>

    php artisan make:model RealState
    php artisan make:model Category
    php artisan make:model UserProfile

<h3>Gerar os Controllers:</h3>

    php artisan make:controller Api/RealStateController
    php artisan make:controller Api/UserController --resource --api
    php artisan make:controller Api/CategoryController --resource --api

<h3>Gerar os Request:</h3>

    php artisan make:request RealStateRequest
    php artisan make:request UserRequest
    php artisan make:request CategoryRequest

</center>
