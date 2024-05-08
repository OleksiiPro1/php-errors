# php-errors

# Включить показ ошибок. Для этого в начале файла some-file.php, перед подключением файлов, добавьте следующие строки:
ini_set('error_reporting', E_ALL);
ini_set('display_errors', 1);


# For WP

wp-config.php

define('WP_DEBUG', true);
define('WP_DEBUG_LOG', true);
define('WP_DEBUG_DISPLAY', false);


