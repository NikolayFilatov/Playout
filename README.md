Playout
=======

Zf2 module for set layouts

Installation
============

1. Add require "neiron/playout": "dev-master" to composer.json in your project
and install module.

2. Create configuration file in autoload directory in your project with content:
    'module_layouts' => [
        'Application' => 'layout/application',
        'MyModule' => 'layout/mymodule'
    ]