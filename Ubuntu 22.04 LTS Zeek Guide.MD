Simply Enter the following the Ubuntu Terminal
# Installing Dependencies
```
sudo su
```
```
sudo apt update
```
```
sudo apt-get install cmake make gcc g++ flex bison libpcap-dev libssl-dev python3 python3-dev swig zlib1g-dev
```
```
sudo apt install python3-git python3-semantic-version
```
```
sudo apt install curl
```
# Installing ZEEK LTS
```
sudo apt update
```
```
echo 'deb http://download.opensuse.org/repositories/security:/zeek/xUbuntu_22.04/ /' | sudo tee /etc/apt/sources.list.d/security:zeek.list
```
```
curl -fsSL https://download.opensuse.org/repositories/security:zeek/xUbuntu_22.04/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/security_zeek.gpg > /dev/null
```
```
sudo apt update
```
```
sudo apt install zeek-lts
```
Now Return to the [ReadMe.MD](https://github.com/cyberseef/Zeek_Installation_Guide/blob/bb7c92aad1ad6a0fb7c5570805e4780ac8301b6b/ReadMe.MD)
