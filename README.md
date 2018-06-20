# Permission	Command Examples	Description
rwx rwx rwx	chmod 777 filename
### chmod -R 777 dir	Anybody can read, write, execute.
rwx rwx r-x	chmod 775 filename
### chmod -R 775 dir	Owner & Group can read, write, execute. Everyone else can read, execute.
rwx rwx r–	chmod 774 filename
### chmod -R 774 dir	Owner & Group can read, write, execute. Everyone else can read.
rwx r-x r-x	chmod 755 filename
### chmod -R 755 dir	Owner can read, write, execute. Everyone else can read, execute.
rwx — —	chmod 700 filename
### chmod -R 700 dir	Owner can read, write, execute. No one else has any rights.
rw- rw- rw-	chmod 666 filename
### chmod -R 666 dir	Everyone can read, write.
rw- rw- r–	chmod 664 filename
### chmod -R 664 dir	Owner & Group can read, write. Everyone else can read.
rw- r– r–	chmod 644 filename
### chmod -R 644 dir	Owner can read, write. Everyone else can read.
