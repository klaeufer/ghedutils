# GitHub Utilities for Education

The purpose of these utilities is to handle some use cases commonly
encountered in the education environment, initially:

- accept pending invites
- list or clone matching repos into directories named by userid 

*This is a work in progress.*

# Prerequisites

- Linux or Mac OS
- bash
- curl
- jq
- GitHub userid in `GITHUB_USERID` environment variable
- GitHub access token in `GITHUB_ACCESS_TOKEN` environment variable

# Installation

    $ [ -x ~/bin ] || mkdir ~/bin
    $ git clone https://github.com/klaeufer/ghedutils ~/bin/ghedutils

# Usage

To accept pending invites:

    $ ~/bin/ghedutils/ghai

To clone and/or pull matching repositories into current directory
(based on simple substring matching):

    $ ~/bin/ghedutils/ghcm <name>

# References

- http://tldp.org/LDP/Bash-Beginners-Guide/html
