<div align="center">

# asdf-jase64 [![Build](https://github.com/ogontaro/asdf-jase64/actions/workflows/build.yml/badge.svg)](https://github.com/ogontaro/asdf-jase64/actions/workflows/build.yml) [![Lint](https://github.com/ogontaro/asdf-jase64/actions/workflows/lint.yml/badge.svg)](https://github.com/ogontaro/asdf-jase64/actions/workflows/lint.yml)

[jase64](https://github.com/ogontaro/jase64) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add jase64
# or
asdf plugin add jase64 https://github.com/ogontaro/asdf-jase64.git
```

jase64:

```shell
# Show all installable versions
asdf list-all jase64

# Install specific version
asdf install jase64 latest

# Set a version globally (on your ~/.tool-versions file)
asdf global jase64 latest

# Now jase64 commands are available
jase64 --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ogontaro/asdf-jase64/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [ogontaro](https://github.com/ogontaro/)
