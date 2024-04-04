# setup-my-mac
:apple: All kind of Useful macOS Commands & [Shortcuts](https://en.wikipedia.org/wiki/Shortcuts_(Apple)) 
 
## Commands for automated macOS setup:

### # system 

```sh
sudo scutil --set ComputerName prafaelo.com
sudo scutil --set LocalHostName prafaelo
dscacheutil -flushcache
```

### # [homebrew](https://brew.sh/)

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

### # [vagrant](https://formulae.brew.sh/cask/vagrant)
```sh
brew install --cask vagrant

vagrant version
```

### # [virtualbox](https://formulae.brew.sh/cask/virtualbox#default)
```sh
brew install --cask virtualbox

# VBoxManage manual: https://www.virtualbox.org/manual/ch08.html
VBoxManage -version
```

### # [Microsoft Remote Desktop](https://formulae.brew.sh/cask/microsoft-remote-desktop#default)
```sh
brew install --cask microsoft-remote-desktop
```

### # git [1](https://git-scm.com/),[2](https://github.com/git/git)

```sh
brew install git
PATH=/usr/local/git/bin:$PATH

git config --global user.name "prafaelo"
git config --global user.email "prafaelo@icloud.com"
git config -l #show all local git param
```

### # [github desktop](https://github.com/desktop/desktop)

```sh
# Github Desktop, see https://github.com/desktop/desktop
brew install --cask github
```


### # [java](https://github.com/AdoptOpenJDK/homebrew-openjdk)

```sh
# // openjdk by AdoptOpenJDK and hostspot-vm

brew tap AdoptOpenJDK/openjdk
brew search adoptopenjdk

# // Force install JDK 16
brew install --cask adoptopenjdk16
java -version
```

### # [vscode](https://github.com/microsoft/vscode)

```sh
brew install --cask visual-studio-code
```

```sh
## Update default settings to my custom settings
cd /Users/si/Library/Application\ Support/Code/User/ && curl -O https://raw.githubusercontent.com/prafaelo/setup-my-mac/main/vscode/settings.json
```

<!-- 

Reference List:

- https://git.herrbischoff.com/awesome-macos-command-line/about/

- Apple macOS How-to guides, examples and more:
https://ss64.com/osx/syntax.html

-->



### # [Python3](https://www.python.org/downloads/)

```sh
## From https://formulae.brew.sh/formula/python@3.11
brew install python@3.11
```

```sh
## Also https://docs.brew.sh/Homebrew-and-Python#python-3y
python3 -m pip install --upgrade setuptools # https://pypi.org/project/setuptools/
python3 -m pip install --upgrade pip        # https://pip.pypa.io/en/stable/
```

```sh
## Python Packages

pip3 install numpy       # scientific computing: https://numpy.org/
pip3 install matplotlib  # draft data plots: https://matplotlib.org/
pip3 install pandas      # data manipulation: https://pandas.pydata.org

pip3 list
```



