# gcloud-ps1: Google Cloud Platform prompt for bash

A script that lets you add the active Google Cloud Platform configuration on
`gcloud` to your Bash prompt strings (i.e. the `$PS1`).

Inspired by [kube-ps1](https://github.com/jonmosco/kube-ps1).

## Installation

1. Clone this repository
2. Source the gcloud-ps1.sh in your `~/.bashrc`

```sh
source /path/to/gcloud-ps1.sh
PS1='[\u@\h \W $(gcloud_ps1)]\$ '
```
