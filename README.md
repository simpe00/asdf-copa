<div align="center">

# asdf-copa [![Build](https://github.com/simpe00/asdf-copa/actions/workflows/build.yml/badge.svg)](https://github.com/simpe00/asdf-copa/actions/workflows/build.yml) [![Lint](https://github.com/simpe00/asdf-copa/actions/workflows/lint.yml/badge.svg)](https://github.com/simpe00/asdf-copa/actions/workflows/lint.yml)

[copa](https://github.com/simpe00/asdf-copa) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add copa
# or
asdf plugin add copa https://github.com/simpe00/asdf-copa.git
```

copa:

```shell
# Show all installable versions
asdf list-all copa

# Install specific version
asdf install copa latest

# Set a version globally (on your ~/.tool-versions file)
asdf global copa latest

# Now copa commands are available
copa --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/simpe00/asdf-copa/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Simon Peppel](https://github.com/simpe00/)
