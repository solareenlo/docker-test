# paperist/alpine-texlive-ja

[![Docker Automated build](https://img.shields.io/docker/automated/paperist/alpine-texlive-ja.svg)](https://hub.docker.com/r/paperist/alpine-texlive-ja/)
[![Docker Image Size](https://images.microbadger.com/badges/image/paperist/alpine-texlive-ja.svg)](https://microbadger.com/images/paperist/alpine-texlive-ja "Get your own image badge on microbadger.com")
[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg)](https://github.com/RichardLitt/standard-readme)

> Minimal TeX Live image for Japanese based on alpine

Forked from [umireon/docker-texci] \(under the MIT License\).

[umireon/docker-texci]: https://github.com/umireon/docker-texci

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [Contribute](#contribute)
- [License](#license)

## Install

```bash
docker pull paperist/alpine-texlive-ja
```

## Usage

```bash
$ docker run --rm -it -v $PWD:/workdir paperist/alpine-texlive-ja
$ latexmk -C main.tex && latexmk main.tex && latexmk -c main.tex
```

## Contribute

PRs accepted.

## License

MIT © 3846masa



