# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test sesh https://github.com/marcellmartini/asdf-sesh.git "sesh --help"
```

Tests are automatically run in GitHub Actions on push and PR.
