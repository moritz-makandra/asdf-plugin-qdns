<div align="center">

# asdf-qdns [![Build](https://github.com/moritz-makandra/asdf-qdns/actions/workflows/build.yml/badge.svg)](https://github.com/moritz-makandra/asdf-qdns/actions/workflows/build.yml) [![Lint](https://github.com/moritz-makandra/asdf-qdns/actions/workflows/lint.yml/badge.svg)](https://github.com/moritz-makandra/asdf-qdns/actions/workflows/lint.yml)


[qdns](https://github.com/natesales/q) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add qdns https://github.com/moritz-makandra/asdf-plugin-qdns.git
```

qdns:

```shell
# Show all installable versions
asdf list-all qdns

# Install specific version
asdf install qdns latest

# Set a version globally (on your ~/.tool-versions file)
asdf global qdns latest

# Now qdns commands are available
q --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/moritz-makandra/asdf-qdns/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Moritz Kraus](https://github.com/moritz-makandra/)
