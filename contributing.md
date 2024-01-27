# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test jase64 https://github.com/ogontaro/asdf-jase64.git "jase64 --help"
```

Tests are automatically run in GitHub Actions on push and PR.
