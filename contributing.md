# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test zephyr-sdk https://github.com/tangybbq/asdf-zephyr-sdk.git "arm-zephyr-eabi-gcc --version"
```

Tests are automatically run in GitHub Actions on push and PR.
