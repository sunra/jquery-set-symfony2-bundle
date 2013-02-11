jQuary and set of plugins for Symfony2 projects
===============================================

Symfony2 bundled & in composer packaged

https://github.com/sunra/jquery-set-symfony2-bundle


Contents
--------
jQuery 1.8.3, 1.9.0, 1.9.1
jQuery Migrate 1.1.0

Plugins
-------
- jQuery.Timers        n/a       http://jquery.offput.ca/timers/
- jQuery-Tags-Input    1.3.3     https://github.com/xoxco/jQuery-Tags-Input



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
<script src="http://code.jquery.com/jquery-migrate-1.0.0.js"></script>

<script src="{{ asset('bundles/sunrajqueryset/js/jquery-plugin/jQueryTimers/jquery.timers.js') }}"></script>

```