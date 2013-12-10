# travis-build

A simple script that builds your travis CI project inside a Docker container.

Quick Intro:

* make sure that `travis-build` is in your `PATH`
* make sure that you have permissions to run docker.
* make sure that you have a ".travis.yml" file in CWD.

Run `travis-build`.

## Limitations

* No support for the build matrix at this point.
* All the limitations of the Docker sandbox.
