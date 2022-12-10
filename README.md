# Getting Started

## Step 1 : Require Chatify Using Command

````javascript
composer require munafio/chatify
````

## Step 2 : Install Chatify Using Command

````javascript
php artisan chatify:install
````

## Step 3 : Migrate Using Command

````javascript
php artisan migrate
````

## Step 4 : Install JetStream through Composer

````javascript
composer require laravel/jetstream
````

## Step 5 : Install JetStream through Composer

````javascript
php artisan jetstream:install livewire
````

## Step 6 : Install npm & after Installation Run Migrate Command Again

````javascript
npm install
npm run build
php artisan migrate
````

## Step 7 : Change Chatify Pusher Configuration

1. Go to https://pusher.com/docs/channels/using_channels/events/#triggering-client-events & Sign Up
2. Create an App
3. Go to App Setting -> Enable Client Events
4. Go to App Keys
5. Here You Find Your Configuration Settings
6. Add this Configuration Setting to .env File

````javascript
PUSHER_APP_ID=1522939
PUSHER_APP_KEY=7fc7a62d096d5454f621
PUSHER_APP_SECRET=f5801a81cee383a527d3
PUSHER_HOST=
PUSHER_PORT=443
PUSHER_SCHEME=https
PUSHER_APP_CLUSTER=ap2
````

