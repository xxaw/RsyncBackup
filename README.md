# RsyncBackup
flexible Rsync backupscript (bash) for local backup &amp; remotes (airgap)
Welcome to the RsyncBackup!

with this flexible script its possible (with a little help of crontab) to preform a backup of you files using Rsync.

usage: Backup_delete_[versionnumber].sh [backuplocation] [userDir] [remoteOn|Off] [SLEEPtime] [--delete]

[backuplocation] : in conjuction with -backupPREFIX*- decides where to place all directories

[userDir] : place where the script is located within sub dir /bin/production/

[remoteOn|Off] : switch for local storage or remote (use a pi with external harddisk attached connected by wifi)

[SLEEPtime] : time in between backup locations for writes to be completed

[--delete]' : very important switch, used for removing files not existing on source location

for now build in script on line 21
