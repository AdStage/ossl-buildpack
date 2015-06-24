# OpenSSL buildpack

This builds a Heroku instance with linked to OpenSSL 0.9.8zg.

## Use with ddollar/heroku-buildpack-multi

    $ heroku config:set BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi

    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-ruby.git
    https://github.com/gtank/ossl-buildpack.git
