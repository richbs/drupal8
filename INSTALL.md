# Installation tips

Bring in PHP dependencies
```
composer install
```

Set-up Drush, the Drupal command-line utility
```
./vendor/bin/drush init
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

Set theme
```
drush config-set system.theme default zurb_foundation
```

Get Site UUID
```
drush config-get "system.site" uuid
```

Set Site UUID
```
drush config-set "system.site" uuid 571040e4-b92c-49b5-ac8d-e76220ae6f82
```

