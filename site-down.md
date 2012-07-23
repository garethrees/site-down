# Site Down

## Check the server is up and the DNS responds

* $ ping xxx.xxx.xxx.xxx
* $ host domain_name

## Check that the application and Apache are running

<!-- TODO -->

## Check the Apache logs and the application log

Are there error messages at the bottom of the file? Does anything look unusual?

* $ tail -n 2000 /var/log/httpd/error_log
* $ tail -n 2000 /var/log/httpd/access_log
* $ tail -n 2000 APP_ROOT/log/production.log

## Check that MySQL is running

<!-- TODO -->

## Check the recent command line history

What was entered in the last few days? Could it have broken the site?

* $ history