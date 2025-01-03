<div align="center">

# asdf-sesh [![Build](https://github.com/marcellmartini/asdf-sesh/actions/workflows/build.yml/badge.svg)](https://github.com/marcellmartini/asdf-sesh/actions/workflows/build.yml) [![Lint](https://github.com/marcellmartini/asdf-sesh/actions/workflows/lint.yml/badge.svg)](https://github.com/marcellmartini/asdf-sesh/actions/workflows/lint.yml)

[sesh](https://github.com/joshmedeski/sesh) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add sesh
# or
asdf plugin add sesh https://github.com/marcellmartini/asdf-sesh.git
```

sesh:

```shell
# Show all installable versions
asdf list-all sesh

# Install specific version
asdf install sesh latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sesh latest

# Now sesh commands are available
sesh --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/marcellmartini/asdf-sesh/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Marcell Martini](https://github.com/marcellmartini/)
