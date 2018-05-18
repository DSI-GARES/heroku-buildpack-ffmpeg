Heroku buildpack: FFMpeg
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for using [ffmpeg](http://www.ffmpeg.org/) in your project.

Usage
-----
To use this buildpack, add https://github.com/DSI-GARES/heroku-buildpack-ffmpeg to your buildpack.

The binaries are downloaded from https://github.com/DSI-GARES/heroku-binaries/raw/master/ffmpeg.tar.gz

You can verify installing ffmpeg by following command.

    $ heroku run "ffmpeg -version"
