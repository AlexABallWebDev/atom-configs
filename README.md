# atom-configs
My Atom editor configurations. This repo is an attempt at making it possible to transfer my configuration between computers.

It should be possible to install the packages from packages.list by running:
apm install --packages-file packages.list

A new version of these configurations can be created by copying the files (not folders) in .atom into this repo, and also updating packages.list by running the command:
apm list --installed --base > packages.list
