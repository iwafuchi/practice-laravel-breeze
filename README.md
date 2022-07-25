# 作業メモ

## Laravel install
composer create-project laravel/laravel your_project_name --prefer-dist "9.*"

## 所有者:グループの変更
chown -R myusername:mygroupname your_project_name

## 権限変更
chmod -R 777 storage

## Breeze install
composer require laravel/breeze --dev
php artisan breeze:install
npm install
npm run dev
php artisan migrate
npm run build

## 参考資料
https://readouble.com/laravel/9.x/ja/releases.html