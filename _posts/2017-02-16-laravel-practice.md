#### check out laravel version
php artisan -V

#### setup a local simple IDE
php artisan serve

#### files related to routing
~/routers/web.php
~/routers/api.php
~/routers/channels.php
~/routers/console.php
#### file of view
~/resources/views/welcome.blade.php
#### setup database connection
~/config/database.php
#### checkout current application environment
php artisan env
#### database migration
php artisan make:migration create_houses_table

composer dump-autoload

php artisan cache:clear

php artisan make:migration create_houses_table --create=houses

.env

~/app/Providers/AppServiceProvider.php
public function boot()
{
    Schema::defaultStringLength(191);
}

DB::table('tablename')->get();

dd();

+--------- comparison ------------------------------------------+
php artisan make:controller PostController
php artisan make:model Post
php artisan make:migration create_posts_table --create=posts
+--------- with ------------------------------------------------+
php artisan make:model Post -mc
+---------------------------------------------------------------+

php artisan make:controller Tasks -r

php artisan tinker
>>>App\Post::all()

Node.js
curl --silent --location https://rpm.nodesource.com/setup_7.x | sudo bash -
sudo yum install -y gcc-c++ make
sudo yum install -y nodejs

composer.json - for composer to manage your PHP dependencies
package.json - for npm to manage your Node dependencies

sudo npm install
it will generate node_modules directory

sudo npm run dev
it will compile files to public directory

carbon

static function of class

AppServiceProvider.php

php artisan make:mail Welcome

+---------- mail setup ------------------------------------------+
mailtrap.io
no good, change to mailgun

composer require guzzlehttp/guzzle
but it requires more mem/buff, so make swap

+---------- add swap begin ----------------------------+
/bin/dd if=/dev/zero of=/var/swap.1 bs=1M count=1024
/sbin/mkswap /var/swap.1
/sbin/swapon /var/swap.1
+---------- add swap finish ---------------------------+

guzzle done!

+---------- mailgun configuration ---------------------+

modify .env switch mail drive to mailgun
modify mail.php switch mail drive to mailgun, and setup global from
setup service.php fill up domain(your domain) and private key

done!
+-----------------------------------------------------------------+

php artisan make:mail Greeting --markdown='email.greeting'

php artisan make:request RegistrationRequest

session()
session()->flash()

php artisan make:model Tag

belongsTo
hasMany
belongsToMany

getRouteKeyName

vi /etc/

wget https://dl.eff.org/certbot-auto
chmod a+x certbot-auto
./certbot-auto

+--------- add to config/app.php ----------------------------------+
composer require intervention/image

add to config/app.php
$providers :
Intervention\Image\ImageServiceProvider::class
$aliases :
'Image' => Intervention\Image\Facades\Image::class

php artisan vendor:publish --provider="Intervention\Image\ImageServiceProviderLaravel5"
+------------------------------------------------------------------+

---------- replace php7.0 with php5.6 -----------------------------+

sudo yum remove httpd24 php70 mysql56-server php70-mysqlnd

sudo yum install httpd24 php56 mysql56-server php56-mysqlnd

-------------------------------------------------------------------+

sudo yum install php56-gd
sudo yum install php56-mbstring
sudo yum install phpmyadmin




