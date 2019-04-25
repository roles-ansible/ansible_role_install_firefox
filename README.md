 firefox-installation - ansible role
=======================================
Ansible role to install firefox with some plugins and language packs, if your system packet manager provides them (and they are configured)

If you set the variable ``install_pass_as_password_manager`` to true, it will also install pass and (on arch) the browser extention to communicate. That allowes you to store you passwords in gpg encrypted files on your computer. [Read More](https://www.passwordstore.org/)


 Tested on:
----------

This role is used and tested on Archlinux. 
That is the reason, why there are there the most plugins configured.

 Participate
--------------
Please, if you know a few plugins on any os that should be included in this role, simply open an issue or even better a Pull Request!
