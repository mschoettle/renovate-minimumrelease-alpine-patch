# 42894

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

When using a Docker image with a variant, such as `node:24.14.0-alpine3.23` and `minimumReleaseAge`, the image version does not get updated for patch updates.

See: https://github.com/mschoettle/renovate-minimumrelease-alpine-patch/pull/4

For minor updates it seems to work for some reason: https://github.com/mschoettle/renovate-minimumrelease-alpine-patch/pull/5

## Expected behavior

The image should be updated to v24.14.1 as well.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/42894
