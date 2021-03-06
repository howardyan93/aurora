![aurora](./aurora.png "aurora")

# aurora

[![Build Status](https://travis-ci.org/Luxurioust/aurora.svg?branch=master)](https://travis-ci.org/Luxurioust/aurora)
[![Code Coverage](https://codecov.io/gh/Luxurioust/aurora/branch/master/graph/badge.svg)](https://codecov.io/gh/Luxurioust/aurora)
[![Go Report Card](https://goreportcard.com/badge/github.com/Luxurioust/aurora)](https://goreportcard.com/report/github.com/Luxurioust/aurora)
[![GoDoc](https://godoc.org/github.com/Luxurioust/aurora?status.svg)](https://godoc.org/github.com/Luxurioust/aurora)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](https://github.com/Luxurioust/aurora/blob/master/LICENSE)

## Overview

aurora is a web-based Beanstalk queue server console written in Go and works on macOS, Linux and Windows machines. Main idea behind using Go for backend development is to utilize ability of the compiler to produce zero-dependency binaries for multiple platforms. aurora was created as an attempt to build very simple and portable application to work with local or remote Beanstalk server.

## Features

- Cross-platform support macOS/Linux/Windows 32/64-bit
- Simple installation (distributed as a single binary)
- Zero dependencies
- Common list of servers in config for all users + optional Basic Auth
- Each user can add its own personal Beanstalk server
- Full list of available tubes
- Complete statistics about jobs in tubes
- Realtime auto-update with highlighting of changed values
- You can view jobs in ready/delayed/buried states in every tube
- You can add/kick/delete jobs in every tube
- You can select multiple tubes by regExp and clear them
- You can move jobs between tubes
- Ability to Pause tubes
- Search jobs data field
- Customizable UI (code highlighter, choose columns, edit auto refresh seconds, pause tube seconds)

## Installation

[Precompiled binaries](https://github.com/Luxurioust/aurora/releases) for supported 
operating systems are available.

## Contributing

Contributions are welcome! Open a pull request to fix a bug, or open an issue to discuss a new feature or change.

## Credits

Client for beanstalk use [kr/beanstalk](https://github.com/kr/beanstalk)

TOML parser use [BurntSushi/toml](https://github.com/BurntSushi/toml)

Web UI originally by [ptrofimov/beanstalk_console](https://github.com/ptrofimov/beanstalk_console)

The logo is originally by [Ali Irawan](http://www.solusiteknologi.co.id/using-supervisord-beanstalkd-laravel/). This artwork is an adaptation.

## Licenses

This program is under the terms of the MIT License. See [LICENSE](https://github.com/Luxurioust/aurora/blob/master/LICENSE) for the full license text.