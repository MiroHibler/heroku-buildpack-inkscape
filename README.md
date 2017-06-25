# Heroku Buildpack for Inkscape

## Deprecated

This buildpack is no longer maintained.

Please use Heroku maintained [buildpack](https://elements.heroku.com/buildpacks/heroku/heroku-buildpack-apt) instead and follow their instructions.

If installed, this buildpack will only test existing Inscape installation, therefore it should run at the end of the buildpacks list.

## Install

```sh
$ heroku buildpacks:add https://github.com/MiroHibler/heroku-buildpack-inkscape.git [--index X] [--app APP_NAME]
```

Don't forget to add `inkscape` to your [Aptfile](https://elements.heroku.com/buildpacks/heroku/heroku-buildpack-apt).
