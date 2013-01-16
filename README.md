jQuary and set of plugins for Symfony2 projects
===============================================

Symfony2 bundled & in composer packaged

https://github.com/sunra/jquery-set-symfony2-bundle


Contents
--------
jQuery 1.8.3, 1.9.0

Plugins
-------
jQuery.Timers http://jquery.offput.ca/timers/




Installation
------------

1. Add to composer.json into "require" section
```
"sunra/jquery-set-symfony2-bundle": "dev-master"
```
and run 
```
composer.phar update
```

1. Add to app/AppKernel.php
```
new Sunra\jQuerySetBundle\SunrajQuerySetBundle()
```

2. run :
```
app/console assets:install
```


Usage
-----
```

<script src="{{ asset('bundles/sunrajqueryset/js/jquery/jquery-1.8.3.min.js') }}"></script>

<script src="{{ asset('bundles/sunrajqueryset/js/jquery-plugin/jQueryTimers/jquery.timers.js') }}"></script>

```