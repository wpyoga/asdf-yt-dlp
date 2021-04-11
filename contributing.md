# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test youtube-dl https://github.com/nyrst/asdf-youtube-dl.git "youtube-dl --version"
```

Tests are automatically run in GitHub Actions on push and PR.
