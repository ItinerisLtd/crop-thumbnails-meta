# itinerisltd/crop-thumbnails-meta

Metapackage to install the [Crop-Thumbnails](https://wordpress.org/plugins/crop-thumbnails/) WordPress plugin along with [Itineris'](https://www.itineris.co.uk/) tweaks.

## Installation

Add the `wpackagist.org` repository to your `composer.json`:

```json
"repositories":[
    {
        "type":"composer",
        "url":"https://wpackagist.org",
        "only": ["wpackagist-plugin/*", "wpackagist-theme/*"]
    }
],
```

```bash
composer require itinerisltd/crop-thumbnails-meta
```
