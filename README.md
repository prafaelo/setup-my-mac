# setup-my-mac
 :apple: Commands to automatically configure my mac when I reset the OS x


## [HomeBrew](https://brew.sh/)

```sh
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## [OpenJDK hostspot VM - 16](https://github.com/AdoptOpenJDK/homebrew-openjdk)

```sh
$ brew tap AdoptOpenJDK/openjdk
$ brew search adoptopenjdk
$ brew install --cask adoptopenjdk16
$ java -version
```


## [VS Code](https://github.com/microsoft/vscode)

```sh
$ brew install --cask visual-studio-code
```

## Update

```sh
$ brew update
```
