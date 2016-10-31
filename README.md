# fedora-25-x86_64 #

This is going to be a Fedora 25 box updated monthtly.

Right now it is a minimal server install of **BETA** 1.1.

### Getting started with [Veertu](https://veertu.com/) on OSX ###

```sh
brew cask install vagrant
vagrant plugin install vagrant-veertu

brew cask install veertu-desktop
# The vagrant-veertu provider expects a Veertu.app and not Veertu Desktop.app
ln -sf /Applications/Veertu\ Desktop.app /Applications/Veertu.app

vagrant init brycekbargar/fedora-25-x86_64; vagrant up --provider veertu
```
