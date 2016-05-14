# My DotFiles

Personal collection of scripts and configuration files for linux.


## Installing stuff

To install scripts in `~/bin/` execute:

    run/install-bin

To install the configuration files execute:

    run/install-configs

Note: all scripts in `run/` assume your current directory is `dotfiles`.


## Updating this repository with local stuff

    run/retrieve-locals

This command will copy stuff from your home directory. You can then
inspect the files, add what you want and commit. It also remember you
that you can clean the garbage with:

    git clean -f
