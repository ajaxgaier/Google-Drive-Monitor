Google-Drive-Monitor
====================

Monitor Google Drive for new files. Sends email with changes.

Runs as standalone script. Also offers a GUI to configure the recursion level (how many directory levels to scan) 
and the maximum age of the files to list.

In case of shared files and directories and teams where different members can edit files it is helpful to be up
to date on what has changed. 

Stores defaults in UserProperties. Sends email with result to email address of user (Session.getUser().getEmail()).
