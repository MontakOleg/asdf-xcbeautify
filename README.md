<div align="center">

# asdf-xcbeautify [![Build](https://github.com/MontakOleg/asdf-xcbeautify/actions/workflows/build.yml/badge.svg)](https://github.com/MontakOleg/asdf-xcbeautify/actions/workflows/build.yml) [![Lint](https://github.com/MontakOleg/asdf-xcbeautify/actions/workflows/lint.yml/badge.svg)](https://github.com/MontakOleg/asdf-xcbeautify/actions/workflows/lint.yml)

[xcbeautify](https://github.com/cpisciotta/xcbeautify) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add xcbeautify
# or
asdf plugin add xcbeautify https://github.com/MontakOleg/asdf-xcbeautify.git
```

xcbeautify:

```shell
# Show all installable versions
asdf list-all xcbeautify

# Install specific version
asdf install xcbeautify latest

# Set a version globally (on your ~/.tool-versions file)
asdf global xcbeautify latest

# Now xcbeautify commands are available
xcbeautify --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MontakOleg/asdf-xcbeautify/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Oleg Montak](https://github.com/MontakOleg/)
