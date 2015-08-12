

#Homestead 설치

http://laravel.com/docs/4.2/homestead

vagrant box add laravel/homestead

composer global require "laravel/homestead=~2.0"

homestead init

homestead edit

homestead up


# homestead 설정변경
homestead halt
homestead edit
...
homestead up --provision

( https://laracasts.com/discuss/channels/general-discussion/cannot-run-vagrant-provision-after-adding-a-new-site-to-homestead?page=1 )

# PHPStorm 연동
https://github.com/barryvdh/laravel-ide-helper

## composer require barryvdh/laravel-ide-helper

## [config/app.php]

Barryvdh\LaravelIdeHelper\IdeHelperServiceProvider::class,

## php artisan ide-helper:generate

-- php artisan vendor:publish --provider="Barryvdh\LaravelIdeHelper\IdeHelperServiceProvider" --tag=config
=> 이건 뭔지 모르겠다.
