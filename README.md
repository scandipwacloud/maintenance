# Readymage Maintenance

Adds symlink support for the Magento 2 maintenance flags

## Installation

1. `composer require cweagans/composer-patches ^1.5.0`
   
2. Add to the projects composer.json
    ```json
    {
      "extra": {
          "enable-patching": true
      }
    }
    ```
   
3.  `composer require readymage/maintenance`

## @TODO
- Remove dependency on `cweagans/composer-patches`
- Poke Magento 2 github to possibly fix this in upstream
