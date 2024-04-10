<div align="center">

# asdf-go [![Build](https://github.com/sylvainmetayer/asdf-go/actions/workflows/build.yml/badge.svg)](https://github.com/sylvainmetayer/asdf-go/actions/workflows/build.yml) [![Lint](https://github.com/sylvainmetayer/asdf-go/actions/workflows/lint.yml/badge.svg)](https://github.com/sylvainmetayer/asdf-go/actions/workflows/lint.yml)

[go](https://github.com/golang/go) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add go
# or
asdf plugin add go https://github.com/sylvainmetayer/asdf-go.git
```

go:

```shell
# Show all installable versions
asdf list-all go

# Install specific version
asdf install go latest

# Set a version globally (on your ~/.tool-versions file)
asdf global go latest

# Now go commands are available
go version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/sylvainmetayer/asdf-go/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Sylvain](https://github.com/sylvainmetayer/)
