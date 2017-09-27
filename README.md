# Xen Zynq Distribution Repo Manifests for the Yocto Project Build System

This repository provides Repo manifests to setup the Yocto build system for
XZD.

## Prerequisites

1.  Install Repo

        sudo apt-get install phablet-tools

## Getting Sources

1.  Create an empty directory to hold your working files:

        mkdir Xocto
        cd Xocto

2.  Initialize Repo

        repo init -u git://github.com/dornerworks/xzd-yocto-manifests.git -m xzd.xml -b dw-v2016.4

3.  Clone Repos

        repo sync
