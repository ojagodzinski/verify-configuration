# allegro-actions/verify-configuration

This action verifies your config files.

## Basic usage:

```yaml
steps:
  - uses: actions/checkout@v2
    with:
      ref: ${{ github.head_ref }}

  - uses: allegro-actions/verify-configuration@v1
    with:
      host: configurataion-service-hostname
      service: service-name
```
Please notice that you should check out a branch, not a commit.
Therefore, according to the [docs](https://docs.github.com/en/actions/reference/context-and-expression-syntax-for-github-actions#github-context),
available workflow events are: `pull_request`, `pull_request_target`.

## Use cases

Validate your PR before merging ;)
