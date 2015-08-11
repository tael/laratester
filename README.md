

#install homestead

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
