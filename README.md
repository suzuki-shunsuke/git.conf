# git.conf

~/.gitconfig

```
~/repos/src/github.com/suzuki-shunsuke/git.conf/
  mac_gitconfig
  linux_gitconfig
~/.gitconfig -> ~/repos/src/github.com/suzuki-shunsuke/git.conf/mac_gitconfig
```

## Arch Linux

### gnome-keyring

http://stackoverflow.com/questions/13385690/how-to-use-git-with-gnome-keyring-integration/13390889#13390889
https://github.com/shugo/git-credential-gnomekeyring/issues/2
https://wiki.archlinux.org/index.php/GNOME/Keyring

```
$ pacman -S libgnome-keyring
$ cd /usr/share/git/credential/gnome-keyring
$ make
$ git config --global credential.helper /usr/share/git/credential/gnome-keyring/git-credential-gnome-keyring
```

## LICENSE

[MIT](LICENSE)
