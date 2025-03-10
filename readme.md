# (simple) robots.txt Plugin

A plugin for [Kirby CMS](http://getkirby.com) that generates an `robots.txt`.

## Commercial Usage

This plugin is free but if you use it in a commercial project please consider

- [making a donation](https://www.paypal.me/schnti/5)

## Installation

### Download

[Download the files](https://github.com/schnti/kirby-robots/archive/master.zip) and place them inside `site/plugins/robots`.

### Composer

```
composer require schnti/robots
```

### Git Submodule
You can add the plugin as a Git submodule.

    $ cd your/project/root
    $ git submodule add https://github.com/schnti/kirby-robots.git site/plugins/robots
    $ git submodule update --init --recursive
    $ git commit -am "Add Kirby robots.txt plugin"

Run these commands to update the plugin:

    $ cd your/project/root
    $ git submodule foreach git checkout master
    $ git submodule foreach git pull
    $ git commit -am "Update submodules"
    $ git submodule update --init --recursive

## How to use it

Nothing required.

The [schnti/kirby-sitemap](https://github.com/schnti/kirby-sitemap) plugin is recommended.
