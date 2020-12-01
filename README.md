This is a remark preset used across DNB projects.

It is based on [remark-preset-lint-recommended](https://github.com/remarkjs/remark-lint/tree/main/packages/remark-preset-lint-recommended) with some additions on it's own.

You probably won't need this ;)

## Installation

```shell script
npm install -D git@github.com:davidsneighbour/remark-preset-lint-dnb.git
```

## Configuration

Put the following into `.remarkrc` in the root of your project. Remove the `write-good` line if you want to ensure the quality of text.

```json
{
  "plugins": [
    "remark-preset-lint-dnb",
    ["remark-lint-write-good", false]
  ]
}
```
