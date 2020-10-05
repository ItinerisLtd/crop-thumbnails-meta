# itinerisltd/crop-thumbnails-meta

Metapackage to install the Crop-Thumbnails WordPress plugin along with [Itineris'](https://www.itineris.co.uk/) tweaks.

## Installation

Add `repositories` to `composer.json` (**order matters**):

```json
"repositories":[
    {
        "type": "package",
        "package": {
            "name": "wpackagist-plugin/crop-thumbnails",
            "type": "wordpress-plugin",
            "version": "1.2.6.999",
            "dist": {
                "type": "zip",
                "url": "https://github.com/ItinerisLtd/crop-thumbnails/archive/1.2.6.999.zip"
            }
        }
    },
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
