[![Build Status](https://travis-ci.org/wtanaka/ansible-role-sendmail.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-sendmail)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-sendmail.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-sendmail)

wtanaka.sendmail
================

Installs sendmail

Example Playbook
----------------

    - hosts: servers
      roles:
         - wtanaka.sendmail

### `sendmail_should_shortcircuit`

Default: True

When True, this role short-circuits itself if a "sendmail" is already in the
path

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)


License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
