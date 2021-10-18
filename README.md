# Raspberry-Pi-Projects

## Accessing the Rpi through the command prompt for the first time(with Rpi OS installation)

1. Open command prompt and type following command.

```shell
// comment: rpibimalka98 is the hostname of my raspberry pi

C:\Users\bimal>ssh pi@rpibimalka98
pi@rpibimalka98s password: YOUR_PASSWORD_HERE


Linux rpibimalka98 5.10.17-v7+ #1414 SMP Fri Apr 30 13:18:35 BST 2021 armv7l

The programs included with the Debian GNU/Linux system are free software;
the exact distribution terms for each program are described in the
individual files in /usr/share/doc/*/copyright.

Debian GNU/Linux comes with ABSOLUTELY NO WARRANTY, to the extent
permitted by applicable law.
Last login: Tue Oct 19 00:58:16 2021 from fe80::6028:c37b:5f67:e81d%wlan0

// Initializing the VNC server inside the pi
pi@rpibimalka98:~ $ vncserver


VNC(R) Server 6.7.2 (r42622) ARMv6 (May 13 2020 19:34:20)
Copyright (C) 2002-2020 RealVNC Ltd.
RealVNC and VNC are trademarks of RealVNC Ltd and are protected by trademark
registrations and/or pending trademark applications in the European Union,
United States of America and other jurisdictions.
Protected by UK patent 2481870; US patent 8760366; EU patent 2652951.
See https://www.realvnc.com for information on VNC.
For third party acknowledgements see:
https://www.realvnc.com/docs/6/foss.html
OS: Raspbian GNU/Linux 10, Linux 5.10.17, armv7l

On some distributions (in particular Red Hat), you may get a better experience
by running vncserver-virtual in conjunction with the system Xorg server, rather
than the old version built-in to Xvnc. More desktop environments and
applications will likely be compatible. For more information on this alternative
implementation, please see: https://www.realvnc.com/doclink/kb-546

Running applications in /etc/vnc/xstartup

VNC Server catchphrase: "Quiet Herbert potato. Galileo bambino extreme."
             signature: 23-fc-62-9a-aa-ba-2c-8c

Log file is /home/pi/.vnc/rpibimalka98:2.log
New desktop is rpibimalka98:2 (192.168.x.xxx:x)

```

2. Now open VNC viewer and type the server s ip produced by the above last command!
3. Provide the login credentials
- username: pi 
- password: YOUR_PASSWORD_HERE
