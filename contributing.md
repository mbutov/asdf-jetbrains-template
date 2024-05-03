# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test jetbrains-xxx https://github.com/yyy/asdf-jetbrains-xxx.git "tool.sh --version"
```

Tests are automatically run in GitHub Actions on push and PR.
