<div align="center">

# asdf-trippy [![Build](https://github.com/carbans/asdf-trippy/actions/workflows/build.yml/badge.svg)](https://github.com/carbans/asdf-trippy/actions/workflows/build.yml) [![Lint](https://github.com/carbans/asdf-trippy/actions/workflows/lint.yml/badge.svg)](https://github.com/carbans/asdf-trippy/actions/workflows/lint.yml)

[trippy](https://trippy.rs/start/getting-started/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add trippy
# or
asdf plugin add trippy https://github.com/carbans/asdf-trippy.git
```

trippy:

```shell
# Show all installable versions
asdf list-all trippy

# Install specific version
asdf install trippy latest

# Set a version globally (on your ~/.tool-versions file)
asdf global trippy latest

# Now trippy commands are available
trip --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/carbans/asdf-trippy/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Carlos Latorre](https://github.com/carbans/)
