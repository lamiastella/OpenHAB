==============================================================================
===                  openHAB - the open Home Automation Bus               ====
===                          http://www.openHAB.org                       ====
===                                                                       ====
===                                 ADD-ONS                               ====
==============================================================================

This folder contains necessary files and configs for controlling Philips Hue, 
Insteon PLM, Belkin WeMo, and persisting the data using MySQL. 
Also you will find all the configurations for HABmin in the same folder. 
If you need help with the configs I'd be happy to help via jalal@cs.wisc.edu
For running this HA system:
sudo ./start.sh
and then browse to:
192.168.1.130:8082/openhab.app?sitemap=iotpi
to check the HABmin administrative Web UI browse to:
http://192.168.1.130:8082/habmin/index.html
Each bundle (jar file) is a feature that can be installed independently from
any other bundle in this zip file.
You can thus decide yourself, what features you need and leave out the rest.
See https://github.com/openhab/openhab/wiki/Addons for more details.
