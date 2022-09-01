# setup-my-mac
 :apple: Commands to automatically configure my macOS when I reset it

## # system 

```sh
sudo scutil --set ComputerName prafaelo.com
sudo scutil --set LocalHostName prafaelo
dscacheutil -flushcache
```

## # [homebrew](https://brew.sh/)

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```sh
# // homebrew usefull commands
brew help # // show useful commands
brew update # // update to newest formula and homebrew
brew doctor # // perform troubleshooting
brew list -l # // list all installed formulae and casks
```

## # [vagrant](https://formulae.brew.sh/cask/vagrant)
```sh
brew install --cask vagrant

vagrant version
```

## # [virtualbox](https://formulae.brew.sh/cask/virtualbox#default)
```sh
brew install --cask virtualbox

# VBoxManage manual: https://www.virtualbox.org/manual/ch08.html
VBoxManage -version
```

## # git [1](https://git-scm.com/),[2](https://github.com/git/git)

```sh
brew install git
PATH=/usr/local/git/bin:$PATH

git config --global user.name "prafaelo"
git config --global user.email "prafaelo@icloud.com"
git config -l #show all local git param
```

## # [github desktop](https://github.com/desktop/desktop)

```sh
# Github Desktop, see https://github.com/desktop/desktop
brew install --cask github
```


## # [java](https://github.com/AdoptOpenJDK/homebrew-openjdk)

```sh
# // openjdk by AdoptOpenJDK and hostspot-vm

brew tap AdoptOpenJDK/openjdk
brew search adoptopenjdk

# // Force install JDK 16
brew install --cask adoptopenjdk16
java -version
```

## # [vscode](https://github.com/microsoft/vscode)

```sh
brew install --cask visual-studio-code
```

<!-- 

Reference List:

- https://git.herrbischoff.com/awesome-macos-command-line/about/

- Apple macOS How-to guides, examples and more:
https://ss64.com/osx/syntax.html

-->
