SilverStripe DebugBar module
==================
Use [DebugBar](https://github.com/maximebf/php-debugbar) in SilverStripe. This is only active in Dev mode.

This module will:

- Enable a custom log writer that will log all messages under the messages tab
- Log framework execution based on available hooks
- Log database calls (if you use PDO)
- Display current environment

Include the DebugBar in your template simply by calling $RenderDebugBar

Please note that jQuery is excluded from vendors and you are expected to include your own jQuery.

Installation
==================

Since this extension will increase memory footprint, it is recommended to install it only in dev mode

Either run:

    composer require lekoala/silverstripe-debugbar --dev

Or add: 

    lekoala/silverstripe-debugbar: "dev-master"

to require-dev in your composer.json file

Todos
==================

- Make the database tab work with other drivers

Compatibility
==================
Tested with 3.3+

Maintainer
==================
LeKoala - thomas@lekoala.be