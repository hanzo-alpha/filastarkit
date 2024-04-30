<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>
<p align="center">
    A starting point to create my next Filament 3 💡 app. With pre-installed plugins, pre-configured, and custom page. 
So you don't start all over again.
</p>

#### Features

- 🛡 [Filament Shield](#plugins-used) for managing role access
- 👨🏻‍🦱 customizable profile page from [Filament Breezy](#plugins-used)
- 🌌 Manageable media with [Filament Curator](#plugins-used)
- 🖼 Setting Page Management
- 💌 Backup Management
- 🅻 Activity Log View & Application Health, Also Jobs Monitoring
- Etc..

#### Latest update

###### Version: v0.0.1

- Initial Commit

[Version Releases](https://github.com/hanzo-alpha/filastarkit/releases)

###### Upcoming:

- Filament Multi Tenancy 🔥
- ...

#### Getting Started

Create project with this composer command:

```bash
composer create-project hanzo-alpha/filastarkit
```

Setup your env:

```bash
cd filastarkit
cp .env.example .env
```

Run migration & seeder:

```bash
php artisan migrate
php artisan db:seed
```

<p align="center">or</p>

```bash
php artisan migrate:fresh --seed
```

Now you can access with `/admin` path, using:

```bash
email: superadmin@filastartkit.local
password: superadmin
```

#### Roles Management

This project include roles management.

```
php artisan shield:install
```

#### Setting Management

This project include setting management page.

```
php artisan setting:install
```



#### Plugins

These are [Filament Plugins](https://filamentphp.com/plugins) use for this project.

| **Plugin**                                                                                           | **Author**                                          |
|:-----------------------------------------------------------------------------------------------------| :-------------------------------------------------- |
| [Filament Curator Media Library](https://github.com/filamentphp/spatie-laravel-media-library-plugin) | [Filament Official](https://github.com/filamentphp) |
| [Filament Spatie Settings](https://github.com/filamentphp/spatie-laravel-settings-plugin)            | [Filament Official](https://github.com/filamentphp) |
| [Filament Spatie Tags](https://github.com/filamentphp/spatie-laravel-tags-plugin)                    | [Filament Official](https://github.com/filamentphp) |
| [Shield](https://github.com/bezhanSalleh/filament-shield)                                            | [bezhansalleh](https://github.com/bezhansalleh)     |
| [Exceptions](https://github.com/bezhansalleh/filament-exceptions)                                    | [bezhansalleh](https://github.com/bezhansalleh)     |
| [Breezy](https://github.com/jeffgreco13/filament-breezy)                                             | [jeffgreco13](https://github.com/jeffgreco13)       |
| [Logger](https://github.com/z3d0x/filament-logger)                                                   | [z3d0x](https://github.com/z3d0x)                   |
| [Ace Code Editor](https://github.com/riodwanto/filament-ace-editor)                                  | [riodwanto](https://github.com/riodwanto)           |

### License

Filament Starter is provided under the [MIT License](LICENSE.md).

If you discover a bug, please [open an issue](https://github.com/hanzo-alpha/filastartkit/issues).
