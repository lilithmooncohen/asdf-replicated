<div align="center">

# asdf-replicated [![Build](https://github.com/lilithmooncohen/asdf-replicated/actions/workflows/build.yml/badge.svg)](https://github.com/lilithmooncohen/asdf-replicated/actions/workflows/build.yml) [![Lint](https://github.com/lilithmooncohen/asdf-replicated/actions/workflows/lint.yml/badge.svg)](https://github.com/lilithmooncohen/asdf-replicated/actions/workflows/lint.yml)

[replicated](https://docs.replicated.com/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add replicated
# or
asdf plugin add replicated https://github.com/lilithmooncohen/asdf-replicated.git
```

replicated:

```shell
# Show all installable versions
asdf list-all replicated

# Install specific version
asdf install replicated latest

# Set a version globally (on your ~/.tool-versions file)
asdf global replicated latest

# Now replicated commands are available
replicated version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/lilithmooncohen/asdf-replicated/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Lily Cohen](https://github.com/lilithmooncohen/)
