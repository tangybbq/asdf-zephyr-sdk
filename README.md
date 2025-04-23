<div align="center">

# asdf-zephyr-sdk [![Build](https://github.com/tangybbq/asdf-zephyr-sdk/actions/workflows/build.yml/badge.svg)](https://github.com/tangybbq/asdf-zephyr-sdk/actions/workflows/build.yml) [![Lint](https://github.com/tangybbq/asdf-zephyr-sdk/actions/workflows/lint.yml/badge.svg)](https://github.com/tangybbq/asdf-zephyr-sdk/actions/workflows/lint.yml)

[zephyr-sdk](https://github.com/zephyrproject-rtos/sdk-ng) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add zephyr-sdk
# or
asdf plugin add zephyr-sdk https://github.com/tangybbq/asdf-zephyr-sdk.git
```

zephyr-sdk:

```shell
# Show all installable versions
asdf list-all zephyr-sdk

# Install specific version
asdf install zephyr-sdk latest

# Set a version globally (on your ~/.tool-versions file)
asdf global zephyr-sdk latest

# Now zephyr-sdk commands are available
arm-zephyr-eabi-gcc --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tangybbq/asdf-zephyr-sdk/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [David Brown](https://github.com/tangybbq/)
