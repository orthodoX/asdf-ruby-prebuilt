<div align="center">

# asdf-ruby-prebuilt [![Build](https://github.com/orthodoX/asdf-ruby-prebuilt/actions/workflows/build.yml/badge.svg)](https://github.com/orthodoX/asdf-ruby-prebuilt/actions/workflows/build.yml) [![Lint](https://github.com/orthodoX/asdf-ruby-prebuilt/actions/workflows/lint.yml/badge.svg)](https://github.com/orthodoX/asdf-ruby-prebuilt/actions/workflows/lint.yml)

[ruby-prebuilt](https://github.com/orthodoX/asdf-ruby-prebuilt) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add ruby-prebuilt
# or
asdf plugin add ruby-prebuilt https://github.com/orthodoX/asdf-ruby-prebuilt.git
```

ruby-prebuilt:

```shell
# Show all installable versions
asdf list-all ruby-prebuilt

# Install specific version
asdf install ruby-prebuilt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ruby-prebuilt latest

# Now ruby-prebuilt commands are available
ruby --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/orthodoX/asdf-ruby-prebuilt/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Slobodan Erak](https://github.com/orthodoX/)
