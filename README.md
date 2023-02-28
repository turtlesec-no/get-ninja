# Get Ninja GitHub Action
[![CI](https://github.com/turtlesec-no/get-ninja/actions/workflows/main.yml/badge.svg)](https://github.com/turtlesec-no/get-ninja/actions/workflows/main.yml)

Gets the most recent Ninja

**Works on**: Linux, Windows and MacOS 

## Inputs

No inputs

## Outputs

### `version`

The version string from "ninja --version"

## Example usage

~~~~yaml
- name: Install Ninja
  id: ninja
  uses: turtlesec-no/get-ninja@main

- name: Ninja version
  run: echo "${{ steps.ninja.outputs.version }}"
~~~~
