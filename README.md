# GitHub Utilities for Education

Purpose:

- accept pending invites
- clone matching repos into directories named by userid

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
