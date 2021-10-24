# garbanzo
This project is an e2e containerized local self-hosted runner + local hosted nexsus + action flow C++ CI poc

# garbanzo docker action

This action run a C++ build process for the C++ file designated by the inputs.

## Inputs

## `source-to-build`

**Required** The name of the person to greet. Default `"main.cpp"`.

## Outputs

## `time`

The time we compelete build.

## Example usage

uses: actions/garbanzo@v1
with:
  source-to-build: 'main.cpp'