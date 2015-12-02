# transmission-readynas-os6-arm

Latest version is: os6-arm-2.84-0.01

This is a special build of Transmission Bittorrent client for current line of NETGEAR ReadyNAS OS6 systems on ARM architecture - ReadyNAS 100, 200 series and others.  

You can download the add-on in the Releases section: https://github.com/ssurba/transmission-readynas-os6-arm/releases

##General notes:

* Release notes for Transmission you may find on Transmission developers site: https://trac.transmissionbt.com/wiki/Changes.

* This package requires at least version 6.1.0 of the ReadyNAS OS. 

* Only transmission-daemon, client tools and Web interface are included in this package.

* After installing you should be able to access web interface from your browser by the following URL: http://[ip_address_of_your_NAS]:9091.

* Transmission network share will be created after installation. It provides access to downloaded files, Transmission configuration file (settings.json) and some other special files.

* By default downloaded files are saved to /data/Transmission/downloads. You may later change download path in Transmission configuration.

**WARNING!** Before installing this version please **uninstall any other builds** of Transmission (versions not made by me) and **delete Transmission share** created by the other build. But you can keep previous version of my build and Transmission share created by it, newer version should use and upgrade them.

# Version changes:

## Version 0.01

* Release for GitHub.
