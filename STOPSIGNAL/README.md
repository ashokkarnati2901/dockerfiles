### STOPSIGNAL

STOPSIGNAL is used to how to exit the container.
*By default docker request for exit and wait for sometime, if it is not  exiting then it will be force killed.
*When our container recives the STOPSIGNAL our application can perform the below actions.
   1. You can close the DB connections.
   2. You can do the backup.