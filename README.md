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

        repo init -u http://sanjay/scm/git/Xilinx/XZD_yocto-manifests -m xzd.xml

3.  Clone Repos

        repo sync
