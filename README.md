> [!IMPORTANT]
> Read it carefully.

Step Work by Laravel
----
1. install git bash :
   ```
   https://git-scm.com/downloads
   ```
2. install Laragon  :
   ```
    https://github.com/leokhoa/laragon/releases/download/6.0.0/laragon-wamp.exe
    ```
3. install composer :
   ```
   https://getcomposer.org/Composer-Setup.exe
   ```
4. install nodejs :
   ```
   https://nodejs.org/en
   ```
   install lts
   
6. install vscode :
   ```
   https://code.visualstudio.com/download
   ```
8.  open vs code and go to extensions and install:
   - auto Close Tag
   - Auto Rename tag
   - Gitlens
   - live Share
   - path Debug
   - PHP debug
   - php intelephense
   - laravel blade Snippets
   - laravel Snippets
   - PHP Namespace Resolver
     
9. link vscode to your account github

10. create folder and open it in git bash :
   ```
   git clone https://github.com/Oussama-benrkia/Marketplace
   composer install     ||      composer update
   ```
11. create file .env , copy the content of .env.example and paste into .env 

12. run this commande :
   ```
   php artisan key:generate
   php artisan cache:clear
   php artisan serve
   ```


