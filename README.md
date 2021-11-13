<div align="center">

# asdf-protoc [![Build](https://github.com/nissy-dev/asdf-protoc/actions/workflows/build.yml/badge.svg)](https://github.com/nissy-dev/asdf-protoc/actions/workflows/build.yml) [![Lint](https://github.com/nissy-dev/asdf-protoc/actions/workflows/lint.yml/badge.svg)](https://github.com/nissy-dev/asdf-protoc/actions/workflows/lint.yml)

</div>

[Protocol Buffers (protoc)](https://github.com/protocolbuffers/protobuf) plugin for the [asdf version manager](https://asdf-vm.com).

This repository was created based on [asdf-plugin-template](https://github.com/asdf-vm/asdf-plugin-template/) because it seem [paxosglobal/asdf-protoc](https://github.com/paxosglobal/asdf-protoc) is not so maintained...

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add protoc
# or
asdf plugin add protoc https://github.com/nissy-dev/asdf-protoc.git
```

protoc:

```shell
# Show all installable versions
asdf list-all protoc

# Install specific version
asdf install protoc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global protoc latest

# Now protoc commands are available
protoc --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nissy-dev/asdf-protoc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Daiki Nishikawa](https://github.com/nissy-dev/)
