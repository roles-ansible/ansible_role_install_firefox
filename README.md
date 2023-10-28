 firefox-installation - ansible role
=======================================

```
This ansible role is deprecated and no longer maintained.
Sorry
```

Ansible role to install firefox with some plugins and language packs, if your system packet manager provides them (and they are configured)

If you set the variable ``install_pass_as_password_manager`` to true, it will also install pass and (on arch) the browser extention to communicate. That allowes you to store you passwords in gpg encrypted files on your computer. [Read More](https://www.passwordstore.org/). *But better have a look at [GoPass](https://www.gopass.pw/) if you want to use a good password manager.*


 Testing
----------

This role is in use on Archlinux.
That is the reason, why there are there the most plugins configured.
There are some github actions that will do some basic testing.

 Participate
--------------
Please, if you know a few plugins on any os that should be included in this role, simply open an issue or even better a Pull Request!

 Set as default
------------------
```
xdg-settings set default-web-browser firefox.desktop
```
