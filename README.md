# Heroku Buildpack for Inkscape

Currently installs Inkscape 0.92.1 on Heroku Cedar.

Uses intltool [v0.50.0](https://launchpad.net/intltool)

Runs [test](https://github.com/duhast/heroku-inkscape-test).

## Install

    # Use heroku-buildpack-multi
    $ cd /path/to/your-app
    $ heroku config:add BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi.git

    # Create a .buildpacks file with including ghostscript
    $ cd /path/to/your-app
    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-ruby.git
    https://github.com/MiroHibler/heroku-buildpack-inkscape.git

    # Push changes to deploy
    $ git push
