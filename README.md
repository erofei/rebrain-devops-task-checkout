### IP Networks Scan

This is a tool for scanning ip networks to find active hosts there are. It can work on ubuntu/debian host. You can use it from console or web (in developing).

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
cd ~/snetworks/
sudo cp snetworks.py /usr/sbin/snetwork
sudo chmod +x /usr/sbin/snetwork
sudo snetworks 8.8.8.8 or sudo snetworks + enter
```

## Running the tests

If you run a snetwork without parameters you can scan a free (f) or busy (u) subnet. For free network tool uses icmp scanning, for busy network tool uses port scanning. You can scan several networks, use space between them.

If you will run snetworks without parameters you will choose:
* what network do you want check - f/u
* specify checked subnets
* write result in file or not
* show result on display or not

## Built With

* [Nmap](https://nmap.org/) - is a free and open source utility for network discovery and security auditing. 

## Authors

* Erofeev Pavel - _initial work_ - @ps.erofeev
* Samoilenko Natasha - _editor_ - @natenka

## License

This project is licensed under the GNU GPL
