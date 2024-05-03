# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test PRODUCT https://github.com/GITHUB_USER/asdf-jetbrains-PRODUCT.git "PRODUCT.sh --version"
```

Tests are automatically run in GitHub Actions on push and PR.
