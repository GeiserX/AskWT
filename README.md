![img](https://github.com/GeiserX/askwt/blob/main/extra/logo.jpg?raw=true)
# AskWT

[![askwt compliant](https://img.shields.io/github/license/GeiserX/askwt)](https://github.com/GeiserX/askwt/blob/main/LICENSE)

This project is a Telegram bot assistant to help you prepare for weekend meetings. It uses ChatGPT-4o to write contextual notes for each paragraph, with configurable inputs.

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [Maintainers](#maintainers)
- [Contributing](#contributing)

## Install

This project uses a [Docker container](https://hub.docker.com/repository/docker/drumsergio/askwt) to deploy a Telegram Bot handler.

```sh
$ docker run --name askwt -e TOKEN=[TOKEN] -e OPENAI_API_KEY=[KEY] drumsergio/askwt
```

Docker Hub image available at [drumsergio/askwt](https://hub.docker.com/repository/docker/drumsergio/askwt).

## Usage

Use the command `/start` and follow the prompts

## Maintainers

[@GeiserX](https://github.com/GeiserX).

## Contributing

Feel free to dive in! [Open an issue](https://github.com/GeiserX/askwt/issues/new) or submit PRs.

AskWT follows the [Contributor Covenant](http://contributor-covenant.org/version/2/1/) Code of Conduct.

### Contributors

This project exists thanks to all the people who contribute. 
<a href="https://github.com/GeiserX/askwt/graphs/contributors"><img src="https://opencollective.com/askwt/contributors.svg?width=890&button=false" /></a>


