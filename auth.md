# Auth

- [Installation](#installation)
- [Important](#important)
- [Make Auth](#make)
- [Foundation](#foundation)
- [Migration](#migration)

<a name="installation"></a>
## Installation

Begin by installing this package through Composer. Edit your project's `composer.json` file to require `laravelcollective/auth` or simply run:

```bash
$ composer require laravelcollective/auth
```

<a name="important"></a>
## Important

This package is an agnostic fork of Laravel UI and only handles the Auth components. It provides agnostic HTML blade views.
<!-- For any UI components please see [laravelcollective/presets](laravelcollective.com/docs/presets) -->

<a name="make"></a>
## Make Auth

```bash
$ php artisan make:auth --force=false
```

<a name="foundation"></a>
## Foundation

The Auth Foundation components are all the `auth-backend` components from Laravel UI.

<a name="migration"></a>
## Migrating from Laravel/UI to Collective/Auth

Migration should take less than 2 minutes overall.
Simply switch any namespaces of:

`Illuminate\Foundation\Auth` to `Collective\Auth\Foundation`

and in your routes switch:

`Auth::routes()` to `CollectiveAuth::routes()`.

Everything else should work the same.
