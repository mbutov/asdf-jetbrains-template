TODO replace below
- GITHUB_USER - github username
- PRODUCT - JetBrains product tool name

# asdf-jetbrains-<some-product> [![Build](https://github.com/GITHUB_USER/asdf-jetbrains-PRODUCT/actions/workflows/build.yml/badge.svg)](https://github.com/GITHUB_USER/asdf-jetbrains-PRODUCT/actions/workflows/build.yml) [![Lint](https://github.com/GITHUB_USER/asdf-jetbrains-PRODUCT/actions/workflows/lint.yml/badge.svg)](https://github.com/GITHUB_USER/asdf-jetbrains-PRODUCT/actions/workflows/lint.yml)

[jetbrains-PRODUCT](https://github.com/GITHUB_USER/asdf-jetbrains-PRODUCT) plugin for the [asdf version manager](https://asdf-vm.com).

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `jq` - commandline JSON processor

# Install

Plugin:

```shell
asdf plugin add PRODUCT
# or
asdf plugin add PRODUCT https://github.com/GITHUB_USER/asdf-jetbrains-PRODUCT.git
```

PRODUCT:

```shell
# Show all installable versions
asdf list-all PRODUCT

# Install specific version
asdf install PRODUCT latest

# Set a version globally (on your ~/.tool-versions file)
asdf global PRODUCT latest

# Now jetbrains-PRODUCT commands are available
PRODUCT --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mbutov/asdf-jetbrains-idea/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [GITHUB_USER](https://github.com/GITHUB_USER/)
