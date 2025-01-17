# 33670

## Current behavior

When having an `oci_pull` dependency in a `MODULE.bazel` for a docker image that has a tag and a digest configured then renovate is not updating this digest even so there is a newer one and it is found according to the logs.

## Expected behavior

Renovate should update the `digest` field on the `MODULE.bazel` file.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/33670
