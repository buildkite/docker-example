# Buildkite Docker Compose Pipeline Example

[![Build status](https://badge.buildkite.com/e79a007c073e15bac313d9debb761cfb97bbcf305141c246c4.svg?branch=main)](https://buildkite.com/buildkite/docker-example)
[![Add to Buildkite](https://buildkite.com/button.svg)](https://buildkite.com/new)

This repository is an example [Buildkite](https://buildkite.com/) pipeline for running a simple bash script, [script.sh](script.sh), but from within Docker Compose. It's similar to [our bash-example pipeline](https://github.com/buildkite/bash-example), but using [the docker-compose plugin](https://github.com/buildkite/docker-compose-buildkite-plugin).

The script simply prints some debug output with an inline image, some artifacts, and exits with a success code (0).

<a href="https://buildkite.com/buildkite/docker-example/builds/latest?branch=main"><img width="1504" alt="Screenshot of Buildkite docker example pipeline" src=".buildkite/screenshot.png" /></a>

Click the screenshot above to see this pipeline in Buildkite, check out our [Getting Started Guide](https://buildkite.com/docs/guides/getting-started) for step-by-step instructions on how to get this running, or click _Add to Buildkite_ above to add this project to Buildkite and try it out yourself.

## License

See [License.md](License.md) (MIT)
