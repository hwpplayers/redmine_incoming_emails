# Redmine incoming email project configuration plugin

Redmine plugin that allows for the configuration of which project should be used for issues created from email per user.

This is a fork of http://github.com/markwhitfeld/redmine_incoming_emails.

## Features

* Plugin configuration page allows for the allocation of a default project per user.
 * this project will be used as the default project for issues logged by email

## Getting the plugin

A copy of the plugin can be downloaded from GitLab: https://gitlab.com/monobilisim/redmine/redmine_incoming_emails

## Installation

Clone the repro from github to install the plugin.

Run the following git command from the redmine plugins folder:
```
git clone https://gitlab.com/monobilisim/redmine/redmine_incoming_emails.git redmine_incoming_emails
```
There aren't any database migrations that need to be run for the plugin.

To uninstall the plugin, delete the 'redmine_incoming_emails' folder from the redmine plugins folder

Further information about plugin installation can be found at: http://www.redmine.org/wiki/redmine/Plugins

## Compatibility

The latest version of this plugin is tested with Redmine 4.0.x.

## License

This plugin is licensed under the GNU GPLv2 license. See LICENSE-file for details.
