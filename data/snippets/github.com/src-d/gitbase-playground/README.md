[![Build Status](https://travis-ci.org/src-d/gitbase-playground.svg)](https://travis-ci.org/src-d/gitbase-playground)
[![codecov.io](https://codecov.io/github/src-d/gitbase-playground/coverage.svg)](https://codecov.io/github/src-d/gitbase-playground)
![unstable](https://svg-badge.appspot.com/badge/stability/unstable?a)

# Gitbase Playground

Web application to query git repositories using SQL. Powered by [gitbase](https://github.com/src-d/gitbase).

![Screenshot](.github/screenshot.png?raw=true)


# Usage

## Dependencies

The playground will run the queries against a [gitbase](https://github.com/src-d/gitbase) server, and will request UASTs to a [bblfsh](https://doc.bblf.sh/) server; both should be accessible for the playground; you can check its default [configuration values](docs/CONTRIBUTING.md#configuration).


## Run the Playground

You can run the app from a docker image, a released binary or installing and building the project.

Once the server is running &ndash;with its default values&ndash;, it will be accessible through: http://localhost:8080

Read [more about how to run bblfsh and gitbase dependencies](docs/quickstart.md).

### Run with Docker

```bash
$ docker pull srcd/gitbase-playground:latest
$ docker run -d \
    --publish 8080:8080 \
    --link gitbase \
    --env GITBASEPG_ENV=dev \
    --env GITBASEPG_DB_CONNECTION="gitbase@tcp(gitbase:3306)/none?maxAllowedPacket=4194304" \
    --name gitbasePlayground \
    srcd/gitbase-playground:latest
```


### Run the Binary

Download a binary from our [releases section](https://github.com/src-d/gitbase-playground/releases), and run it:

```bash
$ /download/path/gitbase-playground
```


# Contribute

[Contributions](https://github.com/src-d/gitbase-playground/issues) are more than welcome, if you are interested please take a look to our [Contributing Guidelines](docs/CONTRIBUTING.md). You have more information on how to run it locally for [development purposes here](docs/CONTRIBUTING.md#development).


# Code of Conduct

All activities under source{d} projects are governed by the [source{d} code of conduct](https://github.com/src-d/guide/blob/master/.github/CODE_OF_CONDUCT.md).


## License

GPL v3.0, see [LICENSE](LICENSE)
