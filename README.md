# Buildkite Docker Compose Pipeline Example

[![Build status](https://badge.buildkite.com/e79a007c073e15bac313d9debb761cfb97bbcf305141c246c4.svg?branch=main)](https://buildkite.com/buildkite/docker-example/builds/latest?branch=main)
[![Add to Buildkite](https://img.shields.io/badge/Add%20to%20Buildkite-14CC80)](https://buildkite.com/new)

This repository is an example [Buildkite](https://buildkite.com/) pipeline that runs a simple bash script, [script.sh](script.sh), using [Docker Compose](https://github.com/buildkite/docker-compose-buildkite-plugin).

👉 **See this example in action:** [buildkite/docker-example](https://buildkite.com/buildkite/docker-example/builds/latest?branch=main)

[![Add to Buildkite](https://buildkite.com/button.svg)](https://buildkite.com/new)

<a href="https://buildkite.com/buildkite/docker-example/builds/latest?branch=main">
  <img width="1504" alt="Screenshot of Buildkite docker example pipeline" src=".buildkite/screenshot.png" />
</a>

<!-- docs:start -->

## How it works

This example uses the [Docker Compose plugin](https://github.com/buildkite/docker-compose-buildkite-plugin) to:

- Launch containers
- Run [script.sh](script.sh), which prints output, includes an inline image, generates artifacts, and exits cleanly

This example is functionally similar to the [bash example](https://github.com/buildkite/bash-example), but runs in a containerized environment.

<!-- docs:end -->

## License

See [LICENSE.md](LICENSE.md) (MIT)
