A couple of playbooks
--------------------

This repo consists of a couple of playbooks for setting up my Archlinux "workstations" and
default Debian server.

How to use:
```
$ ansible-playbook install_desktop.yml --extra-vars "target=localhost installuser=username dotfilesrepo=https://github.com/filiphe/dotfiles.git" -K
```
Set `target`, `installuser`, and `dotfilesrepo` appropriately.
