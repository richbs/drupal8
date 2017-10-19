# Installation tips

Bring in PHP dependencies
```
composer install
```

Set-up Drush, the Drupal command-line utility
```
./vendor/bin/drush
```

Export config changes
```
drush config-export
```

Download and install theme
```
wget https://ftp.drupal.org/files/projects/zurb_foundation-8.x-6.0-alpha3.tar.gz
drush en zurb_foundation
```
