Showing how to restrict symfony versions using flex:

```
composer install
composer require symfony/yaml ^2.8 # this won't work
composer require symfony/yaml ^3.4 # this will work
```