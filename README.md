# transmission-readynas-os6-arm

This is a special build of Transmission Bittorrent client for current line of NETGEAR ReadyNAS OS6 systems on ARM architecture - ReadyNAS 100, 200 series and others.  

You can download it in the "Releases" section.

General notes:

- Release notes for Transmission you can read on Transmission developers site: https://trac.transmissionbt.com/wiki/Changes.

- This package requires at least version 6.1.0 of the ReadyNAS OS. 

- Only transmission-daemon, client tools and Web interface are included in this package.

- After installing you should be able to access web interface from your browser by the following URL: http://[ip_address_of_your_NAS]:9091.

- Transmission network share will be created after installation. It provides access to downloaded files, Transmission configuration file (settings.json) and some other special files.

- By default downloaded files are saved to /data/Transmission/downloads. You may later change download path in Transmission configuration.

- Before installing this version please remove any other builds of Transmission (those not made by me). But you can keep previous version of my build, newer version should upgrade it.
