# Contributing to React Native Swipeable Lists

Thank you for helping out with react-native-swipeable-lists!
We'd like to make contributions as pleasant as possible, so here's a small guide of how we see it. Happy to hear your feedback about anything, so please let us know.

### Modifying react-native-swipeable-lists

1. Fork this repository
2. Clone your fork
3. Make a branch for your feature or bug fix (i.e. `git checkout -b added-getfoobar`)
4. Work your magic
5. Execute `yarn link` when done.

### Testing your changes

You can test your changes on any React Native application you have set up locally.

## Sending a pull request

When you're sending a pull request:

- Communication is a key. If you want fix/add something, please open new/find existing issue, so we can discuss it.
- Small pull requests focused on one change are preferred, as those are easier to test/check.

## Commits and versioning

All PRs are merged into the `master` branch, following [conventional commit message](https://www.conventionalcommits.org/en/v1.0.0-beta.3). Combined with [semantic versioning](https://semver.org/), this allows us to have a frequent releases of the library.

Most notably prefixes you'll see:

- **fix**: Bug fixes, triggers _patch_ release
- **feat**: New feature implemented, triggers _minor_
- **chore**: Changes that are not affecting end user (CI config changes, scripts, ["grunt work"](https://stackoverflow.com/a/26944812/3510245))
- **docs**: Documentation changes.
- **perf**: A code change that improves performance.
- **refactor**: A code change that neither fixes a bug nor adds a feature.
- **test**: Adding missing tests or correcting existing tests.

## Release process

We use [Semantic Release](http://semantic-release.org) to release new versions of the library when changes are merged into the `master` branch, which we plan to keep stable. Bug fixes take priority in the release order. The master branch should always contain the latest released code.

## Reporting issues

You can report issues on the [bug tracker](https://github.com/nicastelo/react-native-swipeable-lists/issues). Please search for existing issues and follow the issue template when opening an one. Except no need to add any notes to the changelog as semtice released handles that automatically based on the commit messages.

## License

By contributing to React Native Swipeable Lists, you agree that your contributions will be licensed under the **MIT** license.
