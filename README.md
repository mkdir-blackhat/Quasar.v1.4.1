

Quasar v1.4.1 Latest
Changelog

Added missing WOW64 subsystem autostart locations
Fixed file transfers of files larger than 2 GB
Fixed file transfers of empty files
Fixed browser credentials recovery
Fixed race condition on shutdown
Fixed IP Geolocation
Fixed opening remote shell sessions on non-system drives
Fixed incorrectly set file attributes on client installations
Fixed sorting of listview columns with numbers
Updated dependencies
Notes


Updating a Client

Take a backup of your current Quasar installation directory. You need the old and new version for the update process.
Download the version you want to upgrade to from the Releases page (recommended) or use the latest build from the CI server.
Extract the new files into your Quasar installation directory.
Start the server of the new version and use the Builder to build a new client. Afterwards close the server again to make sure it's not blocking the port.
Start the server from the backup directory and do a right click on the clients you wish to update and select Connection -> Update or Client Management -> Update (in recent versions).
You can either upload the built client from step 4 to your remote clients or let them download the update from an URL.
When the update was successful close the old Quasar server and start the new version. You can remove the backup if everything worked flawlessly.
