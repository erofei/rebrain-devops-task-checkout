### IP Networks Scan

This is a tool for scanning ip networks to find active hosts there are. It can work on ubuntu/debian host. You can use it from console or web.

## Getting Started

You must do on your host:

```
git clone https://github.com/erofei/snetworks.git
```

## Prerequisites

For succes work with the tool you must install on your PC next packeges:

```
sudo apt install nginx
sudo apt install python-pip
sudo apt install nmap 
sudo pip install python-nmap
```

## Installing

```
1. cd ~/snetworks/
1. sudo cp snetworks.py /usr/sbin/snetwork
1. sudo chmod +x /usr/sbin/snetwork
1. sudo snetworks 8.8.8.8 or sudo snetworks :leftwards_arrow_with_hook:
```
:leftwards_arrow_with_hook:

## Running the tests

## Built With

* [Nmap](https://nmap.org/) - is a free and open source utility for network discovery and security auditing. 
