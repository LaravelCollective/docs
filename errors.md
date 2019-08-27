# Forms & HTML

- [Installation](#installation)
- [Publishing](#publishing)

<a name="installation"></a>
## Installation

Begin by installing this package through Composer. Edit your project's `composer.json` file to require `laravelcollective/html`.

    composer require laravelcollective/errors

<a name="publishing"></a>
## Publishing

This package comprises solely of some error pages, SVG images designed by <a href="https://twitter.com/steveschoger">@steveschoger</a> and a simple error template called branded which lets you place a logo in the center of the right panel.

```
$ artisan vendor:publish --provider="Collective\Errors\ErrorsServiceProvider"
```
