# cli-ebrands

## Overview

`cli-ebrands` standardises our local development environment and process when working with Pantheon.

## Pre-installation checklist

- You have a Pantheon account
- Your `$SHELL` is either `bash` or `zsh`

## Installation

```sh
git clone git@github.com:eBrandsAU/cli-ebrands.git ~/workspace/cli-ebrands
ln -fs ~/workspace/cli-ebrands/bin/eb /usr/local/bin/eb
```

## First run

```sh
eb setup
```

## Staring a new project
```sh
eb init
eb pull
eb start
```

## Usage

```sh
usage: eb <command>
# Run `eb` for more details
```
