# Country Select

A fieldtype that let's you select a country from a list maintained by the [league/iso3166](https://github.com/thephpleague/iso3166) package.

## Install 

First add this repo to your composer.json in ProcessWire:

```json
{
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/LostKobrakai/FieldtypeCountrySelect"
    }
  ]
}
```

Then run the following to install the module and it's dependency:

```bash
composer require lostkobrakai/fieldtype-country-select
```

## Requirements

- ProcessWire `>= 2.8.10` | `>= 3.0.10`
- PHP `>= 5.5`