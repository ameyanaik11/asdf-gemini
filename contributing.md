# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test gemini https://github.com/ameyanaik11/asdf-gemini.git "gemini --version"
```

Tests are automatically run in GitHub Actions on push and PR.
