<div align="center">

# asdf-apko [![Build](https://github.com/omissis/asdf-apko/actions/workflows/build.yml/badge.svg)](https://github.com/omissis/asdf-apko/actions/workflows/build.yml) [![Lint](https://github.com/omissis/asdf-apko/actions/workflows/lint.yml/badge.svg)](https://github.com/omissis/asdf-apko/actions/workflows/lint.yml)

[apko](https://github.com/chainguard-dev/apko/tree/main/docs) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `melange`: while not strictly required, apko needs apks built by melange in order to package them into an image

# Install

Plugin:

```shell
asdf plugin add apko
# or
asdf plugin add apko https://github.com/omissis/asdf-apko.git
```

apko:

```shell
# Show all installable versions
asdf list-all apko

# Install specific version
asdf install apko latest

# Set a version globally (on your ~/.tool-versions file)
asdf global apko latest

# Now apko commands are available
apko --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/omissis/asdf-apko/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Claudio Beatrice](https://github.com/omissis/)
