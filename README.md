<div align="center">

# asdf-jet
[![GitHub Actions Test Status][ci-actions-test-badge]][ci-actions-test]
[![GitHub Actions Lint Status][ci-actions-lint-badge]][ci-actions-lint]
[![CircleCI Lint Status][ci-circleci-lint-badge]][ci-circleci-lint]
[![License][license-badge]][license]

[ASDF][asdf-website] plugin for [jet][jet-repo].

</div>

## Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [License](#license)

## Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

## Install

Install the plugin:

```shell
asdf plugin add jet https://github.com/rynkowsg/asdf-jet.git
```

Install jet:

```shell
# Show all installable versions
asdf list-all jet

# Install specific version
asdf install jet latest

# Set a version globally (on your ~/.tool-versions file)
asdf global jet latest

# Now jet tool is available
jet --help
```

Check [asdf][asdf-repo] readme for more instructions on how to install & manage versions.

## License

See [LICENSE](LICENSE) © [Grzegorz Rynkowski][gh-profile-rynkowsg]

[asdf-repo]: https://github.com/asdf-vm/asdf
[asdf-website]: https://asdf-vm.com
[ci-actions-lint-badge]: https://github.com/rynkowsg/asdf-jet/actions/workflows/lint.yml/badge.svg
[ci-actions-lint]: https://github.com/rynkowsg/asdf-jet/actions/workflows/lint.yml
[ci-actions-test-badge]: https://github.com/rynkowsg/asdf-jet/actions/workflows/test.yml/badge.svg
[ci-actions-test]: https://github.com/rynkowsg/asdf-jet/actions/workflows/test.yml
[ci-circleci-lint-badge]: https://circleci.com/gh/rynkowsg/asdf-jet.svg?style=shield
[ci-circleci-lint]: https://circleci.com/gh/rynkowsg/asdf-jet
[gh-profile-rynkowsg]: https://github.com/rynkowsg
[jet-repo]: https://github.com/borkdude/jet
[license-badge]: https://img.shields.io/badge/license-MIT-lightgrey.svg
[license]: LICENSE
