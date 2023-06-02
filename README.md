# Sabristi App

This app is purposed to train and enhance junior capabilities.

## Subject

Create an app with an interface to submit form, auth is **not** mandatory.\
  It needs too a back-office with **mandatory authentification** to retrieve and edit submitted forms.\
  **Use separate branch for your version**

Following features are mandatory:
- Validation
- Sanitization
- Authentification
- Middleware
- At least one table with pagination

You can use any patterns you want, such as Services, Actions, ... \
There is nothing installed, you have to install everything including Laravel !

## Stack
What is not specified below is free to use but, include as little as possible librairies.
### Env
- [Lando](https://docs.lando.dev/)

### Back-end
- MariaDB
- PHP 8.1
- [Laravel 10](https://laravel.com)

### Front-end
- Free to use

### Bonus
- Use [Laravel debugbar](https://github.com/barryvdh/laravel-debugbar), to assure better performance.
- Do not use Livewire, it's tooooooo easy.
- Handmade table is **awesome**



## Installation
1. Clone the project
2. cd in the project directory and create the environment.

```bash
lando rebuild -y
```
