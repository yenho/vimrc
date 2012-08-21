wuman's vimrc
=============
Author: David Wu <david@wu-man.com>


REFERENCE
---------

My vimrc settings are based extensively on the following:

+ [vgod's vimrc](https://github.com/vgod/vimrc)
+ [Amir Salihefendic's vimrc](http://amix.dk/vim/vimrc.html)
+ spf13's ultimate vim distribution [spf13-vim](https://github.com/spf13/spf13-vim/blob/master/.vimrc)


INSTALLATION
------------

Use curl (for Mac OS X):

    curl -o - https://raw.github.com/wuman/vimrc/master/auto-install.sh | sh

or wget (for most UNIX platforms):

    wget -O - https://raw.github.com/wuman/vimrc/master/auto-install.sh | sh


UPDATES
-------

Occasionally I will update my vimrc settings. If you had previously installed my
vimrc settings and wish to pull new changes from my repo or plugin submodules,
run the following script:

    ~/.vim/update-vimrc.sh


PLUGIN INSTALLATION
-------------------

To add a new plugin:

    cd ~/.vim
    git submodule add [GIT_REPOSITORY_URL] bundle/[PLUGIN_NAME]

