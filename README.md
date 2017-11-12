# hub.docker.com/stevenmunro/alpine

# Introduction

Dockerfile to build an [alpine](https://www.alpinelinux.org/) container image.

* Currently tracking 3.6
* [s6 overlay](https://github.com/just-containers/s6-overlay) enabled for PID 1 Init capabilities
* Cron installed along with other tools (bash,curl, less, logrotate, nano, vim) for easier management.
* MSMTP enabled to send mail from container to external SMTP server.

# Authors

- [Steven Munro](stevenmunro at me dot com) [https://github.com/stevenmunro]