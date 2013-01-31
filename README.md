node-webkit SDK
===============

SDK for building installable node-webkit applications.

This is a set of tools to build cross-platform (currently Windows, Linux 32bit, Linux 64bit) applications.

## SDK

Install:

    git clone git://github.com/jsmarkus/node-webkit-sdk.git
    cd node-webkit-sdk
    ant sdk

Create first project:

    ant create -Dtemplate=default -Ddir=/home/user/project1
    cd /home/user/project1

## Project

The following commands are run from your project's directory.

Build nw-package:

    ant app.nw

Configure installjammer project (*coming soon!*):

    ant ij.conf.l32    #for linux 32bit
    ant ij.conf.l64    #for linux 64bit
    ant ij.conf.win    #for windows
