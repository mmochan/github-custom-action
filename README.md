![.github/workflows/main.yml](https://github.com/mmochan/github-custom-action/workflows/.github/workflows/main.yml/badge.svg)

# Hello world docker action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Deacepticons peeps'# github-custom-action
