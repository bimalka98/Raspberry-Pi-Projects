# Raspberry-Pi-Projects

<a href="https://www.raspberrypi.org"><img src="https://www.raspberrypi.org/wp-content/uploads/2012/03/raspberry-pi-logo.png" alt="Raspberry Pi Logo" align="left" style="margin-right: 25px" height=130></a>

> The Raspberry Pi is a series of credit card-sized single-board computers developed in the United Kingdom by the Raspberry Pi Foundation to promote the teaching of basic computer science in schools and developing countries. Official Link: [Raspberry Pi Homepage](https://raspberrypi.com)

This repository contains projects related to RPis that are being done along with the project [SPARK@UOM](https://ent.uom.lk/spark/)

---

## *Accessing the Rpi through the command prompt for the first time(with Rpi OS installation)*

***Watch these videos first to know how to install rpi OS and configure the pi to autoconnect to the local wifi network at booting***

- [Setup Raspberry PI OS with SSH and WIFI the NEW (3/2021) Easy Way](https://youtu.be/nZyyfJYOhbM) ; 
- [Setup raspberry pi without monitor | Raspberry pi SSH/VNC remote access | Setup VNC server](https://youtu.be/AZj2uON6JaI)

1. Open command prompt and type following commands.

###  Input

```shell

bimalka98@DEVICE:~$ ssh pi@rpibimalka98
The authenticity of host 'rpibimalka98 (192.168.8.102)' can't be established.
ECDSA key fingerprint is SHA256:DHkDrtlf2nwgWS9F0yofVPDFauFG7fqVtH6p2SQTmQE.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'rpibimalka98,192.168.8.102' (ECDSA) to the list of known hosts.
pi@rpibimalka98's password: YOUR_PASSWORD_HERE
```

###  Output
```shell
Linux rpibimalka98 5.10.92-v7+ #1514 SMP Mon Jan 17 17:36:39 GMT 2022 armv7l

The programs included with the Debian GNU/Linux system are free software;
the exact distribution terms for each program are described in the
individual files in /usr/share/doc/*/copyright.

Debian GNU/Linux comes with ABSOLUTELY NO WARRANTY, to the extent
permitted by applicable law.
Last login: Fri Jan 28 07:01:06 2022
```

###  Input

```shell
# Initializing the VNC server inside the pi
pi@rpibimalka98:~ $ vncserver
```

###  Output
```shell
VNC(R) Server 6.7.2 (r42622) ARMv6 (May 13 2020 19:34:20)
Copyright (C) 2002-2020 RealVNC Ltd.
RealVNC and VNC are trademarks of RealVNC Ltd and are protected by trademark
registrations and/or pending trademark applications in the European Union,
United States of America and other jurisdictions.
  .
  .
  .
New desktop is rpibimalka98:2 (192.168.x.xxx:x)

```

2. Now open VNC viewer and type the server's ip produced by the above last command! -> 192.168.x.xxx:x

3. Provide the login credentials when asked
  - **username**: pi 
  - **password**: YOUR_PASSWORD_HERE

4. That's it. You are in!

---
 
##  A curated list of awesome Raspberry Pi tools, projects, images and resources

https://github.com/thibmaek/awesome-raspberry-pi
