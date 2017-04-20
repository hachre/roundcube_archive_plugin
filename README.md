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


## What about official support in Roundcube?

Roundcube has a version of this plugin with support for mark-as-read in their master branch. However it isn't compatible with the current 1.2.x branch. I suspect they will officially include it in the 1.4 release of Roundcube since the current 1.3 beta doesn't seem to include it. 
