TODO replace below
- GH_USER - github username
- PRODUCT - JetBrains product tool name

# asdf-jetbrains-<some-product> [![Build](https://github.com/GH_USER/asdf-jetbrains-PRODUCT/actions/workflows/build.yml/badge.svg)](https://github.com/GH_USER/asdf-jetbrains-PRODUCT/actions/workflows/build.yml) [![Lint](https://github.com/mbutov/asdf-jetbrains-PRODUCT/actions/workflows/lint.yml/badge.svg)](https://github.com/mbutov/asdf-jetbrains-idea/actions/workflows/lint.yml)

[jetbrains-PRODUCT](https://github.com/GH_USER/asdf-jetbrains-PRODUCT) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add jetbrains-PRODUCT
# or
asdf plugin add jetbrains-PRODUCT https://github.com/GH_USER/asdf-jetbrains-PRODUCT.git
```

jetbrains-PRODUCT:

```shell
# Show all installable versions
asdf list-all jetbrains-PRODUCT

# Install specific version
asdf install jetbrains-PRODUCT latest

# Set a version globally (on your ~/.tool-versions file)
asdf global jetbrains-PRODUCT latest

# Now jetbrains-PRODUCT commands are available
idea.sh --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mbutov/asdf-jetbrains-idea/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Maxim Butov](https://github.com/mbutov/)
