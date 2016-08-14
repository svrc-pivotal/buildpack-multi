# buildpack-multi

Use multiple buildpacks on your app.  Useful if you need to install Ubuntu packages via apt first.

## Usage

    $ cat .buildpacks
    https://github.com/pivotal-cf-experimental/apt-buildpack
    https://github.com/cloudfoundry/java-buildpack

## License

MIT
