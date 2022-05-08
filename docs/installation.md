# Quick Start - Install boots

> [!TIP]
> boots is installable via [instl.sh](https://instl.sh).\
> You just have to run the following command and you're ready to go!

<!-- tabs:start -->

#### ** Windows **

### Windows Command

```powershell
iwr instl.sh/x0f5c3/boots/windows | iex
```

#### ** Linux **

### Linux Command

```bash
curl -sSL instl.sh/x0f5c3/boots/linux | bash
```

#### ** macOS **

### macOS Command

```bash
curl -sSL instl.sh/x0f5c3/boots/macos | bash
```

#### ** Compile from source **

### Compile from source with Golang

?> **NOTICE**
To compile boots from source, you have to have [Go](https://golang.org/) installed.

Compiling boots from source has the benefit that the build command is the same on every platform.\
It is not recommended to install Go only for the installation of boots.

```command
go install github.com/x0f5c3/boots@latest
```

<!-- tabs:end -->
