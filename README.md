# About
This script will install latest Perforce server on any Ubuntu server.
# Usage
```
wget https://raw.githubusercontent.com/Stanok1/ubuntu-perforce-installer/main/install-perforce.sh
chmod +x install-perforce
sudo ./install-perforce
```
At the end you will be prompted to configre a server, you can use default settings by presssing ENTER but keep in mind that Unreal recommends to use **case-insensitive** setting.

# Starting and stopping the Perforce server
```
p4dctl stop <service name>
p4dctl stop <service name>
```
service name is **master** by default
