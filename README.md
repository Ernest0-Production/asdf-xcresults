<div align="center">

# asdf-xcresults [![Build](https://github.com/Ernest0-Production/asdf-xcresults/actions/workflows/build.yml/badge.svg)](https://github.com/Ernest0-Production/asdf-xcresults/actions/workflows/build.yml) [![Lint](https://github.com/Ernest0-Production/asdf-xcresults/actions/workflows/lint.yml/badge.svg)](https://github.com/Ernest0-Production/asdf-xcresults/actions/workflows/lint.yml)

[xcresults](https://github.com/eroshenkoam/xcresults/blob/main/README.md) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-xcresults  ](#asdf-xcresults--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl` and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add xcresults
# or
asdf plugin add xcresults https://github.com/Ernest0-Production/asdf-xcresults.git
```

xcresults:

```shell
# Show all installable versions
asdf list-all xcresults

# Install specific version
asdf install xcresults latest

# Set a version globally (on your ~/.tool-versions file)
asdf global xcresults latest

# Now xcresults commands are available
xcresults --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Ernest0-Production/asdf-xcresults/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ernest](https://github.com/Ernest0-Production/)
