# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test helix https://github.com/nklmilojevic/asdf-helix.git "hx --version"
```

Tests are automatically run in GitHub Actions on push and PR.
