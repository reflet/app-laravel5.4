# Laravel (5.4.33)
laravel を使ってみる。

※ Laravel 5.4*
https://laravel.com/docs/5.4

## 必要条件
* PHP >= 5.6.4
* OpenSSL PHP Extension
* PDO PHP Extension
* Mbstring PHP Extension
* Tokenizer PHP Extension
* XML PHP Extension


## Laravelをインストールする

Githubからコードをクローンし、composerを使ってLaravel本体と各種ライブラリを配置します。

※ vendorフォルダ内にインストールされます。

**開発環境の場合)**
```
$ git clone https://github.com/reflet/app-laravel5.4.git .
$ composer create-project
```
※ 環境設定ファイル「.env」が自動作成されます。

**本番環境の場合**
```
$ git clone https://github.com/reflet/app-laravel5.4.git .
$ composer install --no-dev
```

## Laravelのバージョン確認

```
$ php artisan --version
Laravel Framework 5.4.33
```

## Composerを使って各種ライブラリをアップグレードする

```
$ php composer.phar self-update
$ php composer.phar update
```
