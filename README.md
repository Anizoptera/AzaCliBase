AzaCliBase
==========

Anizoptera CMF component with basic functionality and helper methods for CLI and Daemon applications (forks, libevent, etc..).

https://github.com/Anizoptera/AzaCliBase

[![Build Status](https://secure.travis-ci.org/Anizoptera/AzaCliBase.png?branch=master)](http://travis-ci.org/Anizoptera/AzaCliBase)

Provides convenient API for commonly needed tasks in CLI or Daemon applications.

Some features:

* Detaching process from the controlling terminal;
* Fork wrapper (with libevent base reinitializing if needed);
* Signals and exit codes reference;
* Signals hadling and simple waiting (with pcntl);
* Get current tty width in columns;
* Get running command by PID;
* Kill process tree;
* Change process title;
*  ... other;

AzaCliBase is a part of [Anizoptera CMF](https://github.com/Anizoptera), written by [Amal Samally](http://azagroup.ru/#amal) (amal.samally at gmail.com) and [AzaGroup](http://azagroup.ru/) team.

Licensed under the MIT License.


Requirements
------------

* PHP 5.3.3 (or later);
* Unix system;
* [pcntl](http://php.net/pcntl);
* [posix](http://php.net/posix);


Optional requirements
---------------------

* [proctitle](http://php.net/proctitle) extension to change process title;
* [aza/libevent](https://packagist.org/packages/aza/libevent) and [libevent](http://php.net/libevent) extension to store one main event base for application;


Installation
------------

The recommended way to install AzaCliBase is [through composer](http://getcomposer.org).
You can see [package information on Packagist.](https://packagist.org/packages/aza/clibase)

```JSON
{
	"require": {
		"aza/clibase": "~1.0"
	}
}
```


License
-------

[MIT](http://www.opensource.org/licenses/mit-license.html), see [LICENSE.md](LICENSE.md)
