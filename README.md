<div align="center">

# asdf-gemini [![Build](https://github.com/ameyanaik11/asdf-gemini/actions/workflows/build.yml/badge.svg)](https://github.com/ameyanaik11/asdf-gemini/actions/workflows/build.yml) [![Lint](https://github.com/ameyanaik11/asdf-gemini/actions/workflows/lint.yml/badge.svg)](https://github.com/ameyanaik11/asdf-gemini/actions/workflows/lint.yml)

[gemini](https://github.com/ameyanaik11/asdf-gemini) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add gemini
# or
asdf plugin add gemini https://github.com/ameyanaik11/asdf-gemini.git
```

gemini:

```shell
# Show all installable versions
asdf list-all gemini

# Install specific version
asdf install gemini latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gemini latest

# Now gemini commands are available
gemini --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ameyanaik11/asdf-gemini/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ameya Naik](https://github.com/ameyanaik11/)
