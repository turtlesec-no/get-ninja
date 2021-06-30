# Get Ninja GitHub Action

Gets the most recent Ninja

**Works on**: Linux, Windows and MacOS 

## Inputs

No inputs

## Outputs

### `version`

The version string from "ninja --version"

## Example usage

~~~~
    - name: Install Ninja
      id: ninja
      uses: turtlesec-no/get-ninja@main

    - name: Ninja version
      run: echo "${{ steps.ninja.outputs.version }}"
~~~~
