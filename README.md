# setup-my-mac
 :apple: Commands to automatically configure my mac when I reset the OS x


## # [homebrew](https://brew.sh/)

```sh
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## # [c](https://github.com/git/git)/[git](https://git-scm.com/)

```sh
$ brew install git
```

```sh
# Github Desktop, see https://github.com/desktop/desktop
$ brew install --cask github
```


## # Java

```sh
# // openjdk by AdoptOpenJDK and hostspot-vm
# // See https://github.com/AdoptOpenJDK/homebrew-openjdk
$ brew tap AdoptOpenJDK/openjdk
$ brew search adoptopenjdk

# // Force install JDK 16
$ brew install --cask adoptopenjdk16
$ java -version
```

## # [vscode](https://github.com/microsoft/vscode)

```sh
$ brew install --cask visual-studio-code
```

## # homebrew usefull commands

```sh
# 
$ brew help # // show all commands
$ brew <command> help # // show the command help/usage
$ brew update # // update to newest formula and homebrew
$ brew doctor # // perform troubleshooting
$ brew list # // List all installed formulae and casks
```
