# VIP Go Skeleton

Welcome to VIP! This repo is a starting point for building your VIP Go site, including all the base folders to be built on.

## Guidebooks

We'd recommend starting with one of the following guidebooks. They include everything you need to know about launching and developing with VIP:

* [Launching with VIP](https://wpvip.com/documentation/launching-with-vip/)
* [Developing with VIP](https://wpvip.com/documentation/developing-with-vip/)

## Quick links to relevant documentation

To dig straight into our documentation and get up and running, try:

* [Understanding your VIP Go codebase](https://wpvip.com/documentation/vip-go/understanding-your-vip-go-codebase/)
* [VIP Go local development](https://wpvip.com/documentation/vip-go/local-vip-go-development-environment/)

## Usage

<<<<<<< HEAD
All the directories in this repo are required, and will be available on production web servers. Any additional directories created will not be available in production.

## Support

If you need help with anything, VIP's support team is [just a ticket away](https://wpvip.com/documentation/vip-go/accessing-vip-support/).

## Your content here
 
Feel free to add to or replace this README.md content with content unique to your project, for example:
 
* Project-specific notes; like a list of VIP environments and branches,
* Workflow documentation; so everyone working in this repo can follow a defined process, or
* Instructions for testing new features.
=======
All the directories here are required and will be available on production web servers. Any extra directories will not be available in production.

## PHPCS

This repo contains a starting point for installing and using a _local_ version of [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer/) (PHPCS). To get started, you'll need [Composer](https://getcomposer.org/), then open a command line at this directory, and run:

```sh
composer install
```

This will:

 - install PHP_CodeSniffer
 - install the VIP Coding Standards
 - install the WordPress Coding Standards
 - install the PHPCompatibilityWP Standard
 - register the above standards with PHP_CodeSniffer

The [`.phpcs.xml.dist`](.phpcs.xml.dist) file contains a _suggested_ configuration, but you are free to amend this. We would strongly recommend:

 - keeping the `WordPress-VIP-Go` rule active
 - keeping the `PHPCompatibilityWP` rule active
 - setting the `prefixes` property for your theme and any plugins ([info](https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards/wiki/Customizable-sniff-properties#naming-conventions-prefix-everything-in-the-global-namespace))
 - setting the `text_domain` property for your theme and any plugins ([info](https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards/wiki/Customizable-sniff-properties#internationalization-setting-your-text-domain)) 
  
We would also recommend keeping the `WordPress-Extra` and `WordPress-Docs` rules active, though these are not required for VIP Go.

You can move or copy the `.phpcs.xml.dist` into the root of your theme and custom plugin directories, and adjust it for more granularity of configuration for theme and custom plugins.

To run PHPCS, navigate to the directory where the relevant `.phpcs.xml.dist` lives, and type:

```sh
vendor/bin/phpcs
```

See the [PHPCS documentation](https://github.com/squizlabs/PHP_CodeSniffer/wiki/Usage) (or run `phpcs -h`) for the available command line arguments.
>>>>>>> 2449627b64c4dabbd9cb117bbaece0d521347f39
