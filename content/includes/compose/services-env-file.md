The `env_file` attribute is used to specify one or more files that contain environment variables to be passed to the containers.

Note that the `env_file` attribute is not intended for 
[variable interpolation](https://github.com/compose-spec/compose-spec/blob/main/spec.md#interpolation)
within a Compose file. To handle variable interpolation, use the `--env-file` flag with the `docker compose` command instead.
