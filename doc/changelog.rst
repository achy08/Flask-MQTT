Changelog
=========

Version 0.0.8
-------------
* add last will to be published on client disconnect
* add `on_publish`, `on_subscribe` and `on_unsubscribe` decorator

Version 0.0.7
-------------
* 100% test coverage
* bugfix: make flask application object at initialization optional again
* proper disconnecting on mqtt._disconnect

Version 0.0.6
-------------
* Flask-MQTT now supports Python 2.7

Version 0.0.5
-------------
* fixed unsupported type annotations for older Python 3 versions

Version 0.0.4
-------------
* documentation improvements
* support Python 3 versions < 3.6 by installing typing package 

Version 0.0.3
-------------
* automatic reconnect
* instant auto-refresh
* set keepalive time in seconds
* logging decorator

Version 0.0.2
-------------
* add SSL/TLS support
