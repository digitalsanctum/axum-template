# Usage

## Generating a new project

If you've cloned the repository, run the following to generate a new project:

```shell
cargo generate --path axum-template --name new-project-name
```

where `axum-template` is the path to this template and `new-project-name` is the name of the new project.

Otherwise, you can generate a new project directly from GitHub:

```shell
cargo generate --git digitalsanctum/axum-template --name new-project-name
```

## Favorite

Add the following to `$CARGO_HOME` to make generating a new project easier:
```toml
[favorites.axum]
path = "/path/to/axum-template"
vcs = "None"
init = false
overwrite = true
```

```shell
cargo generate axum --name new-project-name
```

Read more about favorites [here](https://cargo-generate.github.io/cargo-generate/favorites.html).

## Companion Script

A companion script, [scripts/generate.sh](scripts/generate.sh), is provided to make generating a new project easier. 


## References

- [Cargo Generate Documentation](https://cargo-generate.github.io/cargo-generate/)