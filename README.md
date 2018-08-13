# HAXCMS
HAX CMS seeks to be the smallest possible back-end CMS to make HAX work and be able to build websites with it. Leveraging JSON Outline Schema, HAX is able to author multiple pages, which it then writes onto the file system.

## Install and win the future, NOW!
- Clone this repo: `git clone https://github.com/elmsln/haxcms.git`
- install [docker](https://store.docker.com/search?type=edition&offering=community)
- [install ddev](https://ddev.readthedocs.io/en/latest/#installation) or [install docksal](https://docksal.io/installation/) or [install lando](https://docs.devwithlando.io/installation/installing.html) (We support all 3!)
- open a terminal window, go to the directory and type `ddev start` (for ddev) or `fin init` (for docksal) or `lando start` (for lando)
- go to the link any of them give you in a browser
- username/password is `admin`/`admin` to get building out static sites locally that you can push up anywhere!
- Click the icon in the top right and you're off and running!

## Scope
Generate `.html` files which have only "content" in them. Meaning the contents of the page in question. A simple method of adding new pages and managing the organization of those pages into a simple hierarchy (outline). Support for multiple mini web sites so that you can write a lot about different topics. HAXCMS is only intended to be a micro-site generator and play nicely with the rest of the HAX ecosystem without needing a monster CMS in order to utilize it.

## Features
- All of HAX without needing a bloated CMS to power it
- Incredibly simple, readable file structure of flat HTML files and lightning fast, high scale micro-sites
- No database (simple `.json` files help manage the data)
- Files you can reach out and touch, fork, and theme with ease!
- Support for multiple sites

## Install
Download, checkout and get this package on a server (this is a PHP based implementation so your server should have PHP and Apache or Nginx at minimum). Go to the project root and type `bash haxtheweb.sh` which will step you through configuration.

## Usage
Go to `{{yoursite.com}}` and login with the username and password you entered in the `config.php` by clicking on the login icon

## License
[Apache 2.0](LICENSE.md)
