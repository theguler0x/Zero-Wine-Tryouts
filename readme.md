<img src="https://zerowine-tryout.sourceforge.net/images/zerowine-1-small.jpg" width="auto">

Zero Wine Tryouts: A Malware Analysis Tool - Joxean Koret

Introduction:
Zero wine is an open source (GPL v2) research project to dynamically analyze the behavior of malware. Zero wine just runs the malware using WINE in a safe virtual sandbox (in an isolated environment) collecting information about the APIs called by the program.

The output generated by wine (using the debug environment variable WINEDEBUG) are the API calls used by the malware (and the values used by it, of course). With this information, analyzing malware's behavior turns out to be very easy.


This is Zero Wine Tryouts Alpha 5 Prebuilt VMware Image. (.vmdk)

Download:

https://sourceforge.net/projects/zerowine-tryout/files/zerowine-tryout/0.0.2.x/

https://sourceforge.net/projects/zerowine/files/



##################################

To configure the network, you must edit the following file: 
/etc/network/interfaces

Current configuration:

    #port:8000
    iface eth0 inet static
    address 192.168.198.200
    netmask 255.255.255.0
    gateway 192.168.198.2

######################################

https://www.openhub.net/p/zerowine - 
https://zerowine.sourceforge.net

Contact Information
Author: Joxean Koret
E-Mail:<admin@joxeankoret.com> - <joxeankoret@yahoo.es>
 Website: http://www.joxeankoret.com
