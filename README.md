# apk-repository
My alpine linux apk package repo

[![stability-unstable](https://img.shields.io/badge/stability-unstable-yellow.svg)][stability]
[![Build Status](https://circleci.com/gh/orangemug/apk-repository.png?style=shield)][circleci]

[stability]:   https://github.com/orangemug/stability-badges#unstable
[circleci]:    https://circleci.com/gh/orangemug/apk-repository



## Usage
Install any of the packages from repository with

```sh
apk add \
  --allow-untrusted \
  --repository 'https://github.com/orangemug/apk-repository/releases/download/master' \
  <package-name>

```

