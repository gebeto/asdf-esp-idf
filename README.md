<div align="center">

# WIP! asdf-esp-idf [![Build](https://github.com/gebeto/asdf-esp-idf/actions/workflows/build.yml/badge.svg)](https://github.com/gebeto/asdf-esp-idf/actions/workflows/build.yml) [![Lint](https://github.com/gebeto/asdf-esp-idf/actions/workflows/lint.yml/badge.svg)](https://github.com/gebeto/asdf-esp-idf/actions/workflows/lint.yml)

[esp-idf](https://github.com/gebeto/asdf-esp-idf) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add esp-idf
# or
asdf plugin add esp-idf https://github.com/gebeto/asdf-esp-idf.git
```

esp-idf:

```shell
# Show all installable versions
asdf list-all esp-idf

# Install specific version
asdf install esp-idf latest

# Set a version globally (on your ~/.tool-versions file)
asdf global esp-idf latest

# Now esp-idf commands are available
idf.py --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gebeto/asdf-esp-idf/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Yaroslav Nychkalo](https://github.com/gebeto/)
