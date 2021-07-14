# allegro-actions/verify-configuration

This action verifies your config files.

## Basic usage:

```yaml
steps:
  - uses: allegro-actions/verify-configuration@v1
    with:
      host: http://configurataion-service:8080
      service: service-name
```

## Use cases

Validate your PR before merging ;)
