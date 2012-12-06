Phpup 
=====

Often in development you'll want to run a php project without writing up a full 
apache config for it. This generates a minimal apache config and runs an apache
instance in the foreground.

Tested under:

- Ubuntu 12.04
- Ubuntu 10.04
- Mac OSX 10.7
- Mac OSX 10.8

Installing
----------

```bash
cd /usr/local/bin
wget https://raw.github.com/lox/phpup/master/phpup
chmod +x phpup
```

Alternately, if you want it as part of your project, install [via composer](https://packagist.org/packages/lox/phpup). 

Running
-------

```bash
# Serving the present dir on default port
./phpup

# Serving a single file
./phpup -p 8000 helloworld.php

# Serving cwd directory with an .htaccess
./phpup -p 800 .
```


