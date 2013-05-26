smsc-ufx-7000
=============

X.org drivers for SMSC USB3 to HDMI adapters based on UFX-6000 and UFX-7000 chipsets.


The linux_xorg_1.0.2.1_20111206.tar.gz package contains X.org drivers and Viewspan configuration application allowing easy use of USB3-HDMI and alike adapters under Linux.

The Kernel drivers are present in the Kernel from a long time, but X.org drivers are/were deeply hidden on the SMSC website.
That's why I decided to mirror them here. Before using them you must accept the license that comes with them.


A lot of USB-display output adapters uses DisplayLink chipsets.
There are Linux drivers for older USB2 chipsets but no support for USB3 chipsets (and maybe some newer USB2 chipsets).
SMSC adapters are less popular or explicitly marked that they use SMSC chipset. Gembird USB3 to HDMI adapter is one of SMSC based and with attached X.org drivers it works with Ubuntu 12.04 LTS.


There are however problems. The Viewspan application uses Xinerama and is not compatible with XRandr.
It generates a xorg.conf file which I wasn't able to change that it would work with XRandr on newer distributions.
Example X.org configs are most welcomed :)


Drivers, Viewspan application, the license and release notes files are property of SMSC.


Chipset info: http://www.smsc.com/Technologies/ViewSpan/UFX7000
