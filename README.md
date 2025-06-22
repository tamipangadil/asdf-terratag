<div align="center">

# asdf-terratag [![Build](https://github.com/tamipangadil/asdf-terratag/actions/workflows/build.yml/badge.svg)](https://github.com/tamipangadil/asdf-terratag/actions/workflows/build.yml) [![Lint](https://github.com/tamipangadil/asdf-terratag/actions/workflows/lint.yml/badge.svg)](https://github.com/tamipangadil/asdf-terratag/actions/workflows/lint.yml)

[terratag](https://www.terratag.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add terratag
# or
asdf plugin add terratag https://github.com/tamipangadil/asdf-terratag.git
```

terratag:

```shell
# Show all installable versions
asdf list-all terratag

# Install specific version
asdf install terratag latest

# Set a version globally (on your ~/.tool-versions file)
asdf global terratag latest

# Now terratag commands are available
terratag --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tamipangadil/asdf-terratag/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tami Pangadil](https://github.com/tamipangadil/)
