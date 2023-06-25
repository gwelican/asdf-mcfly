<div align="center">

# asdf-mcfly [![Build](https://github.com/gwelican/asdf-mcfly/actions/workflows/build.yml/badge.svg)](https://github.com/gwelican/asdf-mcfly/actions/workflows/build.yml) [![Lint](https://github.com/gwelican/asdf-mcfly/actions/workflows/lint.yml/badge.svg)](https://github.com/gwelican/asdf-mcfly/actions/workflows/lint.yml)

[mcfly](https://github.com/cantino/mcfly) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add mcfly
# or
asdf plugin add mcfly https://github.com/gwelican/asdf-mcfly.git
```

mcfly:

```shell
# Show all installable versions
asdf list-all mcfly

# Install specific version
asdf install mcfly latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mcfly latest

# Now mcfly commands are available
mcfly --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gwelican/asdf-mcfly/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Peter Varsanyi](https://github.com/gwelican/)
