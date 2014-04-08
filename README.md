Dokku buildpack for serving static sites
========================================

This is a [dokku](https://github.com/progrium/dokku) buildpack for serving static sites with [superstatic](https://www.npmjs.org/package/superstatic). Superstatic is built by [Divshot](www.divshot.com) to power their static site hosting service. This buildpack allows you to deploy your own static site service easily using dokku.

This is forked from the [Heroku node buildpack](https://github.com/heroku/heroku-buildpack-nodejs) and hacked. Caching is not currently working, so superstatic is re-installed every time you deploy.
