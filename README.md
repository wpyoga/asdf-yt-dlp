<div align="center">

# asdf-yt-dlp ![Build](https://github.com/wpyoga/asdf-yt-dlp/workflows/Build/badge.svg) ![Lint](https://github.com/wpyoga/asdf-yt-dlp/workflows/Lint/badge.svg)

[yt-dlp](https://github.com/yt-dlp/yt-dlp) plugin for the [asdf version manager](https://asdf-vm.com).

This project was forked from Nyrst's [asdf-youtube-dl](https://github.com/nyrst/asdf-youtube-dl). The license has been left unchanged, and the changes in this repository are minimal.

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
asdf plugin add yt-dlp https://github.com/wpyoga/asdf-yt-dlp.git
```

yt-dlp:

```shell
# Show all installable versions
asdf list-all yt-dlp

# Install specific version
asdf install yt-dlp latest

# Set a version globally (on your ~/.tool-versions file)
asdf global yt-dlp latest

# Now yt-dlp commands are available
yt-dlp --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/wpyoga/asdf-yt-dlp/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Siegfried Ehret](https://github.com/SiegfriedEhret/)
