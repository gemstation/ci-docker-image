# ci-docker-image

This Docker image contains the base necessary to run CI builds for [Gemforge](https://github.com/gemstation/gemforge).

This sets up:

* Node.js
* Foundry
* Solidity v0.8.21

The latest image is always available at: https://ghcr.io/gemstation/ci-docker-image:latest

## Development

Ensure you have Docker installed locally.

Build the image:

```shell
make build
```

Run the image locally:

```zsh
make run
```

## Publishing the image

In case you need to make any updates to this image, push changes to `master` (or any other) branch and manually trigger the `Build and Publish Docker` workflow in github actions.

