
# laravel-spanish-translate
Traducción completa de los archivos de idioma de Laravel 10 a español.

### Agregar la traducción a tu proyecto
Para utilizar esta traducción, en tu proyecto:
```bash
  php artisan lang:publish
```
Se generará la carpeta **/lang** en la raiz del proyecto, dentro, crea una carpeta llamada **/es**.

Dentro de esta última carpeta pega los 4 archivos:

- auth.php
- pagination.php
- passwords.php
- validation.php

Luego, dirígite a la carpeta **/config** y en el archivo **app.php** cambia la configuración regional a español (linea 86~):
```php
 'locale' => 'es',
```

### Versión de Laravel

Esta traducción corresponde a Laravel 10.10.
Verificar cualquier cambio antes de utilizar.


### Authors

- [@daiv05](https://github.com/daiv05)
