## PXE Kickstart configuration on RaspberryPi

This repo contains the config required for the setup fo PXE server on a RaspberryPi. The supported operating systems include CentOS7/8, ESXi 6.5/7.0 and Windows 10

### The following tools has been used for the setup (Release - Raspbian v10 buster)

- isc-dhcp-server = DHCP server to accept requests from PXE Boot clients.
- tftpd-hpa = Tftp server to serve Boot files for the client hosts.
- apache2 = Webserver to serve the OS-images.

#### I have ***ONLY*** included custom configs which require updating according to your environments. So please update as required.

##### Feedback would be much appreciated.
