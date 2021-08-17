# Install PHP only in Ubuntu Desktop 16.04 or Higher

### To install run the following commands:
```console
$ sudo apt install php-cgi
$ sudo apt install php
```

### Or manually put the resolved dependency:
```console
$ sudo apt install php php8.0-cgi
```

### Then you can run the following commands:
```console
$ cd /path/to/project
$ php -S localhost:8000
```