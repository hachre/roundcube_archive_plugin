# roundcube_archive_plugin
#### Enhanced version of the Roundcube 'archive' plugin that allows to mark mails as read when archiving.

## How to install

1. Remove the original `archive` plugin, then copy this into Roundcube's `plugins/` folder instead.
2. Enable by adding `$config['read_when_archived'] = true;` to the `config/config.inc.php`

### Enjoy!



## What's been changed?

This was forked from the official 'archive' plugin shipping with Roundcube 1.2.4 on 2017-04-20.

Changes:
 - introduced 'read_when_archived' config setting, accepting true/false
 - edited archive.js to disable direct JS API use
 - edited archive.php to add the ability to mark mails as read when archiving
