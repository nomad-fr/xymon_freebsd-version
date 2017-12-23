# xymon_freebsd-version

#### Dependencies 

* zsh
* sudo
* fetch
* awk

#### Configuration

* add this to : /usr/local/www/xymon/client/etc/clientlaunch.cfg

~~~
[freebsd-version]
        ENVFILE $XYMONCLIENTHOME/etc/xymonclient.cfg
        CMD /usr/local/www/xymon/client/ext/freebsd-version
        LOGFILE /usr/local/www/xymon/client/logs/freebsd-version.log
        INTERVAL 1m
~~~
