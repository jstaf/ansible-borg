jstaf.borg
=========

Sets up borg backups for a laptop or other home device as described in
https://jstaf.github.io/posts/backups-with-borg-rsync/.
Specifically, this role is different than others in that it uses
/etc/cron.daily to perform a backup once a day at an unspecified time instead of relying
on a normal cronjob that requires your laptop to be on and connected
to the internet at the specified backup time (or the backup is missed).
This lets you get a reliable backup for every day as long as you powered on your machine
at least once that day.

License
-------

GPL3

