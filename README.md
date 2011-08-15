Linux iPhone Backup
===================

This project is a simple wrapper script around libimobiledevice.

It aims to provide a backup solution for jailbroken iPhones that can be scheduled to automatically
run while your iPhone is plugged into your PC.

It backs up everything that iTunes does, but it also saves your installed Cydia packages and sources.


Requirements
------------

* A jailbroken iPhone with OpenSSH installed.
* libimobiledevice: http://www.libimobiledevice.org/
  (You will need to download the source and compile it to get these binaries on your system: ideviceinfo and idevicebackup2)
* ideviceinstaller from http://git.sukimashita.com/ideviceinstaller.git

