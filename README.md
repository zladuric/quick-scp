quick-scp
=========

qscp or quick-scp is a helper bash script for quick-scp. It's designed to remove the need to type the path of the copied resource twice.

Usage:
======

   qscp PATH [DESTINATION_SERVER] [SOURCE_SERVER]
Example:
========
 qscp src/directory/file.js zlayer.net
> Copying: /usr/bin/scp -i /home/zlatko/.ssh/id_rsa /home/zlatko/Programming/bash/src/directory/file.js zlayer.net:/home/zlatko/Programming/bash/src/directory/file.js

> zlatko@zlayer.net's password:

> file.js                                                             100%  1257  1.2KB/s 00:00


-----------
Parameters:


  PATH: path to a file or directory
optional:
  DESTINATION_SERVER: change from the default destination server set in .qscprc
  SOURCE_SERVER:  change from the default source server (which is local file/localhost)

Additional settings:
  KEY: ssh key to use

