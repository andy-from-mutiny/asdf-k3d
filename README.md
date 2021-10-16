# asdf-k3d [![Build](https://github.com/andy-from-mutiny/asdf-k3d/actions/workflows/build.yml/badge.svg)](https://github.com/andy-from-mutiny/asdf-k3d/actions/workflows/build.yml) [![Lint](https://github.com/andy-from-mutiny/asdf-k3d/actions/workflows/lint.yml/badge.svg)](https://github.com/andy-from-mutiny/asdf-k3d/actions/workflows/lint.yml)

[k3d](https://k3d.io/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add k3d https://github.com/andy-from-mutiny/asdf-k3d.git
```

k3d:

```shell
# Show all installable versions
asdf list-all k3d

# Install specific version
asdf install k3d latest

# Set a version globally (on your ~/.tool-versions file)
asdf global k3d latest

# Now k3d commands are available
k3d --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/andy-from-mutiny/asdf-k3d/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Andy Young](https://github.com/andy-from-mutiny/)
