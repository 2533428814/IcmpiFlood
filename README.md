# IcmpiFlood
Icmp Flood tool that uses multiprocessing to get maximum effect. Written with Python&Scapy

## About
IcmpiFlood is useful program to try icmp flood attack for education purposes.

## Installation
To install the latest development version type the following commands:

```bash
git clone https://github.com/pioneerhfy/IcmpiFlood # Download the latest revision
cd IcmpiFlood # Switch to tool's directory
python IcmpiFlood.py <domain name or ip adress> # Just type this command
```
## Usage

Just run `sudo python IcmpiFlood.py <domain name or ip adress>` from the terminal. If there is no problem in starting program, you'll see banner text in terminal. In order to run this program without any problem, you have to be root user or have root privileges otherwise, you'll encounter annoying socket errors.                         

## Samples

```shell
sudo python IcmpiFlood.py sampleWebsite.com
```

```shell
sudo python piroute.py 192.168.1.1 //IP adress of sampleWebsite
```
## Built With

* [Python 2.7](https://www.python.org/)
* [Scapy 2.3.3](http://www.secdev.org/projects/scapy/) - Used to generate network packets

<p align="center">
<img src="https://github.com/pioneerhfy/piroute/blob/master/blastoise-black.jpg" width="200" height="300">
