# Heroku Buildpack for Inkscape

Installs [Inkscape](https://inkscape.org) v0.92.1 on Heroku.

Uses intltool [v0.51.0](https://launchpad.net/intltool)

Runs [test](https://github.com/duhast/heroku-inkscape-test).

## Install

First add dependences:

```sh
$ heroku buildpacks:add https://github.com/Munett/heroku-buildpack-cmake.git [--index X] [--app APP_NAME]
$ heroku buildpacks:add https://github.com/mojodna/heroku-buildpack-cairo.git [--index X] [--app APP_NAME]
$ heroku buildpacks:add https://github.com/nolman/heroku-gsl-buildpack.git [--index X] [--app APP_NAME]
```
Then add this package:

```sh
$ heroku buildpacks:add https://github.com/MiroHibler/heroku-buildpack-inkscape.git [--index X] [--app APP_NAME]
```
