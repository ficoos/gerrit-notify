gerrit-notify
=============
Gerrit Notifier pulls your gerrit-server changes and popup notifications to your desktop when changes occurred. Such as reviews, comments, merges and inc. All those changes are refered to the configured query.
Gerrit Notifier uses config file `$HOME/.config/gerrit-notify/config`. This file is configured automatically by the following command:
`gerrit-notify configure`

Installation
============
`gerrit-notify install`

After installation gerrit-notify will be loaded during user's log-in.

Requirements
===========
* python-rest-client
* python-httplib2
* python-notify
