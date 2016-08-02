# Laravel Skeleton Installer

## Install
Clone this to a folder of your choice.
Run the installer in a terminal `$ path/to/cloned/dir/skel-intaller` wait for the proccess end and you are ready.

## Options
**Project Directory Name:** The name of the directory to work on. This is the first argument for the command `$ skel-intaller my-cool-project`. Defaults to *myproject*

**Project Directory:** The path of the directory where the Project Directory Name will be created. This is the second argument for the command `$ skel-intaller my-cool-project ../path/to/another/folder/`. Defaults to the current directory (`pwd`).

**Dev Branch:** By default the resources are cloned from master, by adding the option `-d` or `--dev` force resources to be fetched from dev branch. This is not recomended.

`$ skel-intaller -d` or `$ skel-intaller --dev`

## Permission
Dont forget to add execute permission to skel-intaller file. `chmod +x path/to/cloned/dir/skel-installer`

## Global execution
You can run this commnd from anywhere from terminal, just copy the skel-installer to any directory that was in your path. I like to place my stuff in the bin next my user root, to do this follow the steps below.

In a terminal window cd to where you cloned the repo `cd `

Run this command `mkdir -p ~/bin && cp skel-installer ~/bin/`

Add the bin folder to your path, this is platform specific so you need to search how to do this in the latform you use.


