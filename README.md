# lab-automation
You should deploy these lab environments on testing servers and clean them up when you are done. I wrote these because in my line of work you gotta do some stuff sometimes to re-create an awful problem to fix.

Usage:
```
apache build       -  creates httpd environment for testing.
apache destroy     -  destroys httpd environment for testing.
lamp-stack build   -  creates linux/apache/mysql/php environment for testing.
lamp-stack destroy -  destroys linux/apache/mysql/php environment for testing.
nginx build        -  creates nginx testing environment.
nginx destroy      -  destroys nginx testing environment. 
```
