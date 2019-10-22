# GitHub Utilities for Education

Purpose:

- accept pending invites
- list or clone matching repos into directories named by userid 

*This is a work in progress.*

# Prerequisites

- bash
- curl
- jq
- GitHub userid in `GITHUB_USERID` environment variable
- GitHub access token in `GITHUB_ACCESS_TOKEN` environment variable

# Usage

To accept pending invites:

    $ ./ghai

To clone and/or pull matching repositories into current directory
(based on simple substring matching):

    $ ./ghcm <name>

# References

- http://tldp.org/LDP/Bash-Beginners-Guide/html
