<div align="center">

# asdf-youtube-dl ![Build](https://github.com/nyrst/asdf-youtube-dl/workflows/Build/badge.svg) ![Lint](https://github.com/nyrst/asdf-youtube-dl/workflows/Lint/badge.svg)

[youtube-dl](https://github.com/ytdl-org/youtube-dl) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`.

# Install

Plugin:

```shell
asdf plugin add youtube-dl https://github.com/nyrst/asdf-youtube-dl.git
```

youtube-dl:

```shell
# Show all installable versions
asdf list-all youtube-dl

# Install specific version
asdf install youtube-dl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global youtube-dl latest

# Now youtube-dl commands are available
youtube-dl --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nyrst/asdf-youtube-dl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Siegfried Ehret](https://github.com/SiegfriedEhret/)
