# Getting Started
Entering the Zeek Directory
```
cd /opt/zeek/
```
Check the Content of the Directory
```
ls -l
```
Entering "bin" Directory
```
cd bin
```
Checking the Content of the Directory
```
ls
```
To Check the Manual of the Zeek file in this Directory. It will also confirm the proper Installation of Zeek
```
.zeek -h
```
Or
```
zeek -h
```

To Check Zeek Command and Control
```
.zeekctl -h
```
Or
```
zeekctl -h
```

Creating Log for any pcap File
```
zeek -C
```
Adding Path
```
export PATH=/opt/zeek/bin:$PATH
```
Checking ethtool config
```
ethtool -K ens0p3
```
Ensuring no Dropping from any Messages that have Varsack On
```
ethtool -K ens0p3 rx off tx off sg off tso off gso off gro off
